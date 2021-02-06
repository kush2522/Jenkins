CODE_CHANGES = getGitChanges()
pipeline {
  agent any
    stages {
      stage ('Build') {
        when {
          BRANCH_NAME == 'Test'
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
