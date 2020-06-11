node{
 stage('git clone java code') {
    git 'https://github.com/balakumar206/myrepo.git'
}   
    
  stage('git executes maven targets') {
    sh label: '', script: 'mvn install'
}     
    

}
