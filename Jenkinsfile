pipeline {
  agent any
  stages{
    stage("build"){
      steps{
        echo "Building"
         ./gradlew assemble
      }

    }

  
  stage("Test"){
    steps{
      echo "Testing"
      ./gradlew test
    }

  }

}
}