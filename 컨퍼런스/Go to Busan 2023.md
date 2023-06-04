## 2023 golang 컨퍼런스



#### DevRel 담당자가 당신에게 전하는 소프트웨어 개발 여정의 KICK - 최가인님

개발은 7년정도 했다고 하심

대부분 커뮤 생활

DevRel이 무엇?? 개발자와 개발 문화에 대해 이해하고 있어야 함

개발 & 관계

기술 & 커뮤와 개발 생태계 종사자 사이에 있는 사람이 데브렐

이벤트를 기획하고 기술 컨텐츠를 만들고, 개발자 문화를 홍보하는 영역에서 일함

SDK와 API를 홍보하는 역할?

가장 유명한 데브렐중 하나는 가이 가와사키

애플의 위대함을 땅끝까지 전도했다~ 라는 평을 받을 정도로 유명한 사람



오늘의 이아기: 데브렐의 관점에서 예비 개발자 또는 주니어 개발자가 알면 좋은것 7가지

본인의 관심사를 가진 동료를 커뮤니티에서 찾을것

일찍 실패하고, 빨리 실패하고, 자주 실패할 것 => 협업하는 기회를 만들자

비평하는 법을 배울 것 => 경험 레벨이 한층 업그레이드 됨



##### KICK 1 => 개발자 행사 - 컨퍼런스 활동

적극적 참여 

- 직접 발표하기
- 소규모 밋업/ 스터디 직접 개최하기
- 훌륭한 연사 발표 듣기

소극적 참여

- 참영기업 부스 참여와 네트워킹 신청

데브렐 활동의 꽃인 해커톤!

AI 프롬프톤, 데모데이

 

##### KICK 2 => 기술 컨텐츠 제작

- 잘 관리되는 기술 블로그 및 콘텐츠 많이 보기

- - Stripe, google developers, amazon Alexa, apple developer 등등
  - Naver d2, 우아한 형제들, 당근마켓, 프로그래머스 등

- 기술 컨텐츠 제작하기

많이 보는것만큼 잘 만들수 있는 방법이 없다



##### KICK 3 => 오픈소스 프로젝트 참여

- 공유의 진정한 가치 => 오픈소스의 힘
- Hacktoberfest
- 자발적 참여와 기여 => 태생적 한계 존재
- 새로운 언어 연습 또는 개인 브랜딩에 추천
- 특히 신입분들은 차별화, 소통 경험에 도움됨

플러터 공부하다가 관심이 생겨서 오픈소스를 까봤는데 이해가 잘 되지 않았다;; 발표자님은 오픈소스 프로젝트 참여할 때 어떤 느낌이 들었나?



##### KICK 4 => 개발자 커뮤니티와 뉴스레터

- 개발자 커뮤니티 사이트와 친하게 지내기

- - 스오플, 디코, 깃헙, OKKY, 레딧

- 뉴스레터

- - 앤드류 챈, geekiness, hacker news, the information, two cents



##### KICK 6 => 느슨한 연결

- 실무자들이 많이 등장하는 플랫폼을 통해 콜드콜, 정보 수집 및 네트워킹

- - 커리어리, 커피챗, 롱블랙, 디코, 카톡 옾챗 등

- 링크드인 프로필 꼭 만들것! (영문으로)

- 구인구직 사이트에서 개발자 카테고리 유심히 살펴보기

- - 원티드랩, 프로그래머스, 점팻, 로켓펀치, 위시캣, 비긴메이트, 리멤버커리어
  - LinkedIn jobs, Indeed, Glassdoor, [recruit.net](http://recruit.net), super rookie
  - 

##### KICK 7 => 회고

- 개발자는 왜 회고할까요?

- - 회고 = 성장
  - 개인 / 팀 / 프로젝트
  - 애자일 프로세스

- 다양한 방법론 존재

- - KPT
  - 5F
  - 4L
  - PMI

- 저널링(Journaling)

- - 지식 저장소이자 데이터베이스
  - 본인의 작업 시간을 예측하고, 얼마나 많은 문제들을 해결하고 발전했는지 알 수 있다





#### Go with Flutter - 다이어리 서비스 만들기 (박제창)

대부분 국내 백엔드 서비스는 스프링,, 파이썬이라면 fastapi

오늘은 flutter와 go, sqlite로 간단한거 만들 것

(라이브 코딩)

Fiber를 사용해서 만듦

스타 눌렀음 ^_^

<a>https://github.com/JAICHANGPARK/go-to-busan-hands-on</a>





#### Go로 사용자 행동 데이터 분석하기 - 김건님

서비스 사용자들의 행동을 분석하는것

그 사용자들이 서비스를 얼마나 쓰는지, 이탈을 잘 하는지 확인 할 수 있음

사용자별 이벤트를 모아 분석하는 것

Snowflake, anarch spark, big query, druid, amazon redshift

유저 단위로 이벤트를 모음

지금 나와있는 서비스는 범용적이여서 우리가 필요한 분야에서는 조금만 더 빠르게 하면 만들 수 있다

사용자 행동 데이터 분석을 위한 db를 만들자!

Left; Airbride’s purpose -built OLAP DB written go

- Fast : 사용자 행동 데이터 분석에 최적화 된 형태로 데이터를 저장 및 핸들링함
- Highly Available: 노드 장애애 대비하여 데이터를 복제하여 저장함
- Scalable : 런타임에 동적으로 클러스터 멤버십을 관리할 수 있어 확장에 용이함
- Easy to Operate : 단순한 컴포넌트로 구성된 클러스터이기에 운영에 용이함
- Easy to use : 사용자 행동 데이터 분석에 특화된 쿼리 인터페이스를 제공함



왜 Go를 사용했는지?

- Easy to use/ learn
- Fast
- Concurrent / Parallel Execution
- Rich Ecosystem(esp. Distributed System)



Query Later: 쿼리 API 제공, 쿼리 플래닝, 쿼리 최적화, 쿼리 실행 등을 함

Processing Layer : 분산 맵리듀스 프레임워크를 통해 쿼리를 분산 처리함

Storage Layer : Columnar 포맷을 사용해 데이터를 효과적으로 압축, 쿼리함



회고

고 그래서 빠름?? 고로 만들수 있음?? 라는 질문이 많이 들어온다고 한다

go로 db를 만들면서 느낀 점들

- Abstraction costs, but worth it
- Rarely, Dark rts is the answer, but mostly not
- Channels and Goroutines are not free
- Disk and Network IO are still expensive
- Proper designs outweigh language overheads



golang을 쓰면서 하지 말아야 할것들

- go에서 empty 인터페이스를 사용하지 말 것

- Dark Arts를 사용하지 말 것
- 

써볼 것 : Pporf 씽크풀, gcflags, empty struct





#### Go로 시작하는 CI/CD 입문 - 정예준

##### 토이 프로젝트 소개

백준을 풀고 커밋을 했음

너무 귀찮다;;

Go로 자동화 만들어버림



##### CI / CD 소개

빌드, 테스트, 통합 그리고 배포까지 개발에서 반복되는 절차들을 자동화해서 생산성을 높이는 기술



##### golang으로 pr 메시지 자동화 도구

설정용 JSON 파일 parsing

풀리퀘에 올라온 파일 목록 확인

https://github.com/google/go-github

깃 커밋 & 푸시 => 소스파일 추가

풀 리퀘 => 리뷰 진행

깃허브 봇 => pr 메시지 자동 생성

머지 브랜치 => pr 닫기





#### 개발 및 운영을 위한 golang 기반 cli 라이브러리 - 백경준

##### CLI 알아보기

CLI : Command Line Interface

GUI : Graphical User Interface

cli는 코드 치는거

gui는 유저가 보는거

CLI 특징 : 효율적인 시스템자원 사용, 자동화 용이, 원격 제어 용이

소프트웨어 개발, 시스템 관리, 자동화 등 다양한 분야에서 필수적인 도구로 인식되고 있음



##### CLI 라이브러리 소개

Cobra : CLI 애플리케이션 개발을 돕는 개발 도구





#### 영지식 증명

이거 재밌었는데 내용이 너무 어려워서 못적음; 나중에 공부해봄





#### 스타트업에서 Go 개발자로 살아남기 - 박현상

##### 우연한 계기로 Go 언어를 사용하게 된 계기

무슨 분야의 개발자가 되어야 할까?

무슨 프로그래밍 언어를 써야 할까?

프로그래밍의 매력이 없네….?

이 프로그래밍 언어를 배워서 과연 커리어를 성공적으로 쌓을 수 있을까?

이 프로그래밍 언어를 쓰는 회사가 있을까?

“Go라는 언어가 있는데 공부해보는게 어떻나~?”

몇개월동안 Go를 공부하고 나서 꾸준한 관심을 가지고 있따는 점을 인상깊게 보고 좋은 기회로 합류하게 됨



##### Go 언어를 공부하는 방법

Tucker의 Go 언어 프로그래밍 <== 책 너무 좋음

[golangkorea.github.io](http://golangkorea.github.io)

Effective go, nomadcoders.go



##### Go 언어로 프로젝트하면 좋을 주제들

백엔드 

- ORM : entgo, gorm, sqlx
- JWT + Redis : 사용자 인증 관련 회원가입, 로그인, 로그아웃, 인증
- gRPC
- Serverless

오픈소스 

- CNCF : Kubernets
- Docker : compose, ETC
- 

##### 회사에서는 어떻게 Go를 사용하고 있는지

발표자님 회사에서는 대부분 Go를 사용하고 있다고 한다



Go언어를 사용하는 회사

42bot, 당근마켓, 쿠팡, GitLab, 



개발자로서, 그리고 한 사람으로써

하고싶은 것들이 너무 많음

사내에서는 조직문화, 테크니컬 라이팅 등등…

개인적으로 다양한 분들과 다양한 이야기를 나누면서 성장하기, 사진전 개최, 사진집 제작, 이것저것…





#### Go와 GPT / PalM2 로 슬랙 메시지 감정분류 해보기 - 한성민

Feat. Go를 왜 하면 좋을까?



LLM (Large Language Model): 거대 자연어 모델

RLHF : 인간 피드백형 강화학습

PaLM2 : 구글이 만든 개쩌는 자연어 모델



##### Generative AI

Image / Video / Audio / Sound 등등 여러 분야에서 AI가 인간과 동등 또는 그 이상의 실력을 가지고 있다

NLP / Text 까지도?



##### Go의 특징

- 고루틴을 이용한 경량 스레드 사용 가능
- 학습 진입장벽이 낮음
- 컴파일 속도가 매우매우 빠름
- 빠른 런타임 성능

Go의 키워드는 30가지 이하로 다른 언어보다 적은 편이다



GPT API를 이용해 ~한 문장은 긍정적이다, ~한 문장은 부정적이다고 학습 시킨 후 문장을 입력받아서

긍정, 부정을 추측하는 방식이다.