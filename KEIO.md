# KEIO

## 運輸状況

> https://i.opentidkeio.jp/data/traffic_info.json

*HTTPリクエスト：GET*

`ps`車両情報

| 項       | タイプ                         | 内容             | 備考     |
| ------- | ------------------------------| ---------------- | -------- |
| tr      | str                           |車両番号           |          |
| sy      | str                           |車種               |          |
| sy_tr   | str                           |車種               |車種変更|
| ki      | str                           |走行方向            |`0`新宿方面、`1`八王子方面|
| bs      | str                           |停靠ホーム          |          |
| dl      | str                           |遅延時間            |          |
| ik      | str                           |行き先             |          |
| ik_tr   | str                           |行き先駅           |          |
| sr      | str                           |両目              |          |
| inf     | str                           |運営情報           |          |

<details>
<summary>Json Back</summary>
  
  ```json
{
    "up": [
        {
            "dt": [
                {
                    "yy": "2024",
                    "mt": "02",
                    "dy": "16",
                    "hh": "24",
                    "mm": "26",
                    "ss": "10"
                }
            ],
            "st": "0"
        }
    ],
    "TS": [
        {
            "id": "E002",
            "sn": "K",
            "ps": [
                {
                    "tr": " 5721 ",
                    "sy": "6",
                    "sy_tr": "6",
                    "ki": "1",
                    "bs": "2",
                    "dl": "01",
                    "ik": "402",
                    "ik_tr": "048",
                    "sr": "10",
                    "inf": ""
                }
            ]
        },
        {
            "id": "E004",
            "sn": "K",
            "ps": [
                {
                    "tr": " 5120A",
                    "sy": "6",
                    "sy_tr": "6",
                    "ki": "0",
                    "bs": "2",
                    "dl": "02",
                    "ik": "300",
                    "ik_tr": "033",
                    "sr": "8",
                    "inf": ""
                }
            ]
        },
        {
            "id": "E006",
            "sn": "K",
            "ps": [
                {
                    "tr": " 5621 ",
                    "sy": "6",
                    "sy_tr": "6",
                    "ki": "1",
                    "bs": "1",
                    "dl": "00",
                    "ik": "305",
                    "ik_tr": "006",
                    "sr": "8",
                    "inf": ""
                },
                {
                    "tr": " 6124 ",
                    "sy": "6",
                    "sy_tr": "6",
                    "ki": "0",
                    "bs": "4",
                    "dl": "00",
                    "ik": "302",
                    "ik_tr": "006",
                    "sr": "8",
                    "inf": ""
                }
            ]
        },
        {
            "id": "E009",
            "sn": "K",
            "ps": [
                {
                    "tr": " 2705 ",
                    "sy": "3",
                    "sy_tr": "3",
                    "ki": "1",
                    "bs": "1",
                    "dl": "00",
                    "ik": "402",
                    "ik_tr": "050",
                    "sr": "10",
                    "inf": ""
                }
            ]
        },
        {
            "id": "E010",
            "sn": "K",
            "ps": [
                {
                    "tr": " 5223 ",
                    "sy": "6",
                    "sy_tr": "6",
                    "ki": "1",
                    "bs": "1",
                    "dl": "02",
                    "ik": "027",
                    "ik_tr": "027",
                    "sr": "10",
                    "inf": ""
                }
            ]
        },
        {
            "id": "E012",
            "sn": "K",
            "ps": [
                {
                    "tr": " 6600 ",
                    "sy": "6",
                    "sy_tr": "6",
                    "ki": "0",
                    "bs": "3",
                    "dl": "00",
                    "ik": "302",
                    "ik_tr": "006",
                    "sr": "8",
                    "inf": ""
                }
            ]
        },
        {
            "id": "E016",
            "sn": "K",
            "ps": [
                {
                    "tr": " 5221 ",
                    "sy": "6",
                    "sy_tr": "6",
                    "ki": "1",
                    "bs": "2",
                    "dl": "02",
                    "ik": "027",
                    "ik_tr": "027",
                    "sr": "10",
                    "inf": ""
                }
            ]
        },
        {
            "id": "E022",
            "sn": "K",
            "ps": [
                {
                    "tr": " 0213 ",
                    "sy": "1",
                    "sy_tr": "1",
                    "ki": "1",
                    "bs": "2",
                    "dl": "01",
                    "ik": "027",
                    "ik_tr": "032",
                    "sr": "10",
                    "inf": "この列車は高幡不動駅で各駅停車 京王八王子行きとなります。"
                }
            ]
        },
        {
            "id": "E024",
            "sn": "K",
            "ps": [
                {
                    "tr": " 5219 ",
                    "sy": "6",
                    "sy_tr": "6",
                    "ki": "1",
                    "bs": "1",
                    "dl": "03",
                    "ik": "027",
                    "ik_tr": "027",
                    "sr": "10",
                    "inf": ""
                }
            ]
        },
        {
            "id": "E029",
            "sn": "K",
            "ps": [
                {
                    "tr": " 6017 ",
                    "sy": "6",
                    "sy_tr": "6",
                    "ki": "1",
                    "bs": "1",
                    "dl": "00",
                    "ik": "032",
                    "ik_tr": "032",
                    "sr": "10",
                    "inf": ""
                }
            ]
        },
        {
            "id": "E031",
            "sn": "K",
            "ps": [
                {
                    "tr": " 6135 ",
                    "sy": "6",
                    "sy_tr": "6",
                    "ki": "1",
                    "bs": "1S",
                    "dl": "00",
                    "ik": "401",
                    "ik_tr": "043",
                    "sr": "10",
                    "inf": ""
                }
            ]
        },
        {
            "id": "E032",
            "sn": "K",
            "ps": [
                {
                    "tr": " 6020 ",
                    "sy": "6",
                    "sy_tr": "6",
                    "ki": "0",
                    "bs": "2",
                    "dl": "00",
                    "ik": "304",
                    "ik_tr": "027",
                    "sr": "10",
                    "inf": ""
                }
            ]
        },
        {
            "id": "E033",
            "sn": "K",
            "ps": [
                {
                    "tr": " 5623 ",
                    "sy": "6",
                    "sy_tr": "6",
                    "ki": "1",
                    "bs": "5",
                    "dl": "00",
                    "ik": "305",
                    "ik_tr": "006",
                    "sr": "10",
                    "inf": ""
                }
            ]
        },
        {
            "id": "E042",
            "sn": "K",
            "ps": [
                {
                    "tr": " 6133 ",
                    "sy": "6",
                    "sy_tr": "6",
                    "ki": "1",
                    "bs": "1",
                    "dl": "00",
                    "ik": "401",
                    "ik_tr": "043",
                    "sr": "10",
                    "inf": ""
                }
            ]
        },
        {
            "id": "E048",
            "sn": "S",
            "ps": [
                {
                    "tr": " 6758 ",
                    "sy": "6",
                    "sy_tr": "6",
                    "ki": "0",
                    "bs": "4",
                    "dl": "00",
                    "ik": "302",
                    "ik_tr": "048",
                    "sr": "10",
                    "inf": ""
                }
            ]
        },
        {
            "id": "E054",
            "sn": "S",
            "ps": [
                {
                    "tr": " 6760 ",
                    "sy": "6",
                    "sy_tr": "6",
                    "ki": "0",
                    "bs": "2",
                    "dl": "00",
                    "ik": "302",
                    "ik_tr": "048",
                    "sr": "10",
                    "inf": ""
                }
            ]
        },
        {
            "id": "E081",
            "sn": "I",
            "ps": [
                {
                    "tr": " 0449 ",
                    "sy": "6",
                    "sy_tr": "6",
                    "ki": "1",
                    "bs": "1",
                    "dl": "00",
                    "ik": "093",
                    "ik_tr": "093",
                    "sr": "5",
                    "inf": ""
                }
            ]
        },
        {
            "id": "E084",
            "sn": "I",
            "ps": [
                {
                    "tr": " 0331A",
                    "sy": "6",
                    "sy_tr": "6",
                    "ki": "1",
                    "bs": "1",
                    "dl": "01",
                    "ik": "097",
                    "ik_tr": "097",
                    "sr": "5",
                    "inf": ""
                }
            ]
        },
        {
            "id": "E089",
            "sn": "I",
            "ps": [
                {
                    "tr": " 0329A",
                    "sy": "6",
                    "sy_tr": "6",
                    "ki": "1",
                    "bs": "1",
                    "dl": "00",
                    "ik": "097",
                    "ik_tr": "097",
                    "sr": "5",
                    "inf": ""
                },
                {
                    "tr": " 0027A",
                    "sy": "2",
                    "sy_tr": "2",
                    "ki": "1",
                    "bs": "2",
                    "dl": "00",
                    "ik": "097",
                    "ik_tr": "097",
                    "sr": "5",
                    "inf": ""
                }
            ]
        },
        {
            "id": "E094",
            "sn": "I",
            "ps": [
                {
                    "tr": " 0508 ",
                    "sy": "6",
                    "sy_tr": "6",
                    "ki": "0",
                    "bs": "2",
                    "dl": "00",
                    "ik": "093",
                    "ik_tr": "093",
                    "sr": "5",
                    "inf": ""
                }
            ]
        }
    ],
    "TB": [
        {
            "id": "D004",
            "sn": "K",
            "ps": [
                {
                    "tr": " 0215 ",
                    "sy": "1",
                    "sy_tr": "1",
                    "ki": "1",
                    "bs": "0",
                    "dl": "02",
                    "ik": "027",
                    "ik_tr": "032",
                    "sr": "10",
                    "inf": "この列車は高幡不動駅で各駅停車 京王八王子行きとなります。"
                }
            ]
        },
        {
            "id": "D045",
            "sn": "S",
            "ps": [
                {
                    "tr": " 2703 ",
                    "sy": "3",
                    "sy_tr": "3",
                    "ki": "1",
                    "bs": "0",
                    "dl": "03",
                    "ik": "402",
                    "ik_tr": "054",
                    "sr": "10",
                    "inf": ""
                }
            ]
        },
        {
            "id": "D052",
            "sn": "S",
            "ps": [
                {
                    "tr": " 2701 ",
                    "sy": "3",
                    "sy_tr": "3",
                    "ki": "1",
                    "bs": "0",
                    "dl": "01",
                    "ik": "402",
                    "ik_tr": "054",
                    "sr": "8",
                    "inf": ""
                }
            ]
        },
        {
            "id": "D097",
            "sn": "I",
            "ps": [
                {
                    "tr": " 0327A",
                    "sy": "6",
                    "sy_tr": "6",
                    "ki": "1",
                    "bs": "0",
                    "dl": "02",
                    "ik": "097",
                    "ik_tr": "097",
                    "sr": "5",
                    "inf": ""
                }
            ]
        },
        {
            "id": "D102",
            "sn": "K",
            "ps": [
                {
                    "tr": " 6955 ",
                    "sy": "6",
                    "sy_tr": "6",
                    "ki": "1",
                    "bs": "0",
                    "dl": "00",
                    "ik": "301",
                    "ik_tr": "301",
                    "sr": "10",
                    "inf": ""
                }
            ]
        }
    ]
}
  ```

</details>

## 

>https://i.opentidkeio.jp/dia/{列車id}.json

<details>
<summary>Json Back</summary>
  
  ```json
{
    "dy": [
        {
            "st": "2",
            "sn": "笹塚",
            "tt": "0:05",
            "pa": "1"
        },
        {
            "st": "3",
            "sn": "代田橋",
            "tt": "",
            "pa": "0"
        },
        {
            "st": "4",
            "sn": "明大前",
            "tt": "0:08",
            "pa": "1"
        },
        {
            "st": "5",
            "sn": "下高井戸",
            "tt": "",
            "pa": "0"
        },
        {
            "st": "6",
            "sn": "桜上水",
            "tt": "",
            "pa": "0"
        },
        {
            "st": "7",
            "sn": "上北沢",
            "tt": "",
            "pa": "0"
        },
        {
            "st": "8",
            "sn": "八幡山",
            "tt": "",
            "pa": "0"
        },
        {
            "st": "9",
            "sn": "芦花公園",
            "tt": "",
            "pa": "0"
        },
        {
            "st": "10",
            "sn": "千歳烏山",
            "tt": "0:13",
            "pa": "1"
        },
        {
            "st": "11",
            "sn": "仙川",
            "tt": "",
            "pa": "0"
        },
        {
            "st": "12",
            "sn": "つつじヶ丘",
            "tt": "",
            "pa": "0"
        },
        {
            "st": "13",
            "sn": "柴崎",
            "tt": "",
            "pa": "0"
        },
        {
            "st": "14",
            "sn": "国領",
            "tt": "",
            "pa": "0"
        },
        {
            "st": "15",
            "sn": "布田",
            "tt": "",
            "pa": "0"
        },
        {
            "st": "16",
            "sn": "調布",
            "tt": "0:17",
            "pa": "1"
        },
        {
            "st": "17",
            "sn": "西調布",
            "tt": "",
            "pa": "0"
        },
        {
            "st": "18",
            "sn": "飛田給",
            "tt": "",
            "pa": "0"
        },
        {
            "st": "19",
            "sn": "武蔵野台",
            "tt": "",
            "pa": "0"
        },
        {
            "st": "20",
            "sn": "多磨霊園",
            "tt": "",
            "pa": "0"
        },
        {
            "st": "21",
            "sn": "東府中",
            "tt": "",
            "pa": "0"
        },
        {
            "st": "22",
            "sn": "府中",
            "tt": "0:23",
            "pa": "1"
        },
        {
            "st": "23",
            "sn": "分倍河原",
            "tt": "0:26",
            "pa": "1"
        },
        {
            "st": "24",
            "sn": "中河原",
            "tt": "",
            "pa": "0"
        },
        {
            "st": "25",
            "sn": "聖蹟桜ヶ丘",
            "tt": "0:29",
            "pa": "1"
        },
        {
            "st": "26",
            "sn": "百草園",
            "tt": "",
            "pa": "0"
        },
        {
            "st": "27",
            "sn": "高幡不動",
            "tt": "0:33",
            "pa": "1"
        },
        {
            "st": "28",
            "sn": "南平",
            "tt": "0:37",
            "pa": "1"
        },
        {
            "st": "29",
            "sn": "平山城址公園",
            "tt": "0:39",
            "pa": "1"
        },
        {
            "st": "30",
            "sn": "長沼",
            "tt": "0:41",
            "pa": "1"
        },
        {
            "st": "31",
            "sn": "北野",
            "tt": "0:43",
            "pa": "1"
        },
        {
            "st": "32",
            "sn": "京王八王子",
            "tt": "0:46",
            "pa": "1"
        }
    ]
}
  ```

</details>

## 運輸状況

運輸 message

> https://i.opentidkeio.jp/unkouinf/unkou_pub.csv

*HTTPリクエスト：GET*

運輸 data

> https://i.opentidkeio.jp/unkouinf/unkou_pub2.csv

*HTTPリクエスト：GET*

線区：`senku_1` 京王線・相模原线　`senku_2` 井の頭線

```json
{
    jyokyo_1: "概ね平常運行",
    jyokyo_2: "運転見合わせ",
    jyokyo_3: "一部運転見合わせ",
    jyokyo_4: "遅れています",
}
```

## 車種

> https://i.opentidkeio.jp/config/syasyu.json

*HTTPリクエスト：GET*

<details>
<summary>Json Back</summary>
  
  ```json
{
    "syasyu": [
        {
            "code": "1",
            "style": "STYLE_STOP_0",
            "iconname": "特",
            "name": "特急",
            "name_e": "Special Express"
        },
        {
            "code": "2",
            "style": "STYLE_STOP_2",
            "iconname": "急",
            "name": "急行",
            "name_e": "Express"
        },
        {
            "code": "3",
            "style": "STYLE_STOP_4",
            "iconname": "快",
            "name": "快速",
            "name_e": "Rapid"
        },
        {
            "code": "4",
            "style": "STYLE_STOP_DUMMY",
            "iconname": "",
            "name": "",
            "name_e": ""
        },
        {
            "code": "5",
            "style": "STYLE_STOP_3",
            "iconname": "区",
            "name": "区間急行",
            "name_e": "Semi Express"
        },
        {
            "code": "6",
            "style": "STYLE_STOP_5",
            "iconname": "各",
            "name": "各駅停車",
            "name_e": "Local"
        },
        {
            "code": "7",
            "style": "STYLE_STOP_DUMMY",
            "iconname": "",
            "name": "",
            "name_e": ""
        },
        {
            "code": "8",
            "style": "STYLE_STOP_DUMMY",
            "iconname": "",
            "name": "",
            "name_e": ""
        },
        {
            "code": "9",
            "style": "STYLE_STOP_6",
            "iconname": "京",
            "name": "京王ライナー",
            "name_e": "KEIO LINER"
        },
        {
            "code": "10",
            "style": "STYLE_STOP_7",
            "iconname": "臨",
            "name": "臨時",
            "name_e": "Extra"
        },
        {
            "code": "11",
            "style": "STYLE_STOP_8",
            "iconname": "高",
            "name": "Mt.TAKAO",
            "name_e": "Mt.TAKAO"
        },
        {
            "code": "99",
            "style": "STYLE_MULTI_TRAIN",
            "iconname": "",
            "name": "",
            "name_e": ""
        }
    ]
}
  ```

</details>

## 線路

> https://i.opentidkeio.jp/config/line.json

*HTTPリクエスト：GET*

<details>
<summary>Json Back</summary>
  
  ```json
{
    "line": [
        {
            "code": "1",
            "name": "京王線",
            "kubun": "KO",
            "style": "STYLE_KEIO_LINE"
        },
        {
            "code": "2",
            "name": "相模原線",
            "kubun": "KO",
            "style": "STYLE_KEIO_LINE"
        },
        {
            "code": "3",
            "name": "井の頭線",
            "kubun": "IN",
            "style": "STYLE_INO_LINE"
        }
    ]
}
  ```

</details>

## 場所

> https://i.opentidkeio.jp/config/position.json

*HTTPリクエスト：GET*

<details>
<summary>Json Back</summary>
  
  ```json
{
    "pos": [
        {
            "ID": "E001",
            "name": "新宿",
            "kind": "駅"
        },
        {
            "ID": "U001",
            "name": "笹塚～新宿",
            "kind": "駅間",
            "max_disp": "3"
        },
        {
            "ID": "D001",
            "name": "新宿三丁目～新宿",
            "kind": "駅間",
            "max_disp": "3"
        },
        {
            "ID": "E002",
            "name": "笹塚",
            "kind": "駅"
        },
        {
            "ID": "U002",
            "name": "代田橋～笹塚",
            "kind": "駅間",
            "max_disp": "3"
        },
        {
            "ID": "D002",
            "name": "新宿～笹塚",
            "kind": "駅間",
            "max_disp": "3"
        },
        {
            "ID": "S002",
            "name": "幡ヶ谷～笹塚",
            "kind": "駅間",
            "max_disp": "2"
        },
        {
            "ID": "E003",
            "name": "代田橋",
            "kind": "駅"
        },
        {
            "ID": "U003",
            "name": "明大前～代田橋",
            "kind": "駅間",
            "max_disp": "3"
        },
        {
            "ID": "D003",
            "name": "笹塚～代田橋",
            "kind": "駅間",
            "max_disp": "3"
        },
        {
            "ID": "E004",
            "name": "明大前",
            "kind": "駅"
        },
        {
            "ID": "U004",
            "name": "下高井戸～明大前",
            "kind": "駅間",
            "max_disp": "3"
        },
        {
            "ID": "D004",
            "name": "代田橋～明大前",
            "kind": "駅間",
            "max_disp": "3"
        },
        {
            "ID": "E005",
            "name": "下高井戸",
            "kind": "駅"
        },
        {
            "ID": "U005",
            "name": "桜上水～下高井戸",
            "kind": "駅間",
            "max_disp": "3"
        },
        {
            "ID": "D005",
            "name": "明大前～下高井戸",
            "kind": "駅間",
            "max_disp": "3"
        },
        {
            "ID": "E006",
            "name": "桜上水",
            "kind": "駅"
        },
        {
            "ID": "U006",
            "name": "上北沢～桜上水",
            "kind": "駅間",
            "max_disp": "3"
        },
        {
            "ID": "D006",
            "name": "下高井戸～桜上水",
            "kind": "駅間",
            "max_disp": "3"
        },
        {
            "ID": "E007",
            "name": "上北沢",
            "kind": "駅"
        },
        {
            "ID": "U007",
            "name": "八幡山～上北沢",
            "kind": "駅間",
            "max_disp": "3"
        },
        {
            "ID": "D007",
            "name": "桜上水～上北沢",
            "kind": "駅間",
            "max_disp": "3"
        },
        {
            "ID": "E008",
            "name": "八幡山",
            "kind": "駅"
        },
        {
            "ID": "U008",
            "name": "芦花公園～八幡山",
            "kind": "駅間",
            "max_disp": "3"
        },
        {
            "ID": "D008",
            "name": "上北沢～八幡山",
            "kind": "駅間",
            "max_disp": "3"
        },
        {
            "ID": "E009",
            "name": "芦花公園",
            "kind": "駅"
        },
        {
            "ID": "U009",
            "name": "千歳烏山～芦花公園",
            "kind": "駅間",
            "max_disp": "3"
        },
        {
            "ID": "D009",
            "name": "八幡山～芦花公園",
            "kind": "駅間",
            "max_disp": "3"
        },
        {
            "ID": "E010",
            "name": "千歳烏山",
            "kind": "駅"
        },
        {
            "ID": "U010",
            "name": "仙川～千歳烏山",
            "kind": "駅間",
            "max_disp": "3"
        },
        {
            "ID": "D010",
            "name": "芦花公園～千歳烏山",
            "kind": "駅間",
            "max_disp": "3"
        },
        {
            "ID": "E011",
            "name": "仙川",
            "kind": "駅"
        },
        {
            "ID": "U011",
            "name": "つつじヶ丘～仙川",
            "kind": "駅間",
            "max_disp": "3"
        },
        {
            "ID": "D011",
            "name": "千歳烏山～仙川",
            "kind": "駅間",
            "max_disp": "3"
        },
        {
            "ID": "E012",
            "name": "つつじヶ丘",
            "kind": "駅"
        },
        {
            "ID": "U012",
            "name": "柴崎～つつじヶ丘",
            "kind": "駅間",
            "max_disp": "3"
        },
        {
            "ID": "D012",
            "name": "仙川～つつじヶ丘",
            "kind": "駅間",
            "max_disp": "3"
        },
        {
            "ID": "E013",
            "name": "柴崎",
            "kind": "駅"
        },
        {
            "ID": "U013",
            "name": "国領～柴崎",
            "kind": "駅間",
            "max_disp": "3"
        },
        {
            "ID": "D013",
            "name": "つつじヶ丘～柴崎",
            "kind": "駅間",
            "max_disp": "3"
        },
        {
            "ID": "E014",
            "name": "国領",
            "kind": "駅"
        },
        {
            "ID": "U014",
            "name": "布田～国領",
            "kind": "駅間",
            "max_disp": "3"
        },
        {
            "ID": "D014",
            "name": "柴崎～国領",
            "kind": "駅間",
            "max_disp": "3"
        },
        {
            "ID": "E015",
            "name": "布田",
            "kind": "駅"
        },
        {
            "ID": "U015",
            "name": "調布～布田",
            "kind": "駅間",
            "max_disp": "3"
        },
        {
            "ID": "D015",
            "name": "国領～布田",
            "kind": "駅間",
            "max_disp": "3"
        },
        {
            "ID": "E016",
            "name": "調布",
            "kind": "駅"
        },
        {
            "ID": "U016",
            "name": "西調布～調布",
            "kind": "駅間",
            "max_disp": "3"
        },
        {
            "ID": "D016",
            "name": "布田～調布",
            "kind": "駅間",
            "max_disp": "3"
        },
        {
            "ID": "S016",
            "name": "京王多摩川～調布",
            "kind": "駅間",
            "max_disp": "2"
        },
        {
            "ID": "E017",
            "name": "西調布",
            "kind": "駅"
        },
        {
            "ID": "U017",
            "name": "飛田給～西調布",
            "kind": "駅間",
            "max_disp": "3"
        },
        {
            "ID": "D017",
            "name": "調布～西調布",
            "kind": "駅間",
            "max_disp": "2"
        },
        {
            "ID": "E018",
            "name": "飛田給",
            "kind": "駅"
        },
        {
            "ID": "U018",
            "name": "武蔵野台～飛田給",
            "kind": "駅間",
            "max_disp": "3"
        },
        {
            "ID": "D018",
            "name": "西調布～飛田給",
            "kind": "駅間",
            "max_disp": "3"
        },
        {
            "ID": "E019",
            "name": "武蔵野台",
            "kind": "駅"
        },
        {
            "ID": "U019",
            "name": "多磨霊園～武蔵野台",
            "kind": "駅間",
            "max_disp": "3"
        },
        {
            "ID": "D019",
            "name": "飛田給～武蔵野台",
            "kind": "駅間",
            "max_disp": "3"
        },
        {
            "ID": "E020",
            "name": "多磨霊園",
            "kind": "駅"
        },
        {
            "ID": "U020",
            "name": "東府中～多磨霊園",
            "kind": "駅間",
            "max_disp": "3"
        },
        {
            "ID": "D020",
            "name": "武蔵野台～多磨霊園",
            "kind": "駅間",
            "max_disp": "3"
        },
        {
            "ID": "E021",
            "name": "東府中",
            "kind": "駅"
        },
        {
            "ID": "U021",
            "name": "府中～東府中",
            "kind": "駅間",
            "max_disp": "3"
        },
        {
            "ID": "D021",
            "name": "多磨霊園～東府中",
            "kind": "駅間",
            "max_disp": "3"
        },
        {
            "ID": "S021",
            "name": "府中競馬正門前～東府中",
            "kind": "駅間",
            "max_disp": "2"
        },
        {
            "ID": "E022",
            "name": "府中",
            "kind": "駅"
        },
        {
            "ID": "U022",
            "name": "分倍河原～府中",
            "kind": "駅間",
            "max_disp": "3"
        },
        {
            "ID": "D022",
            "name": "東府中～府中",
            "kind": "駅間",
            "max_disp": "3"
        },
        {
            "ID": "E023",
            "name": "分倍河原",
            "kind": "駅"
        },
        {
            "ID": "U023",
            "name": "中河原～分倍河原",
            "kind": "駅間",
            "max_disp": "3"
        },
        {
            "ID": "D023",
            "name": "府中～分倍河原",
            "kind": "駅間",
            "max_disp": "3"
        },
        {
            "ID": "E024",
            "name": "中河原",
            "kind": "駅"
        },
        {
            "ID": "U024",
            "name": "聖蹟桜ヶ丘～中河原",
            "kind": "駅間",
            "max_disp": "3"
        },
        {
            "ID": "D024",
            "name": "分倍河原～中河原",
            "kind": "駅間",
            "max_disp": "3"
        },
        {
            "ID": "E025",
            "name": "聖蹟桜ヶ丘",
            "kind": "駅"
        },
        {
            "ID": "U025",
            "name": "百草園～聖蹟桜ヶ丘",
            "kind": "駅間",
            "max_disp": "3"
        },
        {
            "ID": "D025",
            "name": "中河原～聖蹟桜ヶ丘",
            "kind": "駅間",
            "max_disp": "3"
        },
        {
            "ID": "E026",
            "name": "百草園",
            "kind": "駅"
        },
        {
            "ID": "U026",
            "name": "高幡不動～百草園",
            "kind": "駅間",
            "max_disp": "3"
        },
        {
            "ID": "D026",
            "name": "聖蹟桜ヶ丘～百草園",
            "kind": "駅間",
            "max_disp": "3"
        },
        {
            "ID": "E027",
            "name": "高幡不動",
            "kind": "駅"
        },
        {
            "ID": "U027",
            "name": "南平～高幡不動",
            "kind": "駅間",
            "max_disp": "3"
        },
        {
            "ID": "D027",
            "name": "百草園～高幡不動",
            "kind": "駅間",
            "max_disp": "3"
        },
        {
            "ID": "S027",
            "name": "多摩動物公園～高幡不動",
            "kind": "駅間",
            "max_disp": "2"
        },
        {
            "ID": "E028",
            "name": "南平",
            "kind": "駅"
        },
        {
            "ID": "U028",
            "name": "平山城址公園～南平",
            "kind": "駅間",
            "max_disp": "3"
        },
        {
            "ID": "D028",
            "name": "高幡不動～南平",
            "kind": "駅間",
            "max_disp": "3"
        },
        {
            "ID": "E029",
            "name": "平山城址公園",
            "kind": "駅"
        },
        {
            "ID": "U029",
            "name": "長沼～平山城址公園",
            "kind": "駅間",
            "max_disp": "3"
        },
        {
            "ID": "D029",
            "name": "南平～平山城址公園",
            "kind": "駅間",
            "max_disp": "3"
        },
        {
            "ID": "E030",
            "name": "長沼",
            "kind": "駅"
        },
        {
            "ID": "U030",
            "name": "北野～長沼",
            "kind": "駅間",
            "max_disp": "3"
        },
        {
            "ID": "D030",
            "name": "平山城址公園～長沼",
            "kind": "駅間",
            "max_disp": "3"
        },
        {
            "ID": "E031",
            "name": "北野",
            "kind": "駅"
        },
        {
            "ID": "U031",
            "name": "京王八王子～北野",
            "kind": "駅間",
            "max_disp": "3"
        },
        {
            "ID": "D031",
            "name": "長沼～北野",
            "kind": "駅間",
            "max_disp": "3"
        },
        {
            "ID": "S031",
            "name": "京王片倉～北野",
            "kind": "駅間",
            "max_disp": "2"
        },
        {
            "ID": "E032",
            "name": "京王八王子",
            "kind": "駅"
        },
        {
            "ID": "D032",
            "name": "北野～京王八王子",
            "kind": "駅間",
            "max_disp": "3"
        },
        {
            "ID": "E033",
            "name": "新線新宿",
            "kind": "駅"
        },
        {
            "ID": "U033",
            "name": "初台～新線新宿",
            "kind": "駅間",
            "max_disp": "3"
        },
        {
            "ID": "D033",
            "name": "新宿三丁目～新線新宿",
            "kind": "駅間",
            "max_disp": "2"
        },
        {
            "ID": "E034",
            "name": "初台",
            "kind": "駅"
        },
        {
            "ID": "U034",
            "name": "幡ヶ谷～初台",
            "kind": "駅間",
            "max_disp": "2"
        },
        {
            "ID": "D034",
            "name": "新線新宿～初台",
            "kind": "駅間",
            "max_disp": "2"
        },
        {
            "ID": "E035",
            "name": "幡ヶ谷",
            "kind": "駅"
        },
        {
            "ID": "U035",
            "name": "笹塚～幡ヶ谷",
            "kind": "駅間",
            "max_disp": "2"
        },
        {
            "ID": "D035",
            "name": "初台～幡ヶ谷",
            "kind": "駅間",
            "max_disp": "2"
        },
        {
            "ID": "E036",
            "name": "府中競馬正門前",
            "kind": "駅"
        },
        {
            "ID": "D036",
            "name": "東府中～府中競馬正門前",
            "kind": "駅間",
            "max_disp": "2"
        },
        {
            "ID": "E037",
            "name": "多摩動物公園",
            "kind": "駅"
        },
        {
            "ID": "D037",
            "name": "高幡不動～多摩動物公園",
            "kind": "駅間",
            "max_disp": "2"
        },
        {
            "ID": "E038",
            "name": "京王片倉",
            "kind": "駅"
        },
        {
            "ID": "U038",
            "name": "山田～京王片倉",
            "kind": "駅間",
            "max_disp": "2"
        },
        {
            "ID": "D038",
            "name": "北野～京王片倉",
            "kind": "駅間",
            "max_disp": "2"
        },
        {
            "ID": "E039",
            "name": "山田",
            "kind": "駅"
        },
        {
            "ID": "U039",
            "name": "めじろ台～山田",
            "kind": "駅間",
            "max_disp": "2"
        },
        {
            "ID": "D039",
            "name": "京王片倉～山田",
            "kind": "駅間",
            "max_disp": "2"
        },
        {
            "ID": "E040",
            "name": "めじろ台",
            "kind": "駅"
        },
        {
            "ID": "U040",
            "name": "狭間～めじろ台",
            "kind": "駅間",
            "max_disp": "2"
        },
        {
            "ID": "D040",
            "name": "山田～めじろ台",
            "kind": "駅間",
            "max_disp": "2"
        },
        {
            "ID": "E041",
            "name": "狭間",
            "kind": "駅"
        },
        {
            "ID": "U041",
            "name": "高尾～狭間",
            "kind": "駅間",
            "max_disp": "2"
        },
        {
            "ID": "D041",
            "name": "めじろ台～狭間",
            "kind": "駅間",
            "max_disp": "2"
        },
        {
            "ID": "E042",
            "name": "高尾",
            "kind": "駅"
        },
        {
            "ID": "U042",
            "name": "高尾山口～高尾",
            "kind": "駅間",
            "max_disp": "2"
        },
        {
            "ID": "D042",
            "name": "狭間～高尾",
            "kind": "駅間",
            "max_disp": "2"
        },
        {
            "ID": "E043",
            "name": "高尾山口",
            "kind": "駅"
        },
        {
            "ID": "D043",
            "name": "高尾～高尾山口",
            "kind": "駅間",
            "max_disp": "2"
        },
        {
            "ID": "E044",
            "name": "京王多摩川",
            "kind": "駅"
        },
        {
            "ID": "U044",
            "name": "京王稲田堤～京王多摩川",
            "kind": "駅間",
            "max_disp": "3"
        },
        {
            "ID": "D044",
            "name": "調布～京王多摩川",
            "kind": "駅間",
            "max_disp": "2"
        },
        {
            "ID": "E045",
            "name": "京王稲田堤",
            "kind": "駅"
        },
        {
            "ID": "U045",
            "name": "京王よみうりランド～京王稲田堤",
            "kind": "駅間",
            "max_disp": "3"
        },
        {
            "ID": "D045",
            "name": "京王多摩川～京王稲田堤",
            "kind": "駅間",
            "max_disp": "3"
        },
        {
            "ID": "E046",
            "name": "京王よみうりランド",
            "kind": "駅"
        },
        {
            "ID": "U046",
            "name": "稲城～京王よみうりランド",
            "kind": "駅間",
            "max_disp": "3"
        },
        {
            "ID": "D046",
            "name": "京王稲田堤～京王よみうりランド",
            "kind": "駅間",
            "max_disp": "3"
        },
        {
            "ID": "E047",
            "name": "稲城",
            "kind": "駅"
        },
        {
            "ID": "U047",
            "name": "若葉台～稲城",
            "kind": "駅間",
            "max_disp": "3"
        },
        {
            "ID": "D047",
            "name": "京王よみうりランド～稲城",
            "kind": "駅間",
            "max_disp": "3"
        },
        {
            "ID": "E048",
            "name": "若葉台",
            "kind": "駅"
        },
        {
            "ID": "U048",
            "name": "京王永山～若葉台",
            "kind": "駅間",
            "max_disp": "3"
        },
        {
            "ID": "D048",
            "name": "稲城～若葉台",
            "kind": "駅間",
            "max_disp": "3"
        },
        {
            "ID": "E049",
            "name": "京王永山",
            "kind": "駅"
        },
        {
            "ID": "U049",
            "name": "京王多摩センター～京王永山",
            "kind": "駅間",
            "max_disp": "3"
        },
        {
            "ID": "D049",
            "name": "若葉台～京王永山",
            "kind": "駅間",
            "max_disp": "3"
        },
        {
            "ID": "E050",
            "name": "京王多摩センター",
            "kind": "駅"
        },
        {
            "ID": "U050",
            "name": "京王堀之内～京王多摩センター",
            "kind": "駅間",
            "max_disp": "3"
        },
        {
            "ID": "D050",
            "name": "京王永山～京王多摩センター",
            "kind": "駅間",
            "max_disp": "3"
        },
        {
            "ID": "E051",
            "name": "京王堀之内",
            "kind": "駅"
        },
        {
            "ID": "U051",
            "name": "南大沢～京王堀之内",
            "kind": "駅間",
            "max_disp": "3"
        },
        {
            "ID": "D051",
            "name": "京王多摩センター～京王堀之内",
            "kind": "駅間",
            "max_disp": "3"
        },
        {
            "ID": "E052",
            "name": "南大沢",
            "kind": "駅"
        },
        {
            "ID": "U052",
            "name": "多摩境～南大沢",
            "kind": "駅間",
            "max_disp": "3"
        },
        {
            "ID": "D052",
            "name": "京王堀之内～南大沢",
            "kind": "駅間",
            "max_disp": "3"
        },
        {
            "ID": "E053",
            "name": "多摩境",
            "kind": "駅"
        },
        {
            "ID": "U053",
            "name": "橋本～多摩境",
            "kind": "駅間",
            "max_disp": "3"
        },
        {
            "ID": "D053",
            "name": "南大沢～多摩境",
            "kind": "駅間",
            "max_disp": "3"
        },
        {
            "ID": "E054",
            "name": "橋本",
            "kind": "駅"
        },
        {
            "ID": "D054",
            "name": "多摩境～橋本",
            "kind": "駅間",
            "max_disp": "3"
        },
        {
            "ID": "E081",
            "name": "渋谷",
            "kind": "駅"
        },
        {
            "ID": "U081",
            "name": "神泉～渋谷",
            "kind": "駅間",
            "max_disp": "3"
        },
        {
            "ID": "E082",
            "name": "神泉",
            "kind": "駅"
        },
        {
            "ID": "U082",
            "name": "駒場東大前～神泉",
            "kind": "駅間",
            "max_disp": "3"
        },
        {
            "ID": "D082",
            "name": "渋谷～神泉",
            "kind": "駅間",
            "max_disp": "3"
        },
        {
            "ID": "E083",
            "name": "駒場東大前",
            "kind": "駅"
        },
        {
            "ID": "U083",
            "name": "池ノ上～駒場東大前",
            "kind": "駅間",
            "max_disp": "3"
        },
        {
            "ID": "D083",
            "name": "神泉～駒場東大前",
            "kind": "駅間",
            "max_disp": "3"
        },
        {
            "ID": "E084",
            "name": "池ノ上",
            "kind": "駅"
        },
        {
            "ID": "U084",
            "name": "下北沢～池ノ上",
            "kind": "駅間",
            "max_disp": "3"
        },
        {
            "ID": "D084",
            "name": "駒場東大前～池ノ上",
            "kind": "駅間",
            "max_disp": "3"
        },
        {
            "ID": "E085",
            "name": "下北沢",
            "kind": "駅"
        },
        {
            "ID": "U085",
            "name": "新代田～下北沢",
            "kind": "駅間",
            "max_disp": "3"
        },
        {
            "ID": "D085",
            "name": "池ノ上～下北沢",
            "kind": "駅間",
            "max_disp": "3"
        },
        {
            "ID": "E086",
            "name": "新代田",
            "kind": "駅"
        },
        {
            "ID": "U086",
            "name": "東松原～新代田",
            "kind": "駅間",
            "max_disp": "3"
        },
        {
            "ID": "D086",
            "name": "下北沢～新代田",
            "kind": "駅間",
            "max_disp": "3"
        },
        {
            "ID": "E087",
            "name": "東松原",
            "kind": "駅"
        },
        {
            "ID": "U087",
            "name": "明大前～東松原",
            "kind": "駅間",
            "max_disp": "3"
        },
        {
            "ID": "D087",
            "name": "新代田～東松原",
            "kind": "駅間",
            "max_disp": "3"
        },
        {
            "ID": "E088",
            "name": "明大前",
            "kind": "駅"
        },
        {
            "ID": "U088",
            "name": "永福町～明大前",
            "kind": "駅間",
            "max_disp": "3"
        },
        {
            "ID": "D088",
            "name": "東松原～明大前",
            "kind": "駅間",
            "max_disp": "3"
        },
        {
            "ID": "E089",
            "name": "永福町",
            "kind": "駅"
        },
        {
            "ID": "U089",
            "name": "西永福～永福町",
            "kind": "駅間",
            "max_disp": "3"
        },
        {
            "ID": "D089",
            "name": "明大前～永福町",
            "kind": "駅間",
            "max_disp": "3"
        },
        {
            "ID": "E090",
            "name": "西永福",
            "kind": "駅"
        },
        {
            "ID": "U090",
            "name": "浜田山～西永福",
            "kind": "駅間",
            "max_disp": "3"
        },
        {
            "ID": "D090",
            "name": "永福町～西永福",
            "kind": "駅間",
            "max_disp": "3"
        },
        {
            "ID": "E091",
            "name": "浜田山",
            "kind": "駅"
        },
        {
            "ID": "U091",
            "name": "高井戸～浜田山",
            "kind": "駅間",
            "max_disp": "3"
        },
        {
            "ID": "D091",
            "name": "西永福～浜田山",
            "kind": "駅間",
            "max_disp": "3"
        },
        {
            "ID": "E092",
            "name": "高井戸",
            "kind": "駅"
        },
        {
            "ID": "U092",
            "name": "富士見ヶ丘～高井戸",
            "kind": "駅間",
            "max_disp": "3"
        },
        {
            "ID": "D092",
            "name": "浜田山～高井戸",
            "kind": "駅間",
            "max_disp": "3"
        },
        {
            "ID": "E093",
            "name": "富士見ヶ丘",
            "kind": "駅"
        },
        {
            "ID": "U093",
            "name": "久我山～富士見ヶ丘",
            "kind": "駅間",
            "max_disp": "3"
        },
        {
            "ID": "D093",
            "name": "高井戸～富士見ヶ丘",
            "kind": "駅間",
            "max_disp": "3"
        },
        {
            "ID": "E094",
            "name": "久我山",
            "kind": "駅"
        },
        {
            "ID": "U094",
            "name": "三鷹台～久我山",
            "kind": "駅間",
            "max_disp": "3"
        },
        {
            "ID": "D094",
            "name": "富士見ヶ丘～久我山",
            "kind": "駅間",
            "max_disp": "3"
        },
        {
            "ID": "E095",
            "name": "三鷹台",
            "kind": "駅"
        },
        {
            "ID": "U095",
            "name": "井の頭公園～三鷹台",
            "kind": "駅間",
            "max_disp": "3"
        },
        {
            "ID": "D095",
            "name": "久我山～三鷹台",
            "kind": "駅間",
            "max_disp": "3"
        },
        {
            "ID": "E096",
            "name": "井の頭公園",
            "kind": "駅"
        },
        {
            "ID": "U096",
            "name": "吉祥寺～井の頭公園",
            "kind": "駅間",
            "max_disp": "3"
        },
        {
            "ID": "D096",
            "name": "三鷹台～井の頭公園",
            "kind": "駅間",
            "max_disp": "3"
        },
        {
            "ID": "E097",
            "name": "吉祥寺",
            "kind": "駅"
        },
        {
            "ID": "D097",
            "name": "井の頭公園～吉祥寺",
            "kind": "駅間",
            "max_disp": "3"
        },
        {
            "ID": "E101",
            "name": "新宿三丁目",
            "kind": "駅"
        },
        {
            "ID": "U101",
            "name": "新線新宿～新宿三丁目",
            "kind": "駅間",
            "max_disp": "3"
        },
        {
            "ID": "E102",
            "name": "曙橋",
            "kind": "駅"
        },
        {
            "ID": "E103",
            "name": "市ヶ谷",
            "kind": "駅"
        }
    ]
}
  ```

</details>

## 行き先

> https://i.opentidkeio.jp/config/ikisaki.json

*HTTPリクエスト：GET*

<details>
<summary>Json Back</summary>
  
  ```json
{
    "ikisaki": [
        {
            "code": "001",
            "name": "京王線新宿"
        },
        {
            "code": "002",
            "name": "笹塚"
        },
        {
            "code": "003",
            "name": "代田橋"
        },
        {
            "code": "004",
            "name": "明大前"
        },
        {
            "code": "005",
            "name": "下高井戸"
        },
        {
            "code": "006",
            "name": "桜上水"
        },
        {
            "code": "007",
            "name": "上北沢"
        },
        {
            "code": "008",
            "name": "八幡山"
        },
        {
            "code": "009",
            "name": "芦花公園"
        },
        {
            "code": "010",
            "name": "千歳烏山"
        },
        {
            "code": "011",
            "name": "仙川"
        },
        {
            "code": "012",
            "name": "つつじヶ丘"
        },
        {
            "code": "013",
            "name": "柴崎"
        },
        {
            "code": "014",
            "name": "国領"
        },
        {
            "code": "015",
            "name": "布田"
        },
        {
            "code": "016",
            "name": "調布"
        },
        {
            "code": "017",
            "name": "西調布"
        },
        {
            "code": "018",
            "name": "飛田給"
        },
        {
            "code": "019",
            "name": "武蔵野台"
        },
        {
            "code": "020",
            "name": "多磨霊園"
        },
        {
            "code": "021",
            "name": "東府中"
        },
        {
            "code": "022",
            "name": "府中"
        },
        {
            "code": "023",
            "name": "分倍河原"
        },
        {
            "code": "024",
            "name": "中河原"
        },
        {
            "code": "025",
            "name": "聖蹟桜ヶ丘"
        },
        {
            "code": "026",
            "name": "百草園"
        },
        {
            "code": "027",
            "name": "高幡不動"
        },
        {
            "code": "028",
            "name": "南平"
        },
        {
            "code": "029",
            "name": "平山城址公園"
        },
        {
            "code": "030",
            "name": "長沼"
        },
        {
            "code": "031",
            "name": "北野"
        },
        {
            "code": "032",
            "name": "京王八王子"
        },
        {
            "code": "033",
            "name": "新線新宿"
        },
        {
            "code": "034",
            "name": "初台"
        },
        {
            "code": "035",
            "name": "幡ヶ谷"
        },
        {
            "code": "036",
            "name": "府中競馬正門前"
        },
        {
            "code": "037",
            "name": "多摩動物公園"
        },
        {
            "code": "038",
            "name": "京王片倉"
        },
        {
            "code": "039",
            "name": "山田"
        },
        {
            "code": "040",
            "name": "めじろ台"
        },
        {
            "code": "041",
            "name": "狭間"
        },
        {
            "code": "042",
            "name": "高尾"
        },
        {
            "code": "043",
            "name": "高尾山口"
        },
        {
            "code": "044",
            "name": "京王多摩川"
        },
        {
            "code": "045",
            "name": "京王稲田堤"
        },
        {
            "code": "046",
            "name": "京王よみうりランド"
        },
        {
            "code": "047",
            "name": "稲城"
        },
        {
            "code": "048",
            "name": "若葉台"
        },
        {
            "code": "049",
            "name": "京王永山"
        },
        {
            "code": "050",
            "name": "京王多摩センター"
        },
        {
            "code": "051",
            "name": "京王堀之内"
        },
        {
            "code": "052",
            "name": "南大沢"
        },
        {
            "code": "053",
            "name": "多摩境"
        },
        {
            "code": "054",
            "name": "橋本"
        },
        {
            "code": "081",
            "name": "渋谷"
        },
        {
            "code": "082",
            "name": "神泉"
        },
        {
            "code": "083",
            "name": "駒場東大前"
        },
        {
            "code": "084",
            "name": "池ノ上"
        },
        {
            "code": "085",
            "name": "下北沢"
        },
        {
            "code": "086",
            "name": "新代田"
        },
        {
            "code": "087",
            "name": "東松原"
        },
        {
            "code": "088",
            "name": "明大前"
        },
        {
            "code": "089",
            "name": "永福町"
        },
        {
            "code": "090",
            "name": "西永福"
        },
        {
            "code": "091",
            "name": "浜田山"
        },
        {
            "code": "092",
            "name": "高井戸"
        },
        {
            "code": "093",
            "name": "富士見ヶ丘"
        },
        {
            "code": "094",
            "name": "久我山"
        },
        {
            "code": "095",
            "name": "三鷹台"
        },
        {
            "code": "096",
            "name": "井の頭公園"
        },
        {
            "code": "097",
            "name": "吉祥寺"
        },
        {
            "code": "101",
            "name": "新宿三丁目"
        },
        {
            "code": "102",
            "name": "曙橋"
        },
        {
            "code": "103",
            "name": "市ヶ谷"
        },
        {
            "code": "104",
            "name": "九段下"
        },
        {
            "code": "105",
            "name": "神保町"
        },
        {
            "code": "106",
            "name": "小川町"
        },
        {
            "code": "107",
            "name": "岩本町"
        },
        {
            "code": "108",
            "name": "馬喰横山"
        },
        {
            "code": "109",
            "name": "浜町"
        },
        {
            "code": "110",
            "name": "森下"
        },
        {
            "code": "111",
            "name": "菊川"
        },
        {
            "code": "112",
            "name": "住吉"
        },
        {
            "code": "113",
            "name": "西大島"
        },
        {
            "code": "114",
            "name": "大島"
        },
        {
            "code": "115",
            "name": "東大島"
        },
        {
            "code": "116",
            "name": "船堀"
        },
        {
            "code": "117",
            "name": "一之江"
        },
        {
            "code": "118",
            "name": "瑞江"
        },
        {
            "code": "119",
            "name": "篠崎"
        },
        {
            "code": "120",
            "name": "本八幡"
        },
        {
            "code": "300",
            "name": "京王線新宿・都営新宿線方面"
        },
        {
            "code": "301",
            "name": "都営新宿線方面"
        },
        {
            "code": "302",
            "name": "京王線新宿方面"
        },
        {
            "code": "303",
            "name": "調布方面"
        },
        {
            "code": "304",
            "name": "高幡不動方面"
        },
        {
            "code": "305",
            "name": "八幡山方面"
        },
        {
            "code": "306",
            "name": "笹塚方面"
        },
        {
            "code": "400",
            "name": "京王八王子方面"
        },
        {
            "code": "401",
            "name": "高尾山口方面"
        },
        {
            "code": "402",
            "name": "橋本方面"
        },
        {
            "code": "403",
            "name": "府中・府中競馬正門前方面"
        },
        {
            "code": "501",
            "name": "明大前・永福町方面"
        },
        {
            "code": "502",
            "name": "吉祥寺方面"
        },
        {
            "code": "999",
            "name": "-"
        }
    ]
}
  ```

</details>

## その他

> https://i.opentidkeio.jp/data/error_info.json

*HTTPリクエスト：GET*

<details>
<summary>Json Back</summary>
  
  ```json
{
    "up": "02/16 04:00",
    "schedule": "0"
}
  ```

</details>

> https://i.opentidkeio.jp/config/other_chg.json

*HTTPリクエスト：GET*

<details>
<summary>Json Back</summary>
  
  ```json
{
    "chg": [
        {
            "code": "01",
            "line": "1",
            "mark": "KO",
            "app": [
                {
                    "app_type": "#JR_APP",
                    "app_name": "JR東日本",
                    "app_link": "jreast-app://?vid=C602-0001&kid=6003-0002&at4=0866"
                },
                {
                    "app_type": "#METRO_APP",
                    "app_name": "東京メトロ",
                    "app_link": "metroapp://?contentsId=stationTimetable&sourceAppId=keio-train-app&useUserStation=0&stationId=odpt.Station:TokyoMetro.Marunouchi.Shinjuku"
                },
                {
                    "app_type": "#TOEI_APP",
                    "app_name": "都営地下鉄（新宿）",
                    "app_link": "toeiapp://timetable?station_id=4254&from=keio"
                },
                {
                    "app_type": "#SEIBU_APP",
                    "app_name": "西武鉄道",
                    "app_link": "seibuapp://invoke?f=timetable&s=S1400SS&kid=keioapp"
                },
                {
                    "app_type": "#ODA_APP",
                    "app_name": "小田急電鉄",
                    "app_link": "odakyuapp://stations/timetables?station_code=001&source=keioapp"
                },
                {
                    "app_type": "#TOEI_APP",
                    "app_name": "都営地下鉄（新宿西口）",
                    "app_link": "toeiapp://timetable?station_id=9217&from=keio"
                }
            ],
            "other": [
                {
                    "linkname": "ＪＲ　中央線　山手線　埼京線　湘南新宿ライン",
                    "link": "http://www.jreast.co.jp/sp/"
                },
                {
                    "linkname": "都営地下鉄　都営新宿線　都営大江戸線",
                    "link": "http://www.kotsu.metro.tokyo.jp"
                },
                {
                    "linkname": "東京メトロ　丸の内線",
                    "link": "http://www.tokyometro.jp/index.html"
                },
                {
                    "linkname": "西武鉄道",
                    "link": "https://www.seiburailway.jp/"
                },
                {
                    "linkname": "小田急線",
                    "link": "http://www.odakyu.jp"
                }
            ]
        },
        {
            "code": "07",
            "line": "1",
            "mark": "KO",
            "app": [
                {
                    "app_type": "#TOKYU_APP",
                    "app_name": "東急電鉄",
                    "app_link": "tokyulineapp://timetable/784?kid=keio-train-app"
                }
            ],
            "other": [
                {
                    "linkname": "東急　世田谷線",
                    "link": "http://www.tokyu.co.jp/sp/"
                }
            ]
        },
        {
            "code": "25",
            "line": "1",
            "mark": "KO",
            "app": [
                {
                    "app_type": "#JR_APP",
                    "app_name": "JR東日本",
                    "app_link": "jreast-app://?vid=C602-0001&kid=6003-0002&at4=1385"
                }
            ],
            "other": [
                {
                    "linkname": "ＪＲ　南武線",
                    "link": "http://www.jreast.co.jp/sp/"
                }
            ]
        },
        {
            "code": "29",
            "line": "1",
            "mark": "KO",
            "app": [],
            "other": [
                {
                    "linkname": "多摩モノレール",
                    "link": "http://www.tama-monorail.co.jp/sp/"
                }
            ]
        },
        {
            "code": "34",
            "line": "1",
            "mark": "KO",
            "app": [
                {
                    "app_type": "#JR_APP",
                    "app_name": "JR東日本",
                    "app_link": "jreast-app://?vid=C602-0001&kid=6003-0002&at4=1227"
                }
            ],
            "other": [
                {
                    "linkname": "ＪＲ　中央線　横浜線　八高線",
                    "link": "http://www.jreast.co.jp/sp/"
                }
            ]
        },
        {
            "code": "36",
            "line": "1",
            "mark": "KO",
            "app": [
                {
                    "app_type": "#JR_APP",
                    "app_name": "JR東日本",
                    "app_link": "jreast-app://?vid=C602-0001&kid=6003-0002&at4=0149"
                }
            ],
            "other": [
                {
                    "linkname": "ＪＲ　南武線",
                    "link": "http://www.jreast.co.jp/sp/"
                }
            ]
        },
        {
            "code": "40",
            "line": "1",
            "mark": "KO",
            "app": [
                {
                    "app_type": "#ODA_APP",
                    "app_name": "小田急電鉄",
                    "app_link": "odakyuapp://stations/timetables?station_code=075&source=keioapp"
                }
            ],
            "other": [
                {
                    "linkname": "小田急　多摩線",
                    "link": "http://www.odakyu.jp"
                }
            ]
        },
        {
            "code": "41",
            "line": "1",
            "mark": "KO",
            "app": [
                {
                    "app_type": "#ODA_APP",
                    "app_name": "小田急電鉄",
                    "app_link": "odakyuapp://stations/timetables?station_code=076&source=keioapp"
                }
            ],
            "other": [
                {
                    "linkname": "小田急　多摩線",
                    "link": "http://www.odakyu.jp"
                },
                {
                    "linkname": "多摩モノレール",
                    "link": "http://www.tama-monorail.co.jp/sp/"
                }
            ]
        },
        {
            "code": "45",
            "line": "1",
            "mark": "KO",
            "app": [
                {
                    "app_type": "#JR_APP",
                    "app_name": "JR東日本",
                    "app_link": "jreast-app://?vid=C602-0001&kid=6003-0002&at4=1224"
                }
            ],
            "other": [
                {
                    "linkname": "ＪＲ　横浜線　相模線",
                    "link": "http://www.jreast.co.jp/sp/"
                }
            ]
        },
        {
            "code": "52",
            "line": "1",
            "mark": "KO",
            "app": [
                {
                    "app_type": "#JR_APP",
                    "app_name": "JR東日本",
                    "app_link": "jreast-app://?vid=C602-0001&kid=6003-0002&at4=0931"
                }
            ],
            "other": [
                {
                    "linkname": "ＪＲ　中央線",
                    "link": "http://www.jreast.co.jp/sp/"
                }
            ]
        },
        {
            "code": "53",
            "line": "1",
            "mark": "KO",
            "app": [],
            "other": [
                {
                    "linkname": "高尾山ケーブルカー",
                    "link": "http://www.takaotozan.co.jp/sp/"
                }
            ]
        },
        {
            "code": "01",
            "line": "3",
            "mark": "IN",
            "app": [
                {
                    "app_type": "#JR_APP",
                    "app_name": "JR東日本",
                    "app_link": "jreast-app://?vid=C602-0001&kid=6003-0002&at4=0808"
                },
                {
                    "app_type": "#TOKYU_APP",
                    "app_name": "東急電鉄",
                    "app_link": "tokyulineapp://timetable/26?kid=keio-train-app"
                },
                {
                    "app_type": "#METRO_APP",
                    "app_name": "東京メトロ",
                    "app_link": "metroapp://?contentsId=stationTimetable&sourceAppId=keio-train-app&useUserStation=0&stationId=odpt.Station:TokyoMetro.Ginza.Shibuya"
                }
            ],
            "other": [
                {
                    "linkname": "ＪＲ　山手線　埼京線　湘南新宿ライン",
                    "link": "http://www.jreast.co.jp/sp/"
                },
                {
                    "linkname": "東急　東横線　田園都市線",
                    "link": "http://www.tokyu.co.jp/sp/"
                },
                {
                    "linkname": "東京メトロ　銀座線　半蔵門線　副都心線",
                    "link": "http://www.tokyometro.jp/index.html"
                }
            ]
        },
        {
            "code": "05",
            "line": "3",
            "mark": "IN",
            "app": [
                {
                    "app_type": "#ODA_APP",
                    "app_name": "小田急電鉄",
                    "app_link": "odakyuapp://stations/timetables?station_code=007&source=keioapp"
                }
            ],
            "other": [
                {
                    "linkname": "小田急線",
                    "link": "http://www.odakyu.jp"
                }
            ]
        },
        {
            "code": "17",
            "line": "3",
            "mark": "IN",
            "app": [
                {
                    "app_type": "#JR_APP",
                    "app_name": "JR東日本",
                    "app_link": "jreast-app://?vid=C602-0001&kid=6003-0002&at4=0596"
                }
            ],
            "other": [
                {
                    "linkname": "ＪＲ 中央線",
                    "link": "http://www.jreast.co.jp/sp/"
                }
            ]
        }
    ]
}
  ```

</details>

> https://i.opentidkeio.jp/config/railroad_chg.json

*HTTPリクエスト：GET*

<details>
<summary>Json Back</summary>
  
  ```json
{
    "chg": [
        {
            "name": "JR",
            "link": "http://www.jreast.co.jp/sp/"
        },
        {
            "name": "ODA",
            "link": "http://www.odakyu.jp"
        },
        {
            "name": "TAMA",
            "link": "http://www.tama-monorail.co.jp/sp/"
        },
        {
            "name": "METORO",
            "link": "http://www.tokyometro.jp/index.html"
        },
        {
            "name": "TOEI",
            "link": "http://www.kotsu.metro.tokyo.jp"
        },
        {
            "name": "TOKYU",
            "link": "http://www.tokyu.co.jp/sp/"
        },
        {
            "name": "TAKAO",
            "link": "http://www.takaotozan.co.jp/sp/"
        }
    ]
}
  ```

</details>

> https://i.opentidkeio.jp/config/other_chg_app.json

*HTTPリクエスト：GET*

<details>
<summary>Json Back</summary>
  
  ```json
{
    "chg": [
        {
            "code": "01",
            "line": "1",
            "mark": "KO",
            "app": [
                {
                    "app_type": "#JR_APP",
                    "app_name": "JR東日本",
                    "line": [
                        {
                            "icon": "#IconJC",
                            "linename": "中央線快速電車",
                            "link": "jreast-app://?vid=C601-0001&kid=6003-0001&at4=0866&line=56&lineCode=57"
                        },
                        {
                            "icon": "#IconJB",
                            "linename": "中央・総武線各駅停車",
                            "link": "jreast-app://?vid=C601-0001&kid=6003-0001&at4=0866&line=56&lineCode=56"
                        },
                        {
                            "icon": "#IconJY",
                            "linename": "山手線",
                            "link": "jreast-app://?vid=C603-0001&kid=6003-0001&at4=0866"
                        },
                        {
                            "icon": "#IconJA",
                            "linename": "埼京線",
                            "link": "jreast-app://?vid=C601-0001&kid=6003-0001&at4=0866&line=43&lineCode=43"
                        },
                        {
                            "icon": "#IconJS",
                            "linename": "湘南新宿ライン",
                            "link": "jreast-app://?vid=C601-0001&kid=6003-0001&at4=0866&line=46-1&lineCode=46-1"
                        }
                    ]
                },
                {
                    "app_type": "#METRO_APP",
                    "app_name": "東京メトロ",
                    "line": [
                        {
                            "icon": "#IconMM",
                            "linename": "丸ノ内線",
                            "link": "metroapp://?contentsId=trainLocation&sourceAppId=keio-train-app&useUserStation=0&stationId=odpt.Station:TokyoMetro.Marunouchi.Shinjuku"
                        }
                    ]
                },
                {
                    "app_type": "#SEIBU_APP",
                    "app_name": "西武鉄道",
                    "line": [
                        {
                            "icon": "#IconSS",
                            "linename": "新宿線",
                            "link": "seibuapp://invoke?f=position&l=L009&s=S1400SS&kid=keioapp"
                        }
                    ]
                },
                {
                    "app_type": "#ODA_APP",
                    "app_name": "小田急電鉄",
                    "line": [
                        {
                            "icon": "#IconOH",
                            "linename": "小田原線",
                            "link": "odakyuapp://all_train_positions?station_code=001&source=keioapp"
                        }
                    ]
                },
                {
                    "app_type": "#TOEI_APP",
                    "app_name": "都営地下鉄",
                    "app_name2": "東京都交通局",
                    "line": [
                        {
                            "icon": "#IconTOS",
                            "linename": "新宿線",
                            "link": "toeiapp://trainlocation?line_id=3&station_id=4254&from=keio"
                        },
                        {
                            "icon": "#IconTOE",
                            "linename": "大江戸線",
                            "link": "toeiapp://trainlocation?line_id=1&station_id=4254&from=keio"
                        },
                        {
                            "icon": "#IconTOE",
                            "linename": "大江戸線（新宿西口）",
                            "link": "toeiapp://trainlocation?line_id=1&station_id=9217&from=keio"
                        }
                    ]
                }
            ],
            "other": [
                {
                    "linkname": "ＪＲ　中央線　山手線　埼京線　湘南新宿ライン",
                    "link": "http://www.jreast.co.jp/sp/"
                },
                {
                    "linkname": "東京メトロ　丸の内線",
                    "link": "http://www.tokyometro.jp/index.html"
                },
                {
                    "linkname": "西武鉄道",
                    "link": "https://www.seiburailway.jp/"
                },
                {
                    "linkname": "小田急線",
                    "link": "http://www.odakyu.jp"
                },
                {
                    "linkname": "都営地下鉄　都営新宿線　都営大江戸線",
                    "link": "http://www.kotsu.metro.tokyo.jp"
                }
            ]
        },
        {
            "code": "07",
            "line": "1",
            "mark": "KO",
            "app": [
                {
                    "app_type": "#TOKYU_APP",
                    "app_name": "東急電鉄",
                    "line": [
                        {
                            "icon": "#IconSG",
                            "linename": "世田谷線",
                            "link": "tokyulineapp://tid/26007/784?kid=keio-train-app"
                        }
                    ]
                }
            ],
            "other": [
                {
                    "linkname": "東急　世田谷線",
                    "link": "http://www.tokyu.co.jp/sp/"
                }
            ]
        },
        {
            "code": "25",
            "line": "1",
            "mark": "KO",
            "app": [
                {
                    "app_type": "#JR_APP",
                    "app_name": "JR東日本",
                    "line": [
                        {
                            "icon": "#IconJN",
                            "linename": "南武線",
                            "link": "jreast-app://?vid=C601-0001&kid=6003-0001&at4=1385&line=63&lineCode=63"
                        }
                    ]
                }
            ],
            "other": [
                {
                    "linkname": "ＪＲ　南武線",
                    "link": "http://www.jreast.co.jp/sp/"
                }
            ]
        },
        {
            "code": "34",
            "line": "1",
            "mark": "KO",
            "app": [
                {
                    "app_type": "#JR_APP",
                    "app_name": "JR東日本",
                    "line": [
                        {
                            "icon": "#IconJC",
                            "linename": "中央線快速電車",
                            "link": "jreast-app://?vid=C601-0001&kid=6003-0001&at4=1227&line=56&lineCode=57"
                        },
                        {
                            "icon": "#IconJB",
                            "linename": "中央・総武線各駅停車",
                            "link": "jreast-app://?vid=C601-0001&kid=6003-0001&at4=1227&line=56&lineCode=56"
                        },
                        {
                            "icon": "#IconJH",
                            "linename": "横浜線",
                            "link": "jreast-app://?vid=C601-0001&kid=6003-0001&at4=1227&line=70&lineCode=70"
                        }
                    ]
                }
            ],
            "other": [
                {
                    "linkname": "ＪＲ　中央線　横浜線　八高線",
                    "link": "http://www.jreast.co.jp/sp/"
                }
            ]
        },
        {
            "code": "36",
            "line": "2",
            "mark": "KO",
            "app": [
                {
                    "app_type": "#JR_APP",
                    "app_name": "JR東日本",
                    "line": [
                        {
                            "icon": "#IconJN",
                            "linename": "南武線",
                            "link": "jreast-app://?vid=C601-0001&kid=6003-0001&at4=0149&line=63&lineCode=63"
                        }
                    ]
                }
            ],
            "other": [
                {
                    "linkname": "ＪＲ　南武線",
                    "link": "http://www.jreast.co.jp/sp/"
                }
            ]
        },
        {
            "code": "40",
            "line": "2",
            "mark": "KO",
            "app": [
                {
                    "app_type": "#ODA_APP",
                    "app_name": "小田急電鉄",
                    "line": [
                        {
                            "icon": "#IconOT",
                            "linename": "多摩線",
                            "link": "odakyuapp://all_train_positions?station_code=075&source=keioapp"
                        }
                    ]
                }
            ],
            "other": [
                {
                    "linkname": "小田急線",
                    "link": "http://www.odakyu.jp"
                }
            ]
        },
        {
            "code": "41",
            "line": "2",
            "mark": "KO",
            "app": [
                {
                    "app_type": "#ODA_APP",
                    "app_name": "小田急電鉄",
                    "line": [
                        {
                            "icon": "#IconOT",
                            "linename": "多摩線",
                            "link": "odakyuapp://all_train_positions?station_code=076&source=keioapp"
                        }
                    ]
                }
            ],
            "other": [
                {
                    "linkname": "小田急線",
                    "link": "http://www.odakyu.jp"
                }
            ]
        },
        {
            "code": "45",
            "line": "2",
            "mark": "KO",
            "app": [
                {
                    "app_type": "#JR_APP",
                    "app_name": "JR東日本",
                    "line": [
                        {
                            "icon": "#IconJH",
                            "linename": "横浜線",
                            "link": "jreast-app://?vid=C601-0001&kid=6003-0001&at4=1224&line=70&lineCode=70"
                        }
                    ]
                }
            ],
            "other": [
                {
                    "linkname": "ＪＲ　横浜線　相模線",
                    "link": "http://www.jreast.co.jp/sp/"
                }
            ]
        },
        {
            "code": "52",
            "line": "1",
            "mark": "KO",
            "app": [
                {
                    "app_type": "#JR_APP",
                    "app_name": "JR東日本",
                    "line": [
                        {
                            "icon": "#IconJC",
                            "linename": "中央線快速電車",
                            "link": "jreast-app://?vid=C601-0001&kid=6003-0001&at4=0931&line=56&lineCode=57"
                        },
                        {
                            "icon": "#IconJB",
                            "linename": "中央・総武線各駅停車",
                            "link": "jreast-app://?vid=C601-0001&kid=6003-0001&at4=0931&line=56&lineCode=56"
                        }
                    ]
                }
            ],
            "other": [
                {
                    "linkname": "ＪＲ　中央線",
                    "link": "http://www.jreast.co.jp/sp/"
                }
            ]
        },
        {
            "code": "01",
            "line": "3",
            "mark": "IN",
            "app": [
                {
                    "app_type": "#JR_APP",
                    "app_name": "JR東日本",
                    "line": [
                        {
                            "icon": "#IconJY",
                            "linename": "山手線",
                            "link": "jreast-app://?vid=C603-0001&kid=6003-0001&at4=0808"
                        },
                        {
                            "icon": "#IconJA",
                            "linename": "埼京線",
                            "link": "jreast-app://?vid=C601-0001&kid=6003-0001&at4=0808&line=43&lineCode=43"
                        },
                        {
                            "icon": "#IconJS",
                            "linename": "湘南新宿ライン",
                            "link": "jreast-app://?vid=C601-0001&kid=6003-0001&at4=0808&line=46-1&lineCode=46-1"
                        }
                    ]
                },
                {
                    "app_type": "#TOKYU_APP",
                    "app_name": "東急電鉄",
                    "line": [
                        {
                            "icon": "#IconTY",
                            "linename": "東横線",
                            "link": "tokyulineapp://tid/26001/26?kid=keio-train-app"
                        },
                        {
                            "icon": "#IconDT",
                            "linename": "田園都市線",
                            "link": "tokyulineapp://tid/26003/26?kid=keio-train-app"
                        }
                    ]
                },
                {
                    "app_type": "#METRO_APP",
                    "app_name": "東京メトロ",
                    "line": [
                        {
                            "icon": "#IconMG",
                            "linename": "銀座線",
                            "link": "metroapp://?contentsId=trainLocation&sourceAppId=keio-train-app&useUserStation=0&stationId=odpt.Station:TokyoMetro.Ginza.Shibuya"
                        },
                        {
                            "icon": "#IconMZ",
                            "linename": "半蔵門線",
                            "link": "metroapp://?contentsId=trainLocation&sourceAppId=keio-train-app&useUserStation=0&stationId=odpt.Station:TokyoMetro.Hanzomon.Shibuya"
                        },
                        {
                            "icon": "#IconMF",
                            "linename": "副都心線",
                            "link": "metroapp://?contentsId=trainLocation&sourceAppId=keio-train-app&useUserStation=0&stationId=odpt.Station:TokyoMetro.Fukutoshin.Shibuya"
                        }
                    ]
                }
            ],
            "other": [
                {
                    "linkname": "ＪＲ　山手線　埼京線　湘南新宿ライン",
                    "link": "http://www.jreast.co.jp/sp/"
                },
                {
                    "linkname": "東急　東横線　田園都市線",
                    "link": "http://www.tokyu.co.jp/sp/"
                },
                {
                    "linkname": "東京メトロ　銀座線　半蔵門線　副都心線",
                    "link": "http://www.tokyometro.jp/index.html"
                }
            ]
        },
        {
            "code": "05",
            "line": "3",
            "mark": "IN",
            "app": [
                {
                    "app_type": "#ODA_APP",
                    "app_name": "小田急電鉄",
                    "line": [
                        {
                            "icon": "#IconOH",
                            "linename": "小田原線",
                            "link": "odakyuapp://all_train_positions?station_code=007&source=keioapp"
                        }
                    ]
                }
            ],
            "other": [
                {
                    "linkname": "小田急線",
                    "link": "http://www.odakyu.jp"
                }
            ]
        },
        {
            "code": "17",
            "line": "3",
            "mark": "IN",
            "app": [
                {
                    "app_type": "#JR_APP",
                    "app_name": "JR東日本",
                    "line": [
                        {
                            "icon": "#IconJC",
                            "linename": "中央線快速電車",
                            "link": "jreast-app://?vid=C601-0001&kid=6003-0001&at4=0596&line=56&lineCode=57"
                        },
                        {
                            "icon": "#IconJB",
                            "linename": "中央・総武線各駅停車",
                            "link": "jreast-app://?vid=C601-0001&kid=6003-0001&at4=0596&line=56&lineCode=56"
                        }
                    ]
                }
            ],
            "other": [
                {
                    "linkname": "ＪＲ 中央線",
                    "link": "http://www.jreast.co.jp/sp/"
                }
            ]
        }
    ]
}
  ```

</details>
