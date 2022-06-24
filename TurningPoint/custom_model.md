### tflite custom model 제작하는 방법
https://sapphire-carver-8ca.notion.site/custom-model-90eb8a84e1aa44c49846f40407bdc637

tflite model maker 사용하기
cache로 부터  데이터 로드

csv로 부터 데이터 로드

training data set을 csv로 만들기 위해서는 google cloud platform 에 AutoML Vision을 사용한다.
pascal_voc로 부터 데이터셋 로드

💡
이 영상에서는 이 방법을 채택
마이크로 컨트롤러를 감지하는 이미지 데이터셋 준비
labelImg 를 이용해 이미지 라벨링
xml → csv

10:03초

1) xml_to_csv.py를 실행해서 xml→csv로 변환
2) generate_tfcord.py에서 라벨이름 custom했던 라벨 이름으로 변환
3) lablemap file 만들기

4)config 파일 설정
→유튜브 더 참고
모델 메이커를 사용해 이미지 감지 모델 만들기
안드로이드 용으로 배포

flutter에 모델 적용
찾아봐야함
