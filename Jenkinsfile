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
            steps {
               echo 'lint checks'
            }
          }
     stage ('unit tests') {
                 steps {
                    echo 'unit tests'
                 }
               }
     stage ('prepare artifact) {
                 steps {
                    echo 'prepare artifact'
                 }
               }
   }
}