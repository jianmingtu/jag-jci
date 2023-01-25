## Templates to create openshift components related to jag-jci-secure api deployment

### Command to execute template
1) Login to OC using login command
2) Run below command in each env. namespace dev/test/prod
   ``oc process -f jag-jci-secure.yaml --param-file=jag-jci-secure.env | oc apply -f -``
