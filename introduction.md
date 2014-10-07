# Introduction

- what is jenkins

## Basics

- Job lifecycle
- Using slaves
- Job organization (folders, views, nested views)

## Advanced topics

- Build triggers (periodical, SCM polling/notification)
- Job Parameters
- Build pipelines
  - [Build Pipeline Plugin](https://wiki.jenkins-ci.org/display/JENKINS/Build+Pipeline+Plugin)
- Matrix jobs
- Remote access
  - [CLI](https://wiki.jenkins-ci.org/display/JENKINS/Jenkins+CLI)
  - [Remote API](https://wiki.jenkins-ci.org/display/JENKINS/Remote+access+API)
  - Client for [Python](https://pypi.python.org/pypi/jenkinsapi) and [Ruby](http://rubydoc.info/gems/jenkins_api_client/1.0.1/frames)

## Plugins

### SCM
- git
- subversion
- multiple SCM

### Build steps
- shell
- build tools (maven, ant, gradle)
- [Beaker Builder Plugin](https://wiki.jenkins-ci.org/display/JENKINS/Beaker+Builder+Plugin)

### Post build steps
- notifiers (mail, email-ext, irc)
- archivers (artifacts, test results, specific reports, html publisher)
- external publishers (deploying)

### Misc
- [EnvInject Plugin](https://wiki.jenkins-ci.org/display/JENKINS/EnvInject+Plugin)
- [JobConfigHistory Plugin](https://wiki.jenkins-ci.org/display/JENKINS/JobConfigHistory+Plugin)
- [Xvnc Plugin](https://wiki.jenkins-ci.org/display/JENKINS/Xvnc+Plugin)
- [Build-timeout Plugin](https://wiki.jenkins-ci.org/display/JENKINS/Build-timeout+Plugin)
- [Timestamper](https://wiki.jenkins-ci.org/display/JENKINS/Timestamper)
- [Ownership Plugin](https://wiki.jenkins-ci.org/display/JENKINS/Ownership+Plugin)
- [Dashboard View](https://wiki.jenkins-ci.org/display/JENKINS/Dashboard+View)

## Best partices

- Keep source in SCM, not in job configration
- Avoid manual steps - automate build triggering and result notifications
- Restrict jobs to label, not particual slave names

## Further reading

- http://www.wakaleo.com/books/jenkins-the-definitive-guide
- https://wiki.jenkins-ci.org/display/JENKINS/Use+Jenkins
- https://wiki.jenkins-ci.org/display/JENKINS/Plugins
