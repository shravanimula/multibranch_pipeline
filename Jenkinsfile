node('built-in') 
{
    stage('Continuous Download_main') 
	{
    git 'https://github.com/sunildevops77/maven.git'
	}
    stage('Continuous Build_main') 
	{
    sh label: '', script: 'mvn package'
	}
  
}
