pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
          sh "printenv | sort"
          sh 'bash $WORKSPACE/Build/startnodes.sh'
        
      }
    }

   

  }
}
