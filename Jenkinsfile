pipeline {
   agent {
     node { label 'workstation'}
   }
   stages {
     stage ('code quality') {
       steps {
          echo 'code quality'
       }
     }
     stage ('lint checks') {
      when {
              branch 'main'
      }
       steps {
           echo 'lint checks'
       }
     }
     stage ('unit tests') {
      when {
            branch 'main'
      }
       steps {
          echo 'unit tests'
       }
     }
     stage ('prepare artifact') {
      when { tag "*" }
       steps {
          echo 'prepare artifact'
       }
     }
   }
}