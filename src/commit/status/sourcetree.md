---
layout: git
title: "소스트리 Untracked 파일 확인하기"
keyword: "status, 워킹디렉터리, Untracked, 소스트리"
description: "소스트리를 이용하여 깃의 파일 상태를 확인하는 방법에 대해서 학습니다. gui를 통하여 쉽게 상태를 확인할 수 있습니다."
breadcrumb:
- "commit"
- "status"
- "sourcetree"
---

# 소스트리에서 새 파일 감지
---
소스트리를 사용하여 깃의 `status` 명령어과 동일한 `상태`를 확인할 수 있습니다.  

<br>

## 소스트리 저장소 연동
---
소스트리를 실행합니다. 아직 gitstudy04 폴더와 소스트리를 `연동`하지 않았습니다.  
새 탭에서 `Add 버튼`을 클릭합니다.  

탐색을 눌러 깃 배시에서 만든 gitstudy04 폴더를 찾아 선택한 후 추가를 누릅니다.  

소스트리에 저장소 추가  
![소스트리에 저장소 추가](./img/04-4.jpg)  

<br>

## 파일의 상태확인
---
gitstudy04 저장소를 추가했다면 소스트리에서 왼쪽의 파일 `상태 탭`을 선택합니다.  

소스트리에서 새 파일 감지  
![소스트리에서 새 파일 감지](./img/04-5.jpg)  

새로 작성한 index.htm 파일이 소스트리의 스테이지에 `올라가지 않은 파일 목록`에 추가된 것을 확인할 수 있습니다.  

<br>

## 소스트리와 명령어
---
소스트리는 `GUI`로 상태를 직관적으로 표시해 줍니다.  
사실 내부적으로는 소스트리가 status 명령어를 대신 깃에 입력하는 것입니다.  
따라서 직접 status 명령어를 실행하지 않아도 쉽게 확인할 수 있습니다.  

<br>