pipeline {
  agent any
  stages{
    stage("build"){
      steps{
        // echo "Building"
        sh "./gradlew assemble"
      }

    }

  
  stage("Test"){
    steps{
      // echo "Testing"
      sh "./gradlew test"
    }

  }

}
}