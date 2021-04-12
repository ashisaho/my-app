node{
    stage('SCM checkout'){
    git 'https://github.com/ashisaho/my-app'
    }
    stage('compile-package'){
    sh 'mvn package'
    }
}
