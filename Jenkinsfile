pipeline {
    agent any

    stages {
        stage('Sync') {
            steps {
                echo 'Syncing..'
                git branch: 'main', url: 'https://github.com/saibalban2/my-portfolio.git'
            }
        }
        stage('Build') {
            steps {
                echo 'Building..'
                
            }
        }
     stage('Test') {
            steps {
                echo 'Testing..'
                
            }
        }
    }
}
