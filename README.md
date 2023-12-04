https://dlcdn.apache.org/spark/spark-3.5.0/spark-3.5.0-bin-hadoop3.tgz


```
wget https://dlcdn.apache.org/spark/spark-3.5.0/spark-3.5.0-bin-hadoop3.tgz
tar zxvf spark-3.5.0-bin-hadoop3.tgz
sudo mv spark-3.5.0-bin-hadoop3 /opt/spark
export SPARK_HOME=/opt/spark
export PATH=$PATH:$SPARK_HOME/bin
source .venv/bin/activate
pip install --upgrade pip
pip install -r requriment.txt 

```

Сервер

```
start-master.sh
```
Доп процесс

```
start-slave.sh
```


https://www.guru99.com/pyspark-tutorial.html
