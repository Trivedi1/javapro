node
{
    stage('checkout')
    {
        checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [],         userRemoteConfigs: [[credentialsId: 'f9985d40-89d5-4d59-8df5-2b14731714dc', url: 'https://github.com/Trivedi1/javapro.git']]])
        def workspace;
    }
    stage('static code analysis')
    {
        echo 'static code analysis'
    }
    stage('Build')
    {
        echo 'Build the code'
    }
    stage('Test')
    {
        echo 'Test the code'
    }
    stage('Delivery')
    {
        echo 'Delivery the code'
    }
}

