pipeline{
    agent any
    stages{
        stage("Checkout"){
            steps{
                checkout scm
                script{
                    cat test.txt
                }
            }
        }
        stage("end"){
            steps{
                script{
                    echo "This is last stage."
                }
            }
        }
    }   
}
