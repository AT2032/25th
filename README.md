# サーボ周りの製作方法
この作業は接合班との協力作業なので作業日は接合班と日程を調整する。  
接合班がテール桁を作り終わった段階で桁に穴をあけてその部分から中子までケーブルを通す。  
メイン電装からサーボまでのケーブルは途中で中継コネクタを挟み，T字とテールが接合した際に中継のコネクタ同士を繋げる
![Image](https://github.com/user-attachments/assets/3144c7ea-0470-4842-9ea3-f9c12fdfe161)


## 使う部品
* 軟質マイクコード スーパーフレックス VSVC 3芯  
  https://shop.oyaide.com/products/s_vsvc_3.html
* サーボ用コネクタ(サーボ付属)  
  https://kondo-robot.com/product/krs-4034hv-ics
* 中継コネクタ  
  https://www.amazon.co.jp/gp/product/B07RR7JD52/
## ➀桁にケーブルを通す穴をあける(接合班)
かんざしから少し離した位置に6.5mmほどの穴をあける  
穴はぴったりすぎるとケーブルに力が加わった際に断線する可能性があるため，少し余裕があるくらいの大きさで開けてもらう  
![Image](https://github.com/user-attachments/assets/82a9f5be-6a7b-4f79-ba3b-fb1ea1238507)
## ➁ケーブルを通す
穴からケーブルを通し，テールに通し，サーボに付属する専用のケーブルを切ってケーブルとはんだ付けする  
ケーブルのつなげ方は以下の通りである  
<サーボコネクタ―ケーブル>
* GND-黒，シールド
* POW-赤
* ICS－SIG-白
### 注意点
サーボのコネクタとサーボは桁の外側で接続するため，中子に通すケーブルの長さはある程度長くとっておく
![Image](https://github.com/user-attachments/assets/57ca0cd3-527e-41e0-a6c4-02ed749c3211)
## ➂中子を桁の中に入れる(接合班)
中子を桁の中子の穴まで入れる。  
中子を入れたら一度，サーボにコネクタを繋げて穴に入るかの確認を行う(接続できない場合はもう一度ケーブルをはんだ付けし直す)  
![Image](https://github.com/user-attachments/assets/6ee2fe46-75e6-4d64-8b9d-b426ce82bd12)



