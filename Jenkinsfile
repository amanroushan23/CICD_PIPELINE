pipeline {
agent any

stages {
stage('checkout') {
steps {
git url: 'https://github.com/amanroushan23/CICD_PIPELINE.git', branch: 'main'
}
}
stage('build') {
steps {
echo 'Building the project...'
}
}
stage('test') {
steps {
echo 'Running test.....'
}
}
stage('Deploy') {
steps {
echo 'Deploying the project...'
}
}
}
}
