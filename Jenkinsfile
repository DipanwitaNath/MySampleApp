pipeline {
  agent any
     stages {
       stage ("build") {
         steps {
           echo "build stage is in progress"
           script {
              def test = 2 +5 > 6 ? 'cool': 'not cool'
              echo test
           }
         }
       }
       stage ("test") {
         steps {
           echo "test stage is in progress"
           echo "jenkins automation test again" 
         }         
       }
       stage ("deploy") {
         steps {
           echo "deploy stage is in progress"
         }         
       }       
     }
}
