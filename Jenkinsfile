properties([pipelineTriggers([pollSCM('* * * * *')])])
node{
    stage("clone"){
        git "https://github.com/lenats03/git_jen_py.git"
    }
    stage("show files"){
    bat "dir"    
    }
}
