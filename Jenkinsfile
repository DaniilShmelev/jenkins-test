pipeline {
    agent none

    stages {

        stage ('Hello') {
            agent any

            steps {
                echo 'Hello, '

                sh '''#!/bin/bash

                    echo "Hello from bash"
                    exit 1
                '''
            }
        }
    }
}
