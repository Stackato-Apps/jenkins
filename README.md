Jenkins
==========

Jenkins is an extendable open source continuous integration server.
   
	http://jenkins-ci.org/

Deploying on HPE Helion Stackato
--------------------------------
To deploy the application, run these commands:

    $ cd jenkins

And then

    $ cf push

Note
----
This repository uses a modified version of https://github.com/jenkinsci/jenkins/ to ensure compatibility with the [Java Buildpack](https://github.com/cloudfoundry/java-buildpack)
