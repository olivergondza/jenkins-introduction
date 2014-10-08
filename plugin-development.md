# Plugin development

## Setup

Import following maven projects in your IDE

- https://github.com/jenkinsci/jenkins
- https://github.com/jenkinsci/sample-extensions
- https://github.com/jenkinsci/ui-samples-plugin

## Topics

- Do I need new plugin?
  - [Remote API](https://wiki.jenkins-ci.org/display/JENKINS/Remote+access+API)
  - [Groovy scripts](https://wiki.jenkins-ci.org/display/JENKINS/Jenkins+Script+Console)
- What can I tweak from plugin?
  - task 1: Log when Jenkins started and finished loading jobs.
  - task 2: Log "START" and "END" at the beginning and end of every build. (hint: `RunListener`)
- [Stapler](http://stapler.kohsuke.org/reference.html)
- Jelly
  - task 3: Create custom `RootAction` with sidepanel
- Localization
  - Java code
  - Jelly
- Jenkins databinding
- Persistence
- Remoting (`Channel`, `FilePath`, `Launcher`)
  - task 4: Run arbitrary java code in slave JVM during build
  - task 5: Text file in slave workspace
  - task 6: Launch process on slave machine
- Jenkins CLI
  - task 7: Create cusom CLI command
- Tests

## Best practices

- Check existing plugins for overlapping functionality
- Choose minimal Jenkins version
- Release back to the community
  - Start in own repo
  - Ask on jenkinsci-dev to fork under jenkinsci org
  - Create community wiki page
  - Release

## Further reading

- https://wiki.jenkins-ci.org/display/JENKINS/Plugins
- https://wiki.jenkins-ci.org/display/JENKINS/Extension+points
- https://wiki.jenkins-ci.org/display/JENKINS/Plugin+tutorial
- https://wiki.jenkins-ci.org/display/JENKINS/Extend+Jenkins
