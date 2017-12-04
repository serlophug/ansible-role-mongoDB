[![License](https://img.shields.io/badge/license-Apache%202-blue.svg)](https://www.apache.org/licenses/LICENSE-2.0)
[![Build Status](https://travis-ci.org/serlophug/ansible-role-mongoDB.svg?branch=master)](https://travis-ci.org/serlophug/ansible-role-mongoDB)
MongoDB
=========

Install the latest version of MongoDB. 


Role Variables
--------------
- ```cpu_arch```: i686 or x86_64	. Default: ``` x86_64```.

Example Playbook
----------------

Install MongoDB:
```yml
- hosts: all
  roles:
    - { role: 'serlophug.mongoDB'}
```


License
-------

GNU General Public License v2 [1]

[1] https://www.r-project.org/COPYING
