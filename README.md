MotionEditor
============
　　GUIを用いてロボットのモーションを作成するためのコンポーネントです。  
　これを用いると、サーボモータが同期して動くため各関節の角度を目で確認しながらモーションを作成でき、  
　容易にMotionLoderが読み込めるXML形式に出力可能です。  

#### コンポーネントの仕様####
　　[![画像1][image1]](http://cloud.github.com/downloads/s-ryuki/Pictures/MotionEditor_Comm.png)
[image1]:http://cloud.github.com/downloads/s-ryuki/Pictures/MotionEditor_Comm.png

　ここでいうサーボマネージャとは私たちが作った[PrsServoManager](https://github.com/s-ryuki/PrsServoManager)、
[McuComm](http://github.com/s-ryuki/McuComm)、またはそれに準ずるコンポーネントのことをさします。  
　  
　  
#### MotionEditorの使い方####
　　[![画像2][image2]](http://cloud.github.com/downloads/s-ryuki/Pictures/MotionEditor＿GUI_Guide2.png)
[image2]:http://cloud.github.com/downloads/s-ryuki/Pictures/MotionEditor＿GUI_Guide2.png

　　　　　　File：　出力するファイルの名前を入力  
　　　　　　Time：　サーボを目的角度まで動かすのにかける時間[ms]  
　　　　　　Wait：　目的角度に動いたあとの待機時間[ms]  
　　　　　　Pose：　の番号(同じものが２つあると前にあるものが優先される)  


　作成したモーションファイルはMotionEditorフォルダ内に出力されます。  

　操作できるサーボモータの個数を増やす場合は、MotionEditorフォルダ内の  
　iniフォルダ内にあるMotionEditor.iniを編集することができます。  

　 [![画像3][image3]](http://cloud.github.com/downloads/s-ryuki/Pictures/MotionEditor_ini.png)
[image3]:http://cloud.github.com/downloads/s-ryuki/Pictures/MotionEditor_ini.png

  
