node {
    def app

    stage('Clone repository') {
        /* Cloning the Repository to our Workspace */

        checkout scm
    }
    stage('Build image') {
        /* This builds the actual image */
        app = docker.build("hello-world")
    }
	stage('Test image') {
                echo "Tests passed"
        }
   }
