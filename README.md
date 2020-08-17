# 2020AIChallenge_Solution
2020년 nipa에서 개최한 AI 챌린지 수상 코드를 올려놓은 레포(상금 1.6억원)

<h2>[과제 03] 얼굴 다각도 인식 및 조회 모델 개발</h2>
![16th_prob](/img/16th_prob.png)
<ul>
  <li><strong>주제</strong></li>
    얼굴 다각도 인식 및 조회 모델 개발
    측면 얼굴 이미지로 정면 얼굴 동일인 조회
  <li><strong>배경</strong></li>
    대부분의 얼굴인식 테스트는 얼굴이 잘 나온 데이터들을 대상으로 이뤄지기 때문에 인식률이 높게 나오지만 실제 케이스에서는 측면과 같은 방해 요소가 고려되어야 함
    다각도에서의 얼굴 인식이 가능한 모델 개발의 필요성이 증대
  <li><strong>과제설명</strong></li>
    주어진 다각도의 (90도 -정면 및 측면) 얼굴 이미지를 학습하여, 임의의 측면얼굴 주어졌을 경우, 동일인의 정면 얼굴을 조회하는 모델을 개발하여 성능 비교
  <li><strong>활용 모델 및 기술</strong></li>
    SiameseNetwork
</ul>

<h2>[과제 16]  어린이 음성데이터에 나오는 문장을 텍스트 형태로 변환</h2>
<ul>
  <li><strong>주제</strong></li>
    어린이 음성데이터에 나오는 문장을 텍스트 형태로 변환
    어린이 음성으로 녹음된 파일의 발화 내용을 텍스트 형태로 변환
  <li><strong>배경</strong></li>
    기존 음성인식기에 대한 어린이 발화 성능 고찰이 필요함
    최근 어린이를 타겟으로 하는 인공지능 스피커 서비스, AI 교육 서비스가 개발됨에 따라 어린이 음성 인식에 대한 성능 향상 및 데이터셋의 필요성이 증대됨
  <li><strong>과제설명</strong></li>
    주어진 어린아이의 음성데이터를 학습시켜 음성데이터의 문장을 텍스트 형태로 변환하는 STT 모델을 개발하여 성능 비교
  <li><strong>활용 모델 및 기술</strong></li>
    MFCC
</ul>

<h2>[과제 19] 우주 전파 재난 대비를 위한 예측 모델 개발</h2>
<ul>
  <li><strong>주제</strong></li>
    우주 전파 재난 대비를 위한 예측 모델 개발
    태양입자유입(Proton Flux) 양상 예측
  <li><strong>배경</strong></li>
    태양플레어, 코로나물질방출과 같은 태양활동으로 인해 지구로 유입된 고에너지 proton입자들로 위성장애, 극항로 방사선 피폭, 통신장애 등을 발생시킴
    원인이 되는 Proton 입자는 Traval Time이 다소 긴 편으로 예측에 어려움
  <li><strong>과제설명</strong></li>
    태양 활동에 의해 지구로 유입되는 것들 중 상대적으로 지구에 먼저 도착하는 X-ray, SWE, EPM을 기반으로 이후 지구에 유입될 것으로 예상되는 Proton입자의 양을 예측
  <li><strong>활용 모델 및 기술</strong></li>
    lightgbm, xgboost, catboost, stacking, permutation importance
</ul>
