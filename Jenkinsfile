node {

    stage('Build'){
        echo "Building Maven Project"
        echo "Building Stage"
        checkout scm
        sh 'mvn -f Pipeline-Demo/pom.xml clean install'
    }
    stage('Test'){
        echo "Testing Stage"
    }
    stage('Deploy'){
        echo "Deployment Stage"
    }
    
}
