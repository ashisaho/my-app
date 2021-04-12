node{
  stage('SCM checkout'){
    git 'https://github.com/ashisaho/my-app.git'
  }
  stage('Compile-Package'){
    sh 'mvn package'
  }
  stage('Email Notification'){
    mail bcc: '', body: 'welcome to email alerts ', cc: '', from: '', replyTo: '', subject: 'jenkinsjob', to: 'learnme.work@gmail.com'
  }
}
