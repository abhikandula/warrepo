node{
   stage('SCM Checkout'){ 
     git 'https://github.com/abhikandula/warrepo'
   }
   stage('Compile-Package'){
     sh 'mvn package'
   }
}
