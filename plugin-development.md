# Plugin development

## Setup

Import following maven projects in your IDE

- https://github.com/jenkinsci/jenkins
- https://github.com/olivergondza/jenkins-workshop

Make sure you can build jenkins-workshop using `mvn clean package`.

## Topics

- Do I need new plugin?
  - [Remote API](https://wiki.jenkins-ci.org/display/JENKINS/Remote+access+API)
  - [Groovy scripts](https://wiki.jenkins-ci.org/display/JENKINS/Jenkins+Script+Console)
- What can I tweak from plugin?
  - [`@Initializer`](http://javadoc.jenkins-ci.org/hudson/init/Initializer.html)
  - task 1: Log when Jenkins started and finished loading jobs.
  - [`@Extension`](http://javadoc.jenkins-ci.org/hudson/Extension.html)
  - task 2: Log "START" and "END" at the beginning and end of every build. (hint: `RunListener`)
- [Stapler](http://stapler.kohsuke.org/reference.html)
- [Jelly](https://wiki.jenkins-ci.org/display/JENKINS/Basic+guide+to+Jelly+usage+in+Jenkins)
  - task 3: Create custom `RootAction` with sidepanel
- Localization
  - Java code
  - Jelly
- Jenkins databinding
  - [`@DataBoundConstructor`](https://github.com/stapler/stapler/blob/master/core/src/main/java/org/kohsuke/stapler/DataBoundConstructor.java)
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
