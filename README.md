# 2026 청아제 안내 사이트

한국교통대학교 증평캠퍼스 학생들이 축제 일정, 타임테이블, 라인업, 부스 안내를 QR코드나 링크로 빠르게 확인할 수 있도록 만든 정적 웹사이트입니다.

## 기본 정보

- 축제명: 2026 청아제
- 대상: 한국교통대학교 증평캠퍼스 학생
- 주최·주관: 제15대 보건생명대학 학생회 서/화(緖花)
- 배포 방식: GitHub Pages
- 예상 배포 주소: https://skyhy0228.github.io/jeungpyeong-festival/

## 파일 구조

```text
jeungpyeong-festival/
├── index.html
├── style.css
├── festival-bg.jpg
└── README.md
```

## 수정 방법

- 문구, 일정, 라인업, 부스 안내는 `index.html`에서 수정합니다.
- 색상, 배치, 모바일 화면 스타일은 `style.css`에서 수정합니다.
- Hero 배경 이미지는 `festival-bg.jpg` 파일을 같은 이름으로 교체하면 됩니다.
- React, Next.js, Vite 없이 순수 HTML/CSS 정적 사이트로 배포합니다.

## GitHub Pages 배포

GitHub repository의 `Settings > Pages`에서 아래처럼 설정합니다.

- Source: Deploy from a branch
- Branch: main
- Folder: /root

설정 후 잠시 기다리면 아래 주소로 접속할 수 있습니다.

https://skyhy0228.github.io/jeungpyeong-festival/

## QR코드 공유 방법

1. GitHub Pages 배포 주소가 정상 접속되는지 확인합니다.
2. QR코드 생성 사이트에서 배포 주소를 입력해 QR코드를 만듭니다.
3. 생성한 QR코드를 포스터, 현수막, 부스 안내물, 인스타그램 공지에 넣습니다.
4. 현장에서 학생들이 휴대폰 카메라로 QR코드를 스캔해 사이트에 접속할 수 있도록 안내합니다.
