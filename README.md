# ワールドマップ作成

## 事前準備
GeoLite2から`GeoLite2 Cityファイル`をダウンロード
https://www.maxmind.com/en/accounts/658025/geoip/downloads


Foliumよりマップデータのダウンロード

```shell
git clone https://github.com/python-visualization/folium.git
```

## ライブラリ

```
pandas
numpy
geoip2==4.5.0
pycountry==20.7.3
folium===0.12.1.post1
```