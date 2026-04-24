# Experiment Log

- v0: family mean baseline 제출 성공
- EDA: train/test 기간, 키(date, store, family) 유니크 확인
- Sales: 0 비율 31.3%, heavy-tail → log1p 타당
- Promo: onpromotion ↔ sales 신호 확인(corr 0.428)
- Oil: 주말 누락 진단 → oil_daily ffill/bfill로 커버리지 1.0
- Tx: 결측이 특정 store/날짜에 집중됨 진단
- (WIP) expected_transactions backtest (cell 11)
