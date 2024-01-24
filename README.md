# home-server-playbook

自宅サーバセットアップ用Ansible playbook

## 準備

* Ansibleがない場合はインストール

    ```sh
    python -m venv .venv
    source .venv/bin/activate
    pip install ansible
    ```

* `inventories/sample.yaml` を参考にインベントリを作成する

## 実行例

```sh
ansible-playbook -i inventories/<任意>.yaml ubuntu_site.yaml
```
