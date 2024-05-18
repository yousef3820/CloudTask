pipeline {
    agent any
    stages {
        stage('Hello') {
            steps{
                git branch: 'main', credentialsId: 'f512e789-c8df-4387-8630-0b323053dd97', url: 'https://github.com/yousef3820/name.git'
            }
        }
        stage('Execute Commands') {
            steps {
                // Step 2: Execute a Windows batch command
                bat 'CloudTask.bat'          
        }
    }
}
