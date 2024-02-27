pipeline 
	{	
	agent any
	stages
		{
		stage("git")
			{
			steps
				{
				git "https://github.com/Lohithreddy-k/jenkins.git"
				}
			}
		stage("run")
			{
			steps
				{
				bat "mvn clean"
				}
			}
		}
	}
