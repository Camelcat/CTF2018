# CTF2018
---#sCTF 2016 Q1 : banana-boy-20---



1.-- 確定檔案格式 --

![圖片](pic/file.png)


2.-- 查看檔案內藏的字串 --(猜 CTF/.........)



3.-- 使用binwalk分析檔案--(binwalk carter.jpg)

![圖片](pic/binwalk.png)



4.-- 使用dd抽出檔案 --(dd if=carter.jpg of=new.jpg skip=140147 bs=1)

![圖片](pic/dd.png)


(if是指定輸入檔
 of是指定輸出檔
 skip是指定從輸入檔開頭跳過140147個塊後再開始複製
 bs設置每次讀寫塊的大小為1位元組)



![圖片](pic/new.jpg)




---#ABCTF 2016 : just-open-it---

1.-- 查看檔案內藏的字串 --(猜 CTF/.........)

![圖片](pic/justopenit/strings.png)

![圖片](pic/justopenit/stringsGREP.png)


---#CSAW QUALS 2015: keep-calm-and-ctf---

1.-- 確定檔案格式 --


2.-- 查看檔案內藏的字串 --(猜 CTF/.........)

3.-- 安裝工具並學習使用技術 --(jpg metadata linux)

4.-- 查看檔案並讀出答案 --

![picture](pic/keepkalmandctf/exiftool.png)

