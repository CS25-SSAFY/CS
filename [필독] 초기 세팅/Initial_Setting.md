# 초기 세팅 방법 [필독!!@@]
### 앞으로 스터디 파일을 제출하는 방법입니다. 밑의 과정을 따라해주세요!!
1. 밑의 사진에 보이는 Branches를 클릭합니다.  
![!\[Alt text\](image-1.png)](Initial_Setting1.png)
2. New branch를 클릭합니다.  
![!\[Alt text\](image-2.png)](Initial_Setting2.png)
3. 브랜치 명으로 자신의 깃허브 닉네임을 입력하고, Create new branch를 클릭해주세요. 저의 닉네임은 JiEung2이기 때문에 그렇게 설정해주었습니다.  
![!\[Alt text\](image-3.png)](Initial_Setting3.png)
4. 그 이후, 자신이 사용할 폴더에 클론을 받아줍니다.
5. 자신이 클론 받은 위치에서 브랜치를 바꿔줍니다. 단, 브랜치를 바꿀 때는 본인이 위에서 만들었던 브랜치명을 사용합니다.   
    `브랜치 변경 명령`
    ```shell
    git checkout <브랜치명>
    ```
    `주의` git 옆의 괄호 안이 본인의 브랜치 명으로 바뀌었는지 확인해주세요.  
    ![!\[Alt text\](<스크린샷 2024-01-28 오후 11.21.11.png>)](Initial_Setting4.png)
6. 만들어져있는 폴더 안에 자신의 정리파일을 넣어줍니다.  
    `주의` 되도록이면 파일 이름을 영어로 해주세요. 특히나 맥은 한글로 작성 시 제목이 깨지기 때문에 주의해주세용~~
7. 그 후, add를 하고 commit, push까지 날려줍니다.  

    `주의` 커밋 메시지는 본인의 이름과 추가한 파일의 이름으로 작성합니다.
    밑의 사진은 예시이기 때문에 커밋 메시지를 테스트입니다. 라고 했습니다.
    ```
    git commit -m "[지응] - Network Equipment"
    ```
    `주의` push를 할 땐, master나 main이 아닌 본인의 브랜치명으로 해주세요.
    ```
    git push origin JiEung2
    ```  
    ![!\[Alt text\](<스크린샷 2024-01-28 오후 11.35.18.png>)](Initial_Setting5.png)
8. 이제 저희 깃허브를 들어가보면 Compare & pull request라는 것이 뜰겁니다!! 이걸 클릭해주세요.  
![!\[Alt text\](image-5.png)](Initial_Setting6.png)
9. 그 이후 제목을 다음과 같이 작성해줍니다.
    `[본인의 이름] - n주차 제출`  
    ![!\[Alt text\](image-6.png)](Initial_Setting7.png)
10. 마지막으로 Create pull request를 눌러주면 끝입니다!!

### 메뉴바의 Pull requests를 눌렀을 때, 본인이 날린 pr이 보이면 성공입니다.  
![!\[Alt text\](image-7.png)](Initial_Setting8.png)
### 한 번 설정해두면 5번까지는 다시 안해도 됩니다. 하지만 add, commit, push를 할 때 현재 브랜치가 본인의 아이디인지 한 번 더 확인하고 진행해주세용~~  
### 고생하셨습니다!! 앞으로 빠이팅 해봅시다!!