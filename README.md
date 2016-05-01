# Jelastic Railo Cartridge
This cartridge provides [Railo](http://www.getrailo.org/) on Jelastic Platform.

**Railo** server is the fastest CFML engine available, thus is the best way to accelerate your CFML and Java development. Server is fully compatible with JBoss Application Server,  Tomcat and other popular servers.

This server is a good way to develop dynamic and performant web sites due to a mixture of tag and script syntax. It gives an easy way to build Java EE based web applications without the complexities of Java. 

Main features:
* compatibility - interacts with all of the core features of CFML;
* performance - the highest performing CFML engine available;
* extensibility - Railo is open source, so if you run into an issue you can just download the source and add your own custom patch.

Follow the [link](http://ops-docs.jelastic.com/private-add-cartridge) in order to find out how to enable the current cartridge at Jelastic dashboard.

### What Jelastic cartridge is?

Jelastic [Platform-as-Infrastructure](http://docs.jelastic.com/what-is-platform-as-infrastructure) supports **OpenShift’s cartridge model** to make it easier for independent software vendors (ISVs) offering core services in multiple platforms and for a wider array of cloud ecosystems and marketplaces. This open standard for technology packaging and deployment enables ISVs and end-users to integrate their own middleware, databases, and services into the platform and make them available to PaaS developers building applications.

A **cartridge** is an advanced packaging format. In our case, it is represented with existing OpenShift cartridge specifications, extended with Jelastic configurations, to provide more complex functionality and the ability to make adjustments in Jelastic. This additional tuning is required based on the difference between the architectures of the two platforms (Jelastic and OpenShift).

Such configuration is quite easy - you just need to fork a basic cartridge and add custom settings. Detailed instruction on how to create your own cartridge can be seen [here](http://ops-docs.jelastic.com/create-cartridge).


### How to add a cartridge to Jelastic Cloud?

Ready cartridge (your own or one of those we’ve already prepared for you) can be added to the Jelastic PaI via JCA. After that it should be tested and published in order to become available through the dashboard. Find out the details in [this](http://ops-docs.jelastic.com/private-add-cartridge) instruction.
