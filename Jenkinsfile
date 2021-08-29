node('master') 
{
    stage('Continuous Download_testing') 
	{
    git 'https://github.com/sunildevops77/maven.git'
	}
    stage('Continuous Build_testing') 
	{
    sh label: '', script: 'mvn package'
	}
    
}
