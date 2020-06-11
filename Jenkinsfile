node{
 stage('1st stage git clone java code') {
    git 'https://github.com/balakumar206/myrepo.git'
}   
    
  stage('2nd stage git executes maven targets') {
    sh label: '', script: 'mvn install'
}     
    

}
