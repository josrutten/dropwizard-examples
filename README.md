# Dropwizard Examples

This project contains examples of working with [Dropwizard](http://dropwizard.codahale.com). 
Dropwizard is a Java framework for developing RESTful web services with standard Java libraries 
like Jersey and Jackson. Adding to these Dropwizard provides simple yet elegant solutions to 
configuration, metrics, operational tools and more.

# Running the samples

To run the examples simply execute:

    $ mvn exec:java

This runs the main class com.github.bjpbakker.dropwizardexamples.Main with arguments:server config/config.yml

To run the examples simply execute the jar and provide it your configuration. A default 
configuration is available in `config/config.yml`. You can override the default configuration file by running:

    $ java exec:java -Dexec.args="server config/myownconfiguration.yml"

