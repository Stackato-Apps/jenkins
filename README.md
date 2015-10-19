Jenkins
==========

Jenkins is an extendable open source continuous integration server.
   
	http://jenkins-ci.org/

Deploying on HPE Helion Stackato
--------------------------------
To deploy the application, run these commands:

    $ cd jenkins

And then

    $ stackato push -n

Note
----
This repository contains the extracted contents of a jenkins.war file for compatibility with the HPE Helion Stackato App Store. The source used to generate the aforementioned war file can be found at https://github.com/jenkinsci/jenkins/ and has been modified to be compatible with the built-in [Java Buildpack](https://github.com/cloudfoundry/java-buildpack/tree/v2.4).
