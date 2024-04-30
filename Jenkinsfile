pipeline{
	agent any
	stages{
		stage ('cleaning stage'){
			steps{
				bat "mvn clean"
			}
	}
		stage ('compiling stage'){
			steps{
				bat "mvn compile"
			}
	}
		stage ('installing stage'){
			steps{
				bat "mvn install"
			}
	}
}
}
	
