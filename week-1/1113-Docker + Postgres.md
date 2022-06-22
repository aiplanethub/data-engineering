# Docker + Postgres

[Code](https://github.com/DataTalksClub/data-engineering-zoomcamp/blob/main/week_1_basics_n_setup/2_docker_sql)

# Introduction to Docker
* Why do we need Docker
* Creating a simple "data pipeline" in Docker

<iframe width="100%" height="315" src="https://youtube.com/embed/EYNwNlOrpr0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


# Ingesting NY Taxi Data to Postgres
* Running Posgtres locally with Docker
* Using pgcli for connecting to the database
* Exploring the NY Taxi dataset
* Ingesting the data to the database
* Note if you have problems with pgcli, check [this video](https://www.youtube.com/watch?v=3IkfkTwqHx4&list=PL3MmuxUbc_hJed7dXYoJw8DoCuVHhGEQb) for an alternative way to connect to your database


<iframe width="100%" height="315" src="https://youtube.com/embed/2JM-ziJt0WI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


# Connecting pgAdmin and Postgres
* The pgAdmin tool
* Docker networks

<iframe width="100%" height="315" src="https://youtube.com/embed/hCAIVe9N0ow" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


# Putting the ingestion script to Docker
* Converting the Jupyter notebook to a Python script
* Parametrizing the script with argparse
* Dockerizing the ingestion script

<iframe width="100%" height="315" src="https://youtube.com/embed/B1WwATwf-vY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


# Running Postgres and pgAdmin with Docker-Compose
* Why do we need Docker-compose
* Docker-compose YAML file
* Running multiple containers with docker-compose up


<iframe width="100%" height="315" src="https://youtube.com/embed/hKI6PkPhpa0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


# SQL refreshser
* Adding the Zones table
* Inner joins
* Basic data quality checks
* Left, Right and Outer joins
* Group by

<iframe width="100%" height="315" src="https://youtube.com/embed/QEcps_iskgg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

# Optional 
* If you have some problems with docker networking, check Port Mapping and Networks in Docker
* Docker networks
* Port forwarding to the host environment
* Communicating between containers in the network
* .dockerignore file

<iframe width="100%" height="315" src="https://youtube.com/embed/tOr4hTsHOzU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>