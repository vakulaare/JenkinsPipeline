pipeline{
    agent any
    stages{
          stage('Stage one'){
              steps{
                    echo 'This is first stage of pipeline build'
               }
}

          stage('Stage Two'){
                steps{
                     echo 'This is Second stage of pipeline build'
                     input('Do You want to proceed')
               
                   }
}
    }
 }         
