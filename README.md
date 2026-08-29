# shopping-listapp

**같이 쓰는 메모장** — 여러 사람이 함께 보고 쓰는 실시간 체크리스트 앱입니다.

## 기능

- 항목 추가 / 체크 / 삭제
- 드래그 핸들로 항목 순서 변경
- 체크된 항목 일괄 삭제
- 완료율을 보여주는 진행률 바
- Supabase 데이터베이스와 연동되어 모든 방문자가 같은 목록을 실시간으로 공유
- 라이트/다크 모드 자동 대응

## 기술 스택

- HTML / CSS / JavaScript (별도 빌드 없는 단일 파일 `index.html`)
- [Supabase](https://supabase.com) (`shopping_items` 테이블) — 데이터 저장 및 실시간 동기화
- [Vercel](https://vercel.com) — 배포

## 실행 방법

`index.html`을 정적 파일로 서빙하면 됩니다. 예:

```bash
python -m http.server 8000
```

이후 브라우저에서 `http://localhost:8000/index.html` 접속.
