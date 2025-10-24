# Legged RL Sim2Real — Minimal Reproduction Plan

목표: 4주 내 CartPole/Pendulum PPO·SAC 재현 → LeggedGym 평지 보행 실행, 
이후 도메인 랜덤화 및 빠른 적응(RMA)으로 강건성 향상.  
**재현성 원칙:** `bash scripts/run.sh` 1커맨드로 로깅/그래프/데모 생성(일정: <YYYY-MM-DD> 업데이트).

## 진행 현황 (체크리스트)
- [ ] 주차별 환경 세팅 완료
- [ ] CartPole PPO 학습곡선 저장
- [ ] Pendulum SAC 학습곡선 저장
- [ ] LeggedGym 평지 보행 데모(30초)
- [ ] 도메인 랜덤화(마찰/질량) 전후 비교표

## 디렉토리
```
scripts/   # 재현 스크립트 (run.sh)
videos/    # 30초 데모
logs/      # 학습 로그(그래프/테이블)
docs/      # CV, 4주 계획 등 문서
```

## 빠른 시작 (예정)
```
bash scripts/run.sh
```
> 최초에는 자리표시자(placeholder)만 포함됩니다. 학습 코드 연결은 1주차 말 업데이트.