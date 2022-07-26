pipeline {
    agent {
        docker { 
            image 'hashicorp/terraform'
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