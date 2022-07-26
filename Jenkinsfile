pipeline {
    agent {
        docker { 
            image 'tieungao1988/terraform'
            alwaysPull true
        }
    }
    stages {
        stage("Terraform checking") {
            steps {
                echo "======Start======="
                sh 'terraform --version'
            }
        }
    }   
}