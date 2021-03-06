# SAMP Welcome to Los Santos korea mode
GTA San Andreas MultiPlayer의 WTLS 서버의 모드를 클론한 자유 장르의 게임모드 입니다. <br><br>
WTLS 서버 주소: s2.gta-multiplayer.cz:7777 <br>
[WTLS 공식 홈페이지](https://www.gta-multiplayer.cz/) <br>
[한국 GTA:SA 다음 커뮤니티](http://cafe.daum.net/GTA2)

# Purpose
이 프로젝트의 궁극적인 목표는 Pawno 언어에 관심이 있는 개발자들과의 협업과 공부 목적에 있습니다.
외국의 참신하고 재미있는 모드를 클론함으로써 다양한 기술을 익히고, 또 모드를 서비스해 즐기기 위함입니다.
RP모드에 국한된 한국 서버에 새롭고 재밌는 모드를 내보이고자 합니다.

# Contributing
이 프로젝트에 기여하는 방법에는 세 가지가 있습니다.<br>
아래의 방법 외에 프로젝트에 기여하고 싶은 방법이 있다면 이메일 혹은 커뮤니티를 통해 언제든지 문의해주세요.
1. 기획안 작성하기
2. 작성된 기획안에 따라 개발하기
3. 기능 개선
4. 버그 수정
5. 버그 제보

* [이슈 작성 가이드](https://github.com/skqoaudgh/samp-wtls-korea/blob/master/documents/%EC%9D%B4%EC%8A%88%20%EC%9E%91%EC%84%B1%20%EA%B0%80%EC%9D%B4%EB%93%9C.md)
* [기획안 작성 가이드](https://github.com/skqoaudgh/samp-wtls-korea/blob/master/documents/%EA%B8%B0%ED%9A%8D%EC%95%88%20%EC%9E%91%EC%84%B1%20%EA%B0%80%EC%9D%B4%EB%93%9C.md)

# Pull Request Process
프로젝트 기여의 시작은 Pull Request입니다. 프로젝트에 기여하기 위해 아래 과정을 따라주세요.

## 기본
1. 프로젝트 정식 Contributor라면 현재 프로젝트 저장소에서 새로운 브랜치를 만든다.
2. 아니라면 프로젝트를 Fork한 후에 해당 저장소에서 새로운 브랜치를 만든다.
    * 제목: <docs | feature | bugfix>/이슈번호-이름 (ex. feature/#1-notice)
    * 이슈번호를 필요로하기 때문에 작업을 진행하기 전에 **Issues**탭에 이슈를 등록한다.
3. 해당 프로젝트 저장소를 로컬 환경에 Clone한다.
4. 해당 브랜치 혹은 저장소에서 원하는 작업을 진행한다.

## 기획안 작성하기
1. 작성하려는 기획안이 이미 작성됐는지 확인한다.
2. 기획안 작성에 대해 **Issues** 탭에 새로운 이슈를 작성하고 이슈번호를 확인한다. ('#'과 숫자 조합)
    * 기획안 이슈 템플릿을 사용한다.
    * 제목: docs: 기획안 제목 (ex. docs: 공지사항 메시지)
3. 기획안을 proposals 폴더에 작성한다.
    * 제목: 기획안 제목 (ex. 공지사항 메시지)
4. 변경사항을 **Commit**한다.
5. **Pull Request**한다.
    * 제목: 기획안 제목 <이슈번호> (ex. 공지사항 메시지 기획안 작성 #1)
    * 내용: Pull Request 목적 및 변경사항에 대한 상세 내용 등
    * 한 Pull Request에 여러 변경사항을 포함하지 않는다. (즉, 하나의 기획안이 Pull Request 되어야 한다)
 
## 작성된 기획안에 따라 개발하기
1. Proposals 폴더에서 원하는 기획안을 선택한다.
2. 프로젝트 Commit 내역 및 Pull Request 목록에서 해당 기획안의 개발이 완료되었는지 확인한다.
3. **Issues** 탭에 새로운 이슈를 작성하고 이슈번호를 확인한다. ('#'과 숫자 조합)
    * 개발 이슈 템플릿을 사용한다.
    * 제목: feature: 기획안 제목 (ex. feature: 공지사항 메시지)
4. 선택한 기획안에 대한 개발을 진행한다.
5. 변경사항을 **Commit**한다.
6. **Pull Request**한다.
    * 제목: 기능 이름 <이슈번호> (ex. 공지사항 메시지 기능 추가 #2)
    * 내용: Pull Request 목적 및 변경사항에 대한 상세 내용 등
    * 한 Pull Request에 여러 변경사항을 포함하지 않는다. (즉, 하나의 기능 개발이 Pull Request 되어야 한다)

## 기능 개선 
1. **Issues** 탭에 올라온 기능 개선 요청 목록에서 하나를 선택하고 이슈번호를 확인한다. ('#'과 숫자 조합)
    * 개선이 필요한 기능은 반드시 이슈 등록을 한 후에 수정을 하도록 한다.
2. 기능을 개선한다.
3. **Pull Request**한다.
    * 제목: 기능 이름 <이슈번호> (ex. 공지사항 메시지 출력 로직 수정 #3)
    * 내용: Pull Request 목적 및 변경사항에 대한 상세 내용 등
    * 한 Pull Request에 여러 변경사항을 포함하지 않는다. (즉, 하나의 기능 개발이 Pull Request 되어야 한다)

## 버그 수정
1. **Issues** 탭에 올라온 버그 제보 목록에서 하나를 선택하고 이슈번호를 확인한다. ('#'과 숫자 조합)
    * 발견된 버그는 반드시 이슈 등록을 한 후에 수정을 하도록 한다.
2. 버그를 수정한다.
3. **Pull Request**한다.
    * 제목: 버그 이름 <이슈번호> (ex. 공지사항 메시지 출력 버그 수정 #4)
    * 내용: Pull Request 목적 및 변경사항에 대한 상세 내용 등
    * 한 Pull Request에 여러 변경사항을 포함하지 않는다. (즉, 하나의 기능 개발이 Pull Request 되어야 한다)

## 버그 제보
* **Issues** 탭에 새로운 이슈를 작성한다.
    * 버그제보 이슈 템플릿을 사용한다.
    * 제목: report: 간략한 버그 설명 (ex. report: 공지사항이 제대로 표시되지 않는 버그)

# License
<a rel="license" href="http://creativecommons.org/licenses/by-sa/3.0/"><img alt="크리에이티브 커먼즈 라이선스" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/3.0/88x31.png" /></a><br />이 저작물은 <a rel="license" href="http://creativecommons.org/licenses/by-sa/3.0/">크리에이티브 커먼즈 저작자표시-동일조건변경허락 3.0 Unported 라이선스</a>에 따라 이용할 수 있습니다.
