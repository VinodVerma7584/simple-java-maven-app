node {
    stage ('checkout'){
        echo "checkout from github"
        checkout scm
    }
    stage('Build') {
        if (env.BRANCH_NAME == 'master') {
            echo 'I only execute on the master branch'
        } else {
            echo 'I execute elsewhere'
        }
    }
}
