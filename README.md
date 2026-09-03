# 설대영어 단어퀴즈 GitHub 배포본 v6

최종 갱신: 2026-09-03

v6 핵심 수정:
- 결과화면 오답 단어의 '🔊 다시 듣기' 버튼을 학생이 누른 바로 그 탭 이벤트 안에서
  브라우저 SpeechSynthesis를 직접 호출하도록 전면 수정
- 기존 자동 재생용 TTS 함수와 분리하여 iPhone/Safari의 사용자 제스처 제한에 대응
- 결과 화면이 다시 그려져도 오답마다 다시 듣기 버튼을 자동 보완
- 수동 다시 듣기는 volume=1.0, en-US, rate=0.86
- v5의 답 제출 후 자동 발음, 영어→한글 자동 발음, 소리 확인 보강은 그대로 유지

GitHub 업로드:
- ZIP의 9개 폴더 + README.md를 기존 저장소에 덮어쓰기
- voca-highschool-essential 및 저장소 루트 index.html은 기존 것을 유지
