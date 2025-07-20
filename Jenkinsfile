pipeline
{
    agent any
    stages
    {
        stage('Download_origin')
        {
            steps
            {
                git 'https://github.com/IntelliqDevops/maven.git'
            }
        }
        stage('Build_origin')
        {
            steps
            {
                sh 'mvn package'
            }
        }
   }
}
