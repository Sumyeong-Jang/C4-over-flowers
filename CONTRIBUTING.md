# Contributing

이 리포지토리에 기여할 때 누가, 어떤 내용을, 어떻게 변경하였는지 구분하기 위해 아래의 규칙을 지켜봅시다

## 풀 리퀘스트 프로세스

1. `main`브랜치에 되도록 바로 커밋하지 말기.
2. 환경 변수가 추가되거나, 포트가 변경되거나, 파일 경로가 변경되는 등 프로젝트를 구동하기 위한 절차가 변경된 경우, README.md 를 변경하기.
3. 눈갱 방지를 위해 최소한 코드 에디터가 제공하는 [코드 정리(Linting)](https://code.visualstudio.com/docs/python/linting) 기능을 사용하여 *(VSCode 의 경우 cmd+k+f)* [PEP8](https://peps.python.org/pep-0008/)을 준수하려고 노력해 보기.
4. git 커밋에도 컨벤션이 있습니다. 한번 지켜봅시다 예쁘면 좋잖아요!
    - 🐛 : Bugfix, 버그 패치
    - ✨ : Feat, 기능 추가
    - 🎨 : Style & Typo, 기능 변경 없이 간단한 변수명, 파일명, 경로변경 등의 작업
    - 🔧 : Refactor, 기능 변경 없이 레거시를 리팩터링하는 거대한 작업
    - 📝 : Docs, 기능 변경 없이 문서 및 주석 수정
    - 🎉 : First commit

```text
<타입 이모지> <한글 한줄설명> (이슈링크)
# 한 줄 띄우기
<커밋에 대한 본문(선택 사항) 한글 설명>
🎨 여러개를 한번에 커밋하는 경우 사용하고 이렇게 설명을 달아줘도 좋음
```

`example`
```text
✨ EDA 모델 추가 (#102)

시각화로 탐색적 분석을 추가함
📝 README.md 에 데모 gif 추가 (#501)
```


### 참고

- [Github for SAI](https://sejongai.notion.site/Github-for-SAI-16f0ab49fa5c475e91751f68016d0af9)
- [CONTRIBUTING.md template](https://gist.github.com/PurpleBooth/b24679402957c63ec426)
- [VSCode Linting](https://code.visualstudio.com/docs/python/linting)
- [Python PEP8](https://peps.python.org/pep-0008/)
- [Git commit convention](https://www.conventionalcommits.org/ko/v1.0.0/)
- [Git commit convention reference: FastAPI Template project](https://github.com/tiangolo/full-stack-fastapi-postgresql)
- [Sementic versioning](https://semver.org/lang/ko/)
- [Repository convention reference: SSAFY BookFlex project](https://github.com/glenn93516/BookFlex)
