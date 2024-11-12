# End-to-End ETL Pipeline


## Technologies Used

- [**Apache Kafka**](https://kafka.apache.org/documentation/)
- [**Apache Airflow**](https://airflow.apache.org/docs/)
- [**Docker**](https://docs.docker.com/compose/intro/compose-application-model/)
- [**SQLAlchemy**](https://docs.sqlalchemy.org/en/20/intro.html)
- [**Pandas**](https://pandas.pydata.org/docs/user_guide/index.html#user-guide)
- [**NumPy**](https://numpy.org/doc/2.1/user/basics.html)
- [**Apache Spark**](https://spark.apache.org/docs/3.5.3/)
- [**PostgreSQL**](https://www.postgresql.org/docs/current/index.html)


## Prerequisites
- Python 3.8+
- Docker
- Venv or Conda


## Set up a Virtual Environment

```sh
python3 -m venv venv
source venv/bin/activate  
```

## Install Dependencies

```sh
pip install pandas numpy sqlalchemy pyspark apache-airflow
```


## Usage

1. Initialize the Airflow database:
```sh
airflow db init
```

2. Start the Airflow web server and scheduler:
```sh
airflow webserver --port 8080
airflow scheduler

```






