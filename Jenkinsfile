pipeline {
  agent any
    stages {
      stage ('Build') {
        when {
          expression {
            BRANCH_NAME == 'Test'
          }
        }
        steps{
           echo "This is a build stage"      
        }
      }
      stage ('Test') {
        steps{
         echo "This is a Test Stage"
        }
      }
      stage ('Final') {
        steps{
         echo "This is a Final Stage"
        }
      }
    }
}
