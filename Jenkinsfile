pipeline{
    agent any
    stages{
          stage('Stage one'){
              Steps{
                    echo 'This is first stage of pipeline build'
               }
}

          stage('Stage Two'){
                Steps{
                     echo 'This is Second stage of pipeline build'
                     input('Do You want to proceed')
                     sh "mkdir /docker"
                   }
}
    }
 }         
