# 봇 명령어 description서

이 문서는 봇에서 사용할 수 있는 모든 명령어와 그 사용 방법을 설명합니다.

## 기본 명령어

### !ping
- **description**: 봇이 응답하는지 확인합니다.
- **Example**: `!ping`
- **Response**: `🏓 pong!`

### !팔로우
- **description**: 사용자가 팔로우한 기간을 확인합니다.
- **Example**: `!팔로우`
- **response**: `⏳ 팔로우한지 X일 Y시간 Z분 W초 지났습니다.` (팔로우한 경우)

### !투네
- **description**: 후원 링크를 제공합니다.
- **Example**: `!투네`
- **response**: `🎁 https://toon.at/donate/nya_an`

### !명령어
- **description**: 준비 중인 명령어임을 알립니다.
- **Example**: `!명령어`
- **response**: `🛠️ 준비 중`

### 냐하
- **description**: 인사말입니다.
- **Example**: `냐하`
- **response**: `🖐️ 냐하로`

### !냐하
- **description**: 인사말에 대한 response입니다.
- **Example**: `!냐하`
- **response**: `🖐️ 니에`

### !케이온
- **description**: 애니메이션 '케이온'에 대한 response입니다.
- **Example**: `!케이온`
- **response**: `🎵 명작입니다`

## 출석 관련 명령어

### !출석, !출첵
- **description**: 출석체크를 합니다.
- **Example**: `!출석` 또는 `!출첵`
- **response**: `🔥 [사용자명], +X 포인트! (연속 출석: Y일)`

### !포인트
- **description**: 현재 보유한 포인트를 확인합니다.
- **Example**: `!포인트`
- **response**: `💰 [사용자명]님의 현재 포인트는 'X'에요.`

### !체크인정보
- **description**: 연속 체크인 및 누적 체크인 정보를 확인합니다.
- **Example**: `!체크인정보`
- **response**: `🔥 [사용자명]님의 연속 체크인: X일, 누적 체크인: Y일`

## 포인트 관련 명령어

### !give [숫자] [닉네임]
- **description**: 특정 사용자에게 포인트를 줍니다. (스트리머 또는 채팅 매니저만 사용 가능)
- **Example**: `!give 100 냐안님`
- **response**: `💸 [발신자]님이 [수신자]님에게 '100' 포인트를 주셨어요.`

## 배팅 관련 명령어

### !betstart [배팅시간(분)] [옵션1] [옵션2] ...
- **description**: 배팅을 시작합니다. (스트리머 또는 채팅 매니저만 사용 가능)
- **Example**: `!betstart 10 승리 패배 무승부`
- **response**: `🏁 배팅 시작! 옵션: 승리, 패배, 무승부`

### !bet [금액] [옵션]
- **description**: 특정 옵션에 포인트를 배팅합니다.
- **Example**: `!bet 100 승리`
- **response**: `💰 [사용자명]님이 '100' 포인트를 [승리]에 배팅했습니다.`

### !betcurrent
- **description**: 현재 배팅 상태를 보여줍니다.
- **Example**: `!betcurrent`
- **response**: 현재 배팅 상태와 각 옵션에 배팅된 포인트 및 배당률을 보여줍니다.

### !betclose
- **description**: 배팅을 종료합니다. (스트리머 또는 채팅 매니저만 사용 가능)
- **Example**: `!betclose`
- **response**: `⏰ 배팅이 종료되었습니다. 결과를 기다려주세요.`

### !betcancel
- **description**: 배팅을 취소하고 배팅한 포인트를 반환합니다. (스트리머 또는 채팅 매니저만 사용 가능)
- **Example**: `!betcancel`
- **response**: `🚫 배팅이 취소되었습니다. 배팅한 금액이 반환되었습니다.`

### !betpay [옵션]
- **description**: 특정 옵션에 배팅한 사용자에게 포인트를 지급합니다. (스트리머 또는 채팅 매니저만 사용 가능)
- **Example**: `!betpay 승리`
- **response**: `🎉 [승리] 옵션에 배팅한 사용자에게 포인트가 지급되었습니다.`

## 노래 관련 명령어

### !sr [링크/검색어]
- **description**: 포인트를 소모하여 유튜브 동영상을 재생 목록에 추가합니다.
- **Example**: `!sr https://www.youtube.com/watch?v=TgOAdwmfkhA`
- **response**: `🔎 [사용자명]님의 요청으로 '[검색어]'를 재생 목록에 추가했습니다.`

### !sl, !songlist
- **description**: 재생 목록에 있는 노래의 개수를 확인합니다.
- **Example**: `!sl` 또는 `!songlist`
- **response**: `📜 재생 목록에 X개의 노래가 있습니다.`

### !songlist [인덱스]
- **description**: 특정 인덱스에 있는 노래의 정보를 확인합니다.
- **Example**: `!songlist 1`
- **response**: `📀 [1] [검색어] (요청자: [사용자명])`

### !cs, !currentsong
- **description**: 현재 재생 중인 노래의 정보를 확인합니다.
- **Example**: `!cs` 또는 `!currentsong`
- **response**: `🎵 현재 재생 중: [검색어] (요청자: [사용자명])`
