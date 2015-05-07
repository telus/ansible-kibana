# ansible-kibana

[Kibana](https://www.elastic.co/products/kibana) - Explore & Visualize Your Data

[![Platforms](http://img.shields.io/badge/platforms-ubuntu-lightgrey.svg?style=flat)](#)

Tunables
--------
* `kibana_elasticsearch_url` (string) - Where should kibana look for elasticsearch.

Dependencies
------------
* [telusdigital.apt-repository](https://github.com/telusdigital/ansible-apt-repository/)

Example Playbook
----------------
    - hosts: servers
      roles:
         - role: telusdigital.kibana

License
-------
[MIT](https://tldrlegal.com/license/mit-license)

Contributors
------------
* [Aaron Pederson](https://aaronpederson.github.io) | [e-mail](mailto:aaronpederson@gmail.com) | [Twitter](https://twitter.com/GunFuSamurai) 
