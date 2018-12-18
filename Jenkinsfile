node{
   stage('Scm Checkout'){
      git 'https://github.com/cyberkingsam/my-app'
   }
   stage('Compile-Package'){
         sh 'mvn package'
         }
   stage('sending-email-notificatio')
   {
      mail bcc: '', body: '''Hi,

Jenkins build notification.

Thanks,
Jenkins''', cc: 'mynameissam2010@gmail.com', from: '', replyTo: '', subject: 'Jenkins build notification', to: 'saxenasam@outlook.com'
   }
}


