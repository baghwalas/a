pipeline{
    agent any

    tools {
         maven 'Maven2'
         jdk 'jdk'
    }

        stage('build'){
            steps{
               sh 'mvn install -Dv=${BUILD_NUMBER}'
            }
        }
    }
}
