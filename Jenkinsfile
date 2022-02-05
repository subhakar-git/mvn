node('master') 
{
    stage('ContinuousDownload_Main')
    {
        git 'https://github.com/intelliqittrainings/maven.git'             
    }
    stage('ContinuousBuild_Main')
    {
        sh 'mvn package'
    }
    
}
