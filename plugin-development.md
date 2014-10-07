# Plugin development

## Setup

Import following maven projects in your IDE

- https://github.com/jenkinsci/jenkins
- https://github.com/jenkinsci/sample-extensions
- https://github.com/jenkinsci/ui-samples-plugin

## Topics

- Do I need new plugin?
- What can I tweak from plugin?
  - task 1: Log when Jenkins started and finished loading jobs.
  - task 2: Log "START" and "END" at the beginning and end of every build. (hint: `RunListener`)
- Stapler - http://stapler.kohsuke.org/reference.html
- Jelly
  - task 3: Create custom `RootAction` with sidepanel
- Jenkins databinding
- Persistence
- Remoting (`Channel`, `FilePath`, `Launcher`)

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
