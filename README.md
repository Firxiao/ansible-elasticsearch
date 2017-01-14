Role Name
=========
Install the elasticsearch 2.x

Requirements
------------
aneible >= 2.2

Role Variables
--------------
```

#Download from https://github.com/medcl/elasticsearch-rtf/releases
elasticsearch_zip: /opt/files/elasticsearch-rtf-2.2.1.zip
elasticsearch_zip_name: elasticsearch-rtf-2.2.1
#Download from http://download.oracle.com/otn-pub/java/jdk/8u111-b14/jre-8u111-linux-x64.rpm
jre_rpm: /opt/files/jre-8u111-linux-x64.rpm
# elasticsearch cluster name 
cluster_name: elasticsearch
# discovery.zen.ping.unicast.hosts
list_of_hosts: '"192.168.33.17","192.168.33.18","192.168.33.19"'
ES_USER: elasticsearch
ES_HOME: /opt/elasticsearch

```

Dependencies
------------

Example Playbook
----------------
```
    - hosts: servers
      roles:
         - { role: Firxiao.elasticsearch }
```

License
-------

MIT

Author Information
------------------

Firxiao
