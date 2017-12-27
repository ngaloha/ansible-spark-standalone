Role Name
=========

Installation of Spark standalone

Requirements
------------

Java

Role Variables
--------------
spark.version
  default 2.2.1
scala.varion
  default 2.11
hadoop.version
  default 2.7


Dependencies
------------
No

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: mgalokha.ansible-spark-standalone, spark.version: 2.2.1 }

License
-------

Apache

Author Information
------------------

Nazar Halokha
