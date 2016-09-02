install_java
============

Deploy openJDK 7 and 8 and declare 8 as default version


Role Variables
--------------

Default var
install_java_alternative_path: "/usr/lib/jvm/java-8-openjdk-amd64/jre/bin/java" (could be used to declare JAVA7 as default version)
install_java_apt_openjdk8_repository: "ppa:openjdk-r/ppa"   (openjdk8 repository)
install_java_apt_cache_update: yes   (apt-get update ?)
install_java_apt_cache_lifetime: 3600   (minimum number of seconds between cache upgrade )


How to use 
----------

Put here the way to use this role.

    - hosts: server
      roles:
         - { role: install-java }

License
-------

Licensed under the MIT License. See the [LICENSE](LICENSE) file for details.


Author Information
------------------

See my other "work on my computer" ansible things on https://www.github.com/bjolivot
