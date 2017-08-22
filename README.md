# UnitTestingSetup
Unit Testing Setup and links

Karma seems to be a node application, which loads the 
configuration file karma.conf.js as a node module
connects with a Browser and 
runs Jasmine tests.

Sometimes browsers disconnects then 
it might be that browser keeps running the tests,
in the meantime karma tries to connect with it. (there is a setting for timeout browserDisconnectTimeout)

Node starts a Karma web server which listens at some port (by default it is http://localhost:9876/).
