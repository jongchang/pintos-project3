Brand new pintos for Operating Systems and Lab (CS330), KAIST, by Youngjin Kwon.

The manual is available at https://casys-kaist.github.io/pintos-kaist/.

---

## README for README

본 문서는 필요한 정보를 한 곳에서 관리하기 위해 만들어졌습니다. 공지사항, URL 인덱싱, 브리핑 내용 정리로 사용할 예정입니다. 깃허브 이슈를 통해서 할 일 목록과 수정제안등을 할 수 있고, Pull Request를 통해서 본 리포지토리에 기여할 수 있습니다.

Project 3에서 팀이 섞이고 코드가 섞이기 때문에 혼란을 최소화 하기 위해 구현물에 대한 문서화를 확실히 해야할 것으로 보입니다. 따라서 [Coding Convention](#coding-convention) 쪽으로 가셔서 어떤 docstring 규격을 사용할건지, 어떤 포매터를 사용할건지 등에 대한 정보를 확인하시기 바랍니다.

- [\[WEEK07-11\] 정글 끝까지 (private)](https://jungle7-7610626261f4.herokuapp.com/pages/W07-os.html) | 학습범위, 일정, 팀 프로젝트등 여기에 없는 웬만한 건 저기에 다 있습니다.
- 권영진 교수님 강의 전 읽고 갈 것들
    - [Pintos_1.pdf](https://drive.google.com/file/d/1rr1VobnaR8QiWq3TVImvzzHWWdB5d4B5/view)
    - [01_os_review.pdf](https://drive.google.com/file/d/1v7ZT0uCqnSFQQY3jQsnXnCh9WHPpgQxZ/view?usp=sharing)
    - [CS 6200: Introduction to Operating Systems Course Videos (Georgia Tech College of Computing)](https://omscs.gatech.edu/cs-6200-introduction-operating-systems-course-videos)
- [진행상황 구글 스프레드시트 (private)](https://docs.google.com/spreadsheets/d/1SjVvI3bUMruBB_XWPMXSnzziP343g9UCFIphWU4D2iE/edit#gid=0)
- 공부자료
    - [PintOS 검색어(키워드) 목록 (private)](https://jungle7-7610626261f4.herokuapp.com/pages/pintos-keywords.html)
    - [OSTEP](https://pages.cs.wisc.edu/~remzi/OSTEP/)
- Q&As
    - [Project 1 Q&A (private)](https://jungle7-7610626261f4.herokuapp.com/pages/pintos-questions1.html)

## swjungle 공지사항

### 브리핑

- **10:00** 모닝 화이팅 및 오늘의 다짐 공유하는 시간
- **저녁(시간미정)** 학습기간 동안에는 공부한 것들에 대한 내용을 다루고 구현기간 동안에는 다 함께 머리를 맞댄 결과물에 대해서 이야기 나눌듯?

### 추석기간에 빠지는 날들

- @smi-23 2023-09-30 ~ 2023-10-01
- @coding-jjun 2023-09-27(저녁) ~ 2023-09-30
- @ChoiWheatley None

### 권영진 교수님의 OS 강의일정

- 2023-09-26T10:30:00 (7주차 화요일)
- 2023-10-10T10:30:00 (8주차 화요일)
- OS abstraction 개념에 초점을 맞추어 진행.
- 강의 슬라이드는 swjungle 페이지에서 확인바람.

## Objectives

### Project1: Threads

- Alarm Clock

- Priority Scheduling

- Advanced Scheduler(option)

### Project2: User Programs

- Argument Passing

- User Memory Access

- System Calls

- Process Termination Message

- Deny Write On Executables

- Extend File Descriptor(option)

## Coding Convention

C 코드 포매팅은 [clang-format](https://clang.llvm.org/docs/ClangFormat.html)을 사용할 예정입니다. vs-code의 C/C++ 익스텐션 자체로 clang-format을 지원하기 때문에 설정만 같은 값으로 맞춰주면 됩니다. 다양한 회사들의 코딩 컨벤션을 갈아끼우기 쉽게 만들었기 때문에 구체적으로 어떤 회사의 컨벤션을 따라야 할 건지는 정해봐야 알겠습니다. 

[Doxygen Documentation Generator](https://marketplace.visualstudio.com/items?itemName=cschlosser.doxdocgen)를 사용하여 기존에 `///`를 사용한 docstring 자동생성에 더 많은 기능과 자동완성을 제공해 줄 수 있습니다. 

변수명, 전역변수, 정적변수 사용규칙까지 세세하게 강제하지는 않겠습니다. 하지만 팀원들의 코드가 일관적이 되도록 신경쓸 수 있다면 좋을 것 같습니다.

## Presentation

매 주차가 끝나는 날 오전에 발표를 진행한다고 합니다. 아직 정확히 어떤 발표를 진행한다는 건지 잘 모르겠어서 코치님한테 질문 남겼습니다.

- [Project 1: 2023-10-03](#)
- [Project 2: 2023-10-10](#)