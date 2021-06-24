properties([[$class: 'GithubProjectProperty', displayName: '', projectUrlStr: 'https://github.com/paswado/pycharm-repo/'], pipelineTriggers([pollSCM('* * * * *')])])
node {
    stage ("one") {
        git branch: 'main', url: 'https://github.com/paswado/pycharm-repo'
        bat "more 1.txt"
    }
}
