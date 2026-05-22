pipeline {
agent any
stages {
  stage('Checkout') {
    steps {
// Checkout code from the Git repository
     sh 'echo checking out'
   }
  }
stage('Build') {
  steps {
// Build the Java application (replace with your build commands)
  sh 'javac -version'
 }
}
stage('Deploy') {
  steps {
  // Deploy the application (replace with your deployment commands)
  //1st change made from VScode
   sh 'echo "Deploying the application"'
   }
  }
 }
}
