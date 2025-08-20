pipeline {
	agent any
	stages{
		stage('checkout'){
			steps{
				git branch:'main',url:
'https://github.com/Dboss666/Jaggu-Gaja.git'
		}
	}
	stage('hello'){
	steps{
		echo "Hello from Jenkins Pipeline!"
		}
	}
	stage('Goodbye'){
		steps{
		echo"Pipeline finished successfully"
		}
	}
	}
}

