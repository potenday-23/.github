# 문화생활 티켓 아카이빙 서비스 티캣츠(Ticats)
![로고](https://github.com/potenday-23/tickets_backend/assets/82714785/583637a8-0796-4abc-949c-faea3d87e4b0)

[1️⃣ 앱 다운받기(출시 검토중!)👈](https://drive.google.com/file/d/1Nsd-iJ7azwFYLCXXw6m8QavjiCGtM7Cy/view?usp=drivesdk)

[2️⃣ 서비스 소개서 보러가기👈](https://file.notion.so/f/f/da2fc6b2-1845-4cbe-9aab-ca4922314a62/3a93adb8-5e9b-424c-84d8-8c85497e6c7e/%E1%84%90%E1%85%B5%E1%84%8F%E1%85%A2%E1%86%BA%E1%84%8E%E1%85%B3(Ticats)_%E1%84%89%E1%85%A5%E1%84%87%E1%85%B5%E1%84%89%E1%85%B3_%E1%84%89%E1%85%A9%E1%84%80%E1%85%A2%E1%84%89%E1%85%A5_20231112.pdf?id=5629a314-3816-4c17-920b-17d3e789c0b5&table=block&spaceId=da2fc6b2-1845-4cbe-9aab-ca4922314a62&expirationTimestamp=1699977600000&signature=Gy9Dz2_1w29RwF50lgkkBThklY3-a_AgmL3_91HRKmA&downloadName=%E1%84%90%E1%85%B5%E1%84%8F%E1%85%A2%E1%86%BA%E1%84%8E%E1%85%B3%28Ticats%29_%E1%84%89%E1%85%A5%E1%84%87%E1%85%B5%E1%84%89%E1%85%B3+%E1%84%89%E1%85%A9%E1%84%80%E1%85%A2%E1%84%89%E1%85%A5_20231112.pdf)

## 말하는 감잔데요 팀소개
|                   기획                    |                백엔드 개발                 |              프론트엔드 개발               |                 디자이너                 |
|:---------------------------------------:|:-------------------------------------:|:-----------------------------------:|:------------------------------------:|
|                   윤희원                   |                  김가영                  |                 진희륜                 |                 백지수                  |
| [wonhee0619](https://github.com/wonhee0619) | [gabang2](https://github.com/gabang2) | [SerenityS](https://github.com/SerenityS) | [ssrbsg@naver.com](ssrbsg@naver.com) |

## Summary
![image](https://github.com/potenday-23/tickets_backend/assets/82714785/c1206254-eb11-4034-8a4a-44613856a42f)
- 나의 문화생활을 티켓으로 만들 수 있어요.
- 다른 사람의 티켓을 확인하고, 나의 아카이빙에 참고할 수 있어요.

## Skils
언어 및 프레임워크: ![Static Badge](https://img.shields.io/badge/Java-17-Green) ![Static Badge](https://img.shields.io/badge/Spring_boot-REST-Green)<br/>
데이터베이스 및 테스트: ![Static Badge](https://img.shields.io/badge/MySQL-8-blue) ![Static Badge](https://img.shields.io/badge/JUnit-Green) <br/>
배포 : ![Static Badge](https://img.shields.io/badge/LINUX-039BC6) ![Static Badge](https://img.shields.io/badge/AWS-Orange) <br/>

## Installation
1. 환경변수 설정
   - TICKETS_DB_URL : MySQL 데이터베이스 URL
   - TICKETS_DB_USER : MySQL 데이터베이스 유저
   - TICKETS_DB_PW : MySQL 데이터베이스 패스워드
   - TICKETS_S3_ACCESS : S3 Access key 정보 
   - TICKETS_S3_SECRET : S3 Secret key 정보
   - TICKETS_SECRET : JWT Secret 키 정보
   - TICKETS_CLIENT : KAKAO Client 정보(현재 비활성화)
   - TICATS_SSL_PW : ssl 인증서의 pw 정보
2. Ticats 어플리케이션 백엔드 build
    ```bash
    ./gradlew bootjar
    ./gradlew bootrun
    ```

## Running Tests
Ticats 어플리케이션 백엔드 Test(미구현)
```bash
  ./gradlew test
```
> Coverage ScreenShot ![Static Badge](https://img.shields.io/badge/Test_Passed-7/7-green)<br/>

## 백엔드 API 문서
![image](https://github.com/potenday-23/tickets_backend/assets/82714785/8e56a65c-1d6d-40d8-931c-41e8a6a67458)
[티캣츠 백엔드 API 문서 바로가기👈](https://www.ticats.r-e.kr/swagger-ui/)

## 프로젝트 진행 및 이슈 관리
[![Github Project](https://img.shields.io/badge/Github-%23000000.svg?style=for-the-badge&logo=Github&logoColor=white)](https://github.com/potenday-23/tickets_backend/issues)

## 설계
- E-R Diargram
![ERD Cloud](https://github.com/potenday-23/tickets_backend/assets/82714785/5b4e207d-35ef-4153-8ce5-a25844bc17cf)
- Architecture
![Architecture](https://github.com/potenday-23/tickets_backend/assets/82714785/021b3e23-66bc-4724-9c31-4e550342f38d)


## TIL 및 회고
### 회고

### TIL
- [QueryDsl에서의 월별 조회를 위한 GroupBy](https://www.notion.so/gabang2/QueryDsl-3b8f3bc3ba30457b8b59371b0654df1d)
- [LocalDateTime 클라이언트 에러 처리](https://www.notion.so/gabang2/LocalDateTime-b69aeadeb78a46349474cb395ffe1e80?pvs=25)
- [JWT Filter에서의 에러 처리 - 미완료](https://www.notion.so/gabang2/JWT-Filter-Error-8c488e856bbb48b9a554146b29c96a5d)
- [LocalDateTime 100% 활용하기 - 미완료](https://www.notion.so/gabang2/LocalDateTime-100-51a54847578f45a88af44eb533390285)
- [테스트 코드 작성법 - 미완료](https://www.notion.so/gabang2/4d89c76418c04972a165966258fe4ce0)

