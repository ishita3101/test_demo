pipeline {
    agent any

    stages {
        stage('Git pull source code'){
            steps{
                git branch: 'main', url: 'https://github.com/ishita3101/test1.git'
            }
        }
        
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
    }
}
