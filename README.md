## 읽기 전에
- 필수 매개 변수는 [매개변수]로, 선택 매개 변수는 {매개변수}로 표시해요.

# 기본 명령어

## !help
- **설명**: 모든 명령어와 그 사용법을 표시합니다.
- **사용법**: `!help`

## !ping
- **설명**: 봇이 응답합니다. pong!
- **사용법**: `!ping`

## !follow
- **설명**: 자신의 팔로우 기간을 표시합니다.
- **사용법**: `!follow`
- **aliases**: `!팔로우`

# 출석 체크 명령어

## !checkin
- **설명**: 출석 체크를 합니다.
- **사용법**: `!checkin`
- **aliases**: `!출첵`, `!출석`, `!체크인`
- **비고**: 자정을 기준으로 초기화됩니다. 연속으로 출석하면 더 많은 포인트를 얻습니다. ( 1연속당 150 )

## !checkininfo
- **설명**: 자신의 출석 정보를 출력합니다. 현재 연속 출석일과 총합 출석일을 출력합니다.
- **사용법**: `!checkininfo`
- **aliases**: `!체크인정보`

# 포인트 관련 명령어

## !point
- **설명**: 자신의 보유 포인트를 출력합니다.
- **사용법**: `!point`
- **aliases**: `!포인트`
- **비고**: 여러가지 기능에 사용 할 수 있는 포인트입니다.

## !give
- **설명**: 대상 유저에게 포인트를 지급합니다. (뺏을수도 있어요)
- **사용법**: `!give [nickname] [수량]`
- **비고**: 수량에 마이너스를 입력하면 뺏을 수 있습니다.
- **제한**: 매니저 이상부터 사용 가능한 명령어입니다.

# 가챠 관련 명령어

## !gacha
- **설명**: 닉네임 왼쪽에 붙일 수 있는 뱃지의 조각을 뽑습니다.
- **사용법**: `!gacha {횟수(1~10)}`
- **aliases**: `!가챠`
- **비고**: 10종류의 조각을 모두 뽑으면 그 등급의 뱃지를 획득합니다.
- **cost**: Bronze 100, Silver 250, Gold 500, Platinum 1000
- **제한**: Platinum 등급의 뱃지를 완성하면 더 이상 가챠가 불가능합니다.

## !badge
- **설명**: 자신이 보유한 뱃지들을 출력합니다.
- **사용법**: `!badge`
- **aliases**: `!배지`, `!뱃지`

## !piece
- **설명**: 자신이 도전중인 뱃지의 조각 현황을 출력합니다.
- **사용법**: `!piece`
- **aliases**: `!조각`
- **제한**: Platinum 등급의 뱃지를 완성하면 더 이상 조각 현황을 볼 수 없습니다.

# 노래 신청 관련 명령어

## !songrequest
- **설명**: 틀고싶은 노래를 재생 할 수 있습니다.
- **사용법**: `!songrequest [링크/검색어]`
- **aliases**: `!sr`
- **cost**: 50

## !currentsong
- **설명**: 현재 재생중인 노래의 정보를 출력합니다.
- **사용법**: `!currentsong`
- **aliases**: `!cs`

## !songlist
- **설명**: 큐에 대기중인 노래의 목록과 길이를 출력합니다.
- **사용법**: `!songlist {큐 번호}`
- **aliases**: `!sl`
- **비고**: 매개변수를 입력하지 않으면 큐의 길이를, 특정 번호를 입력하면 그 큐에 대기중인 노래의 정보를 출력합니다.

## !songskip
- **설명**: 현재 재생중인 노래를 스킵합니다.
- **사용법**: `!songskip`
- **제한**: 매니저 이상부터 사용 가능한 명령어입니다.

# 닉네임 색깔 변경 명령어

## !color
- **설명**: 화면 채팅창에 보이는 자신의 닉네임 색깔을 변경합니다.
- **사용법**: `!color [r] [g] [b]`
- **비고**: rgb값을 직접 입력 할 수 있습니다.
- **cost**: 5000

# 명령어 추가 (매니저 전용)

## !addcommand
- **설명**: 새 단순 출력 명령어를 추가 할 수 있습니다.
- **사용법**: `!addcommand [명령어] [출력]`
- **aliases**: `!addcom [명령어] [출력]`
- **제한**: 매니저 이상부터 사용 가능한 명령어입니다.

## !removecommand
- **설명**: addcommand 명령어로 추가한 명령어를 삭제 할 수 있습니다.
- **사용법**: `!removecommand [기존명령어]`
- **aliases**: `!removecom [기존명령어]`, `!delcom [기존명령어]`
- **제한**: 매니저 이상부터 사용 가능한 명령어입니다.
