Week 4: Analytics Engineering
Goal: Transforming the data loaded in DWH to Analytical Views developing a [dbt project](
https://github.com/DataTalksClub/data-engineering-zoomcamp/blob/main/week_4_analytics_engineering/taxi_rides_ny/README.md). 

Slides 

<p><iframe allowfullscreen width="100%" height="569" class="google-slides-iframe" frameborder="0" scrolling="no" src="https://docs.google.com/presentation/d/1xSll_jv0T8JF4rYZvLHfkJXYqUjPtThA/embed?start=false&loop=false&delayms=3000"></iframe></p>


# Prerequisites
We will build a project using dbt and a running data warehouse. By this stage of the course you should have already:
* A running warehouse (BigQuery or postgres)
* A set of running pipelines ingesting the project dataset (week 3 completed): [Taxi Rides NY dataset](https://github.com/DataTalksClub/data-engineering-zoomcamp/blob/main/week_4_analytics_engineering/dataset.md
) 
* Yellow taxi data - Years 2019 and 2020
* Green taxi data - Years 2019 and 2020
* fhv data - Year 2019.

Note:
* A quick hack has been shared to load that data quicker, check instructions in [week3/extras](https://github.com/DataTalksClub/data-engineering-zoomcamp/tree/main/week_3_data_warehouse/extras) 
* If you recieve an error stating "Permission denied while globbing file pattern." when attemting to run fact_trips.sql this video may be helpful in resolving the issue



<iframe width="100%" height="315" src="https://youtube.com/embed/kL3ZVNL9Y4A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

/


# Setting up dbt for using BigQuery (Alternative A - preferred)
You will need to create a dbt cloud account using [this link](https://www.getdbt.com/signup/) and connect to your warehouse [following these instructions](https://docs.getdbt.com/docs/dbt-cloud/cloud-configuring-dbt-cloud/cloud-setting-up-bigquery-oauth). 

More detailed instructions in [dbt_cloud_setup.md](https://github.com/DataTalksClub/data-engineering-zoomcamp/blob/main/week_4_analytics_engineering/dbt_cloud_setup.md) 

Optional: If you feel more comfortable developing locally you could use a local installation of dbt as well. You can follow the [official dbt documentation](https://docs.getdbt.com/dbt-cli/installation) or follow the [dbt with BigQuery on Docker](https://github.com/DataTalksClub/data-engineering-zoomcamp/blob/main/week_4_analytics_engineering/docker_setup/README.md) guide to setup dbt locally on docker. You will need to install the latest version (1.0) with the BigQuery adapter (dbt-bigquery).



# Setting up dbt for using Postgres locally (Alternative B)
As an alternative to the cloud, that require to have a cloud database, you will be able to run the project installing dbt locally. You can follow the [official dbt documentation](https://docs.getdbt.com/dbt-cli/installation) or use a docker image from [oficial dbt repo](https://github.com/dbt-labs/dbt/). You will need to install the latest version (1.0) with the postgres adapter (dbt-postgres). After local installation you will have to set up the connection to PG in the profiles.yml, you can find the templates [here](https://docs.getdbt.com/reference/warehouse-profiles/postgres-profile)