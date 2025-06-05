pipeline {
    agent any
    stages {
            stage('SCM Checkout') {
                steps {
                    git branch: 'master', url: 'https://github.com/priyanju192/git_lab2.git', credentialsId: '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'
                }
            }
         
            stage('task') {
                steps {
                     sh "ls"
                }
            }
    }
}