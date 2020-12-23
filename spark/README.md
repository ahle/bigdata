




## 
Enter into the shell:
spark-shell
pyspark

## error
basedir must be absolute /.ivy2/local

## environment for pyspark
https://github.com/ahle/bigdata/releases/download/0.1/venv-spark.zip


### Run on zeppelin
 docker run -it -p 18080:18080 -p 8088:8080 -d mirkoprescha/spark-zeppelin-docker
 
### Run spark on jupyter (recommended)
https://medium.com/@suci/running-pyspark-on-jupyter-notebook-with-docker-602b18ac4494

```cmd
docker run --name=spark-notebook -it --rm -p 8888:8888 -v [host_dir]:/home/jovyan/work jupyter/pyspark-notebook

docker exec -it spark-notebook /bin/sh
jupyter notebook list
get token 
http://localhost:8888/?token=e144d004f6652ae6406a78adf894621e62fdeb1fc57d02e8
```

### install spark on windows

```
spark-class org.apache.spark.deploy.master.Master -h 192.168.1.19
spark-class org.apache.spark.deploy.master.Worker spark://192.168.1.19:7077
```

### avro
```
spark-submit --packages org.apache.spark:spark-avro_2.12:3.0.1 --master spark://192.168.0.100:7077 main.py
```

