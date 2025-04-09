# web_yolo
이 프로그램은 yolov5.pt 원형 모델을 이용하여 object Detect를 하는 파이썬 프로그램을 하였고 파이썬 코드를 index.html로 바꾸어 달라고 copilot을 이용하여 진행하였다.


파이썬으로 사물인식 앱 만들기
1 폴더 만들기 - code로 열기 - 터미널 열고
2 가상환경 만들기
3 가상환경과 프로젝트 연결하기
4 코파일럿과 작업
copilot-edit에 입력하는 프롬프트는 다음과 같다
"
파이썬과 opencv로  yolov5 모델을 이용해서 웹카메라로 사물인식하는 간단한 코드를 작성해줘
"
코드 공유 함.
![image](https://github.com/user-attachments/assets/406870f3-770f-4e5d-ab6c-69b480bfb64a)

(yolov5s.pt를 자동 다운로드 함)
 파일

webcam_yolo_gui.py

youtube에서 동영상을 다운로드 받을려면
pip install yt-dlp 가 있어야 하고

yt-dlp -f mp4 -o "youtube_video.mp4" https://youtu.be/JfCE2MRFEGA?si=eMNIAFRhDFgH2nbG

SAN FRANCISCO - Rainy Day Street Walk in Downtown San Francisco, California, USA, Travel, 4K UHD
SAN FRANCISCO - Rainy Day Street Walk in Downtown San Francisco, California, USA, Travel, 4K UHDSAN FRANCISCO - 비오는 날, 도시풍경, 다운타운 샌프란시스코, 캘리포니아, 미국, 여행, 거리풍경...
www.youtube.com
이 명령으로 해당 주소의 동영상을 다운로드 받을수 있음 .
음소거 해제

00:00:01
01:00:00



프롬프트는 이렇게 작성했어.
"
원래 코드를 내가 다운로드 받아 놓은 youtube_video.mp4를 플레이 하면서 디택션 하는 코드를 작성해서 youtube_detext.py에 저장하고 플레이가 종료 되면 반복 되도록 만들어줘
"

결과물은 이렇게
![image](https://github.com/user-attachments/assets/50445f0e-8666-447a-b514-9a6091a4dc4d)


오늘 수업 마지막으로
프롬프트를 이렇게 해서
자 이번엔 웹카메라와 파이썬 코드로 되어 있는 것을 웹에서 구동 할 수 있게 index.html로 만들어줘
결과를 한번 보자
![image](https://github.com/user-attachments/assets/052191f7-3edc-4149-836c-f257fadc180f)
