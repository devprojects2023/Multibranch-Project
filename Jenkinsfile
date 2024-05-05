pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
    }
    
    stages {
        stage('Git') {
            steps {
                 git branch: 'main', url: 'https://github.com/devprojects2023/Multibranch-Project'
            }
        }
    }
}
