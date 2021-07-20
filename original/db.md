###   データベース詳細
購入
|属性|型|PK|NN|FK|
|----|-|--|---|--|
|order_id|bigint(20)|〇|〇|ー|
|costomer_code|varchar(50)|ー|〇|ー|
|purchase_date|date|ー|〇|ー|
|total_price|int(11)|ー|〇|ー|

購入詳細
|属性|型|PK|NN|FK|
|----|-|--|---|--|
|order_id|bigint(20)|〇|〇|ー|
|buy_code|bigint(20)|〇|〇|ー|
|price|date|ー|〇|ー|
|num|int(11)|ー|〇|ー|

顧客
|属性|型|PK|NN|FK|
|----|-|--|---|--|
|costomer_code|varchar(50)|〇|〇|ー|
|order_id|bigint(20)|ー|〇|ー|
|pass|varchar(50)|ー|〇|ー|
|name|varchar(20)|ー|〇|ー|
|address|varchar(100)|ー|〇|ー|
|tel|varchar(20)|ー|〇|ー|
|mail|varchar(100)|ー|〇|ー|


商品
|属性|型|PK|NN|FK|
|----|-|--|---|--|
|item_code|int(11)|〇|〇|ー|
|item_name|varchar(50)|ー|〇|ー|
|price|int(11)|ー|〇|ー|
|category_id|int(11)|ー|〇|ー|
|image|varchar(200)|ー|〇|ー|
|detail|vrchar(500)|ー|〇|ー|

