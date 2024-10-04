grafana
=================

Setup grafana

OS Platform
-----------------

### Debian

- bookworm
- bullseye

Role Variables
--------------

### [defaults/main.yml](defaults/main.yml)

設定方法の詳細については[defaults/main.yml](defaults/main.yml)のサンプルコードなどを参照してください。

#### `grafana_port`

ポート番号

#### `grafana_base_cfg`

基本設定

#### `grafana_access_control_cfg`

アクセスコントロール設定

#### `grafana_dashboards_cfg`

ダッシュボード設定

#### `grafana_datasources_cfg`

データソース設定

#### `grafana_notifiers_cfg`

通知設定

#### `grafana_plugins_cfg`

プラグイン設定

### [vars/main.yml](vars/main.yml)

設定値については[vars/main.yml](vars/main.yml)を参照してください。

#### `grafana_apt_key_url`

#### `grafana_apt_key_download_dest`

#### `grafana_apt_key_dest`

#### `grafana_config_dir`

#### `grafana_config_provisioning_dir`

Example Playbook
--------------

```yaml
- hosts: servers
  roles:
    - role: grafana
```

License
--------------

Apache License 2.0
