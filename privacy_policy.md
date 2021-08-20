# Privacy Policy - RASMDep pRMT application

The RASMDep App is built base upone the RADAR-CNS pRMT App app and it is a Free app. The data collected by this app is sent directly to the RASMDep platform hosted at Leitwert AG (Switzerland) as part of the RASMDep project. Only use this app if you have signed consent in person to be part of studies conducted as part of the RASMDep project. The Data Controller of the collected data is ETH Zürich.

This page informs you of the RASMDep project policies regarding the collection, use and disclosure of Personal Information we receive from users of the RASMDep passive Remote Monitoring Technology (pRMT) app.

We use your Personal Information, as described below, only for techinical research conducted by the partners of the RASMDeo project. Personal Information will not be shared with other parties without your consent. By using this app, you agree to the collection and use of the information given below for the purpose of the research stated in the inform consent from only. Anonymised data derived may be made publicly available, identifiable data will not.

## Information Collection and Use

The app is able to collect personally identifiable information from your phone and connected devices. The data collected depends on which functionalities, the so-called plugins, are activated. In the next sections an overview is given of all available plugins and the information they collect. The version of the app determines which plugins are activated. Please check the app description to see which plugins are activated. The data that the app collects will remain within Switzerland.

The personal information collected will be retained by us and used as described in this privacy policy upto 10 years for identifiable contact data. Anonymised data may be preserved indefinitely.

The app does use third party services that may collect information used to identify you, and these may reside outside of the EU. Link to privacy policy of third party service providers used by the app:

    Google Play Services

By using the app statistics plugin listed below, this service may link use of our app with a Google account and phone characteristics.

    OpenWeatherMap

By using the OpenWeatherMap plugin listed below, this service may link the use of its API with an IP address and current location.

## Data types per plugin

### Phone sensors

    * Location of the phone as provided by GPS and/or the cellular network. Coordinates are collected as relative coordinates, making it nearly impossible to determine the absolute location of the phone. Android permissions needed: ACCESS_COARSE_LOCATION and ACCESS_FINE_LOCATION.
    * Call and sms log as provided by the Android system. The following data of calls/sms messages are collected: timestamp, length, type and the irreversibly encoded target phone number (as a sha256 hash). Android permissions needed: READ_SMS and READ_CALL_LOG.
    * Number of contacts in contact list, and number of added and removed contacts. Android permissions needed: READ_CONTACTS. Specific contacts are not stored, only the number of contacts.
    * Phone usage as provided by the Android system. The following usage information is collected: phone startup, shutdown, unlock events, application name, application launch time and application close time. Android permissions needed: PACKAGE_USAGE_STATS.
    * Other non-identifiable phone sensor data; acceleration, gyration, magnetic field, ambient light, battery level and number of bluetooth connections.

### Application Status

General logging of the status of the application. The timezone, connection status, number of records sent and application uptime are logged.

### OpenWeatherMap plugin

Using the OpenWeatherMap API, the weather plugin collects data about the approximate weather local to the phone. It uses the location of the phone to query the data from OpenWeatherMap, but does not collect location itself.
