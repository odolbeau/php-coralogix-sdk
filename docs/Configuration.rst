Configuration
=============

Using Coralogix PHP SDK requires these mandatory parameters:

* **PRIVATE KEY** - A unique ID which represents your company. This ID will be sent to your mail once you register to `Coralogix`.

* **APPLICATION NAME** - The name of your main application. For example, a company named *“SuperData”* could insert the *“SuperData Production”* string parameter; or if they want to debug their test environment, they might insert the *“SuperData – Test”*.

* **SUBSYSTEM NAME** - Your application probably has multiple subsystems. For example: Backend servers, Middleware, Frontend servers etc. In order to help you examine and filter the data you need, inserting the subsystem parameter is vital.