node {
    
   stage('Preparation') {
       
      git 'https://github.com/anuj-nits/LiquorStoreApp.git'
   }
   stage('compile') {
        build 'Liquorcompile'
   }
   stage('test') {
    build 'LiquorTest'
   }
   stage('pacakge') {
    build 'LiquorPacakge'
   }
}
