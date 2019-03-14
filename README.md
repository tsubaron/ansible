# hostsファイル作成
cp hosts.example hosts

# 作成する環境に応じて実行
## wordpress
ansible-playbook wordpress.yml -i hosts
## laravel
ansible-playbook laravel.yml -i hosts
## phoenix
ansible-playbook phoenix.yml -i hosts
