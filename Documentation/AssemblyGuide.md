# 組み立てガイド


## 1. 必要なもの

* はんだ付けセット
* 接着剤
* プラスドライバー
* 各種部品([PartsList](./PartsList.md)参照)

---

## 2. 組み立て手順

### Step 1: 基板（PCB）への部品実装と配線
部品と導線のはんだ付けを行います。  
LRボタン用基板は表裏を間違えやすいです。GNDの印字がない方にスイッチの押す部分がきます。

<div align="center">
  <img src="../Image/WiringDiagram.png" width="500" alt="配線図">
  <p>配線図</p> </div>
<div align="center">
  <img src="../Image/Assembly1.png" width="500" alt="Assembly1">
  <p>はんだ付けが完了した基板</p> </div>

### Step 2: GP2040-CEのインストール
GP2040-CEをインストールします。すべてのボタンが動くことを確認してピンマッピングの設定を行います。

<div align="center">
  <img src="../Image/PinMapping.png" width="500" alt="PinMapping">
  <p>ピンマッピング</p> </div>

### Step 3: スティックの組み立て
①スティックの土台のパーツ(StickBase)にナットを、軸のパーツ(StickAxis)に磁石を接着剤でつけ組み合わせます。  
②スティックの土台の欠けている部分を右下にして、横方向にパーツ(StickHorizontal)をはめ込みます。  
③残りのパーツ(StickVertical)をはめ込みます。  
④スティックの頭のパーツ(StickHead)に軸につけた磁石と引き合うように磁石を接着します。これは今は組み合わせずに本体を組み立てた後にはめ込みます。  
これでスティックは完成です。3Dプリントのばらつきやバリによって滑らかに動かないときはやすり等で調整します。
<div align="center">
  <img src="../Image/Assembly2.png" width="250" alt="Assembly2">
  <p>スティック組み立て①</p> </div>

<div align="center">
  <img src="../Image/Assembly3.png" width="250 " alt="Assembly3">
  <p>スティック組み立て②</p> </div>

<div align="center">
  <img src="../Image/Assembly4.png" width="250 " alt="Assembly4">
  <p>スティック組み立て③</p> </div>

<div align="center">
  <img src="../Image/Assembly0.png" width="250 " alt="Assembly0">
  <p>スティック組み立て④</p> </div>

### Step 4: 本体の組み立て
①本体前面(Front)にナットを接着します。  
②本体背面(Back)とはんだ付けした基板を組み合わせてねじとナットで固定します。  
③ボタンパーツをキースイッチにはめ込みます。パーツが大きめなので接着剤かマスキングテープなどシート状のものを噛ませてはめ込むことで固定します。  
④本体背面と前面を組み合わせてねじとナットで固定します。  
⑤端子がついている面から基板をねじで固定します。  
⑥スティックの頭をはめ込んで完成です
<div align="center">
  <img src="../Image/Assembly5.png" width="500" alt="Assembly5">
  <p>本体組み立て①</p> </div>

<div align="center">
  <img src="../Image/Assembly6.png" width="500 " alt="Assembly6">
  <p>本体組み立て②</p> </div>

<div align="center">
  <img src="../Image/Assembly7.png" width="500 " alt="Assembly7">
  <p>本体組み立て③</p> </div>

<div align="center">
  <img src="../Image/Assembly8.png" width="500 " alt="Assembly8">
  <p>本体組み立て④</p> </div>
  
<div align="center">
  <img src="../Image/Assembly9.png" width="500 " alt="Assembly9">
  <p>本体組み立て⑤</p> </div>

<div align="center">
  <img src="../Image/Assembly10.png" width="500 " alt="Assembly10">
  <p>本体組み立て⑥</p> </div>