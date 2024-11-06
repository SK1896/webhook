pipeline{
	agent{
		label {
			label "built-in"
			
	}
	}
		stages {
			stage('git'){
				steps{
					sh "yum install java-17-amazon-corretto.x86_64 docker -y"
					
				
					

				}
			}
			
			
			stage('copy') {
				steps{
					
						sh "cp -r /mnt/SprintBootService-1/target/SpringBootExecutableJarFileDemo-0.0.1-SNAPSHOT.jar /mnt/velocity/"
					
				}
			}
			
	}

}
