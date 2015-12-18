a simple CalendarView component for Android

![http://img.f.hatena.ne.jp/images/fotolife/K/Kazzz/20101108/20101108175639.png](http://img.f.hatena.ne.jp/images/fotolife/K/Kazzz/20101108/20101108175639.png)

CalendarViewはAndroid 1.6以降で動作するシンプルなカレンダービューです。

日本の祭日判定にK.Tsunoda氏の"kt祝日名取得"を阿蛭 栄一氏がJavaにポーティングした"KtHoliday.java"をほぼそのまま使用しており、ビュー上で祭日を判定/表示することができます。

年月を変更する方法として以下をサポートしています

**「<<」又は「>>」のタップにより、それぞれ前月、次月に遷移します**

**「年月」表示部のタップにより、ダイアログで入力した年月に遷移します**

**左右又は上下のフリックモーションを検出して前月、次月に遷移します**


なお、拡張不可能なandroid SDKのNumberPickerを再作成しています。その際に内部リソースをリフレクションにより参照しているため、今後のSDKのバージョンで問題が発生する可能性があります。


関連リンク

K.Tsunoda(AddinBox)
http://www.h3.dion.ne.jp/~sakatsu/holiday_logic.htm


Javaによる祝日判定ロジック実装の試み
http://www.abiru.jp/obsolutes/souko/KtHoliday_Java/KtHolidayJava_source.html


カスタムNumberPickerの作成 - にゃんだふる日記
http://d.hatena.ne.jp/rmiya/20100917/1284702384