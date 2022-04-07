pipeline {
    agent any 
stages {
        stage('Build') {
            steps {
                sh "ssh -F /opt/machine-id/ssh_config ubuntu@scottgallagher-node01.scottgallagher.teleportdemo.com 'touch /home/ubuntu/test.text'"
            }
        }
}
