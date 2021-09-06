pipeline {
      agent any
      environment {
        PATH = "/Applications/apache-maven-3.8.2/bin:$PATH"
      }
      stages {
            stage('Init') {
                  steps {
                        echo 'Hi, this is Ashok from Morbi'
                        echo 'We are Starting the Testing'
                  }
            }
            stage('Build') {
                  steps {
                        echo 'Building Sample Maven Project'
                  }
            }
            stage('Deploy') {
                  steps {
                        echo "Deploying in Staging Area"
                  }
            }
            stage('Deploy Production') {
                  steps {
                        echo "Deploying in Production Area"
                  }
            }
      }
}