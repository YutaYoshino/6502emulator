# 6502emulator

　APPLE2のROMイメージを実行するための、簡易的なMOS6502エミュレータです。  
 コマンドラインで、APPLE2のシステムモニターやBASICが動作します。
 
 ## ■ ROMイメージファイル
 
   実行には、APPLE2のROMイメージファイルが別途必要です。  
　　[ ROMイメージファイル要件 ]
    Size    　　：12KB  
    Entry Point :$0xfffc  
    Language    :MOS6502 Machine Language  
 
 
 ## ■ 起動方法
 
   1. ROMイメージファイルを、実行ファイルと同じディレクトリに配置
   2. ROMイメージファイルのファイル名を、"ROM.bin"にリネーム
   3. 実行ファイルをスターと
 
 
 ## ■ APPLE2システムモニタ- 簡易操作方法
 
 　メモリアドレスを入力　： メモリ内容を表示  
   'b' を入力           : システムモニター　→ ROMイメージ内臓のBASICへ遷移  
   'F666G' を入力       : システムモニター  → ROMイメージ内臓のアセンブラへ遷移  
   'CALL -151' を入力   : システムモニターへ遷移  
   'r' を入力           : リセット  


 ## ■ Notice
 
   APPLE2のROMイメージファイルの実行が目的のため、以下の命令はテストしていません。
   Decimal Mode  
   割り込み関連  
