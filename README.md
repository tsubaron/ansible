# Ansible実行手順
## hostsファイル作成

```
  $ cp hosts.example hosts
```

## 作成する環境に応じてamzn2/tasks/main.ymlを変更

```
  $ vim amzn2/tasks/main.yml
```

## ansible実行

```
  $ ansible-playbook amzn2.yml -i hosts
```

# Ansibleテスト用のサーバー
## AmazonoLinux2のボックスファイルインストール
```
  $ vagrant box add gbailey/amzn2
```

## サーバー起動
```
  $ cd test_server
  $ vagrant up
```
