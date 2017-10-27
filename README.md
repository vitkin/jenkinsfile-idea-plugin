# jenkins-pipeline-plugin

An IntelliJ plugin to add support for "Jenkinsfile" pipeline definitions

## Required plugin

- [Grammar-Kit](https://github.com/JetBrains/Grammar-Kit)

## Building

1. Right click on `Jenkins.bnf` and select **Generate Parse Code**
( <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>G</kbd> )

2. Right click on `Jenkins.flex` and select **Run JFlex Generator**
( <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>G</kbd> )
    > **Note:** If asked to select a *Download Directory* keep the
    > default which is the project directory.

3. Right click on the project and select
**Build Module 'jenkins-pipeline-plugin'**.

4. Right click on the project and select
**Prepare Plugin Module 'jenkins-pipeline-plugin' For Deployment**.

## Installing

1. Go to **File** > **Settings...** > **Plugins**.

2. Click on **Install plugin from disk...**.

3. Go to the project folder and choose the file
`jenkinsfile-idea-plugin.jar`.