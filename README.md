# 도착 — 공통 레포 (`pr-obably-fine/.github`)

도착 팀의 기능 단위 큰 이슈와 조직 공통 규칙·템플릿을 두는 곳이에요. 이 레포 이름이 `.github`라서 여기 있는 `CONTRIBUTING.md`와 `.github/pull_request_template.md`는 자기 파일이 없는 모든 레포에 자동으로 적용돼요.

## 처음 왔다면

1. [CONTRIBUTING.md](./CONTRIBUTING.md)에서 브랜치·커밋·이슈·PR 규칙을 읽어요.
2. [로드맵](https://github.com/orgs/pr-obably-fine/projects/1)에서 내 이슈의 시작일·마감일을 확인해요.
3. 이슈 번호로 브랜치를 만들어 작업하고, PR 본문에 `Closes #번호`를 적어요.

## 저장소

| 저장소 | 접두어 | 담는 것 |
| --- | --- | --- |
| [.github](https://github.com/pr-obably-fine/.github) | — | 기능 단위 큰 이슈, 공통 규칙·템플릿 |
| [frontend](https://github.com/pr-obably-fine/frontend) | `FE` | 웹 화면 |
| [backend](https://github.com/pr-obably-fine/backend) | `BE` | Spring API |
| [infra](https://github.com/pr-obably-fine/infra) | `INF` | 서버·도메인·S3·KMS·SES·모니터링·배포 |

큰 이슈는 이 레포에, 실제 작업은 각 저장소의 서브 이슈로 나눠요. 큰 이슈의 책임자가 서브 이슈까지 맡아요.

## 팀

| 이름 | GitHub | 맡은 영역 |
| --- | --- | --- |
| 카일 | [@euijin1212](https://github.com/euijin1212) | 백엔드·인프라 |
| 소니 | [@soyuniii](https://github.com/soyuniii) | 프론트엔드 |
| 커비 | [@tomchaccom](https://github.com/tomchaccom) | 백엔드·인프라·프론트 |
| 우찬 | [@YuChanSong321](https://github.com/YuChanSong321) | 풀스택 |

리뷰 고리: 커비 → 우찬 → 카일 → 소니 → 커비 ("리뷰한다" 방향)

## 일정

- 스프린트: 11/26(목) ~ 12/4(금). 12/4에 처음부터 끝까지 시연해요.
- 작업 하나는 2~3일 안에 끝내요. 선행 작업이 있으면 그 작업의 마감 날부터 겹쳐 시작해요.
- 마감은 날짜별 마일스톤(`11/27 마감` 등)과 이슈의 Start date·Target date로 관리해요.

## 공통 규칙 파일

| 파일 | 내용 |
| --- | --- |
| [CONTRIBUTING.md](./CONTRIBUTING.md) | 브랜치·커밋·이슈·PR 컨벤션 |
| [.github/pull_request_template.md](./.github/pull_request_template.md) | PR 템플릿 |

규칙을 바꾸고 싶으면 이 레포에 PR을 올려요.
