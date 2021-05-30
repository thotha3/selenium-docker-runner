pipeline{
	agent any
		stages("Run Test"){
			steps{
				sh "docker-compose up"
			}
		}
		tages("Bring Grid Down"){
			steps{
				sh "docker-compose down"
			}
		}
	}
}