pipeline
{
agent any
tools
{
maven 'mymaven'
}
stages
{
stage('clone repo')
{
steps
{
git branch: 'dev', url: 'https://github.com/Bhupi-Test/Multi_Branch_project.git'
}
}
}
}
