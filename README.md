# Shine-NG
Visualising Web Archive via Solr - Grails Framework version

##### Grails prefers convention over configuration, therefore the location of files defines their purpose. Structure of the grails-app directory:

- **assets** – a place where we store static assets files like styles, javascript files or images
- **conf** – contains project configuration files:
  - *application.yml* contains standard web app settings like data source, mime types, and other Grails or Spring related settings
  - *resources.groovy* contains spring bean definitions
  - *logback.groovy* contains logging configuration
- **controllers** – responsible for handling requests and generating responses or delegating them to the views. By convention, when a file name ends with *Controller, the framework creates a default URL mapping for each action defined in the controller class
- **domain** – contains the business model of the Grails application. Each class living here will be mapped to database tables by GORM
- **i18n** – used for internationalization support
- **init** – an entry point of the application
- **services** – the business logic of the application will live here. By convention, Grails will create a Spring singleton bean for each service
- **taglib** – the place for custom tag libraries
- **views** – contains views and templates
