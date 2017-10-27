## 제목 : Azure App Service 실습   
	(개발을 할 줄 몰라도 그런대로 따라할 수 있는) 

### **주최** : [ASP.NET Korea User Group](https://www.facebook.com/groups/AspxKorea/)
### **대상** : 초, 중급 개발자(개발언어 무관)
> Azure App Service를 약간이라도 사용해본 사람은 이번 실습으로 내공이 +100 되는데 제 파란이빨 마우스를 겁니다.

#### **강사** : 한국 마이크로소프트 김태영 부장 (feat. Taeyo)

#### 실습시간(예상) : 5~7시간 

## HOL(Hands-on Lab) 진행 순서

### 기술 세션 : Azure App Service 살펴보기 (+ 잘들 모르는 Tips 방출)

- 실습 1 : App Service 생성 및 개발 실습
    - Git을 사용하여 다양한 코드 배포(HTML, ASPX, JSP 3단 변신)
	- 런타임 플랫폼 변경 및 실행
	- 실행 관련 이슈 트러블슈팅
    - Continous Deployment를 통한 자동 배포

- 실습 2 : Java WebApp(WAR) 배포 및 운영 실습
	- 이미 만들어져 있는 WAR 파일을 App Service에 배포
	- 온라인 에디터로 실시간 소스 수정
	- SCM(Kudu)을 통해서 Web App의 내부 콘솔 살펴보기
	- WebApp의 Authentication 기능을 이용한 보안 설정
		- https://docs.microsoft.com/ko-kr/azure/app-service-mobile/app-service-mobile-how-to-configure-microsoft-authentication
### 기습 미니 세션 : Basic web application 아키텍처 검토 및 고려해야 할 사항.

- 실습 3 : 간단한 ASP.NET Web App 구축 및 배포 (Visual Studio 사용)
	- https://docs.microsoft.com/en-us/azure/app-service-web/app-service-web-get-started-dotnet
- 실습 4 : WebApp + DB로 구성된 WebApp 구축 및 배포 (Visual Studio 사용)  
	- 소스에서는 Entity Framework를 사용하고 있으나 굳이 이해하지 않아도 실습에는 지장없음
	- 실습 URL : https://docs.microsoft.com/en-us/azure/app-service-web/app-service-web-tutorial-dotnet-sqldatabase
	- 시간이 부족할 경우, 이 실습은 자습으로 넘길 가능성이 있음.

- 실습 5 : 배포 슬롯(Slot) 적용 방법 실습

- 실습 6 : Azure API App 및 Swagger 실습 (3-Layer Arch.)
	- 실습 URL : https://docs.microsoft.com/en-us/azure/app-service-api/app-service-api-dotnet-get-started
	- 시간이 부족할 경우, 이 실습은 자습으로 넘길 가능성이 있음.

### 모든 참가자는 다음의 사항들을 반드시 본인의 노트북에 설치하고 오셔야 합니다.

### 참가자 준비물 (필수)
> 1. 노트북  
> 2. Azure 계정(무료 계정이든, MSDN 계정이든, 회사 계정이든)  
> 3. 테더링 가능한 스마트폰(네트워크 사정이 안 좋을 경우 테더링을 강추합니다)  

> **준비물 미 준비 시에는 실습을 제대로 따라하실 수 없으며, 그 부분은 본인의 책임입니다**

### 강좌 참여 시 사전 준비 및 설치 사항(필수)
> - Visual Studio 2017 설치 (Community 버전 무관)  
>   (빨간 박스로 표시한 Azure 개발, ASP.NET 개발은 필수이며, 그 밖에 필요한 것 설치)
>   ![이미지](./images/install.png)
> 
> - Visual Studio Code 설치 : https://code.visualstudio.com/  
> - Git 설치 : https://git-scm.com/  
> - Github.com 계정 생성  
> - Github Desktop 설치 : https://desktop.github.com/  
> - ...
