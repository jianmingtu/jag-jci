## Templates to create openshift components related to jag-jci-application-secure api deployment

### Command to execute template
1) Login to OC using login command
2) Run below command in each env. namespace dev/test/prod
   ``oc process -f jag-jci-application-secure.yaml --param-file=jag-jci-application-secure.env | oc apply -f -``
