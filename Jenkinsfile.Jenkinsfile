pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                svn poll: true, url: 'https://IMATIA177.imatiasl.lan/svn/Repo1/SvnBerto/BertoDemo'
                echo 'Building..'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
             echo 'Deploying....'
            }
        }
    }
}
