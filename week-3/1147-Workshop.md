# [Workshop](https://github.com/DataTalksClub/data-engineering-zoomcamp/blob/main/week_3_data_warehouse/airflow.md) 

* Integrating Bigquery with Airflow (+ Week 2 Review) - Video 
<iframe width="100%" height="315" src="https://youtube.com/embed/lAxAhHNeGww" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


* Setup: Copy over the `airflow` directory (i.e. the Dockerized setup) from `week_2_data_ingestion`:

`cp ../week_2_data_ingestion/airflow airflow`

Also, empty the logs directory, if you find it necessary.

* DAG: [gcs_to_bq_dag.py](https://github.com/DataTalksClub/data-engineering-zoomcamp/blob/main/week_3_data_warehouse/airflow/dags/gcs_to_bq_dag.py)