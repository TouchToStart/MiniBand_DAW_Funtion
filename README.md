# Mini Band

Tone.js와 Web Audio API를 활용하여 구현한 웹 DAW(Digital Audio Workstation)입니다.
<br/><br/>


## Usage

![main](./public/samples/images/readme01.png)
<br/><br/>

### 실행방법

터미널에 npm install 을 실행하여 필수 패키지를 다운합니다.
<br/><br/>
터미널에 npm run dev 을 실행하여 서버를 가동하고, http://localhost:5173/ 에 접속합니다
<br/><br/>

### 악기 선택 
악기 선택 tab에서 사용할 악기를 선택합니다.
<br/><br/>
아래의 키보드 매핑 안내 이미지에서 키 세팅을 확인하고 키보드를 눌러 연주합니다.
<br/><br/>
Piano는 ',' &nbsp;'.'을 눌러 옥타브를 Up & Down 가능합니다.
<br/><br/>

### 녹음 / 재생
'Start Recording' / 'Stop Recording' 버튼을 토글 or ' / '을 누르는 것으로 녹음이 가능합니다.
<br/><br/>
오디오 음원의 재생 버튼을 눌러 녹음된 음원을 재생 가능합니다.
<br/><br/>
음원의 볼륨 슬라이드를 조절하며 볼륨과 mute 설정이 가능합니다.
<br/><br/>

### 트랙 편집

'Add Track' 버튼을 눌러 트랙을 생성합니다.
<br/><br/>
'+' 버튼을 눌러 녹음된 음원을 트랙에 삽입합니다.
<br/><br/>
'Loop On' / 'Loop Off' 버튼을 토글시켜 트랙 안의 음원들을 loop 시킬 수 있습니다.
<br/><br/>
트랙 안의 음원들의 재생 버튼을 눌러 각각 재생할 수 있고, 트랙의 'Play Track' 버튼을 눌러 트랙 안의 모든 음원을 동시에 재생할 수 있습니다.
<br/><br/>
'Mix Down' 버튼을 누르면 트랙 안의 음원들이 하나의 음원으로 융합되어 Mix Down 버튼 옆에 생성됩니다. Mix Down된 음원의 ...을 클릭하여 .wav 확장자의 음원으로 다운 가능합니다.
<br/><br/>

## 추후 업데이트 목록

일렉, 베이스 등 추가 악기 지원
<br/>
메트로놈 기능
<br/>
플러그인 지원
<br/>
이펙터 기능
