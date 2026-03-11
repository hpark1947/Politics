# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

정치 관련 프로젝트. 프롬프트와 가이드 문서를 관리하는 저장소.

## Structure

- `guide.md` — 프로젝트 가이드 문서
- `Prompts/` — 프롬프트 파일 디렉토리

## GitHub 한글 깨짐 대응

GitHub에서 한글 파일이 유니코드 이스케이프 시퀀스(예: `\354\260\270\352\263\240`)로 표시되는 경우가 있다. 이는 GitHub의 트리 렌더링 캐시 문제로, 다음 절차로 해결한다:

1. 해당 파일에 공백 추가 등 사소한 변경을 가한 빈 커밋 또는 더미 커밋을 생성
2. push하여 GitHub 캐시를 갱신
3. GitHub 웹에서 한글이 정상 표시되는지 확인

이 문제가 발생하면 즉시 위 절차를 수행할 것.

## 참고

- 모든 문서는 한국어로 작성
