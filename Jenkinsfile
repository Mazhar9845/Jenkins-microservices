
pipeline { 
   agent { docker { image 'maven:3.6.3'}}
      stages {
      stage('Allah') {
            steps {
               echo 'Allah'
            }
        }
        stage('Testing Docker') {
            steps {
               echo 'build'
            }
        }
        stage('Test') {
            steps {
            
		echo "Test"
	}
  }
  }
  post {
      always {
         echo "Allah"
         }
      success {
          echo " I a doing hard work for the success"
          }
         }
  }
