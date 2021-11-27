# CS_NOTE  
### Linux檔案命名  
  >1.英文字元(以小寫為主，大小寫有區分)  
  >2.長度至多256個字元  
  >3.檔案名不可使用的字元:?、*、空格、$、&、/、.、 


### 常用語法  
  >cd:變換目錄  
  >cp:複製  
  >mv:移動  
  >cat:查看檔案內容    
  >pwd:顯示幕前的目錄  
  >Is:顯示目錄下的所有內容  
  >nano.檔案名.檔案類型  
    ctrl C顯示游標所在、ctrl W查詢命令     
  >mkdir:建立一個新的目錄、rmdir:刪除一個裡面是空的目錄   


### 壓縮檔案  
1.備份資料時方便整理  
2.節省硬碟空間(正常是使用bytes單位計量，最小計量可用到bites)  
3.方便資訊在網路上流通  
4.可視情況將檔案加密  
  #gzip  
    壓縮: gzip FileName  解壓縮: gunzip FileName.gz/gzip -d FileName.gz  
  #xz  
    壓縮: xz -z FileName  解壓縮: xz -z FileName.xz  
  #tar.gz  
    壓縮: tar -zcvf FileName.tar.gz DirName 解壓縮: tar -zxvf FileName.tar.gz   
    

**絕對路徑**  
由根目錄寫起，指定的某一個目錄  
**相對路徑**  
相對於目前工作目錄的路徑  
