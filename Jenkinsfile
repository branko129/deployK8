node {
    def app
      
  stage('Deploy to k8') {
    sshagent(['k8_s']) {
    sh 'scp /tmp/test root@neomkubedev00.webmedia.int:/tmp'
            }
       }
}
