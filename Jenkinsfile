#!/usr/bin/env groovy
pipeline {
    agent any 
    stages {
        stage('Stage 1') {
            steps {
                echo 'Hello world!' 
				echo env.BUILD_ID
				echo currentBuild.displayName
            }
        }
    }
}
