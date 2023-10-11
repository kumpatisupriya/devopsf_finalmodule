pipeline{
  agent any stages{
    stage("Deploy"){
      steps{
        echo "Deploy successful"
        bat "mvn compile"
      }
    }
    stages("Build"){
      steps{
        echo "Build successful"
        bat "mvn clean"
      }
    }
     stages("Test"){
      steps{
        echo "Test successful"
        bat "mvn test"
      }
    }
  }
}
        
