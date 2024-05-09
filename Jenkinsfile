pipeline{

        agent any

        stages{

            stage('Hello from Jenkins job'){

                steps{

                    sh "echo ~/Hello from the Jenkins job"

                }

            }

         stage('Make Files'){

                steps{

                    sh "touch ~/1.txt 2.txt 3.txt 4.txt 5.txt" 

                }

            }
            stage ('Zip and archive'){

              steps{

                sh "zip ~/archive.zip *.txt"
        }

}
}
}
