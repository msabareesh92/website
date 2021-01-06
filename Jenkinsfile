node{
stage('SCM Checkout')
{ git 'https://github.com/msabareesh92/website'
}
stage('compile')
{
def mvnHome= tool name: 'Maven 3', type: 'maven'
sh "${mvnHome}/bin/mvn package"
}
}
