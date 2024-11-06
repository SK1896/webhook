pipeline{
	agent{
		label {
			label "built-in"
			customWorkspace "/mnt"
	}
	}
		stages {
			stage('git'){
				steps{
					sh "yum update -y"
					sh "yum install java-17-amazon-corretto.x86_64 git docker -y"
					sh "git clone https://github.com/SK1896/SprintBootService-1.git"
				
					

				}
			}
			
			
			stage('copy') {
				steps{
					
						sh "cp -r /mnt/SprintBootService-1/target/SpringBootExecutableJarFileDemo-0.0.1-SNAPSHOT.jar /mnt/velocity/"
					
				}
			}
			
	}

}
