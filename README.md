# FrFr Go

김언지 : 코딩, 디자인 구상
전민정 : 코딩, 디자인 구상
전수빈 : 코딩, 디자인 구상



# Page 설명

## 메인 화면에서 
 전국 팔도와 각 자치구가 나타나도록 지도를 크게 나타내어 표시하였습니다. 전국 팔도와 자치구 중에서 산불 제보가 들어온 지역을 조회하기 위해 해당지역을 클릭하여 각 지역 산불 실태가 뜨는 페이지로 들어갈 수 있습니다. 메인 화면 상단 웹페이지 이름을 클릭하면 새로고침이 되고, 웹페이지 옆 '제보하기' 아이콘을 누르면 제보를 할 수 있게 만들었습니다.  웹페이지 이름 옆 비상구 아이콘을 클릭할 시에는 재난 시 대피요령에 대한 내용이 있는 페이지로 이동, 소화기 아이콘을 클릭할 시에는 화재 시 소화기 사용법에 대한 동영상으로 이동하게 됩니다. 메인 화면 하단 좌측에는 language 창으로, 클릭 시 각 나라별 언어를 클릭할 수 있게 뜨기 때문에 사용자는 국적에 맞는 언어로 웹페이지를 볼 수 있습니다. 제보가 들어오는 즉시 메인화면에 제보 수만큼 불 아이콘이 뜨게 합니다. 

## 제보 화면에서
 메인 화면에서 제보하기로 들어오면 전국 팔도의 지도가 새롭게 뜨게 됩니다. 여기서 제보를 할 지역을 클릭해줍니다. 전국 팔도와 자치구 중에서 제보 지역을 한 곳 선택을 하게 되면 해당 지역의 시/군/구가 나와있는 지도와 시/군/구가 적힌 표, 산불 3단계 선택란, 구체적인 장소, 자유롭게 의견을 받는 란이 나옵니다. 제보자는 제보를 할 해당 지역을 표에서 클릭하고, 산불 정도에 따라 1, 2, 3단계 중 하나를 선택하고, 추가할 의견이 있으면 의견란에 의견을 자유롭게 써 줍니다.


## 산불 실황 화면에서 

 사용자는 메인 화면에서 조회하고자 하는 지역을 선택하여 산불 실황 화면으로 들어옵니다. 지역 선택 후 산불 실황 화면은 해당 지역에 해당하는 지도가 뜨면서 제보의 개수만큼 메인화면처럼 불을 나타냅니다. 지도 아래에는 제보자들이 제보한 시간, 제보 내용(산불 피해 정도, 구체적인 장소), 제보자들의 의견을 제보 시간순으로 띄워서 나타내줍니다. 

## 개선할 점

 본 웹페이지에서는 프론트 엔드를 먼저 제작하여 메인화면에서 웹페이지 제목을 클릭할 시에는 새로고침, 각 아이콘을 클릭할 시에는 해당 페이지로 넘어가게 하고, 제보하기 클릭 시 뜨는 제보창 만들기까지 구현하였으나, 백 엔드 연동을 하지 못하여 제보에 따라 지도에 불 아이콘을 개수대로 표현하며 제보 내용을 띄우는 것을 구현하지 못하였습니다. 또한 메인페이지에서 산불 실황 페이지로 넘어가는 것을 제대로 구현하지 못했습니다.따라서 추후에 백 엔드를 연동하고 나머지 페이지를 구현하고자 합니다.
