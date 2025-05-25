pipeline{
    agent any
    stages{
        stage("Checkout"){
            steps{
                checkout scm
                script{
                    def fileContent = readFile 'test.txt'
                    echo fileContent
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
