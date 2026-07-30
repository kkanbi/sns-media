# sns-media

SNS 업로드용 이미지·영상 호스팅 저장소.

인스타그램/쓰레드 API는 로컬 파일을 직접 받지 않고 **공개 HTTPS URL**만 받는다.
그래서 발행 직전에 이 저장소로 파일을 올려 URL을 만들고, 그 URL로 발행한다.

- 발행 스크립트: `gabi_plan_control/_system/scripts/sns_publish.py`
- 업로드 경로: `uploads/YYYY-MM-DD_<슬러그>/01.jpg ...`

## 주의

이 저장소는 **공개**다. 발행할 콘텐츠만 넣는다.
개인 기록·초안·메모는 절대 넣지 않는다 (그건 비공개 볼트에 있다).
