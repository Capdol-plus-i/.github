# DYNAMIXEL XL330, XL430, STS3215, ST-3215-C018 서보 모터 상세 비교

5종류의 모터(XL330-M077-T, XL330-M288-T, XL430-W250-T, STS3215, ST-3215-C018)를 동일한 기준으로 자세히 비교해드리겠습니다.

## 1. 물리적 특성

| 특성 | XL330-M077-T | XL330-M288-T | XL430-W250-T | STS3215 | ST-3215-C018 |
|------|--------------|--------------|--------------|---------|---------------|
| 크기(mm) | 20×34×26 | 20×34×26 | 28.5×46.5×34.0 | 45.2×24.7×35 | 45.2×24.7×35 |
| 무게(g) | 18 | 18 | 57 | 55 | 55 ± 1 |
| 케이스 소재 | 엔지니어링 플라스틱 | 엔지니어링 플라스틱 | 엔지니어링 플라스틱 | 플라스틱 | PA+GF(플라스틱) |
| 기어 소재 | 엔지니어링 플라스틱 | 엔지니어링 플라스틱 | 엔지니어링 플라스틱 | 금속(구리) | 구리(Copper) |
| 기어 유형 | 스퍼 기어 | 스퍼 기어 | 스퍼 기어 | 구리 기어 | 구리 기어 |
| 축 베어링 | 명시되지 않음 | 명시되지 않음 | 명시되지 않음 | 볼 베어링 | 볼 베어링 |
| 모터 유형 | 코어드 모터 | 코어드 모터 | 코어드 모터 | 코어리스 모터 | 코어 모터 |
| 출력축 | 명시되지 않음 | 명시되지 않음 | 명시되지 않음 | 25T | 25T/OD5.9mm |
| 이중축 지원 | 명시되지 않음 | 명시되지 않음 | 명시되지 않음 | 지원 (듀얼 축) | 지원 (듀얼 축) |

## 2. 전기적 특성

| 특성 | XL330-M077-T | XL330-M288-T | XL430-W250-T | STS3215 | ST-3215-C018 |
|------|--------------|--------------|--------------|---------|---------------|
| 작동 전압 범위 | 3.7-6.0V | 3.7-6.0V | 6.5-12.0V | 6.0-7.4V | 4.0-14.0V |
| 권장 전압 | 5.0V | 5.0V | 11.1V | 7.4V | 12.0V |
| MCU | ARM Cortex-M0+ (64MHz, 32bit) | ARM Cortex-M0+ (64MHz, 32bit) | ARM Cortex-M3 (72MHz, 32bit) | Feetech 개발 TTL 제어 보드 | Feetech 개발 TTL 제어 보드 |
| 대기 전류 | 15mA | 15mA | 52mA | 명시되지 않음 | 30mA |
| 무부하 전류 | 0.15A @5.0V | 0.15A @5.0V | 0.15A @12.0V | 0.15A @6.0V | 0.18A @12.0V |
| 정지 전류 | 1.5A @5.0V | 1.5A @5.0V | 1.4A @12.0V | 2.0A @6.0V | 2.7A @12.0V |
| 정격 전류 | 명시되지 않음 | 명시되지 않음 | 명시되지 않음 | 명시되지 않음 | 0.9A |
| 모터 내부저항 | 명시되지 않음 | 명시되지 않음 | 명시되지 않음 | 명시되지 않음 | 1.0Ω |

## 3. 성능 특성

| 특성 | XL330-M077-T | XL330-M288-T | XL430-W250-T | STS3215 | ST-3215-C018 |
|------|--------------|--------------|--------------|---------|---------------|
| 정지 토크 | 0.22N·m ≈ 2.2kg·cm @5.0V | 0.52N·m ≈ 5.3kg·cm @5.0V | 1.5N·m ≈ 15.3kg·cm @12.0V | 19.5kg·cm @6.0V | 30kg·cm @12.0V |
| 정격 토크 | 명시되지 않음 | 명시되지 않음 | 명시되지 않음 | 6.5kg·cm @6.0V | 10kg·cm |
| 기어비 | 77.5:1 | 288.4:1 | 258.5:1 | 명시되지 않음 | 1/345 (345:1) |
| 무부하 속도 | 363.0rpm ≈ 0.165sec/60° @5.0V | 104.0rpm ≈ 0.577sec/60° @5.0V | 61.0rpm ≈ 0.984sec/60° @12.0V | 0.238sec/60° @6.0V ≈ 252.1rpm | 0.222sec/60° @12.0V ≈ 45.0rpm |
| 백래시 | 명시되지 않음 | 명시되지 않음 | 명시되지 않음 | 명시되지 않음 | ≤0.5° |
| 작동 온도 | -5°C ~ 70°C | -5°C ~ 70°C | -5°C ~ 72°C | -20°C ~ 70°C | -10°C ~ 60°C |
| 보관 온도 | 명시되지 않음 | 명시되지 않음 | 명시되지 않음 | -30°C ~ 80°C | -30°C ~ 80°C |
| 출력(W) | 명시되지 않음 | 명시되지 않음 | 명시되지 않음 | 명시되지 않음 | 명시되지 않음 |
| 토크 상수(Kt) | 명시되지 않음 | 명시되지 않음 | 명시되지 않음 | 명시되지 않음 | 11kg·cm/A |

## 4. 제어 및 통신

| 특성 | XL330-M077-T | XL330-M288-T | XL430-W250-T | STS3215 | ST-3215-C018 |
|------|--------------|--------------|--------------|---------|---------------|
| 통신 프로토콜 | 프로토콜 2.0, S.BUS, iBUS, RC-PWM | 프로토콜 2.0, S.BUS, iBUS, RC-PWM | 프로토콜 1.0, 프로토콜 2.0(기본) | 디지털 패킷 | 디지털 패킷 |
| 통신 유형 | 반이중 비동기 직렬 통신(8bit, 1stop, No Parity) | 반이중 비동기 직렬 통신(8bit, 1stop, No Parity) | 반이중 비동기 직렬 통신(8bit, 1stop, No Parity) | 반이중 비동기 직렬 통신 | 반이중 비동기 직렬 통신(8bit, 1stop, No Parity) |
| 물리적 링크 | TTL 레벨 멀티드롭 버스 | TTL 레벨 멀티드롭 버스 | TTL 레벨 멀티드롭 버스 | TTL | TTL |
| 통신 속도 | 9,600 ~ 4,000,000bps | 9,600 ~ 4,000,000bps | 9,600 ~ 4,500,000bps | 38,400 ~ 1,000,000bps | 38,400 ~ 1,000,000bps |
| ID 범위 | 0 ~ 252 | 0 ~ 252 | 0 ~ 252 | 0 ~ 253 | 0 ~ 253 |
| 제어 알고리즘 | PID | PID | PID | 명시되지 않음 | PID |
| 피드백 정보 | 위치, 속도, 전류, 실시간 틱, 궤적, 온도, 입력 전압 등 | 위치, 속도, 전류, 실시간 틱, 궤적, 온도, 입력 전압 등 | 위치, 속도, 부하, 실시간 틱, 궤적, 온도, 입력 전압 등 | 부하, 위치, 속도, 입력 전압, 전류, 온도 | 부하, 위치, 속도, 입력 전압, 전류, 온도 |
| 선 길이 | 명시되지 않음 | 명시되지 않음 | 명시되지 않음 | 150mm ± 5mm | 150mm |
| 커넥터 유형 | 명시되지 않음 | 명시되지 않음 | 명시되지 않음 | 명시되지 않음 | 5264-3P |

## 5. 작동 모드 및 분해능

| 특성 | XL330-M077-T | XL330-M288-T | XL430-W250-T | STS3215 | ST-3215-C018 |
|------|--------------|--------------|--------------|---------|---------------|
| 위치 센서 | 컨택리스 앱솔루트 엔코더(12Bit, 360°)<br>AS5601 | 컨택리스 앱솔루트 엔코더(12Bit, 360°)<br>AS5601 | 컨택리스 앱솔루트 엔코더(12Bit, 360°)<br>AS5045 | 12비트 고정밀도 자기 인코딩 센서 | 12비트 자기 인코딩 센서 |
| 분해능 | 0.0879°/펄스, 4,096펄스/회전 | 0.0879°/펄스, 4,096펄스/회전 | 0.0879°/펄스, 4,096펄스/회전 | 0~4096 펄스/회전 (360°) | 0.088°/펄스, 0~4095 펄스/회전 |
| 작동 모드 | - 전류 제어 모드: 무한 회전<br>- 속도 제어 모드: 무한 회전<br>- 위치 제어 모드: 360°<br>- 확장 위치 제어 모드: ±256회전<br>- 전류 기반 위치 제어 모드: ±256회전<br>- PWM 제어 모드: 무한 회전 | - 전류 제어 모드: 무한 회전<br>- 속도 제어 모드: 무한 회전<br>- 위치 제어 모드: 360°<br>- 확장 위치 제어 모드: ±256회전<br>- 전류 기반 위치 제어 모드: ±256회전<br>- PWM 제어 모드: 무한 회전 | - 속도 제어 모드: 무한 회전<br>- 위치 제어 모드: 360°<br>- 확장 위치 제어 모드: ±256회전<br>- PWM 제어 모드: 무한 회전 | - 360° 각도 제어<br>- 다중회전 연속 작동<br>- 스텝 모드<br>- 원키 중앙점 설정 기능<br>- 가/감속 슬로우 시작 및 정지 | - 모드0: 각도 서보 모드(0-360°)<br>- 모드1: 속도 폐루프 모터 모드<br>- 모드2: 속도 개루프 모터 모드<br>- 모드3: 스텝 모드<br>- 다중 루프 모드(±7회전)<br>- 원키 중위 설정 기능 |
| 기계적 각도 제한 | 명시되지 않음 | 명시되지 않음 | 명시되지 않음 | 제한 없음 | 제한 없음 |
| 중위(중립) 위치 | 명시되지 않음 | 명시되지 않음 | 명시되지 않음 | 명시되지 않음 | 180° (2047) |

## 6. 특수 기능 및 보호

| 특성 | XL330-M077-T | XL330-M288-T | XL430-W250-T | STS3215 | ST-3215-C018 |
|------|--------------|--------------|--------------|---------|---------------|
| 과부하 보호 | 명시되지 않음 | 명시되지 않음 | 명시되지 않음 | 지원 | 지원 (80% 부하 2초 지속 시) |
| 과전류 보호 | 명시되지 않음 | 명시되지 않음 | 명시되지 않음 | 지원 | 지원 (2A 초과 2초 지속 시) |
| 과전압/저전압 보호 | 명시되지 않음 | 명시되지 않음 | 명시되지 않음 | 지원 | 지원 (14V 초과 또는 4V 미만) |
| 과열 보호 | 명시되지 않음 | 명시되지 않음 | 명시되지 않음 | 지원 | 지원 (70°C 초과) |
| 가속/감속 제어 | 명시되지 않음 | 명시되지 않음 | 명시되지 않음 | 슬로우 시작/정지 지원 | 명시되지 않음 |
| 원키 중앙점 설정 | 명시되지 않음 | 명시되지 않음 | 명시되지 않음 | 지원 | 지원 (40번 주소에 128 입력) |
| 수명 테스트 | 명시되지 않음 | 명시되지 않음 | 명시되지 않음 | 명시되지 않음 | >100,000회 |
| 모터 소음 | 명시되지 않음 | 명시되지 않음 | 명시되지 않음 | 명시되지 않음 | 45±5dB |
| 방수 기능 | 명시되지 않음 | 명시되지 않음 | 명시되지 않음 | 명시되지 않음 | 지원하지 않음 |

## 7. 응용 분야 적합성

| 응용 분야 | XL330-M077-T | XL330-M288-T | XL430-W250-T | STS3215 | ST-3215-C018 |
|-----------|--------------|--------------|--------------|---------|---------------|
| 소형 로봇 관절 | 매우 높음 (가장 경량, 고속) | 높음 (경량, 중간 토크) | 중간 (무게 중간) | 중간 (무게가 무거움) | 중간 (무게가 무거움) |
| 중형 로봇 관절 | 낮음 (토크 부족) | 중간 | 높음 (높은 토크) | 높음 (높은 토크) | 매우 높음 (가장 높은 토크) |
| 그리퍼/집게 | 낮음 (토크 부족) | 중간 | 높음 (높은 토크) | 매우 높음 (높은 토크) | 매우 높음 (가장 높은 토크) |
| 정밀 제어 | 높음 | 높음 | 높음 | 높음 | 높음 |
| 산업용 장비 | 낮음 (토크 부족) | 중간 | 높음 (높은 토크) | 매우 높음 (고토크, 금속 기어) | 매우 높음 (최고 토크, 금속 기어) |
| 고속 애플리케이션 | 매우 높음 (가장 빠름) | 중간 | 낮음 | 높음 (두 번째로 빠름) | 매우 낮음 (가장 느림) |
| 배터리 효율성 | 매우 높음 (최저 전압, 최저 대기전류) | 매우 높음 (최저 전압, 최저 대기전류) | 낮음 (높은 전압, 높은 대기전류) | 중간 (중간 전압) | 중간 (넓은 전압 범위) |
| 연속 회전 애플리케이션 | 지원 | 지원 | 지원 | 지원 | 지원 |
| 내구성 요구 애플리케이션 | 중간 (플라스틱 기어) | 중간 (플라스틱 기어) | 중간 (플라스틱 기어) | 높음 (금속 기어) | 높음 (금속 기어, 내구성 테스트 통과) |
| 넓은 온도 범위 | 중간 | 중간 | 중간 | 높음 | 중간 |

## 8. 토크-속도 비교 (성능 비)

| 모델 | 정지 토크 | 무부하 속도 | 토크/속도 비율 | 전력 효율 (토크/전압) |
|------|-----------|-------------|----------------|----------------------|
| XL330-M077-T | 2.2kg·cm @5.0V | 363.0rpm | 0.006kg·cm/rpm | 0.44kg·cm/V |
| XL330-M288-T | 5.3kg·cm @5.0V | 104.0rpm | 0.051kg·cm/rpm | 1.06kg·cm/V |
| XL430-W250-T | 15.3kg·cm @12.0V | 61.0rpm | 0.251kg·cm/rpm | 1.28kg·cm/V |
| STS3215 | 19.5kg·cm @6.0V | 252.1rpm | 0.077kg·cm/rpm | 3.25kg·cm/V |
| ST-3215-C018 | 30.0kg·cm @12.0V | 45.0rpm | 0.667kg·cm/rpm | 2.50kg·cm/V |

## 9. 종합 비교 및 선택 가이드

### XL330-M077-T
- **강점**: 가장 경량, 가장 빠른 속도, 최소 전력 소비
- **약점**: 가장 낮은 토크, 플라스틱 기어
- **최적 용도**: 고속 요구, 경량화가 중요한 소형 로봇, 저전력 애플리케이션

### XL330-M288-T
- **강점**: 경량, 중간 토크, 낮은 전력 소비
- **약점**: 플라스틱 기어, 중간 속도
- **최적 용도**: 중간 토크와 중간 속도가 필요한 균형 잡힌 애플리케이션, 배터리 지속시간이 중요한 경우

### XL430-W250-T
- **강점**: 높은 토크, DYNAMIXEL 계열의 호환성
- **약점**: 느린 속도, 높은 작동 전압, 높은 대기 전류
- **최적 용도**: 고토크가 필요하지만 속도가 덜 중요한 중형 로봇 관절, 전력 공급이 안정적인 환경

### STS3215
- **강점**: 높은 토크, 금속 기어, 빠른 속도, 특수 기능(슬로우 시작/정지, 과부하 보호)
- **약점**: 더 큰 크기, 무거운 무게
- **최적 용도**: 산업용 장비, 높은 토크와 내구성이 필요한 응용 분야, 가혹한 환경 조건

### ST-3215-C018
- **강점**: 가장 높은 토크(30kg·cm), 금속 기어, 포괄적인 보호 기능, 넓은 전압 범위(4-14V)
- **약점**: 가장 느린 속도, 큰 크기, 무거운 무게
- **최적 용도**: 최고 토크가 필요한 산업용 장비 및 로봇, 내구성과 안정성이 중요한 응용 분야

## 10. 결론

- **가장 경량 모델**: XL330 시리즈 (각 18g)
- **가장 높은 토크**: ST-3215-C018 (30kg·cm @12V)
- **가장 빠른 속도**: XL330-M077-T (363rpm)
- **가장 넓은 전압 범위**: ST-3215-C018 (4-14V)
- **가장 높은 토크/속도 비율**: ST-3215-C018 (0.667kg·cm/rpm)
- **가장 높은 전력 효율**: STS3215 (3.25kg·cm/V)
- **가장 포괄적인 보호 기능**: ST-3215-C018 및 STS3215
- **가장 내구성 있는 구조**: ST-3215-C018 및 STS3215 (금속 기어, 볼 베어링)
