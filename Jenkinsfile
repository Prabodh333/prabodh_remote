pipeline{
agent any{
stages{
Stage(install httpd){
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
