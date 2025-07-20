pipeline{

agent {
  label 'AGENT-1'
} 

stages {

    stage('Build'){
     
     steps{

      sh "echo this build"
     }

    }



    stage('Test'){
     
     steps{
        sh "echo this test"
     }

    }


   stage('Deploy'){
     
     steps{
        sh "echo this deploy"
     }

    }
}




post{

  always{
    echo" this sections run always"
  }
  success{
    echo" this section run when pipeline success"
  }
  failure{
    echo" this section run when pipe line failure"
  }
}

}