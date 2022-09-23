pipeline {
agent any 

    stages{
     stage(install){
         steps{
      sh "yum install httpd -y"
}
}
    stage(run){
        steps{
       sh "service httpd start"
}
            
        }

    stage(deploy){
 steps{
    "cp -r file 3 /var/www/html/"
}
     
 }
}
}

