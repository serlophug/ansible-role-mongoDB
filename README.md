Role Name
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