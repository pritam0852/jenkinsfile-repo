// declarative pipeline

pipeline{
	agent any
	
	stages{

		stage('cloning'){
			steps{
				git branch: 'main', url: 'https://github.com/pritam0852/jenkinsfile-repo.git'
				echo "clone sucessfull"

			}
		}
		
	}
}