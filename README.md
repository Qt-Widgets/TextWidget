# 텍스트 위젯

> 텍스트를 바탕화면에 심플하게 띄우는 위젯

리눅스에서 사용했던 위젯으로 심플하고 사용이 편리하였으나 윈도우에 유사한 프로그램이 없어서 제작하게 되었다. 기존의 프로그램에서 여러 기능과 단축키가 추가하다보니 사용이 편리한지는 잘 모르게 되었다.

## 설치 방법

Windows 7+ x64 : [TextWidget_x64.zip](https://www.dropbox.com/sh/g10z7q7ecs8fab9/AAADWShDyU6-PBkb2bGZc9t8a?dl=1)

## 상세 설명

리눅스를 사용하면서 가장 좋았던 점은 레이아웃을 내 맘대로 자유롭게 꾸밀 수 있고 예쁜 위젯이 많았다는 것입니다. 제작한 텍스트 위젯이 리눅스에서 사용하던 꽤 맘에 들었던 응용 프로그램을 윈도우에서도 사용하고 싶어서 만든 것 입니다.

![1](https://user-images.githubusercontent.com/35596687/48127923-485a1580-e2c8-11e8-85e1-513b9731b47a.jpg)

기본 레이아웃은 리눅스에서 사용했던 위젯을 그대로 따라하려 노력했으며 `Noto Sans`폰트를 이용하여 가독성을 살리려고 하였습니다. 해당 폰트가 16px의 크기의 흰색 글자는 흐릿하게 나타나는 버그가 있어 볼드체로 처리하였으나, 현재는 사용자가 선택할 수 있도록 변경했습니다.

<br/>

![2](https://user-images.githubusercontent.com/35596687/48127924-48f2ac00-e2c8-11e8-8ef9-e56b025b8e7f.gif)

당연히 사용하면서 불편했던 점은 개선하였습니다. 기존 프로그램은 스크롤 기능이 없고 더블클릭하면 메모장이 켜지는 방식이었습니다. 저는 위젯인 상태에서도 스크롤이 되기를 원했고 그래서 해당 기능을 넣게 되었습니다.

## 사용 예제

프로그램이 활성화(포커스)된 상태에서 사용할 수 있는 단축키

Ctrl + E : 텍스트 파일의 링크 및 방향키로 폼을 움직이는 속도, 자동시작, 폰트 사이즈와 색상을 'E'dit

Ctrl + O : 현재 링크된 텍스트 파일을 'O'pen

Ctrl + R : 편집된 텍스트 파일을 'R'eload

Ctrl + Z : 텍스트를 위 페이지로 올림

Ctrl + X : 텍스트를 아래 페이지로 내림

마우스로 텍스트의 위치를 변경할 수 있으나 정확하게 텍스트를 눌러야 하는 불편함이 있으므로 추가적으로 (←↑↓→)키를 이용하여 움직일 수 있음

폼의 크기는 우측하단에서 조정할 수 있음

## 업데이트 내역

- Update 1 :
  - 수정: 셋팅 버튼을 제거
  - 추가: 단축키 추가
- Update 2 :
  - 추가: 셋팅창 일부 기능 구현
  - 추가: 파일 입출력 함수
  - 추가: 마우스로 폼 움직이는 함수
- Update 3 :
  - 수정: 디자인 변경
  - 수정: '항상 최상위' 기능을 제거
  - 추가: 페이지 스크롤 기능을 가진 단축키 추가
- Update 4 :
  - 추가: 자동 시작 기능 구현
  - 추가: 방향키로 폼을 움직일 수 있도록 개선
- Update 5 :
  - 수정: 한국어 텍스트 지원
  - 수정: HiDPI 지원
- Update 6 :
  - 수정: NotoSans 폰트 적용
  - 추가: 프로그램 아이콘
- Update 7 :
  - 추가: Reload, File Open 단축키
- Update 8 :
  - 추가: AlwaysOnTop 기능 (프로그램 재시작 필요)
  - 추가: 텍스트 배경 생삭 지정 (투명설정은 x, X)
  - 수정: 텍스트 굵게 표시를 선택할 수 있음

## 정보

Jino Bae. – [BLOG](https://baejino.com) – im@baejino.com