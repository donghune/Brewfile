#############################################################
# 안드로이드 개발자 및 macOS 생산성 도구 목록 (Brewfile 발췌) #
#                                                            #
# 안드로이드 개발과 macOS 환경에서 필요한 도구만 간추렸습니다. #
# 설치: $ brew bundle --file $HOME/.Brewfile                 #
#############################################################

# 기본 옵션 설정
cask_args appdir: '~/Applications', require_sha: true  # 앱 설치 경로 및 보안 검증 설정

#############################################################
# 추가 저장소 (Taps)                                         #
#############################################################
tap 'homebrew/bundle'       # Brewfile 사용을 위한 번들 탭 추가
tap 'homebrew/core'         # Homebrew 기본 패키지 저장소
tap 'homebrew/services'     # macOS 서비스 관리 지원

#############################################################
# 안드로이드 개발 도구                                        #
#############################################################

# 개발 환경 및 SDK
cask 'android-studio'       # 안드로이드 앱 개발용 IDE
cask 'android-sdk'          # 안드로이드 SDK
brew 'gradle'               # 자바 빌드 자동화 도구
brew 'openjdk'              # 자바 개발 키트 (안드로이드 개발에 필수)

# 버전 관리 및 협업 도구
brew 'git'                  # 버전 관리 도구
cask 'sourcetree'           # Git GUI 클라이언트
brew 'gh'                   # GitHub CLI 도구
brew 'git-extras'           # 추가 Git 명령어 모음

# 터미널 및 쉘 환경
cask 'iterm2'               # 개선된 터미널 에뮬레이터
brew 'zsh'                  # 강력한 쉘 환경 (기본 bash 대체)
brew 'tmux'                 # 터미널 세션 다중화 도구
brew 'fzf'                  # 퍼지 검색 및 파일 탐색 도구
brew 'ripgrep'              # 빠른 파일 내 검색 도구
brew 'tldr'                 # 간단한 명령어 설명서
brew 'thefuck'              # 잘못 입력한 명령어 자동 수정 도구
cask 'raycast'              # 빠른 앱 실행 및 전역 검색 도구

# 안드로이드 디바이스 관리 및 디버깅 도구
brew 'scrcpy'               # 안드로이드 화면 미러링 및 제어 도구
brew 'watchman'             # 파일 변경 감지 및 핫리로드 지원
brew 'adb'                  # Android Debug Bridge (필수 디버깅 도구)

# API 및 네트워크 도구
cask 'postman'              # API 테스트 및 개발 도구
brew 'httpie'               # 간단한 HTTP 클라이언트 (API 테스트에 유용)

# 코드 편집 및 기타 편의 도구
cask 'visual-studio-code'   # 코드 편집기 (Android Studio 대체 또는 보완)
cask 'boop'                 # 텍스트 변환 도구 (빠른 데이터 처리에 유용)

#############################################################
# macOS 생산성 및 데스크톱 애플리케이션 추가                  #
#############################################################

# 개발 및 디자인 관련 도구
cask 'intellij-idea'        # 전문적인 Java 및 멀티랭귀지 IDE
cask 'figma'                # UI/UX 디자인 협업 도구
cask 'sublime-text'         # 가벼운 코드 및 텍스트 편집기

# 커뮤니케이션 및 작업 관리
mas 'Slack', id: 803453959  # 팀 커뮤니케이션 및 협업 도구
mas '카카오톡', id: 869223134 # 카카오톡 메신저 (팀 및 개인 커뮤니케이션)
cask 'notion'               # 메모 및 작업 관리 도구

# macOS 유틸리티 및 생산성 앱
mas '반디집', id: 1265704574 # 빠르고 가벼운 압축/해제 프로그램
cask 'alfred'               # 강력한 워크플로와 빠른 실행 도구
cask 'magnet'               # 창 정렬 및 분할 화면 기능 제공
mas 'Xcode', id: 497799835  # macOS 및 iOS 개발용 공식 IDE
cask 'google-chrome'        # 빠르고 안전한 웹 브라우저

#############################################################
# 선택적 추가 도구 (개발 및 개인 생산성 향상)                #
#############################################################
#brew 'node'                # Node.js (React Native나 하이브리드 앱 개발 시)
#brew 'python'              # 파이썬 스크립트 실행 및 자동화
#cask 'docker'              # 컨테이너 기반 개발 환경 구축 시 사용
#brew 'jq'                  # JSON 데이터 처리 도구 (API 응답 처리에 유용)

# EOF
