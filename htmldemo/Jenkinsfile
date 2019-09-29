pipeline
{
    agent any
    {
        stages
        {
            stage('initializtaion')
            {
                steps
                {
                    build : 'mvn -f htmldemo/pom.xml clean install'
                }
            }
        }
    }
}