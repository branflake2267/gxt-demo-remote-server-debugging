# gxt-demo-remote-server-debugging
Demo remote super dev mode debugging

## Debugging
Init Debugging by running `mvn install -Pdebug`. 

### Steps in the debug build profile

1. Copy module.nocache.js to the target build project folder. Start the code server get the module.nocache.js super dev mode file.
2. get the local ip address
3. replace the $wnd.location.hostname with local ip
4. deploy the war to the remote server
