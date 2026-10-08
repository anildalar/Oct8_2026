pipeline{
  agent any
  stages{
    stage("Stage 1"){
      steps{
        //sh 'linux command';
        sh "echo RAHUL SHARMA"
        sh ''' 
            whoami 
            ls -al
            cat /etc/os-release
        '''
      }
    }
  }
}
