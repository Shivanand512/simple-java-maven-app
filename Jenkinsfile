node{
    stage("parallel stages"){
    parallel(
        "Build":{
            sh "mvn clean install"
        },
        "Test":{
            sh "mvn clean test"
        },
        "Deploy":{
            echo "Deployment phase"
        }
        
        )
    }
    

}
