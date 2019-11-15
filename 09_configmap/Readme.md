ConfigMaP:

Configuration Parameters that are not secrets can be put into a configmap.

The input can be key value pairs or .conf files themselves

The configmap key-value pairs can be read by the app using:
  ENVIRONMENT VARIABLES

  CONTAINER COMMAND LINE ARGUMENTS IN THE POD CONFIGURATION

  USING VOLUMES

The full config file can be mounted using volumes where the application expects it's config
file.This way the config setting are injeted into the container without changing the container itself.


We can generate config files from files by:

1> Using files(here app.properties).
COMMAND: kubectl create configmap app-config --from-file=app.properties