pipeline {
    agent any

        // Environment Variables
        environment {
        MAJOR = '1'
        MINOR = '0'
        //Orchestrator Services
        UIPATH_ORCH_URL = ""
        UIPATH_ORCH_LOGICAL_NAME = ""
        UIPATH_ORCH_TENANT_NAME = ""
        UIPATH_ORCH_FOLDER_NAME = ""
    }

    stages {

        // Printing Basic Information
        stage('Preparing'){
            steps {
                echo "Jenkins Home ${env.JENKINS_HOME}"
                echo "Jenkins URL ${env.JENKINS_URL}"
                echo "Jenkins JOB Number ${env.BUILD_NUMBER}"
                echo "Jenkins JOB Name ${env.JOB_NAME}"
                echo "GitHub BranhName ${env.BRANCH_NAME}"
                checkout scm

            }
        }
    }

}
