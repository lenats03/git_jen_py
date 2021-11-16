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
/*650000000,jh00j654hg04*/
