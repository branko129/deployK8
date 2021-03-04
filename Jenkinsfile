node {
    def app
      
  stage('Deploy to k8') {
    sshagent(['k8_s']) {
    sh 'ssh root@neomkubedev00.webmedia.int kubectl apply -f /tmp/portal-gateway.yaml'
            }
       }
}
