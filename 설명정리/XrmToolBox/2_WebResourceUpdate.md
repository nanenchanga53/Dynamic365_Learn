# XrmToolBox를 이용한 웹리소스 업로드 방법
## WebResource란?
> 원하는 작업만 있는 스크립트가 포함된 HTML등을 저장해 놓았다 D365솔루션 내에서 사용하기 위한 리소스 모음이라고 보면 된다.(특별한 UI가 필요하면 PowerApps 등으로 만든 APP을 사용하자)
## WebResource 기본 업로드방법
> 기본적인 생성방법은 PowerApps에서 환경은 Dynamic365환경에 들어가 웹 리소스를 하나씩 추가하면 된다. 하지만 하나씩 올리면 귀찮아지고 업데이트도 번거롭다.
![image](https://user-images.githubusercontent.com/39551265/149244538-7478f327-47ae-4d01-aff6-bddfc647c243.png)
![image](https://user-images.githubusercontent.com/39551265/149246037-8f3d240f-5b8c-4314-9e74-0f6d5bba5b3f.png)
## XrmToolBox에서 WebResources Manager 설치
1. 프로그램을 실행하면 Tool Library 창이 나올 것이다.
2. 나온 화면에서 상단에 WebResources Manger를 검색
3. 검색하여 나온 WebResources Manager를 체크표시하고 Install를 클릭하면 설치가 된다. <br>
![image](https://user-images.githubusercontent.com/39551265/149246783-64c6f59c-8ebf-46e8-828a-11795fbcd0fc.png)

## WebResources Manger를 사용하여 업로드
1. 상단 메뉴 중 Tools를 클릭
2. 나오는 목록 중 WebResources Manager를 클릭
3. 좌상단의 메뉴중 File -> Load Web Resources<br>
![image](https://user-images.githubusercontent.com/39551265/149247415-4b10e37c-ad98-4aad-8a8b-e6478593549b.png)

4. Folder and Options 에서 업로드할 WebResource가 있는 폴더를 선택
5. 좌측 웹 리소스 탐색기에서 업로드할 파일을 선택
6. Properties에서 Diplay Name을 변경한다<br>
![image](https://user-images.githubusercontent.com/39551265/149247739-100bee37-d56d-4ca3-b010-09024a4a49ad.png)<br>
7. Pending Updates 에서 **Update and Publishand Add to solution**을 선택
8. Apply 를 클릭한다
9. 나오는 솔루션 중 업로드를 원하는 솔루션을 선택 후 OK를 누루면 업로드가 완료된다.
10. 업로드 완료시 Power Apps 솔루션에서 확인하면 아래 이미지와 비슷할 것이다.<br>
![image](https://user-images.githubusercontent.com/39551265/149248361-6fd0ec8f-82a4-407a-bc19-0a498af28dcd.png)
<br>