# NSYSU_nearby_1km_Youbike_station
此程式將會每隔10分鐘自動抓取TDX資料，以國立中山大學幾何中心半徑1公里內的Youbike為例。

API 呼叫次數限制：
使用 API 金鑰呼叫，每個呼叫來源端 IP 呼叫次數限制為 50 次/秒 (無每日上限)。
不使用 API 金鑰呼叫，則僅能透過瀏覽器呼叫 API，且每個呼叫來源端 IP 的上限為每日 50 次。
因為本程式需每10分鐘呼叫一次，使用者須自行註冊會員，以取得金鑰。

#參考網址
https://blog.jiatool.com/posts/tdx_python/
官方的說明文件：https://github.com/tdxmotc/SampleCode
