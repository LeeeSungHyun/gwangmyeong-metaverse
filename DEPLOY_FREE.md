# 무료 배포 안내

## 구성
- 프런트엔드: Cloudflare Pages Free
- 실시간 아바타/채팅: Supabase Realtime Free
- 소스: GitHub `main`

## Cloudflare Pages 설정
- Framework preset: Vite
- Build command: `npm run build`
- Build output directory: `dist`
- Root directory: `/`
- Environment variables: `VITE_SUPABASE_URL`, `VITE_SUPABASE_ANON_KEY`

## Supabase 설정
1. Supabase에서 Free 프로젝트를 생성합니다.
2. Project URL과 publishable/anon public key를 복사합니다.
3. Cloudflare Pages 프로젝트의 Settings > Variables and Secrets > Production에 위 두 변수를 추가합니다.
4. 재배포합니다.

이 앱은 Supabase 변수가 없으면 개인 체험 모드로 실행됩니다. 실시간 공동 접속을 쓰려면 Supabase 값이 필요합니다.

## 비용 주의
Cloudflare Pages Free와 Supabase Free 범위 내에서 사용합니다. 유료 플랜 전환, 유료 리소스 추가, 사용량 초과 과금이 발생하는 설정은 하지 않습니다. Supabase Free 프로젝트는 일정 기간 비활성 시 일시 중지될 수 있으며, 무료 사용량 한도는 서비스 정책에 따릅니다.
