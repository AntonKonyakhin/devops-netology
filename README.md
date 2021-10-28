# devops-netology

### С помощью файла /terraform/.gitignore 
1. во всех каталогах папка .terraform и то, что внути будут игнорироваться для команд gita
2. игнорируются файлы с расширением .tfstate и оканчивающиеся на любое расширение после .tfstate.
3. игнорируется лог файл crash.log
4. игнорируются файлы оканчивающиеся на .tfvars
5. игнорируются файлы override.tf, override.tf.json, содержат в конце имени  _override.tf и _override.tf.json
6. игнорируются файлы terraform.rc, и оканчивающиеся на .terraformrc в данном каталоге

