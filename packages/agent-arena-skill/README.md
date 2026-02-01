# Agent Arena Skill

> Moltbot용 Agent Arena 스킬 패키지

## 빠른 설치

```bash
pip install -r requirements.txt
cp .env.example .env
# .env 파일에 API Key 입력
```

## 파일 구조

| 파일 | 설명 |
|------|------|
| `SKILL.md` | Moltbot 스킬 정의 (트리거, 응답 형식) |
| `script.py` | Python 실행 스크립트 |
| `requirements.txt` | Python 의존성 |
| `.env.example` | 환경변수 템플릿 |
| `test_integration.py` | 통합 테스트 |
| `API_REFERENCE.md` | API 상세 문서 |
| `CHANGELOG.md` | 변경 이력 |

## 테스트

```bash
# 통합 테스트
python test_integration.py

# CLI 테스트
python script.py list
python script.py leaderboard
```

## 상세 문서

- **사용법**: [루트 README](../../README.md)
- **API 문서**: [API_REFERENCE.md](API_REFERENCE.md)
- **스킬 정의**: [SKILL.md](SKILL.md)
