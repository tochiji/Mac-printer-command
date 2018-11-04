# Mac-printer-command
Macでプリンターを使う際のコマンド一覧。下記で確認  
>ProductName:	Mac OS X  
>ProductVersion:	10.12.6  
>BuildVersion:	16G29  

## lpr [-P Printer Name] file
指定したプリンターでプリントする

## lpstat -s
プリンター一覧を出力する

>システムのデフォルトの送信先: XXXXX  
>XXXXXのデバイス: lpd://XXX.XXX.XXX.XXX/  
>YYYYYのデバイス: lpd://YYY.YYY.YYY.YYY/  
>ZZZZZのデバイス: lpd://ZZZ.ZZZ.ZZZ.ZZZ/  

## lpoptions [-p Printer Name] -l
あるプリンターの設定一覧を取得する

>FXOutputOptions/Output Options: None OffsetCatchTray FinisherTypeCH   >*FinisherTypeCH2and4Holes FinisherTypeCH2and3Holes FinisherTypeD2and4Holes   >FinisherTypeD3Holes  
>FXBookletTray/Right Bottom Tray (Booklet Maker): False *True  
>FXTriFoldOutputTray/C Fold / Z Fold Tray: *False True  
>FXMailboxTray/Mailbox Finisher: *False True  
>  ... 
>FXColorDensityBlackHigh/Shadows (K): +3 +2 +1 *0 -1 -2 -3  
