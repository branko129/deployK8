node {
    def app
      
  stage('Deploy to k8') {
    sshagent(['k8_s']) {
    sh 'ssh -o StrictHostKeyChecking=no root@192.168.9.55 kubectl apply -f /tmp/portal-gateway.yaml'
            }
       }
}
