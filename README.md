# mlops_compose
MLops Services workspace compose

Mlflow - ml workflow and experimenting service  
Dagster - pipeliner ( via airflow)  
Postgres - db  
Minio - s3 storage for artifacts and models  
# params
all params in .env file

minio mlflow folder as bycicle.  
~(dunno effective way to create_bucket automaticly)~

# commands:  
'''
docker compose up -d --build
'''
