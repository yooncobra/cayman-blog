##git/github 더 잘쓰기 session
1. commit comment는
Tag: topic sentence 50문자 이내로
(한 줄 비우고)
body.. 72문자 이내로

내용은 무엇이 바뀌었는지 보다 왜 커밋을 하고 변경을 하게 됬는지를 중심으로 작성할 것

2. 브렌치 이름 짓기
git flow식 이름 짓기
master  : 기준이 되는 믿고 pull할 수 있는 브렌치
develop :

feature/mainUI      : 기능 구현
hotfix/mainUI       :
release/version3.0  :

3. 할 수 있으면 rebase 선호

4. branch protection

5. unit test
unit module을 확인하는 기능
모든 커밋은 무조건 테스트를 통과해야 함->  커밋할 때 마다 테스트에 통과해야만 커밋할 수 있음
(테스팅 + git) 규칙
hook?

6. CI: 지속적 통합
통합 지옥? 프로젝트가 복잡할수록 플러그인/라이브러리에 대한 의존성 증가
빌드 자동화-> 필드만 하는 컴퓨터를 따로 설정-> 빌드머신
Jenkins, Travis CI
그냥 팀원중 아무나 빌드하면 안되나요?-> 버튼하나 불러서 빌드가 되면 괜찮음, 하지만 그렇지 않음

7. 위키
팀 내부에서 공유 되어야 하는 지식들을 모아 놓을 수 있음
-> 서버 api request, parameter, response
내부 text
이슈트래커 -> 이슈들을 보고하는 공간, 태그로 원하는 범주의 이슈를 필터링 할 수 있음(bug)

8. 더 찾아볼 것
다른사람 저장소 fork 해보기
더 전략적인 git flow 사용법
git LFS 플러그인(바이너리가 많으면)
rebase -i, commit -amend, cherry-pick등의 커밋 조작 명령들
gTest를 비롯한 각종 test 도구들
Travis, Jenkins등의 CI 도구들
HockeyApp, Testflight등의 배포도구

쓸데없이 복잡한  규칙 지키는데 시간이 더 들어간다
하지만 체계적이고 일관성있는 개발을 위해 적당한 규칙은 필요하다
-> 팀원들과 충분한 합의를 통해 규칙을 정하자

slideshare 확인해 볼 것!





























