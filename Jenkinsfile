pipeline 
	{	
	agent any
	stages
		{
		stage("git")
			{
			steps
				{
				git "https://github.com/Lohithreddy-k/task0226.git"
				}
			}
		stage("run")
			{
			steps
				{
				sh "java Demo.java"
				sh "python3 main.py"
				}
			}
		}
	}
