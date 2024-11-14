
A **Pipeline** in Jenkins automates the flow of CI/CD using a script-based approach. It supports both **Declarative** and **Scripted** syntax, enabling more complex build processes.

## Syntax Types
- **Declarative**: A simplified syntax, with clearly defined stages and steps.
- **Scripted**: More flexible and allows the use of Groovy scripting.

## Example - Declarative Pipeline
```groovy
pipeline {
    agent any
    stages {
        stage('Build') {
            steps { echo 'Building...' }
        }
        stage('Test') {
            steps { echo 'Testing...' }
        }
        stage('Deploy') {
            steps { echo 'Deploying...' }
        }
    }
}```

## Related Topics
- [[Build Jobs]]