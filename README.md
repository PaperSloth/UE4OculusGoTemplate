# UE4OculusGoTemplate
OculusGo Teloport Example
(Oculus Questでも動作するようです)

## UE4Version
4.19.2

4.20.3

4.21.2

4.22.2(master, develop)
develop bracnchのみ下記のdemoのような動画再生機能をテストで入れています

# Demo
![MediaDemo](https://user-images.githubusercontent.com/8968076/58808596-4507ec00-8655-11e9-88bc-5903c0f1c5ff.gif)


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
