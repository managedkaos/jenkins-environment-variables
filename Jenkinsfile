pipeline {
    agent any

    stages {
        stage('Environment') {
            steps {
                echo "Building.."
                echo "The following variables are available to shell scripts"
                echo "BRANCH_NAME=${env.BRANCH_NAME}"
                echo "BUILD_DISPLAY_NAME=${env.BUILD_DISPLAY_NAME}"
                echo "BUILD_ID=${env.BUILD_ID}"
                echo "BUILD_NUMBER=${env.BUILD_NUMBER}"
                echo "BUILD_TAG=${env.env.BUILD_TAG}"
                echo "BUILD_URL=${env.BUILD_URL}"
                echo "CHANGE_AUTHOR=${env.CHANGE_AUTHOR}"
                echo "CHANGE_AUTHOR_DISPLAY_NAME=${env.CHANGE_AUTHOR_DISPLAY_NAME}"
                echo "CHANGE_AUTHOR_EMAIL=${env.env.CHANGE_AUTHOR_EMAIL}"
                echo "CHANGE_ID=${env.CHANGE_ID}"
                echo "CHANGE_TARGET=${env.CHANGE_TARGET}"
                echo "CHANGE_TITLE=${env.CHANGE_TITLE}"
                echo "CHANGE_URL=${env.CHANGE_URL}"
                echo "EXECUTOR_NUMBER=${env.EXECUTOR_NUMBER}"
                echo "GIT_AUTHOR_EMAIL=${env.GIT_AUTHOR_EMAIL}"
                echo "GIT_AUTHOR_NAME=${env.GIT_AUTHOR_NAME}"
                echo "GIT_BRANCH=${env.GIT_BRANCH}"
                echo "GIT_COMMIT=${env.GIT_COMMIT}"
                echo "GIT_COMMITTER_EMAIL=${env.GIT_COMMITTER_EMAIL}"
                echo "GIT_COMMITTER_NAME=${env.GIT_COMMITTER_NAME}"
                echo "GIT_LOCAL_BRANCH=${env.GIT_LOCAL_BRANCH}"
                echo "GIT_PREVIOUS_COMMIT=${env.GIT_PREVIOUS_COMMIT}"
                echo "GIT_PREVIOUS_SUCCESSFUL_COMMIT=${env.GIT_PREVIOUS_SUCCESSFUL_COMMIT}"
                echo "GIT_URL=${env.GIT_URL}"
                echo "JENKINS_HOME=${env.JENKINS_HOME}"
                echo "JENKINS_URL=${env.JENKINS_URL}"
                echo "JOB_BASE_NAME=${env.JOB_BASE_NAME}"
                echo "JOB_NAME=${env.JOB_NAME}"
                echo "JOB_URL=${env.JOB_URL}"
                echo "NODE_LABELS=${env.NODE_LABELS}"
                echo "NODE_NAME=${env.NODE_NAME}"
                echo "SVN_REVISION=${env.SVN_REVISION}"
                echo "SVN_URL=${env.SVN_URL}"
                echo "WORKSPACE=${env.WORKSPACE}"
				'''
            }
        }
    }
}
