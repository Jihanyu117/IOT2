# IOT2
Iot 기말 과제
 

# 주제 선정 이유

처음 IOT 기술과 스포츠 융합 가능성에 주목하여 ball게임을 주제로 선정했으나 IOT애 대한 기술적 관점에 대해 다룰 수 있는 범위가 지나치게 좁아지고 IOT자체가 다양한 산업과 활동에 폭넓게 활용될 수 있는 기술이다보니 스포츠 이외에 더욱 적용 가능한 기술이 많다 생각이 들기도하였습니다. 
초기 주제였던 농구 게임 중심의 접근은 IoT 기술의 잠재력을 충분히 보여주기에 적합하지 않아 주제를 바꾸어 IoT 기술의 전반적인 활용 사럐와 혁신 가능성에 초점을 맞추어 다양한 관점에서 IoT가 가능하도록 선정하였습니다.



# 앱설명

긴급상황에서 자동 제세동기(AED)를 신속하게 찾고, 사용자를 도울 수 있도록 설계되었습니다.

사용자의 현재 위치를 기반으로 근처에 설치된 AED의 위치를 실시간으로 표시가 가능합니다.
사용자는 자신의 현위치를 문자 메시지로 공유할 수 있어, 주변 사람이나 응급 구조대가 정확한 위치를 파악할 수 있도록 지원합니다.
AED를 처음 사용하는 사람들을 위해 간단한 메뉼얼과 위급한 상황에서도 빠르게 작동법을 익힐 수 있도록 직관적이고 이해하기 쉬운 디자인을 추가하였습니다.
응급 상황에서 지정된 연락처로 빠르게 공유 할수 있는 기능을 포합 시켰습니다.

 

# 디자이너

![사진](https://github.com/Jihanyu117/IOT2/blob/main/AED%20%EB%94%94%EC%9E%90%EC%9D%B4%EB%84%88.jpg)

![문자결과](https://github.com/Jihanyu117/IOT2/blob/main/AED%20%EC%BB%B4%ED%8F%AC%EB%84%8C%ED%8A%B8.png)

![문자결과](https://github.com/Jihanyu117/IOT2/blob/main/AED%20%EC%BB%B4%ED%8F%AC%EB%84%8C%ED%8A%B8.png)

# 블록 

![문자결과](https://github.com/Jihanyu117/IOT2/blob/main/AED-1.png)

버튼: '문자 보내기' 버튼을 클릭했을 때 실행됩니다.
동작:
긴급 문자: 미리 지정된 긴급 연락처에 "신변의 위험!!" 이라는 문자 메시지를 전송합니다.
일반 문자: 미리 지정된 전화번호에 사용자가 작성한 메시지를 전송합니다.
목적: 위급 상황 발생 시 신속하게 도움을 요청할 수 있도록 합니다.

버튼: 'AED 찾기' 버튼을 클릭했을 때 실행됩니다.
동작:액티비티 스타터: 사용자의 현재 위치를 기반으로 가장 가까운 AED(자동 심장 충격기) 위치를 검색하는 웹 페이지를 엽니다.
웹 페이지: https://www.e-gen.or.kr/egen/search_aed.do 
라는 주소의 웹 페이지를 열어 AED 위치를 검색합니다.
목적: 심정지 환자가 발생했을 때 가장 가까운 AED를 빠르게 찾을 수 있도록 합니다

버튼: '현위치' 버튼을 클릭했을 때 실행됩니다.
동작:웹뷰어: 두 번째 블록과 동일하게 https://www.e-gen.or.kr/egen/search_aed.do 
라는 주소의 웹 페이지를 엽니다.
목적: 두 번째 블록과 동일한 목적을 가지며, 다른 방식으로 웹 페이지를 여는 것을 보여줍니다.

# 블록

![문자결과](https://github.com/Jihanyu117/IOT2/blob/main/AED-2.jpg)

버튼: '위치기반정보획득' 버튼을 누르면 실행됩니다.
동작:
위치 정보 가져오기: 기기의 GPS 또는 네트워크 정보를 이용하여 현재 위치(위도, 경도)를 가져옵니다.
주소 변환: 가져온 위도, 경도 정보를 이용하여 해당 위치의 주소를 변환합니다.
목적: 사용자의 현재 위치를 파악하여 다음 단계에서 사용하기 위한 준비 작업입니다.

버튼: '주소확인' 버튼을 누르면 실행됩니다.
동작:
메시지 출력: 첫 번째 블록에서 얻은 주소 정보를 화면에 출력합니다.
네이버 지도 연결: 네이버 지도 검색 URL을 생성하여 해당 주소를 검색하고 지도를 표시합니다.
URL 생성: 네이버 지도 검색 API를 이용하여 위도, 경도 정보를 포함한 검색 URL을 만듭니다.
목적: 사용자에게 현재 위치의 주소를 알려주고, 해당 위치를 네이버 지도에서 확인할 수 있도록 합니다.


# 실행결과

![문자결과](https://github.com/Jihanyu117/IOT2/blob/main/AED%20%EC%8B%A4%ED%96%89-1.jpg)


![문자결과](https://github.com/Jihanyu117/IOT2/blob/main/AED%20%EC%8B%A4%ED%96%89-2.jpg)


![문자결과](https://github.com/Jihanyu117/IOT2/blob/main/AED%20%EB%AC%B8%EC%9E%90%20%EA%B2%B0%EA%B3%BC%EA%B0%92.jpg)


![문자결과](https://github.com/Jihanyu117/IOT2/blob/main/AED%20%EA%B3%B5%EC%9C%A0%20%EA%B2%B0%EA%B3%BC%EA%B0%92.jpg)



----------------------------------------------------------------------------------------------


# 앱설명


"날씨 검색기" 앱은 사용자가 원하는 지역의 날씨 정보를 간편하게 확인할 수 있도록 도와주는 앱입니다.

주요 기능: 지역 검색: 원하는 지역의 이름이나 지역 코드를 입력하여 날씨 정보를 검색할 수 있습니다.
날씨 정보 제공: 검색한 지역의 현재 기온, 체감 온도, 강수 확률, 
풍속, 풍향, 습도 등 
다양한 날씨 정보를 한눈에 확인할 수 있습니다.


# 디자이너


![문자결과](https://github.com/Jihanyu117/IOT2/blob/main/weather%20%EB%94%94%EC%9E%90%EC%9D%B4%EB%84%88.png)


컴포넌트
![문자결과](https://github.com/Jihanyu117/IOT2/blob/main/weather%20%EC%BB%B4%ED%8F%AC%EB%84%8C%ED%8A%B8-1.jpg)


![문자결과](https://github.com/Jihanyu117/IOT2/blob/main/weather%20%EC%BB%B4%ED%8F%AC%EB%84%8C%ED%8A%B8-2.jpg)


![문자결과](https://github.com/Jihanyu117/IOT2/blob/main/weather%20%EC%BB%B4%ED%8F%AC%EB%84%8C%ED%8A%B8-3.jpg)


# 블록


![문자결과](https://github.com/Jihanyu117/IOT2/blob/main/weather%EB%B8%94%EB%9F%AD-1.png)


![문자결과](https://github.com/Jihanyu117/IOT2/blob/main/weather%EB%B8%94%EB%9F%AD-2.png)


![문자결과](https://github.com/Jihanyu117/IOT2/blob/main/weather%EB%B8%94%EB%9F%AD-3.png)


![문자결과](https://github.com/Jihanyu117/IOT2/blob/main/weather%EB%B8%94%EB%9F%AD-4.png)


![문자결과](https://github.com/Jihanyu117/IOT2/blob/main/weather%EB%B8%94%EB%9F%AD-5.png)


![문자결과](https://github.com/Jihanyu117/IOT2/blob/main/weather%EB%B8%94%EB%9F%AD-6.png)


# 실행 결과


![문자결과](https://github.com/Jihanyu117/IOT2/blob/main/weather%20%EA%B2%B0%EA%B3%BC%EA%B0%92-1.jpg)


![문자결과](https://github.com/Jihanyu117/IOT2/blob/main/weather%20%EA%B2%B0%EA%B3%BC%EA%B0%92-2.jpg)


![문자결과](https://github.com/Jihanyu117/IOT2/blob/main/weather%20%EA%B2%B0%EA%B3%BC%EA%B0%92-3.jpg)


![문자결과](https://github.com/Jihanyu117/IOT2/blob/main/weather%20%EA%B2%B0%EA%B3%BC%EA%B0%92-4.jpg)





