# TW_medical_accessibility_2019

=== 醫療院所與醫事人員資料爬取(衛福部醫事查詢系統) ===  
1.以selenium & bf4 自衛福部網站 (https://ma.mohw.gov.tw/masearch/SearchBAS-101-1.aspx) 爬取醫療院所及其醫事人員資料。  
2.資料整理  
3.以地址爬取經緯度  
  
    
=== 醫院資料爬取(衛福部機構公開資訊查詢) ===  
1.以selenium & bf4 自衛福部網站 (https://mcia.mohw.gov.tw/openinfo/A100/A101-1.aspx) 爬取醫院及其醫事人員資料。  
2.資料整理  
  
  
=== 從幾何經緯度計算各村里中點 ===  
1.將政府公開資訊中，各村里的座標幾何資料，進行里中點換算。  
  
  
=== 計算各村里中點與各醫療機構的距離 ===  
1.依座標直線距離，計算各村里與各醫療機構的距離  
2.排序出與每個村裡最接近的各類醫療院所  
  
  
=== 最終分析之tableau檔案 ===  
https://drive.google.com/file/d/15RuVmB-0bKPPO1HZdlWRwMK94Nn-3CXc/view?usp=sharing

