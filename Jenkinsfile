pipeline {
  agent any
  tools{
     maven 'M2_HOME'   
  }
  stages {
    stage ('Build'){
      steps {
       sh 'mvn clean'
       sh 'mvn install'
       sh 'mvn package' 
      }
    }
     stage ('test'){
      steps {
       echo "test step"
       sleep 10 
      }
    }
     stage ('Deploy'){
      steps {
       echo "deploy step"
       sh 'mvn test'
      }
    }
    stage ('docker'){
      steps {
       echo "image step"
       sleep 10 
      }
    } 
  }
}
 
      }
    }
     stage ('test'){
      steps {
       echo "test step"
       sleep 10 
      }
    }
     stage ('Deploy'){
      steps {
       echo "deploy step"
       sleep 10 
      }
    }
    stage ('docker'){
      steps {
       echo "image step"
       sleep 10 
      }
    } 
  }
}
