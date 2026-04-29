# my-ai-skills

Gemini CLI 스킬 포트폴리오 저장소입니다. B2B 비즈니스 인사이트 및 기술 전문성을 강화하는 다양한 스킬들을 관리합니다.

## 🛠️ 스킬 목록

### 1. [b2b-insight-curator](./skills/b2b-insight-curator)
- **설명**: IT/AI 트렌드 자료를 분석하여 B2B 실무자를 위한 SEO 최적화 블로그 아티클로 변환합니다.
- **설치**:
  ```bash
  gemini skills install dist/b2b-insight-curator.skill --scope workspace
  ```

## 🚀 관리 전략
- `skills/`: 스킬 소스 코드 보관
- `dist/`: 패키징된 `.skill` 배포 파일 보관
- 명명 규칙: `hyphen-case` 준수

## 📥 설치 방법
1. 저장소를 클론합니다.
2. `dist/` 폴더의 원하는 스킬을 `gemini skills install` 명령어로 설치합니다.
3. `/skills reload` 명령어로 스킬을 활성화합니다.
