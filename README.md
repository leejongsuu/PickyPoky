🌐 PickyPoky : HyperCLOVA X 기반 일기 분석 AI 서비스
---

### 🍀 팀원 소개
![image](https://github.com/user-attachments/assets/37b09a51-2632-4913-9681-d9cd2f31cb89)

</br>

### 🍀 활동
**시작일** 
*2024.07.20*   
<br>
**1차 완성** 
*2024.08.02*
</br>

</br>

---
### 🍀 개요
**📍PickyPoky는 당신의 감정과 하루를 귀여움으로 채워주는 특별한 일기 어플리케이션입니다.📍** 
</br>
</br>
오늘 하루 어떤 기분이었나요? PickyPoky에선 감정을 **포근한 이모지**로 남겨, 매일매일이 작은 행복으로 채워집니다. 일기를 작성하면서 **감정 이모지**와 **키워드**를 선택하면, 하루의 기억을 더 쉽게 돌아볼 수 있어요. 귀여운 이모지로 가득한 일기장을 열어보세요. 당신의 일상에 알록달록한 감정들이 모여 **나만의 작은 이야기**가 완성됩니다!

![1](https://github.com/user-attachments/assets/d169d460-4a21-4ae7-aabe-7eb7c836e935)
![3-차별점](https://github.com/user-attachments/assets/28e230cd-0a97-4bdf-8498-dfdc8c2f63ab)
![7-기술개요](https://github.com/user-attachments/assets/5b3c4cce-0e97-4356-9c01-d3cca16608e1)

</br>

***※ 보안상의 이유로 코드는 공개되지 않습니다.***

***‼️ 20240820 ~ 비활성화***

</br>

---

### 🍀 PickyPoky IA
![스크린샷 2024-08-21 164213](https://github.com/user-attachments/assets/feca8b18-6c67-4bcc-a154-64aad9553ed8)

</br>

### 🍀 주요 기능
![4-주요기능](https://github.com/user-attachments/assets/ddd86025-5ad7-48d0-bf7d-090396ffbee8)

</br>

---

### 📍 결과물

**시연 영상** <br>
[1차 출시] ![pickypoky](https://github.com/user-attachments/assets/ff9477aa-2314-49f8-9834-1a3baf372822)

</br>

---
### ✨ 향후 추가 기능

1. **일기 작성이 더 즐거워질 거예요!**  
   일기 쓸 때 **이미지**나 **동영상**도 업로드할 수 있다면 어떨까요? 단순한 텍스트가 아닌, 생동감 넘치는 일기로 매일매일이 더 특별해집니다. 오늘 찍은 사진이나 재미있는 동영상도 일기 속에 쏙쏙! 감정을 더 풍부하게 표현할 수 있어요.

</br>

2. **AI가 당신의 감정을 더 잘 이해하도록**  
   우리 PickyPoky는 이미 사용자가 선택한 키워드와 감정뿐만 아니라, AI가 추천해준 감정과 키워드도 꼼꼼히 기록하고 있어요. 앞으로는 **하이퍼클로바 커스텀 프롬프트 엔지니어링**을 통해, AI가 더 정확하게 당신의 감정을 캐치할 수 있도록 업그레이드될 예정입니다. AI와 함께하는 감정 탐험, 기대되지 않나요?

</br>

3. **감정 표현의 무한 확장!**  
   지금은 감정 이모지가 긍정, 부정, 중립 세 가지뿐이지만, 앞으로는 **다양한 감정**이 추가될 거예요! 행복, 슬픔, 설렘, 사랑 등등, 당신의 감정을 더욱 세밀하게 표현할 수 있도록 귀여운 이모지들이 새롭게 등장합니다. 어떤 이모지가 추가될지 기대해 주세요!

</br>

---

### 🍀 아키텍쳐 
![image](https://github.com/user-attachments/assets/58ec1b7b-7d89-4bbd-ba45-31ac86476e6d)

</br>

### 🍀 사용 기술스택
- SpringBoot
- JPA
- Spring Security + Jwt + OAuth 2.0
- MySQL
- NCP
    - Server(VPC)
    - Cloud DB for MySQL(VPC)
    - AI·NAVER API
    - Global DNS
    - CLOVA Studio
    - Cloud Log Analytics
- Docker
- Nginx

</br>

---

### 📚 학습 성과

이번 프로젝트에서 저는 **Naver Cloud Platform(NCP)** 을 활용한 인프라 구축과 AI 연동 작업을 주도적으로 담당했습니다. 이전에는 주로 AWS를 통해 인프라를 구축해왔지만, 이번 프로젝트를 통해 처음으로 NCP를 활용하게 되었습니다. API 서버부터 Cloud DB, Global DNS, Cloud Log Analytics까지, NCP가 제공하는 한국 시장에 최적화된 서비스와 사용자 친화적인 UI/UX를 경험하며 인프라 구축과 관리가 얼마나 효율적일 수 있는지 깨달았습니다. 이 과정에서 NCP의 장점뿐만 아니라, 새로운 클라우드 환경에 신속하게 적응하는 방법을 배우는 소중한 기회를 얻었습니다.

인프라 구축이 완료된 후, 저는 **하이퍼클로바 AI**와의 연동 작업을 진행했습니다. AI 모델의 응답 시간을 단축하고, AI가 제공하는 데이터를 효과적으로 처리하기 위한 알고리즘을 직접 설계하고 구현하며, AI가 제공하는 데이터를 정교하게 다루는 데 집중했습니다. 이러한 과정을 통해 AI 응답 처리에 대한 깊은 이해를 얻었고, 이 데이터를 기반으로 유용한 인사이트를 도출하는 데 성공했습니다.

또한, **OAuth**를 이용한 사용자 인증 처리와 **일기 작성 및 관리 기능** 등의 백엔드 개발 작업도 주도했습니다. PickyPoky에서는 단순한 일기 작성 기능을 넘어서, AI가 추천하는 키워드와 감정을 기반으로 데이터를 축적하고 이를 활용한 **커스텀 프롬프트 엔지니어**링 전략을 세우는 것을 목표로 삼았습니다. 이러한 데이터는 장기적으로 AI 모델의 학습에 중요한 역할을 하며, 사용자 맞춤형 경험을 제공하는 데 핵심적인 자산이 됩니다. 이 과정에서 데이터 수집과 활용 방법에 대한 심도 있는 이해를 갖추게 되었고, 장기적인 데이터 전략의 중요성을 깊이 깨달았습니다.
