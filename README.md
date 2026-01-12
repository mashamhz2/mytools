# mytools
自作業用ツール群<br>
My tools for own work<br>

## これらツール群を参照される方々へ/To people who will be refering these tools
これらツール群は**無保証**であり、保守する予定はありません。そのため、**これらを参照し使用する場合は自己責任**でお願いいたします。**作者は参照し使用された方々に何が起こっても責任を負いません。**<br>
**I AM PLANNING NOTHING TO ASSURE THIS PRODUCTS. THESE ARE NOT GUARANTEED AT ALL. So you must take your own risk.**<br>

## LC(Logic Comparator)
EXORを使ったロジックコンパレータです。自作なので動作は多分怪しいでしょう。アーケード基板の故障解析で、まぁまぁ使えたのでマイツールに登録。<br>
### About caps from C6 to C24
It's not necessary to install these caps at this time.<br>

## SyncSeparator
EL1883を使った複合同期から水平・垂直同期を分離するボードです。ダライアス外伝も問題なく分離できていて目的達成したのでマイツールに登録。<br>
This is the board which separates from composite sync to horizontal and vertical sync, using EL1883. And it's implementing the selector between original c-sync and EL1883 out. Also I tested DARIUS GAIDEN and it's no problem now.<br>

## Hi-Lo Converter
SANSUI ST-71を使った、よくあるハイローコンバータです。オーテク製の安価なハイローコンバータを使用していましたが、アーケード基板のスピーカー出力で音割れが発生したので、新たに買うのもアレですし、諸兄方のこれまでの実績を見つつ作ってみたものです。音割れは解消し目的達成したので、マイツールに登録。<br>

## 1Mbit Mask ROM adaptor
1MbitマスクROM（MB831000等）をJEDECピンアサインのEPROM（MBM27C1001等）で読み出すすることが出来るアダプタです。TL866II-plusで読み出しの動作確認が行えたので、マイツールに登録。<br>
### NOTICE
TL866II-plusにある"CHECK ID"機能は使わない方が良いという意見が有ります。どうも、IDを識別するためにマスクROMでは想定していない電圧がかかるとか。そういう情報を見たため、当該機能のチェックボックスをアンチェックしておくと無難です。<br>

## 1Mbit EPROM adaptor(for Mask ROM assigned)
1MbitマスクROMピンアサインのEPROM（TC571001、MBM27C1000等）をJEDECピンアサインのEPROM（TC571000、MBM27C1001等）に変換するアダプタです。TL866II-plusで読み出し・書き込みの動作確認が行えたので、マイツールに登録。<br>
