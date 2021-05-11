# devops-netology 
**/.terraform/*
игнорируем все файлы .terraform  в любом каталоге

*.tfstate
*.tfstate.*
*.tfvars
игнорируем все фалы с расширением tfstate,tfvars в текущем каталоге

crash.log
игнорируем crash.log в текущем каталоге

override.tf
override.tf.json
*_override.tf
*_override.tf.json
игнорируем override.tf,override.tf.json, _override.tf и _override.tf.json с любым кол-вом символов в начале


.terraformrc
terraform.rc
игнорируем эти фйлы тоже