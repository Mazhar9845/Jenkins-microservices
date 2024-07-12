
pipeline { 
   agent any
   environment {
       
       mavenHome = tool 'mymaven'
       dockerHome = tool 'mydocker'
       PATH = $mavenHome/bin:$dockerHome/bin:$PATH
       
       }
      stages {
      stage('Allah') {
            steps {
               echo 'Allah'
            }
        }
        stage('Testing Docker') {
            steps {
               echo 'build'
               sh 'docker version'
               sh 'mvn --version'
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
