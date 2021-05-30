pipeline{
	agent any
		stages("Run Test"){
			steps{
				sh "docker-compose up"
			}
		}
		stages("Bring Grid Down"){
			steps{
				sh "docker-compose down"
			}
		}
	}
}