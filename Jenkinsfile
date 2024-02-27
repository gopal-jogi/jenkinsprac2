pipeline
	{
	agent any
	stages
		{
		stage("GIT")
			{
			steps
				{
					git "https://github.com/gopal-jogi/jenkinsprac2.git "
				}
			}
		stage("Run")
			{
			steps
				{
					bat "javac Demo.java"
					bat "java Demo.java"
					bat "python3 main.py"
						
				}
			}
		}
	}
