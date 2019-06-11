pipeline{
    agent any
    
    stages{
       
       stage('Pull code from BitBucket'){
           
           steps{
               //checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[credentialsId: '', url: 'https://github.com/martinlindhe/wmi_exporter']]])
                echo "Isnide step 1"
           }
       }
       
       stage('Running Script'){
           
           steps{
               sh "echo Inside gh-pages branch"
           }
       }
       
        
    }
}
