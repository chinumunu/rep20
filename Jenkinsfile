node('master') 
{
    stage('Continuous Download_master') 
	{
    git 'https://github.com/chinumunu/rep20.git'
	}
    stage('Continuous Build_master') 
	{
    sh 'mvn package'
	}


}
