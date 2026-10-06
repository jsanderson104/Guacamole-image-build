pipeline {
    agent {
        label "podman"
    }
    stages {
        stage('Build Guacamole Image') {
            steps {
                sh 'bash build-guacamole-image.bash'
            }
        }
        
        stage('Build MariaDB Image') {
            steps {
                sh 'bash build-mariadb-image.bash'
            }
        }
    }
}
