pipeline{
    agent any
    stages{
        stage("Checkout"){
            steps{
                scm checkout
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
