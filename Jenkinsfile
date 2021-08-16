properties([pipelineTriggers([pollSCM('* * * * *')])])
node {
    stage ("clone"){
        git branch: 'main', url: 'https://github.com/shovalg/jenkins-Ex.1.git'
    }
    stage ("shared files"){
        bat "dir"
    }
}
