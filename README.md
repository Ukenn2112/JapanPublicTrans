# JapanPublicTrans
日本の公共交通データAPI

## JR 
> 列車走行位置

GET
```url
https://frontdoorendpoint01-fheefececgbugmbf.z01.azurefd.net/api/getresource?name=transaction/1.0.1/train_{id}.json
```
Header:
```txt
User-ID:1234567890
User-Agent:JR%E6%9D%B1%E6%97%A5%E6%9C%AC%E3%82%A2%E3%83%97%E3%83%AA%3B%20Mozilla%2F5.0%20(iPhone%3B%20CPU%20iPhone%20OS%2017_4%20like%20Mac%20OS%20X)%20AppleWebKit%2F605.1.15%20(KHTML%2C%20like%20Gecko)%20Mobile%2F15E148
```
| ID | lineCode | lineName |
|---|---|---|
| 31 | 31 | 五日市線 |
| 31 | 35 | 青梅線 |
| 34 | 34 | 宇都宮線 |
| 34 | 46 | 湘南新宿ライン |
| 34 | 102 | 上野東京ライン |
| 35 | 35 | 青梅線 |
| 40 | 40 | 京浜東北線・根岸線 |
| 40 | 70 | 横浜線 |
| 41 | 41 | 京葉線 |
| 41 | 67 | 武蔵野線 |
| 43 | 38 | 川越線 |
| 43 | 43 | 埼京線 |
| 43 | 46 | 湘南新宿ライン |
| 43 | 104 | 相鉄線直通 |
| 43 | 1801 | 相鉄線 |
| 47 | 47 | 常磐線 |
| 47 | 48 | 常磐線快速電車 |
| 47 | 102 | 上野東京ライン |
| 49 | 49 | 常磐線各駅停車 |
| 52 | 52 | 総武快速線 |
| 55 | 46 | 湘南新宿ライン |
| 55 | 55 | 高崎線 |
| 55 | 102 | 上野東京ライン |
| 56 | 56 | 中央・総武各駅停車 |
| 56 | 1705 | 東京メトロ東西線 |
| 57 | 57 | 中央線快速電車 |
| 57 | 58 | 中央本線 |
| 58 | 58 | 中央本線 |
| 58 | 77 | 篠ノ井線 |
| 60 | 46 | 湘南新宿ライン |
| 60 | 102 | 上野東京ライン |
| 63 | 63 | 南武線 |
| 69 | 46 | 湘南新宿ライン |
| 69 | 69 | 横須賀線 |
| 70 | 40 | 京浜東北線・根岸線 |
| 70 | 70 | 横浜線 |
| 87 | 87 | 上越新幹線 |
| 88 | 88 | 東北新幹線 |
| 89 | 89 | 北陸新幹線 |
