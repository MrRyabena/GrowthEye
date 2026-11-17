# GrowthEye

## Scheme and units

- MSU - Magnetic Stirring Unit
- ODMU - Optical Density Measurement Unit
- ECU - Environmental Control Unit

![GrowthEye scheme](schemes/GrowthEye_scheme.png)

## Components

|Component|Unit|Link|Comment|
|--|--|--|--|
|ESP32|-|[AliExpress](https://aliexpress.ru/item/1005006371447527.html?sku_id=12000036932891750)|Main controller|
|TSL2591|ODMU|[AliExpress](https://aliexpress.ru/item/1005006343708454.html?spm=a2g2w.cart.cart_split.8.37234aa6e1CVuM&sku_id=12000036830217424)|Optical density sensor|
|LED 750 nm|ODMU|[ChipDip](https://www.chipdip.ru/product/tds-p003ir-t3a-m1-svetodiod-infrakrasnyy-750nm-ir-3w-9000330853)|LED for optical density measurement|
|O50 motor|MSU|[AliExpress](https://aliexpress.ru/item/1005005872602602.html?spm=a2g2w.cart.cart_split.19.75bc4aa6M9FEC9&sku_id=12000046724823759)|Motor 100-700 rpm, 3-12 V|
|Magnet|MSU|[Ozon](https://www.ozon.ru/product/magnit-disk-10h2-mm-30-sht-komplekt-rosmagnit-1829208707/?is_apparel_size_selected=true&sh=x4l34RXezg)|Magnet for stirring|
|IR-sensor|MSU|[AliExpress](https://aliexpress.ru/item/1005009866385023.html?spm=a2g2w.cart.cart_split.12.75bc4aa6M9FEC9&sku_id=12000050416964170)|IR sensor for motor speed control|
|Heater|ECU|[AliExpress](https://aliexpress.ru/item/1005005898716287.html?shpMethod=CAINIAO_STANDARD&sku_id=12000034762077412&spm=a2g2w.productlist.search_results.3.5a68318b311Nc9)|Heater cable|
|DS18B20|ECU|[AliExpress](https://aliexpress.ru/item/1005008371551087.html?spm=a2g2w.cart.cart_split.5.75bc4aa6M9FEC9&sku_id=12000059707805376)|Temperature sensor|
|Sunlight LED strip|ECU|[Ozon](https://www.ozon.ru/product/svetodiodnaya-lenta-12v-5-metrov-9-6-vt-m-4000k-neytralnyy-belyy-svet-feron-ls612-41448-553677123/?at=1ier1_rv1zO5Q-uKh1HgsrHUGCqYaNhp&from_sku=553677123&oos_search=false&sh=x4l34YZabg)|LED strip for plant growth|
|Solenoid valve|ECU|[AliExpress](https://aliexpress.ru/item/4000945422634.html?spm=a2g2w.cart.0.0.46cf4aa6p6vUKN&sku_id=12000017418940145&channel=choice)|Solenoid valve for CO2 injection|
|DC-DC 3V3|PU|[AliExpress](https://aliexpress.ru/item/1005002921104409.html?spm=a2g2w.orderdetail.0.0.50514aa6mDfmnd&sku_id=12000037961425562&_ga=2.158586554.1897382206.1794901758-611697668.1755021739)|DC-DC converter 12-5V to 3.3V|
|PS 12V 8A|PU|[Ozon](https://www.ozon.ru/product/impulsnyy-blok-pitaniya-12v-100vt-8-3a-dlya-svetodiodnoy-lenty-i-svetilnikov-stabilizirovannyy-1748102492/?at=1pyr1PzgIE1qWmnNMdmb2nWOaP9x55fd&sh=x4l34dpMog)|Power supply 12V 8A|
