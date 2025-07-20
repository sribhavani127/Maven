pipeline
{
    agent any
    stages
    {
        stage('Download_origin')
        {
            steps
            {
                git 'https://github.com/sribhavani127/Maven.git'
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
