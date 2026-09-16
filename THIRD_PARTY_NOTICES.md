# 제3자 구성 요소 고지 (AniimoOverlay)

AniimoOverlay 실행 파일에는 다음 제3자 구성 요소가 포함되어 있습니다. 각 구성 요소에는 아래 라이센스가 적용됩니다.

## Qt 6 (Qt Toolkit)
- 사용 모듈: QtCore, QtGui, QtWidgets, QtNetwork, QtSvg (정적 링크)
- 라이센스: GNU Lesser General Public License v3 (LGPLv3). 전문: https://www.gnu.org/licenses/lgpl-3.0.html
- 저작권: The Qt Company Ltd. 및 기여자. https://www.qt.io/
- LGPL 에 따라 사용자는 Qt 라이브러리 부분을 수정하고 재링크할 권리가 있습니다. 재링크에 필요한 애플리케이션 목적 파일(.obj) 묶음과 링크 절차는 공식 배포처
  https://github.com/BabyShark10/aniimo-overlay-releases 의 Issues 로 요청하면 제공합니다. Qt 소스는 https://code.qt.io/ 에서 받을 수 있습니다.

## Qt 가 포함하는 라이브러리
- FreeType (FreeType License), HarfBuzz (MIT), libpng (PNG Reference Library License), zlib (zlib License), PCRE2 (BSD-3-Clause), double-conversion (BSD-3-Clause). 각 라이센스 전문은 Qt 소스 트리 `src/3rdparty` 에 있습니다.

## Aniimax (홈랜드 생산 데이터)
- https://github.com/spacetot/aniimax — Copyright 2026-Present aebii, MIT License.
- 홈랜드 계산기의 시설·품목 데이터(`resources/data/homeland/*.csv`)와 최적화 방식은 Aniimax 를 참고해 C++ 로 다시 구현했습니다. 원문 라이센스: `resources/data/homeland/LICENSE-aniimax.txt`

## 데이터 출처
- 속성 상성표와 도감 기본 자료는 커뮤니티 자료를 참고했습니다 (출처는 프로그램 안 각 패널의 자료 표기).

## 게임 콘텐츠
- Aniimo 및 관련 이름·이미지·데이터의 권리는 Pawprint Interactive Entertainment Pte. Ltd. 에 있습니다. 이 프로그램은 게임사와 무관한 비공식 팬 메이드 도구이며, 게임 이미지와 위키 텍스트는 사용자가 보는 항목만 공식 CDN/위키에서 그때 받아 표시합니다(재배포하지 않음).
