###   データベース詳細
d_purchase
|属性|型|PK|NN|FK|
|----|-|--|---|--|
|order_id|bigint(20)|〇|〇|ー|
|costomer_code|varchar(50)|ー|〇|ー|
|purchase_date|date|ー|〇|ー|
|total_price|int(11)|ー|〇|ー|

d_purchase_detail
|属性|型|PK|NN|FK|
|----|-|--|---|--|
|detail_id|bigint(20)|〇|〇|ー|
|order_id|bigint(20)|〇|〇|〇|
|item_code|int(11)|ー|〇|ー|
|price|int(11)|ー|〇|ー|
|num|int(11)|ー|〇|ー|

