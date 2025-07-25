pipeline {
	agent any
	stages {
		stage ('init') {
			steps {
			terraform init
			}
		}
		stage ('validate') {
			steps {
			terraform validate
			}
		}
		stage ('plan') {
			steps {
			terraform plan
			}
		}
		stage ('apply') {
			steps {
			terraform apply
			}
		}
	}
}
