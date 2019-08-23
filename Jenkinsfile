pipeline {
    agent any
	
    stages {
        stage('Build') {
		
			when{
				changeRequest title:'change-pr'
			}
		
            steps {                
                echo 'Hello World changing request'
            }
        }
    }
}
