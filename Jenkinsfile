pipeline{
  agents any
  stages{
    stage("Clone"){
      steps{
        echo "Cloning the code from github."
      }
    }
    stage("Build"){
      steps{
        echo "Building the cloned code from Github."
      }
    }
    stage("Test"){
      steps{
        echo "Testing the code."
      }
    }
    stage("Deploy"){
      steps{
        echo "Deploying the application."
      }
    }
  }
}
