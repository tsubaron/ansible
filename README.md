# hostsファイル作成

  $ cp hosts.example hosts

# 作成する環境に応じて実行
## AmazonLinux2 + nginx + mariadb + php

  $ ansible-playbook lnmp.yml -i hosts

## phoenix

  $ ansible-playbook phoenix.yml -i hosts

# Ansibleテスト用のサーバー
## AmazonoLinux2のボックスファイルインストール

  $ vagrant box add gbailey/amzn2

## サーバー起動

  $ cd test_server
  $ vagrant up
