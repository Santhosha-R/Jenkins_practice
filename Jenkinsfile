pipeline {
    agent any
    stages {
        stage {
            steps ('STAGE1') {
                echo "This is stage1 running"
                sh ''' 
                    ls
                '''
            }
        }
        stage {
            steps ('STAGE2') {
                echo "This is stage2 running"
                sh ''' 
                    pwd
                '''
            }
        }
    }
}