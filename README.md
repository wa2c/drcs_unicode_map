# 概要

ARIB字幕のDRCS(外字)をUnicode文字に置換えるための変換テーブルです。

[Caption2Ass_PCR](https://github.com/maki-rxrz/Caption2Ass_PCR)でARIB字幕をASS/SRTファイルに変換する際に参照される UNICODE_cc_DRCS.ini ファイルで使用するために作成しました。他のファイルの定義内容に加えて、録画データから字幕ファイルを抽出した際に、変換に失敗した分を追加しました。

漢字などはそのままの文字が適用される場合もありますが、ビットマップ文字イメージは近い絵文字を割り当てらられます。

# 参照したファイル

* [Caption2Ass_PCR](https://github.com/maki-rxrz/Caption2Ass_PCR):  [UNICODE_cc_DRCS.ini](https://github.com/maki-rxrz/Caption2Ass_PCR/blob/master/bin/ini/Gaiji/UNICODE_cc_DRCS.ini)
* [TVCaptionMod2](https://github.com/xtne6f/TVCaptionMod2): [TVCaptionMod2_Gaiji_std.txt](https://github.com/xtne6f/TVCaptionMod2/blob/master/gaiji/TVCaptionMod2_Gaiji_std.txt)
* [arib2ass](https://github.com/Piro77/arib2ass): [drcs_conv.ini](https://github.com/Piro77/arib2ass/blob/master/drcs_conv.ini)
