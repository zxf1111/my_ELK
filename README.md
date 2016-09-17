# my_ELK

curl 'localhost:9200/_cat/indices?v'

---------
cd /opt/logstash 
bin/logstash -f xxx.conf   test conf stdoutput
-------------
bin/logstash -e 'input { stdin { } } output { stdout {} }'

hello world 

Pipeline main started

2016-09-17T02:47:33.414Z elk.bj.base-fx.com hello world
-------------------
rpm -qc kibana
------------
cd /opt/logstash
bin/logstash -f /etc/logstash/conf.d/logstash-syslog.conf
-------------
