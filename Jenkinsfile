pipeline {
  
  agent any
  
  stages {
    
    stage("build") {
      
        steps {
            echo "building the application for dev environtment"
          script {
              def test = 2 +2 > 3 ? 'waoo' : 'not cool'
              echo test
          }
        }
     }
    stage("test") {
      
        steps {
            echo "testing the application today"
        }
    }
    
    stage("deploy") {
      
        steps {
             echo "deployinmg the application"
        }
    }
    
  }
  
}
    
