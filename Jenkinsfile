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
git branch: 'main', url: 'https://github.com/Bhupi-Test/multibranch_demo.git'
}
}
}
}
