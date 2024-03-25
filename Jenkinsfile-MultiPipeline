pipeline {   
    agent any

    stages {   
        stage('Master') { 
            steps { 
               sh 'echo "This is master branch"' 
            }
        }
     
        stage('sprint1') { 
            steps { 
               sh 'echo "this is sprint1 branch ..."'
            }
        }

        stage("Development") { 
             steps { 
                sh 'echo "Deploying application..."'
            }
        }  
    }
}
