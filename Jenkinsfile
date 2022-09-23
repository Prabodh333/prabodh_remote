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
cp -r index.html /var/www/html/

}
}
}
}
