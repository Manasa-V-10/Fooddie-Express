pipeline {
   agent any
  stages {
    stage("build") {
      steps {
         echo 'building the application...'
         script{
            def test =(2+2 < 5)? 'goood' :'bad'
            echo "${test}"
         }
      }
   } 
     stage("test") {
      steps {
         echo 'testing the application...'
 } 
} 
     stage("deploy") {
      steps {
         echo 'deploying the application...'
      }
     }
  }
}
