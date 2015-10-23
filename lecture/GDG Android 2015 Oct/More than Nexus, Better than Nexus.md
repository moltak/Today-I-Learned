#More than Nexus, Better than Nexus.
#### How to build
http://s.android.com/source/requirements.html

#### 내가 정리한거
1. 파일 시스템 내용을 쭉 살펴봐야함
2. 앱교체
3. android resource management tool? 로 api 안에있는 상수값들 확인 가능

#### aapt로 .apk 파일에 포함된 리소스를 분석할 수 있다
```
$ aapt d --values resources framework-res.apk

spec resource 0x01040029 android:string/default_sms_application: flags=0x00000000
resource 0x01040029 android:string/default_sms_application: t=0x03 d=0x00001e00 (s=0x0008 r=0x00) (string8) "com.android.mms"
```

####References
- http://s.android.com/
- [How to build Android Marshmallow on Nexus 4](http://goo.gl/mYZmCT)
- https://github.com/ganadist/device_lge_mako
- https://github.com/ganadist/device_lge_occam
- https://github.com/ganadist/gms_addon/tree/android-6.0.0_r1

####느낀점
어렵다... 뭔말인지 잘 모르겠으나 흥미가 느껴짐 특히. 쓰레기 같은 크레마샤인에도 만들 수 있지 않을까