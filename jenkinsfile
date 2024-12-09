pipeline{
 agent any 
stages {
stage('Build') {
steps {
//run the python code
bat 'javac HelloWorld.java'
}
}
stage('Run'){
steps {
bat 'java Helloworld'
}
}
}
}
