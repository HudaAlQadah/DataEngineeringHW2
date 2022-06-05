# DataEngineeringHW2
To run this application for UK dag, follow the next steps:
1- make these directories 
 mkdir dags logs plugins data output
2- echo -e "AIRFLOW_UID=$(id -u)\nAIRFLOW_GID=0" > .env

3- init the airflow 
 docker-compose up airflow-init

4- get the docker compose up
 docker-compose up -d

5- now you can find the png in output file and the CSVs in the data file 

6- to stop the docker compose
docker-compose down --volume