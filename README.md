ユーザーマニュアル
=============
ここでは各コンポーネントの簡単な説明とRTMの使用例を示します。  
 
各コンポーネントの概要
--------------------------------
###1. MotionEditor ###
----------------------------------
　　GUIを用いて簡単にモーションを作成するためのコンポーネントです。  
　これを用いると、各関節のサーボモータの角度を目で確認しながらモーションを作成でき、  
　簡単にMotionLoderが読み込めるXML形式に出力可能です。  

+ コンポーネントの仕様  
[![画像1][image1]](http://cloud.github.com/downloads/s-ryuki/Pictures/MotionEditor_Comm.png)
[image1]:http://cloud.github.com/downloads/s-ryuki/Pictures/MotionEditor_Comm.png


+ MotionEditorの使い方
 [![画像2][image2]](http://cloud.github.com/downloads/s-ryuki/Pictures/MotionEditor＿GUI_Guide2.png)
[image2]:http://cloud.github.com/downloads/s-ryuki/Pictures/MotionEditor＿GUI_Guide2.png


　　File：　出力するファイルの名前を入力  
　　Time：　サーボを目的角度まで動かすのにかける時間[ms]  
　　Wait：　目的角度に動いたあとの待機時間[ms]  
　　Pose：　モーションの番号(同じものが２つあると前にあるものが優先される)  


　作成したモーションファイルはMotionEditorフォルダ内に出力されます。

　操作できるサーボモータの個数を増やす場合は、MotionEditorフォルダ内の  
　iniフォルダ内にあるMotionEditor.iniを編集することができます。  
  
