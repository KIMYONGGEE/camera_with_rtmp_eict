# RealTime Camera RTMP with IOS/ Android
**[OverView]**

RTMP 스트리밍 및 카메라 플러그인을 활용하여 IOS/Android 크로스 플랫폼 애플리케이션 구현 

<br/>
<br/>


## Getting Started  / 시작하기 위해서

```
1. RTMP 스트리밍 기능을 사용하기 위해 플러터 카메라 플러그인 라이브러리를 활용해야합니다. 
2. API가 기존 카메라 패카지와 동일하고 설치 요구 사항 또한 같습니다. 
3. 카메라 패키징에 추가로 rtmp url을 가져와서 특정 url로 스트리밍을 시작하는 startStreaming(url)인 추가 API가 필요합니다(Yaml 파일에 추가해둠)
4. 올바른 패키지 사용을 위해서 VScode로 작업하실 경우 pubspec.yaml 파일에서 ctrl + s를 눌러 최신화 해줍니다.

```

## API 특징

* Flutter 기반이기 때문에 IOS/ Android 둘다 사용 가능합니다. 
* 송출될 화면을 위젯을 통해 확인 가능합니다.
* 해당 디바이스 내부 CRUD REST api를 써서 캡쳐 화면이 저장됩니다. 
* api를 사용하여 녹화저장이 가능합니다.

