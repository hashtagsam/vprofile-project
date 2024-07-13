pipeline {
    
	agent any
	
    stages{ 
        
        stage('Test'){
            steps {
                echo 'Hello World'
            }
            
        }

        stage('cat ReadMe file'){
            when {branch "vp-rem" }

            steps {
                sh '''
                    cat 'Hello World'
                '''
            }

                    
        }

    }


}
