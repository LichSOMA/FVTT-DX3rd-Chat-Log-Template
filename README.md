# FVTT-DX3rd_Chat-Log-Template
Template for saving chat logs from FVTT DX3rd system as readable html documents

# 유의사항
1. 이 로그 템플릿은 FVTT 11.315 버전, DX3rd System 1.6 버전, 그리고 MRKB UI 모듈을 사용한 환경에서의 로그를 저장하기 위해 만들어졌습니다. 다른 환경에서의 호환성은 장답할 수 없습니다.
2. 이 html 템플릿은 오라클 클라우드 서버에 호스팅된 경우를 상정하고 만들어졌습니다. 그렇지 않을 경우 html 문서를 웹브라우저로 열더라도 이미지 파일을 불러오는 장애가 발생할 수 있습니다.
3. chat log와 관련된 element를 찾기 편하도록 PopOut! 모듈을 사용하는 걸 권장합니다.

# 사용방법
[ 방법 1 ]

1. 다음 이미지의 '본인 FVTT 주소' 안에 호스팅된 주소를 입력해주세요. (예시: 'https://sample.co.kr/', 이때 마지막에 절대 /를 빠트리지 말아주세요.)

![image](https://github.com/user-attachments/assets/163967a1-37f9-4aa4-aef8-2387f73ad324)

2. 사이드바의 채팅 탭을 우클릭해서 먼저 채팅창을 별도로 연 뒤, PopOut! 모듈의 기능으로 별도의 창으로 만듭니다.

3. F12를 열어 개발자 도구를 엽니다.

4. 개발자 도구의 Elements 탭에서 div id="chat-popout"으로 시작하는 행을 엽니다.

5. 이어서 section class="sidebar-tab sidebar-popout chat-sidebar directory flexcol" 행을 엽니다.

6. 그러면 ol id="chat-log"라는 행이 보일겁니다. 이 행을 우클릭하고 Copy → Copy element를 합니다.

7. 템플릿의 body 안에 복사한 내용을 붙여넣고 저장합니다.
 
![image](https://github.com/user-attachments/assets/ce87434e-496b-4ffb-ab91-ccab841022c7)

8. 이제 이렇게 저장한 html 문서를 웹 브라우저로 여시면 짜잔!(모바일에서도 크기에 맞춰지니 전반적으로 보기 편하실 겁니다.)
 
![image](https://github.com/user-attachments/assets/f195c29a-187f-466b-8876-e55c670c8d98)

[ 방법 2 ]

1. MRKB UI의 로그 저장 버튼을 누른다.

![image](https://github.com/user-attachments/assets/73d36d7e-0e25-4b4e-899f-bf3fb4cfc2f4)

2. 저장된 로그의 내용을 템플릿의 body 안에 복사한 내용을 붙여넣고 저장합니다.
 
![image](https://github.com/user-attachments/assets/ce87434e-496b-4ffb-ab91-ccab841022c7)

3. 이제 이렇게 저장한 html 문서를 웹 브라우저로 여시면 짜잔!(모바일에서도 크기에 맞춰지니 전반적으로 보기 편하실 겁니다.)
 
![image](https://github.com/user-attachments/assets/f195c29a-187f-466b-8876-e55c670c8d98)
