---
layout: post
title: "What is Git?"
info: "About git/github"
tech: "Git"
type: 특강 Topic post
---

## Git이란?

Git은 가장 일반적으로 사용되는 버전 관리 시스템(VCS)입니다. 파일의 변경된 내용을 계속 추적하고, 필요한 경우 특정 버전으로 되돌릴 수 있습니다. 또한, branch기능을 이용해 협업을 더 쉽게 만들어 여러 사람의 소스 코드를 하나로 병합할 수 있도록 만들어줍니다.

## GIT의 특징

Git은 로컬로 실행되는 소프트웨어로 파일과 파일 기록이 모두 로컬 컴퓨터에 저장됩니다. 또한 GIthub 같은 온라인 호스트로 이를 저장할 수 있습니다. Git은 VCS의 종류중 **DVCS(Distributed Version Control Systems)**로 중앙 서버에 있는 코드를 개발자 각각의 컴퓨터에 복사하여 사용하고, 서버에 업로드할 수 있는 시스템입니다.

[Git 설치하기](https://git-scm.com/downloads)

## Stage & Commit

Git으로 파일의 변경사항을 저장하기 위해서는 이를 **Commit**해야합니다. 그리고 Commit을 하기 전에 Git에게 어떤 파일을 Commit할지 **add**하여 **스테이징(Staging)**하는 과정이 필요합니다. Commit을 진행할때는 스테이징 영역에 있는 파일들만 Commit됩니다.

## Github

Git은 로컬로 실행되는 소프트웨어입니다. 이를 다른 사람들과 공유하기 위해서는 Github이라는 Remote Repository, 즉 **원격 저장소**가 필요합니다. 원격 저장소를 설정한 후에 Commit한 내용을 **Push**하면 변경 사항을 원격 저장소에 기록할 수 있습니다. 반대로 원격 저장소에서 변경된 내용을 로컬로 가져올 때는 **Pull**기능을 이용할 수 있습니다.
