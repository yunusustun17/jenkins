pipeline{
	agent any
	stages{
		stage("permission"){
			steps{
				sh "chmod +x hello.sh"
			}
		}
		stage("test"){
			steps{
				sh "./hello.sh"
			}
		}
	}
}
