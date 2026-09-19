# minecraft-friends-resourcepack

마인크래프트 자바 26.3 친구 서버용 리소스팩.

- 최신 배포 파일: `friends-guns-v7.zip` (부품 37개 M4 스타일 소총, 면별 음영 텍스처, 레드닷 정조준 모델, 총기 사운드)
- SHA1: `4ce6268e87597a688e1989df2adc986b1593da62`
- 원본 소스: `source/`

## 26.3에서 걸렸던 함정

1. `pack.mcmeta`에 `min_format`, `max_format`이 없으면 팩 전체가 무시된다.
2. 모델 UV는 텍스처 픽셀이 아니라 항상 0~16 기준이다. 64px 텍스처면 픽셀 좌표를 4로 나눠서 적는다. 범위를 넘으면 모델 굽기가 실패하고 체크무늬가 뜬다.

## 사운드 출처

- 총성: Universfield (Pixabay)
- 장전: freesound community
- 빈총, 명중음: 자체 합성
