# UE4OculusGoTemplate
OculusGo Teloport Example
(Oculus Questでも動作します)

## UE4Version
4.19.2

4.20.3

4.21.2

4.22.2(develop)

4.23.1

4.24.1

4.25.0(master)
※SDK/NDKの設定が大きく変わりました。詳細は下部のError UE4.25をご覧ください

develop branchのみ動画再生機能をテストで入れています

# Demo
![GoTemplate](https://user-images.githubusercontent.com/8968076/58804347-9d86bb80-864c-11e9-8023-c7d7e509cfc2.gif)

# Error
【UE4.21】
UE4.21.2では下記エラーが出ます。
Gitから落としてきたUE4.22からpackage.xmlをコピーしてください

「The specified Android SDK Build Tools version (26.0.1) is ignored, 
as it is below the minimum supported version (26.0.2) for Android Gradle Plugin 3.0.1.」
対応方法
http://pafuhana1213.hatenablog.com/entry/2019/02/06/010250

【UE4.22】
Accept SDK License押下時に
Unable to read xxx/Android/package.xml
と出た場合、4.21と同様にGitのUE4.22からpackage.xmlを取得してください

【UE4.25】
Android SDK および NDK の更新
UE4.25からは従来のAndroidWorksからAndroid StudioでのSDK/NDKの設定となりました。
詳しくは下記のドキュメントにありますが、設定が少し複雑です。
https://docs.unrealengine.com/ja/Platforms/Mobile/Android/Setup/AndroidStudio/index.html

