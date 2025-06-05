Pipeline{
    agent any

    stages{

        stage('clone'){

            steps{
                git 'https://github.com/asija007/my-jenkins-project.git'
            }
        }

        stage('build'){

            steps{

               echo 'build successfull'
            }
        }

        stage('test'){

            steps{
                echo 'tested successfully '
            }
        }

        stage('deploy'){

            steps{
                echo  'deployed'
            }
        }

        stage('display'){

            steps{

                echo 'display'
            }
        }
    }
}