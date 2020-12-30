node{
    stage('Clone') {
        git url: 'https://github.com/abdousmi/jenkins-helloworld.git'
    }
    stage('Build') {
        sh 'javac Main.java'    
    }
    stage('Run') {
        sh 'java Main'
    }
    stage('Test') {
		echo 'Test';
    }
    stage('Deploy') {
		echo 'Deploy';
    }
}
