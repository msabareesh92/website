node{
stage('SCM Checkout')
{ git 'https://github.com/msabareesh92/website'
}
stage('compile')
{
sh 'mvn package'
}
}
