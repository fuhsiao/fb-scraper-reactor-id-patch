# fb-scraper-reactor-id-patch
**問題**   
facebook-scraper 未抓取 post reactors id  

**解決方式**  
修改 extract_reactors 回傳  
如下圖，可由追蹤按鈕得到 id  

<img src="https://github.com/fuhsiao/fb-scraper-reactor-id-patch/assets/86312099/946de2ee-c2ca-499d-b43d-00881956e412" alt="圖片描述" width="425" height="120">
  
詳細請見 `stats_single_post.ipynb`

## reference
+ https://pypi.org/project/facebook-scraper/
