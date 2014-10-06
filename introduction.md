# Introduction

- what is jenkins

## Basics

- job lifecycle
- using slaves

## Advanced topics

- Build triggers
- Job Parameters
- Build pipelines
- Matrix jobs

## Plugins

### SCM
- git
- subversion

### Build steps
- shell
- build tools (maven, ant, gradle)

### Post build steps
- notifiers (mail, email-ext, irc)
- archivers (artifacts, test results, specific reports, html publisher)
- external publishers (deploying)

## Best partices

- Keep source in SCM, not in job configration
- Avoid manual steps - automate build triggering and result notifications
- Restrict jobs to label, not particual slave names

## Further reading

http://www.wakaleo.com/books/jenkins-the-definitive-guide
https://wiki.jenkins-ci.org/display/JENKINS/Use+Jenkins
