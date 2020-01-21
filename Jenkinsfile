pipeline {
agent any
     stages {
          stage ('All stages') {
          parallel {
               stage ('build') {
                        steps {
                            echo 'building.....'
                            sleep 50
                              }
                             }
              stage ('deploy') {
                      steps {
                             echo 'deploy....'
                             sleep 50
                             }
                            }
          }
                   }
                 }
}
