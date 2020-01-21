pipeline {
agent any
     parameters {
          string(name: 'greeting', defaultValue: 'Hello', description: 'How should I greet the world?')
                }
     stages {
          stage ('All stages') {
          parallel {
               stage ('build') {
                        steps {
                             input {`press yes to continue`}
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
