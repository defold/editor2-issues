# Defold Editor 2.0 issues

This repository exists to track [issues](https://github.com/defold/editor2-issues/issues) for the new [Defold editor](http://www.defold.com/editor-two).

The repository also tracks user submitted feature requests and bugs for the engine. Do note that this isn't the master list for engine issues. All engine issues are tracked in a private JIRA project. Issues reported here will get fed into the JIRA project.

Please comment any issue that you don't agree with in terms of the labels below.

## Labels

### Severity

This list is more or less also the exact order in which we fix issues. See 'Switches' below for exceptions to this.

* *blocker* Something that makes you not want to continue using Defold, including any errors like java exceptions and show-stoppers.
* *serious* A bug which has a negative impact on productivity
* *feature* A new thing outside the current feature set
* *minor* A bug or error, but that doesn't really impact productivity

### Switches

* *quick-win?* We suspect the issue is really quick to fix. We check any such issues after we fix *blocker*, but before *serious* issues.
* *embarrassing* An issue that severely hurts our pride as coders, which makes it more likely to be fixed faster.
* *duplicate* Already reported, but left for adding info
* *engine* It's more an issue in the engine part of Defold, rather than editor
* *more-info* We need more info from the reporter in order to understand the issue
* *new* Automatically added to issues reported from "Help > Report Issue" inside the editor
* *kp* Internal use
* *simple* Issue suitable for new editor developers

### Categories
* *text-editor* Related to the text editor
* *debugger* Related to the built in debugger
* *bob* Related to bob/CI
* *3D* Related to 3D
* *documentation* Error in documentation
* *jdk* We suspect a jvm/javafx bug

![Editor screenshot](https://raw.githubusercontent.com/defold/editor2-issues/master/editor.png)
