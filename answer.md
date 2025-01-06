# 第1次練習-練習-PC1
>
>學號：112111202
><br />
>姓名：康祐翔
><br />
>作業撰寫時間：60 (mins，包含程式撰寫時間)
><br />
>最後撰寫文件日期：2025/01/06
>

本份文件包含以下主題：(至少需下面兩項，若是有多者可以自行新增)
- [x] 說明內容
- [x] 個人認為完成作業須具備觀念

## 說明程式與內容

開始寫說明，該說明需說明想法，
並於之後再對上述想法的每一部分將程式進一步進行展現，
若需引用程式區則使用下面方法，
若為.cs檔內程式除了於敘述中需註明檔案名稱外，
還需使用語法` ```語言種類 程式碼 ``` `，其中語言種類若是要用python則使用py，java則使用java，C/C++則使用cpp，
下段程式碼為語言種類選擇csharp使用後結果：

```csharp
public void mt_getResult(){
    ...
}
```

若要於內文中標示部分網頁檔，則使用以下標籤` ```html 程式碼 ``` `，
下段程式碼則為使用後結果：

```html
<%@ Page Language="C#" AutoEventWireup="true" ...>

<!DOCTYPE html>

<html xmlns="http://www.w3.org/1999/xhtml">
<head runat="server">
<meta http-equiv="Content-Type" ...>
    <title></title>
</head>
<body>
    <form id="form1" runat="server">
        <div>
        </div>
    </form>
</body>
</html>
```
更多markdown方法可參閱[https://ithelp.ithome.com.tw/articles/10203758](https://ithelp.ithome.com.tw/articles/10203758)

請在撰寫"說明程式與內容"該塊內容，請把原該塊內上述敘述刪除，該塊上述內容只是用來指引該怎麼撰寫內容。

1. 請執行下面Git操作 (請參照題目pdf)

Ans:

2. 請整理課堂上所提的Git指令，顯示其語法語給予明顯的例子

Ans:
    1.git add(加入檔案到暫存區)
        語法:
            git add (檔案名稱)
        範例:
            git add A.txt
        結果:將檔案交至暫存區 準備提交
    2.git commit(提交暫存區檔案至本地倉庫)
        語法:
            git commit -m"(提交訊息)"
        範例:
            git commit -m"A.txt"
        結果:將暫存區檔案提交至本地倉庫 並附加一則訊息
    3.git push(推送提交至遠端倉庫)
        語法:
            git push (遠端名稱) (分支名稱)
        範例:
            git push origin main
        結果:將本地倉庫的檔案推送提交至遠端倉庫的main分支
    4.git fetch(從遠端倉庫獲取資料)
        語法:
            git fetch (檔案名稱)
        範例:
            git fetch origin
        結果:從遠端倉庫下載更新到本地倉庫 但不會主動合併
    5.git pull(拉取並合併遠端更新)
        語法:
            git pull (遠端名稱) (分支名稱)
        範例:
            git push origin main
        結果:相當於git fetch跟git merge 從遠端倉庫下載並合併
    6.git branch(建立分支)
        語法:
            git branch (分支名稱)
        範例:
            git x
        結果:建立一條名為x的新分支
    7.git checkout(切換分支)
        語法:
            git checkout(分支名稱)
        範例:
            git checkout x
        結果:切換到x分支上
    8.git merge(合併分支)
        語法:
            git merge (分支名稱)
        範例:
            git merge x
        結果:將分支X的內容合併到目前的分支

3. 請先寫出同學認為資料結構一門課每周需要花多少時間？並提出理由。並將「請問要學習大學的資料結構每一週需要對於一般大學生需要多少時間」貼入chatgpt，並將其所建議的敘述貼出後，比較同學所認為若是每周低於chatgpt所評估的時間，兩者主要差異為何？應該怎麼安排自己時間了解資料結構？


Ans:
    1.我認為大概3個小時吧 
    2.建議每週學習時間
    課堂時間： 每週 2～3 小時（通常是 1～2 次課）。
    課後學習時間： 每週 4～6 小時（複習、練習、完成作業）。
    額外學習時間： 每週 2～3 小時（預習、額外練習、專題或進階內容）。
    總計： 每週約 8～12 小時。
    3.大概主要是因為gpt會把課程時間算進去 而我自己認為的時間之所以是3個小時是因為平常回到家都會需要很久的時間 加上有其他科目 自己也會有自己想做的事 所以能用的時間也不是很多

## 個人認為完成作業須具備觀念

開始寫說明，需要說明本次練習需學會那些觀念 (需寫成文章，需最少50字，並且文內不得有你、我、他三種文字)且必須提供完整與練習相關過程的notion筆記連結