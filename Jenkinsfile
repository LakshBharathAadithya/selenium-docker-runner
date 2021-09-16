pipeline{
	agent any
	stages{
		stage("Run Test"){
			steps{
				sh "docker-compose up"
			}
		}
		stage("Start Grid"){
			steps{
				sh "docker-compose down"
			}
		}
	}
}
