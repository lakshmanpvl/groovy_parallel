pipeline {
agent any
     stages {
          parallel (
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
                     )
                   }
                 }
