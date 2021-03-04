node {
    def app
      
  stage('Deploy to k8') {

  steps{
      sshagent(['k8']) {
      sh "ssh root@neomkubedev00.webmedia.int kubectl apply -f /tmp/portal-gateway.yaml"
                }
       }
}
}
