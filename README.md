# Grafana Sample

## 目的

Grafanaによって多様なデータソースが表示されることを試すことを目的として作成。

## アクセス方法

- URL
  - http://localhost:3000
- ID/PW
  - admin/admin

## 導入されるプラグイン

- alexanderzobnin-zabbix-app

## MySQLのサンプルデータ

厚生労働省の新型コロナウィルス感染症のオープンデータ (CSV)　を元にSQLを作成
https://www.mhlw.go.jp/stf/covid-19/open-data.html

### 同封しているデータ

- 陽性者数
- PCR検査実施人数
- 死亡者数

(データは2021-06-08時点のもの)

### 使用方法

```bash
docker-compose exec mysql bash
sh /tmp/sql/create.sh
```
