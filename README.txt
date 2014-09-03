Apache Avro™ is a data serialization system.

Learn more about Avro, please visit our website at:

  http://avro.apache.org/

To contribute to Avro, please read:

  https://cwiki.apache.org/AVRO/how-to-contribute.html


For PPC64:
Other packages to install in order to have tests running:
 - Avro 1.7.4 requires snappy-java >= 1.0.4.1
	1.1.1.1 minimum recommended. 1.1.1.3 for PPC64-LE
 - c++ : Boost:
	- sudo -y apt-get install libboost-all-dev
	- yum  -y         install boost-devel
 - js :
	- sudo -y apt-get install npm node nodejs
	- sudo npm install grunt
	- "node" command (from node package) does not work.
	  "nodejs" command works instead.
	  Tests: In 1st line of node_modules/grunt/bin/grunt, replace node by nodejs.
		nodejs is /usr/bin/nodejs
		node   is hashed (/usr/sbin/node -> /usr/sbin/ax25-node)
 - c# :
	- sudo -y apt-get install mono-devel mono-complete nunit-console nunit
 - ruby :
	- sudo apt-get install ruby-echoe ruby-dev ruby-yajl
	  sudo gem install allison

