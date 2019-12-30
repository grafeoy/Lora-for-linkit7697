# Lora-and-linkit7697

在兩臺Linkit 7697上進行簡單的LoRa單向傳輸\
使用Arduino\
使用https://github.com/sandeepmistry/arduino-LoRa 程式庫\
以seeed的sensor為範例 空氣溫溼度、土壤濕度\
Lora裝置是使用mini LoRa，不過沒用到AT指令就是了，畢竟是「簡單的」範例

# 設定

不知道為什麼lora的程式庫在安裝最新版的情況下，使用linkit 7697編譯會報錯\
我的解決方法是降lora程式庫的版本，實測0.0.1與0.0.0是可以運作的\
我有使用seeed的擴充版(不過應該沒影響就是了)
