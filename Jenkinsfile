pipeline {
    
	agent any
	
    stages{ 
        
        stage('Test'){
            steps {
                echo 'Hello World'
            }
            
        }

        stage('cat ReadMe file'){
            when {branch "vpro-*" }

            steps {
                sh '''
                    cat 'Hello World'
                '''
            }

                    
        }

    }


}
