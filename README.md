# sde-mini-project

USE THE PYTHON ENV

smartCityEnv\Scripts\activate

INSTALL FROM requirements.txt

```bash
docker exec -it sde-mini-project-spark-master-1 spark-submit --master spark://spark-master:7077 --packages org.apache.spark:spark-sql-kafka-0-10_2.12:3.5.0,org.apache.hadoop:hadoop-aws:3.3.1,com.amazonaws:aws-java-sdk:1.11.469 jobs/spark-city.py
```
