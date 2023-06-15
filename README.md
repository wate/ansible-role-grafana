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

設定方法の詳細については[defaults/main.yml](defaults/main.yml)のサンプルコードを参照してください。

### `grafana_port`

ポート番号

### `grafana_base_cfg`

基本設定

### `grafana_access_control_cfg`

アクセスコントロール設定

### `grafana_dashboards_cfg`

ダッシュボード設定

### `grafana_datasources_cfg`

データソース設定

### `grafana_notifiers_cfg`

通知設定

### `grafana_plugins_cfg`

プラグイン設定

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
