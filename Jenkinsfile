pipeline {
         agent any
         stages {
                 stage('CheckOut') {
                 steps {
                     echo 'Code CheckOut step'
                 }
                 }
                 stage('Approve Dev') {
                 steps {
                   input('Do you want to proceed?')
                 }
                 }
				 stage('Dev-Deployment') {
                 steps {
                     echo 'Dev deployment'
                 }
                 }
                 stage('Approve QA') {
                 steps {
                   input('Do you want to proceed?')
                 }
                 }
				 stage('QA-Deployment') {
                 steps {
                     echo 'QA deployment'
                 }
                 }
                 stage('Approve-UAT') {
                 steps {
                   input('Do you want to proceed?')
                 }
                 }
				 stage('UAT-Deployment') {
                 steps {
                     echo 'UAT deployment'
                 }
                 }
				  stage('Approve-PROD') {
                 steps {
                   input('Do you want to proceed?')
                 }
                 }
				 stage('PROD-Deployment') {
                 steps {
                     echo 'Prod deployment'
                 }
                 }
              }
}
