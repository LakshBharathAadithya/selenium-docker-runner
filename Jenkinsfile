pipeline{
	agent any
	stages{
		stage("Run Test"){
			steps{
				bat "docker-compose up"
			}
		}
		stage("Start Grid"){
			steps{
				bat "docker-compose down"
			}
		}
	}
}
