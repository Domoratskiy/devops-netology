# devops-netology

# Проигнорировать все что, находится в любых директориях на любом уровне в директории .terraform
**/.terraform/*

 # проигнорировать все файлы с расширением .tfstate
*.tfstate
 # проигнорировать все файлы с расширением .tfstate.* ,  * - соответствует 0 или более символам
*.tfstate.*

# проигнорировать файл crash.log, 
crash.log
# проигнорировать файл crash.*.log , * - соответствует 0 или более символам
crash.*.log

# проигнорировать любые файлы с расширением *.tfvars.json , * - соответствует 0 или более символам
*.tfvars.json

# Ignore override files as they are usually used to override resources locally and so
# are not checked in
# проигнорировать файл override.tf
override.tf
# проигнорировать файл override.tf.json
override.tf.json
# проигнорировать файлы *_override.tf , * - соответствует 0 или более символам
*_override.tf
# проигнорировать файлы *_override.tf.json , * - соответствует 0 или более символам
*_override.tf.json

# Include override files you do wish to add to version control using negated pattern
# !example_override.tf

# Include tfplan files to ignore the plan output of command: terraform plan -out=tfplan

