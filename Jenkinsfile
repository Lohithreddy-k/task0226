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
				bat "javac Demo.java"
				bat "main.py"
				}
			}
		}
	}
