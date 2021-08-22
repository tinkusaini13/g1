pipeline {
    agent { label 'master' }
    stages {
        stage('git repo & clean') {
            steps {
              // bat "rmdir  /s /q TicketBookingServiceJunitTesting"
                sh "cd /root/g1"
                sh "git clone https://github.com/kishancs2020/TicketBookingServiceJunitTesting.git"
             }
        }
        stage('install') {
            steps {
                sh "install"
            }
        }
        stage('test') {
            steps {
                sh"echo test"
            }
        }
        stage('package') {
            steps {
                sh "echo packages"
            }
        }
    }
}
