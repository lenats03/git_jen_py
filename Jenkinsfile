properties([pipelineTriggers([pollSCM('* * * * *')])])
node{
    stage("clone"){
        git "https://github.com/lenats03/git_jen_py.git/master"
    }
    stage("show files"){
    bat "dir"    
    }
}
