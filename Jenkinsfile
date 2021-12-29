node('built-in') 
{
    stage('Continuous Download') 
	{
    git 'https://github.com/umeshkiran92/multi-project.git'
	}
    stage('Continuous Build') 
	{
    sh label: '', script: 'mvn package'
	}
 }
