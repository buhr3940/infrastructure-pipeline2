properties([pipelineTriggers([githubPush()])])
node('linux') {
    git url: 'https://github.com/jasondbaker/infrastructure-pipeline2.git', branch: 'master'
    stage('Test') {
        sh "env"
    }
}
