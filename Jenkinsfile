node{
  stage('SCM checkout'){
    git 'https://github.com/ashisaho/my-app.git'
  }
  stage('Compile-Package'){
    sh 'mvn package'
  }
}
