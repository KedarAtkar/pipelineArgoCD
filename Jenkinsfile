pipeline{
    agent any
    stages{
        stage("Checkout"){
            steps{
                scm Checkout
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
