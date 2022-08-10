# jenkins-dsl-pipelines

## Overview

Sample repo demonstrating use of Jenkins DSL Pipelines via IntelliJ that will support code completion and validation.

## What is different about this repository?

* This repository is not a passive gist, but a full / working example of the configuration needed to get this working in the IntelliJ IDE
* Includes additional code within the `jenkins.gdsl` file that will help to avoid a bunch of distracting errors in the `.gdsl` file
* I have expanded and extended a number of closures, properties and other items beyond what is provided OOTB via Jenkins
* I have also expanded upon the great work of a few other Github users [@ramna2913](https://gist.github.com/ranma2913/6c2424a5bda07d12d034502fb4b0b7c2) and [@ggarcia24](https://gist.github.com/ggarcia24/fc5acec3288812b34c64a4f2b8f9bca9)

## IDE Setup

1. Clone repository
2. Add groovy SDK support:
   https://www.bonusbits.com/wiki/HowTo:Add_Groovy_SDK_to_IntelliJ_IDEA
3. Ensure IDE / project config has java configured.
4. Navigate to the .gdsl file and execute the CTA "Activate Back"

## How does it work?

Check out this blog article, as it already provides a good baseline and background.

[https://st-g.de/2016/08/jenkins-pipeline-autocompletion-in-intellij](https://st-g.de/2016/08/jenkins-pipeline-autocompletion-in-intellij)
