`sleepdata.csv` 열 설명

|열 이름|data type|통계적 자료형|설명|
|------|----|----|----|
|sleep_date|date||수면 직전 날짜|
|sleep_minute|int|연속형|총 수면 시간(분)|
|snore_count|int|이산형|코골이 횟수|
|snore_minute|int|연속형|총 코골이 시간(분)|
|snore_minute_longest|int|연속형|가장 긴 코골이 시간(분)|
|weather|int|명목형|수면 직전 날씨(0: 맑음, 1: 비, 2: 눈, 3: 기타)
|vaseline_apply|int|명목형|바세린 바름 유무(0: 안바름, 1:바름)|
|pillow_high|int|순서형|베개 높이(0: 안벰, 1: 낮은 베개, 2: 중간 베개, 3: 높은 베개, 4: 중간 + 높은 베개, 5: 낮은 + 중간 + 높은 베개)|
|sleep_position|int|명목형|옆으로 누워잠 유무(0: 천장을 보고 잠, 1: 옆으로 누워 잠)|
|nose_stuff|int|명목형|코막힘 정도(0: 안막힘, 1: 약간 막힘, 2: 많이 막힘)|
|nose_dry|int|명목형|코 건조함 정도(0: 안 건조함, 1: 약간 건조함, 2: 많이 건조함)|
|first_snore|int|연속형|잠들고 첫 번째 코골이까지의 시간(분)|
|other|text||기타 특이사항|
