pipeline {
    agent { label 'master' }
    stages {
        stage('git repo & clean') {
            steps {
              // bat "rmdir  /s /q TicketBookingServiceJunitTesting"
                sh "cd /root/ax"
                sh "git clone https://github.com/kishancs2020/TicketBookingServiceJunitTesting.git"
             }
        }
        stage('install') {
            steps {
                echo "install"
            }
        }
        stage('test') {
            steps {
                echo "test"
            }
        }
        stage('package') {
            steps {
                echp "packages"
            }
        }
    }
}
