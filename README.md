# devops-netology
First editing

В каталог terraform добавлен .gitignore.
Благодаря добавленному .gitignore в будуще будут проигнорированы такие файлы внутри каталога terraform:
* все файлы внутри подкаталога .terraform/
* все файлы заканичвающиеся на ".tfstate" и содержащие ".tfstate." в середине имени
* файл с именем "crash.log" а также все содержащие в середине названия любые символы между crash. и .log (crash.*.log)
* файлы секретов заканичвающиеся на ".tfvars" и ".tfvars.json"
* с именами override.tf и override.tf.json, а также заканичвающиеся на _override.tf и _override.tf.json
* файл .terraform.tfstate.lock.info
* .terraformrc и terraform.rc
