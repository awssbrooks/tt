pipeline {
  
  agent any
  
  stages {
    
    stage("build") {
      
        steps {
            echo "building the application for dev"
          script {
              def test = 2 +2 > 3 ? 'waoo' : 'not cool'
              echo test is successful
          }
        }
     }
    stage("test") {
      
        steps {
            echo "testing the application"
        }
    }
    
    stage("deploy") {
      
        steps {
             echo "deployinmg the application"
        }
    }
    
  }
  
}
    
