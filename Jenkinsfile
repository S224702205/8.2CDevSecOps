pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building project (npm install or maven compile)'
            }
        }
        stage('Unit and Integration Tests') {
            steps {
                echo 'Running tests (e.g., Jest, Mocha, JUnit)'
            }
        }
        stage('Code Analysis') {
            steps {
                echo 'Running static code analysis (e.g., ESLint, SonarQube)'
            }
        }
        stage('Security Scan') {
            steps {
                echo 'Running dependency and security scans (e.g., npm audit)'
            }
        }
        stage('Deploy to Staging') {
            steps {
                echo 'Deploying app to staging environment'
            }
        }
        stage('Integration Tests on Staging') {
            steps {
                echo 'Running integration tests on staging (e.g., Selenium, Postman)'
            }
        }
        stage('Deploy to Production') {
            steps {
                echo 'Deploying to production environment'
            }
        }
    }
}
