# Introduction

Using [myshuttle](https://github.com/joshjohanning-org/MyShuttle) app to do a Sonarqube demo

# Sonarqube setup

Running this on Codespaces, but can run this from anywhere

```bash
docker run -d --name sonarqube -e SONAR_ES_BOOTSTRAP_CHECKS_DISABLE=true -p 9000:9000 sonarqube:latest
```

To start/stop the container: 

```bash
docker stop 8ca696a97753
docker start 8ca696a97753
```

To view logs:

```bash
docker logs 8ca696a97753 -f 
```

# Sonarqube Server info

Sonar Server URL for this Codespace: https://joshjohanning-org-sonarqube-test-5xgpv494cv6gq-9000.githubpreview.dev
Project ID: github-sonarqube-test
