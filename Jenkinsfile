pipeline {
    agent any 
    stages {
        stage('CheckOut') { 
            steps {
                checkout scm 
		        current_ws= WORKSPACE 
            }
        }
	}
}
