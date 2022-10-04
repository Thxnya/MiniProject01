# MiniProject01
미니 프로젝트01 - 중증장애인 교통배려시설 현황 및 문제점 분석



📰 프로젝트 개요<br/>
---
거동이 불편한 중증장애인이 전동휠체어를 이용해서 이동할때에,<br/>
어려움이 없도록 충전소 설치가 잘되어있는지 알아보려고 합니다.<br/>

전동휠체어는 거동이 불편한 중증장애인에게 필수품이지만<br/>
한번의 완전충전으로 이동이 가능한 거리가 길지 않습니다.<br/>
그런데다가 급속충전기의 설치 개수가 부족하고, <br/>
설치 위치에 대한 정보를 알기 어렵습니다.<br/>
따라서 충전시설이 장거리 이동시 어려움이 없을 만큼 충분히 구비되어 있는지를 파악하여 <br/>
중증장애인 관련 정책에 반영할 수 있도록 합니다.<br/>



💬 프로젝트 결론<br/>
---
정보를 얻는 것이 힘든 장애인들은 지금도 어려움을 겪고 있습니다.<br/>

데이터가 제대로 취합되어 있지 않거나 누락된 경우가 많고 <br/>
데이터 확인을 위해서 일일이 각 지자체에서 확인해야하는 번거로움이 있었습니다.<br/>
주요 장애인보조기구 필요 및 소지 현황 데이터는 2017년이후로 업데이트가 되지않고 있습니다.<br/>
따라서 충전소 위치같은 정보들이 필요한 장애인들은 더욱 어려움을 겪을 것이라 생각됩니다.<br/>
<br/>
하지만 전동보장구 충전시설에 관한 법적 근거가 전혀 없습니다.<br/>
설치와 관리에 대한 명확한 기준도 없기때문에 <br/>
다양한 데이터를 통해 전동보장구 충전시설 현황을 심층적으로 분석한 이 자료로 <br/>
해당 사안의 심각성을 알리는데 이용했으면 합니다.<br/>



⚡ 발표 자료<br/>
---
### 데이터 수집
  - csv 다운로드
  - Open API 형태 사용
<img src="https://user-images.githubusercontent.com/104615422/193885816-624d8613-bc90-4538-ad5c-0cd88880c37a.jpg" width="60%" height="60%">
<img src="https://user-images.githubusercontent.com/104615422/193885827-d8e61279-de0b-4628-92b7-6745397118a9.jpg" width="60%" height="60%">
<img src="https://user-images.githubusercontent.com/104615422/193885830-048ddbbf-5169-43f2-88c1-de5875415de2.jpg" width="60%" height="60%">

### 데이터 분석
  - 데이터 전처리
  - 피벗테이블 작성
<img src="https://user-images.githubusercontent.com/104615422/193885833-7aa2f699-d13e-4622-922d-500ee85607e8.jpg" width="60%" height="60%">
<img src="https://user-images.githubusercontent.com/104615422/193885838-afb5ac5c-d160-46a6-bdf6-700cfacde416.jpg" width="60%" height="60%">

  - 막대그래프, 히트맵 작성
<img src="https://user-images.githubusercontent.com/104615422/193885841-526ba25e-bc4e-40ec-ae54-f96e12989029.jpg" width="60%" height="60%">
<img src="https://user-images.githubusercontent.com/104615422/193885845-a813c583-9f95-4090-9a37-0df654fbe45f.jpg" width="60%" height="60%">
<img src="https://user-images.githubusercontent.com/104615422/193885847-fd0b7f45-7eed-4bad-9370-41a970906a01.jpg" width="60%" height="60%">

  - folium 라이브러리
    - 마커표시
    - 빈도에 따른 색상표시
<img src="https://user-images.githubusercontent.com/104615422/193885851-5344515e-8177-4e47-87f9-d2ac25c71370.jpg" width="60%" height="60%">
<img src="https://user-images.githubusercontent.com/104615422/193885854-6b1e6b54-d8b5-43b5-9668-3a0b06914285.jpg" width="60%" height="60%">
<img src="https://user-images.githubusercontent.com/104615422/193885862-1e97d8bd-dbba-4713-99f1-9c2f01cf2049.jpg" width="60%" height="60%">
<img src="https://user-images.githubusercontent.com/104615422/193885865-1f046833-3517-4439-b476-9f354a6d68d7.jpg" width="60%" height="60%">

  - voronoi 라이브러리 이용
<img src="https://user-images.githubusercontent.com/104615422/193885873-6161e296-b48b-48f7-a204-52629b117858.jpg" width="60%" height="60%">
