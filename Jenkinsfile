pipeline {
        agent {
                label "podman"
        }
        stages {
                stage('Build Guacamole Image')
                        steps { bash build-guacamole-image.bash }
                
                stage('Build MariaDB Image')
                        steps {bash build-mariadb-image.bash }
                }
}
}
