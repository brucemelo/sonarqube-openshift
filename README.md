# SonarQube 9.9 with Postgres 15 on OpenShift

Sonarqube for Openshift

Sonarqube `9.9-community`

Postgres `postgres:15`

Easy yml updated for sonarqube 9.9 with postgres 15.

Just copy the project and changes the values


#### Remember to change the values `host` and `password`

### Run command

``oc apply -f sonarqube-openshift.yml``

### Delete command

``oc delete -f sonarqube-openshift.yml``


### Based on 

https://github.com/OpenShiftDemos/sonarqube-openshift-docker