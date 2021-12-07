![heard_disease](https://user-images.githubusercontent.com/92664643/142970693-2bff9940-1d49-4a52-a806-73f58a8f6210.jpg)

# HEART DISEASE AI DATATHON 2021
심초음파/심전도 ai 모델 데이터톤 2021<p>

이 경진대회는 
"2021 인공지능 학습용 데이터 구축사업"의 일환으로 추진된 인공지능 학습용 심장질환 심초음파 및 심전도 데이터셋을 이용하여 심초음파/심전도 질환을 판별하는 AI 진단 모델링 경진대회입니다.

  
# 대회 주제
  주제1.<p>
  심초음파 데이터셋을 활용한 좌심실 분할 AI모델 공모(Apical 2 chamber(A2C) & Apical 4 chamber(A4C) view 이미지를 활용해 좌심실 분할하는 딥러닝 모델 개발)
  <p>
  주제2.<p>
  심전도 데이터셋을 활용한 부정맥 진단 AI 모델 공모(심전도 데이터셋을 활용한 부정맥 진단 AI 모델 개발)

  
# 시상 및 혜택
- 총상금: 2,000 만원<br>

<table class="tbl_prize">
  <tr>
    <th style="text-align:left;width:50%">시상</th>
    <th style="text-align:center;width:15%">상금</th>
        <th style="text-align:left;width:35%">비고</th>
  </tr>
  <tr>
    <td>
      <strong>대상</strong><br>
    </td>
    <td align=center> 500만원 </td>
    <td align=center> 1팀(주제별)</td>
  </tr>
    <tr>
    <td>
      <strong>최우수상</strong><br>
    </td>
    <td style="text-align:center"> 300만원</td>
        <td align=center> 1팀(주제별) </td>
   </tr>
      <tr>
    <td>
      <strong>우수상</strong><br>
    </td>
    <td style="text-align:center">100만원</td>
        <td align=center> 2팀(주제별) </td>
   </tr>

</table>

<br>
   
## 데이터톤 일정
<table class="tbl_schedule">
  <tr>
    <th style="text-align:left;width:50%">행사 내용</th>
    <th style="text-align:center;width:15%">일정</th>
        <th style="text-align:left;width:35%">장소/방식</th>
  </tr>
  <tr>
    <td align=center>
      <strong>참가 신청</strong><br>
    </td>
    <td align=center> 2021년 10월 27일(수) ~ 11월 25일(목)</td>
    <td align=center> https://hdaidatathon.com/ </td>
  </tr>
  
  <tr>
    <td align=center>
      <strong> 사전 공지 </strong><br>
    </td>
    <td align=center>2021년 11월 26일(금)</td>
    <td align=center> 이메일 공지 </td>
  </tr>
  
  <tr>
    <td align=center>
      <strong>(본선) AI 모델 제출</strong><br>
    </td>
    <td align=center>2021년 11월 26일(금) ~ 12월 07일(화)</td>
    <td align=center> hdaidatathon@gmail.com로 제출 </td>
  </tr>
  
  <tr>
    <td align=center>
      <strong>수상자 발표</strong><br>
    </td>
    <td align=center>2021년 12월 15일(수)</td>
    <td align=center> 이메일 공지 </td>
  </tr>
  
  <tr>
    <td align=center>
      <strong> 시상식 </strong><br>
    </td>
    <td align=center>2021년 12월 18일(토)
    <td align=center> 오프라인 장소와 일정은 개별 공지</td>
  </tr>
</table>
※ 일정은 코로나 및 주최·주관 기관의 사정에 따라 변경될 수 있습니다.<br>

<br>

## 대회방식
1. 참가팀은 제공된 심초음파 데이터셋 및 심전도 데이터셋을 활용한 아이디어를 
   제안하고, 제안 아이디어를 구현한 AI 모델을 개발합니다.

2. 본선대회 진행       
- 대회 종료 시 결과 요약지(양식 1 : [팀명]H.D.A.I 2021 결과 요약지.pdf)와 개발된 AI 모델을 제출합니다.<br>

- 데이터 공유: 2021년 11월26일 (금) 14:00<br>

- 결과물 제출: 주제 1. 2021년 11월 26일 (금) ~ 2021년 12월 07일 (화) 23:59 / 주제 2. 2021년 12월  2일 (목) ~ 2021년 12월 12일 (일) 23:59  <br>
-             
              A. AI 모델 제출 : 학습코드, 모델 Weight, 환경, 모델설명(1GB 미만)<br>
                  **성능평가 검증을 위한 실행 가이드를 readme.md에 작성해주시기 바랍니다.*<br>
              B. 결과 요약지 : 첨부파일 양식 1. 결과 요약지(H.D.A.I 2021).doc 활용  
                  **단, 결과요약지 내에 주제 1은 DSC/JI , 주제 2는 AUC 출력값이 보이도록 스크린샷 첨부 * <br>  
- 제출처 E-mail: hdaidatathon@gmail.com <br>

3. 주최측에서 제출된 AI 모델을 종합 평가하여 주제별 대상(1팀), 최우수상(1팀), 
   우수상(2팀)을 선정하여 시상이 진행됩니다.

<br>

## 심사 기준
AI모델 평가
 - 각 참가별 개발한 AI 모델(소스) 및 성능평가표(PDF) 제출
 
주제1. 심초음파 좌심실 분할 AI 모델
  - 체적일치도(Dice Similarity Coefficient, DSC)
  - 유사성측도(Jaccard index, JI)
  
주제2. 심전도 데이터셋을 이용한 부정맥 진단 AI 모델
  - 수신자조작특성(Area Under the ROC Curve, AUC)

## 주최 및 주관
- 주최: 과학기술정보통신부, 한국지능정보사회진흥원
- 주관: 서울대학교병원, 연세대학교 산학협력단

<br>

## 문의 및 FAQ
Issue 페이지에 문의글을 남기시면 담당자가 답변드립니다. <br>
