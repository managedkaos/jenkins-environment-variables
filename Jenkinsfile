pipeline {
    agent any

    stages {
        stage('Environment') {
            steps {
                echo 'Building..'
				sh '''
					#!/bin/bash 
					echo "The following variables are available to shell scripts"
					echo BRANCH_NAME=${BRANCH_NAME}
					echo BUILD_DISPLAY_NAME=${BUILD_DISPLAY_NAME}
					echo BUILD_ID=${BUILD_ID}
					echo BUILD_NUMBER=${BUILD_NUMBER}
					echo BUILD_TAG=${BUILD_TAG}
					echo BUILD_URL=${BUILD_URL}
					echo CHANGE_AUTHOR=${CHANGE_AUTHOR}
					echo CHANGE_AUTHOR_DISPLAY_NAME=${CHANGE_AUTHOR_DISPLAY_NAME}
					echo CHANGE_AUTHOR_EMAIL=${CHANGE_AUTHOR_EMAIL}
					echo CHANGE_ID=${CHANGE_ID}
					echo CHANGE_TARGET=${CHANGE_TARGET}
					echo CHANGE_TITLE=${CHANGE_TITLE}
					echo CHANGE_URL=${CHANGE_URL}
					echo EXECUTOR_NUMBER=${EXECUTOR_NUMBER}
					echo GIT_AUTHOR_EMAIL=${GIT_AUTHOR_EMAIL}
					echo GIT_AUTHOR_NAME=${GIT_AUTHOR_NAME}
					echo GIT_BRANCH=${GIT_BRANCH}
					echo GIT_COMMIT=${GIT_COMMIT}
					echo GIT_COMMITTER_EMAIL=${GIT_COMMITTER_EMAIL}
					echo GIT_COMMITTER_NAME=${GIT_COMMITTER_NAME}
					echo GIT_LOCAL_BRANCH=${GIT_LOCAL_BRANCH}
					echo GIT_PREVIOUS_COMMIT=${GIT_PREVIOUS_COMMIT}
					echo GIT_PREVIOUS_SUCCESSFUL_COMMIT=${GIT_PREVIOUS_SUCCESSFUL_COMMIT}
					echo GIT_URL=${GIT_URL}
					echo JENKINS_HOME=${JENKINS_HOME}
					echo JENKINS_URL=${JENKINS_URL}
					echo JOB_BASE_NAME=${JOB_BASE_NAME}
					echo JOB_NAME=${JOB_NAME}
					echo JOB_URL=${JOB_URL}
					echo NODE_LABELS=${NODE_LABELS}
					echo NODE_NAME=${NODE_NAME}
					echo SVN_REVISION=${SVN_REVISION}
					echo SVN_URL=${SVN_URL}
					echo WORKSPACE=${WORKSPACE}
				'''
            }
        }
    }
}
