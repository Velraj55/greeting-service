pipeline{

    agent any

    stages{

        stage('Deploy') {

            steps {

                sh '''

                    oc project fjjewr-deploy-strategies

                    oc start-build greeting-service --follow --wait

                '''

            }

        }

    }

}
