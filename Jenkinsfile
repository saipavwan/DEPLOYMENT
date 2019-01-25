pipeline {
    stages {
        stage ('Build') {
            steps{
            
           echo "Preparing the application....."
            npm install
	    bower install
            """
            }
        }
        stage ('Tests') {
            steps {

                echo "Testing the application...."
                grunt all
                """     
            }
        }
    } 
}
