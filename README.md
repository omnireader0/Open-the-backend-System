# Open-the-Backend-System
"뒷단은 A상황에서 왜, 어떻게 대응할까?" 백엔드를 해부해보면서 궁금증을 해결하는 프로젝트 

### 🧾 프로젝트 소개

👉`2가지 작은 애플리케이션을 만들었습니다.`

1. **CPU-bound-application** : hash 연산을 하는 애플리케이션을 만들어서 무중단 자동화 배포 시스템을 구성해보았습니다.
2. **I/O-bound-application** : 게시판을 구현하여 빠른 키워드 검색이 가능한 시스템을 구성해보았습니다.

👉`그 과정에서, 다음을 진행했습니다.`

- 애플리케이션 성능 테스트(TPS)
- NGINX로 서버 분산하여 많은 트래픽 처리하기
- GIT, Jenkins 이용한 배포 자동화
- NGINX, rabbitMQ와 빠른 검색 가능한 대규모 트래픽 처리 시스템 구성

### 🧾 프로젝트 목표

실무라고 가정하고 `혼자 질문을 던져보고 답을  찾아가면서`(뇌피셜이므로 정확하지 않을 수 있어요.)

 `자문자답`으로 백엔드를 더 이해하고자 했습니다.

### 🧾 Document

- [프로젝트 이슈 관리](https://github.com/redcarrot01/Open-the-Backend-System/projects/1)
- [깃헙 위키 관리](https://github.com/redcarrot01/Open-the-Backend-System/wiki)
- [Postman API 명세서](https://documenter.getpostman.com/view/13653541/UUy1g7Y3)


### 🔖 최종 구성한 아키텍처

![image](https://user-images.githubusercontent.com/38436013/133194849-21e1e9f7-9c0f-441a-bedf-e48cb70dee81.png)



### 🔱 [개발 위키 전체 보기](https://lean-owner-437.notion.site/Open-the-backend-System-2c11332ea53243f69282b0a647b00ee5)

#### ✨ [BE 개발 과정](https://lean-owner-437.notion.site/786dbdf7f2664c59be1186d25eeaabee?v=ca1cbd8a69cc40f1873b15f75295b5c0)
개발 과정을 순서대로 포스팅했습니다.

#### ❓ [Question](https://lean-owner-437.notion.site/04ef5d833cb647c48910bbe2b2fd8d73?v=380c8663d6004972b106029b568097b2)

자문자답 : 개발에서 생긴 **궁금증**을 정리하고 **답을 찾아나가고** 있습니다.  

#### ✅ [Deep Study](https://lean-owner-437.notion.site/880a31692ac04b929a83be0a23d462c9?v=29a198c3797640a3b1118add1c6e947c)

**더 알고 싶은 내용**들을 정리했습니다.  

#### 📌 [Trouble Shooting](https://lean-owner-437.notion.site/75b5e0f24ccd459ea0509236a2a048da?v=fa0d301c692d4d4c8c5c5860fd9c40e8)

개발에서 발생한 **에러 해결 과정을 공유**하고 싶습니다.   
  

