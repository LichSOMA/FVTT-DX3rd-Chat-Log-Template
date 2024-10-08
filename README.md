# FVTT-DX3rd_Chat-Log-Template
Template for saving chat logs from FVTT DX3rd system as readable html documents

# 유의사항
이 html 템플릿은 오라클 클라우드 서버에 호스팅된 경우를 상정하고 만들어졌습니다. 그렇지 않을 경우 html 문서를 웹브라우저로 열더라도 이미지 파일을 불러오는 장애가 발생할 수 있습니다.
element를 찾기 편하도록 PopOut! 모듈을 사용하는 걸 권장합니다.

# 사용방법
1. 다음 이미지의 '본인 FVTT 주소' 안에 호스팅된 주소를 입력해주세요. (예시: 'https://sample.co.kr/')
![image](https://github.com/user-attachments/assets/5fe2f416-59d3-43c0-9c4f-dc273cdb299a)

2. 사이드바의 채팅 탭을 우클릭해서 먼저 채팅창을 별도로 연 뒤, PopOut! 모듈의 기능으로 별도의 창으로 만듭니다.

3. F12를 열어 개발자 도구를 엽니다.

4. 개발자 도구의 Elements 탭에서 <div id="chat-popout">으로 시작하는 행을 엽니다.

5. 이어서 <section class="sidebar-tab sidebar-popout chat-sidebar directory flexcol"> 행을 엽니다.

6. 그러면 <ol id="chat-log">라는 행이 보일겁니다. 이 행을 우클릭하고 Copy → Copy element를 합니다.

7. 템플릿의 <body></body> 사이에 복사한 내용을 붙여넣고 저장합니다.
![image](https://github.com/user-attachments/assets/7279a8d6-ed97-4adf-aa44-62c6482bc15b)

8. 이제 이렇게 저장한 html 문서를 웹 브라우저로 여시면 짜잔!(모바일에서도 크기에 맞춰지니 전반적으로 보기 편하실 겁니다.)
![image](https://github.com/user-attachments/assets/4047d591-a944-4e9c-8852-12f6e4080590)

