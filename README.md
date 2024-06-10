# TFG

Titulo: GESTIÓN CENTRALIZADA DE LOGS PARA SERVICIOS BIG DATA DESPLEGADOS SOBRE UNA ARQUITECTURA CENTRADA EN EL DATO

# LOCAL

El fichero desplieguev1.yaml es un despliegue inicial en local sin utilizar Filebeat, era Logstash el recolector de logs, el fichero desplieguev2.yaml incluye Filebeat en el despliegue local con Docker.

Los ficheros admin, cliente, consumer, producer son utilizados para indicar las credenciales al acceder a Kafka.
jaas.conf es donde se indican las credenciales correctas de Kafka.

Filebeat.yml es el fichero de configuracion de Filebeat.

logstash.conf y logstash.yml son los dos ficheros de configuracion de Logstash.

logstashComplejoFilebeat, logstashLocal, logstashSimpleFilebeat son ficheros de prueba utilizados para probar diferentes configuraciones de Logstash.

# GOOGLE CLOUD CON DOCKER

El fichero despliegueDocker.yaml es el utilizado para desplegar tanto el stack ELK como los servicios de la plataforma big data en Google Cloud con Docker.

# GOOGLE CLOUD CON KUBERNETES

En el directorio Kubernetes se encuentran los ficheros utilizados para desplegar Kibana y Elasticsearch en Kubernetes. Los ficheros de Filebeat, Logstash, Kafka están en desarrollo o son pruebas.
