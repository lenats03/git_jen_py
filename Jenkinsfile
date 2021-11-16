properties([pipelineTriggers([pollSCM('* * * * *')])])
node{
    stage("clone"){
        /*git "https://github.com/lenats03/git_jen_py.git"*/
        git branch: 'second_branch', url: 'https://github.com/lenats03/git_jen_py.git'
    }
    stage("show files"){
    bat "dir"    
    }
}
/*Lena*/
/*65000000000j654hg04*/
