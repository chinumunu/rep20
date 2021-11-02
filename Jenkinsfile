node('master') 
{
    stage('Continuous Download_loans') 
	{
    git 'https://github.com/chinumunu/rep20.git'
	}
    stage('Continuous Build_loans') 
	{
    sh 'mvn package'
	}


}
