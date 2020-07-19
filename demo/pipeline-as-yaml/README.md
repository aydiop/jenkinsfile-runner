Pipeline as YAML demo
=====================

This demo shows how to use [Pipeline as YAML](https://plugins.jenkins.io/pipeline-as-yaml/) in Jenkinsfile Runner.
It executes a simple "Hello, world!" Pipeline defined as YAML.

## Running (without Docker)

Once Jenkinsfile Runner is built locally, the demo can be launched as...

```bash
java -jar ../../app/target/jenkinsfile-runner-standalone.jar -p ../../vanilla-package/target/plugins/ -w ../../vanilla-package/target/war/jenkins.war -f ./Jenkinsfile.yml 
```