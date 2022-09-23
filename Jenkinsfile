pipeline{
  agent any{
  stages{
     stage(install httpd){
      sh "yum install httpd -y"

}
    stage(run httpd){
       sh "service httpd start"
}
    stage(deply index){
    cp -r file 3 /var/www/html/

}
}
}
}
