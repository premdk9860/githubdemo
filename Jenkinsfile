pipeline
{
agent any
stages
{
stage('clone')
{
steps{
git 'https://github.com/premdk9860/prem.git'
}
}
stage('build')
{
steps{
sh 'javac hello.java'
}
}
stages('run')
{
steps
{
sh 'java hello'
}
}
}
}
