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
        stage ('PARALLEL TEST') {
            parallel {
                stage ('men') {
                    steps  {
                        echo "This is men running"
                        sh ''' 
                            
                            sleep 5
                        '''
                    }
                }
                stage ('chaild') {
                    steps  {
                        echo "This is chaild running"
                        sh ''' 
                            
                            sleep 5
                        '''
                    }
                }
                stage ('baby') {
                    steps  {
                        echo "This is baby running"
                        sh ''' 
                        
                            sleep 5
                        '''
                    }
                }
            }
        }
        stage  ('STAGE2') {
            steps {
                echo "This is stage2 running"
                sh ''' 
                    ls
                    sleep 5
                '''
            }
        }
    }
}