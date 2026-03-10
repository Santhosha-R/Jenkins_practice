pipeline {
    agent any
    stages {
        stage  ('STAGE1') {
            steps {
                echo "This is stage1 running"
                sh ''' 
                    ls
                    sleep 5
                '''
            }
        }
        stage ('STAGE2') {
            steps  {
                echo "This is stage2 running"
                sh ''' 
                    pwd
                    sleep 5
                '''
            }
        }
    }
}