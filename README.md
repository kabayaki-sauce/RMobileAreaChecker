# 概要
※このアプリケーションは非公式アプリです。楽天モバイル株式会社様は一切関与しておりませんので、本アプリケーションに関するお問い合わせは直接以下にお願いします。

    Mail:tlsfukyowaon@gmail.com
    Twitter:@tomo_rice_841

このアプリケーションはAndroid端末で通知バーに現在接続中のエリアを常駐し表示するものです。

楽天モバイルを契約している人を対象として制作していますが、一応日本のエリアは他社回線含めすべて識別できる（はず）なので使ってみてください。

ただ、UNLIMIT契約みたいに複数キャリアを行き来するような契約形態って他にありましたっけ。。。需要があればどうぞ。

Android8(SOV35)での正常動作は確認していますが、Android9以上での動作は確認できておらず、またDualSIM対応端末での動作を前提としていません。これらはアップデートにより対応する予定ですが、現時点では動作する端末が限定的なことをご承知ください。

また、XiaomiやSamsungの端末ではバッテリ－セーバー（バッテリーの最適化）を無効にする必要があることを確認しています。1分程度で取得に失敗してしまう場合これが原因だと思うので確認お願いします。

# プライバシーポリシー
本アプリケーション（以下アプリ）では以下の権限を必要としています。

    android.permission.READ_PHONE_STATE
    android.permission.ACCESS_FINE_LOCATION
    android.permission.ACCESS_COARSE_LOCATION
    android.permission.ACCESS_BACKGROUND_LOCATION
    android.permission.FOREGROUND_SERVICE
    android.permission.VIBRATE
    android.permission.INTERNET
    
アプリをインストールし使用する者（以下使用者）は以下の権限が必要な処理に対し、権限を使用することを了承したものとします。


    android.permission.READ_PHONE_STATE
         電話の情報やSIM情報、現在接続中のエリアに纏わる情報を取得します。


    android.permission.ACCESS_FINE_LOCATION/ACCESS_COARSE_LOCATION/ACCESS_BACKGROUND_LOCATION
         接続中のエリアを取得する際に位置情報サービスが必要になる場合があり、その用途で使用します。

    android.permission.FOREGROUND_SERVICE
         通知バー（バックグラウンド処理）にアプリ常駐するために使用します。

    android.permission.VIBRATE
         通知にバイブレーションを必要としている場合に使用します。


    android.permission.INTERNET
         接続中のエリアを取得する際にインターネット接続権限が必要な場合があり、その用途で使用。また、広告表示にインターネット接続権限が必要になった場合に使用します。

これらアプリ・権限の了承や使用により不具合や損害等が発生した場合、その全責任は使用者が取るものとします。
