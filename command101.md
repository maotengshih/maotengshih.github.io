# CLI新手指令
```
pwd //print workink dir

ls -a（包含隱藏檔）l（longformat） // list -al(包含詳細資料)

cd.. //回上一層
cd /absolute/path //絕對路徑
cd ~/  //省略了 user/yourname

man ‘指令’ //叫男人把‘指令’的說明書拿來

touch filename//碰了就改變時間，或新檔在這一碰中被建立

rm filename  //刪除檔案
rmdir filefolder //刪除資料夾
rm -f(forceToDo) -r(整個資料夾)  //刪除資料夾

mkdir iamfolder //可用tab鍵補全檔名

mv oldName newName //改名，內容移進去改用新名字

cp fileA fileB //拷貝一份檔案Ａ取名叫做Ｂ
cp -r folderA folderB //拷貝一份資料夾Ａ取名叫做Ｂ

grep xx file //把xx	檔案裡抓出來

wget  //非預設 brew install wget
wget 網址 //下載這個網址上的東西
open filename //直接打開檔案

curl -I 網址 //查看各種連線請求的資訊

echo 123 //印出123，跟console.log 有點像
echo 123 > 456.txt //印出123，並存到456.txt
		  >>        //不覆蓋原檔，新增至最後一行

輸入指令 | 輸出指令 //連續技
cat 123 | grep ok >> result   //用cat查看123 這支檔案，接著用 grep 把含有ok的那幾行都抓出來，然後輸出至result這個檔案
```



[編程者的修煉之路](https://medium.com/@maotengshih/%E7%B7%A8%E7%A8%8B%E8%80%85%E7%9A%84%E4%BF%AE%E7%85%89%E4%B9%8B%E8%B7%AF-bd68e6200d6a?source=friends_link&sk=204d2222d0544150912de1940a695b39)