# hpserver-raid

* Dl20 gen9 레이드 구성 방법

  > 서버 전원을 키시고 아래 화면이 나오면 F10을 눌러 intelligent provisioning으로 들어갑니다.<br>
  > 그후 잠시간 지나면 F1, F2가 새로 뜨는데 무시하셔도 됩니다.<br>
  > ![1](https://user-images.githubusercontent.com/14309034/43241137-c5beccfa-90d4-11e8-9b25-a19f660a299e.jpg)<br>
  > 해당 화면에 들어가면 두번째 항목으로 들어갑니다 (Smart Storage Administrator)<br>
  > ![2](https://user-images.githubusercontent.com/14309034/43241139-c5e9539e-90d4-11e8-9cbd-6c6c3ccc4161.jpg)<br>
  > 사진 상으로는 B140i가 되어있지만, 저희 서버에는 H240이 장착되어 있으니 해당 버튼이 생성되 있습니다.<br>
  > 해당 내용을 클릭해 들어가 상단 Configure를 누릅니다.<br>
  > ![3](https://user-images.githubusercontent.com/14309034/43241140-c610e616-90d4-11e8-90d5-7bdc841c23d0.jpg)<br>
  > ![4](https://user-images.githubusercontent.com/14309034/43241141-c6371bf6-90d4-11e8-9d2d-234ffd6954eb.jpg)<br>
  > Unassigned Drives --> 어레이를 잡을 디스크 클릭  하단의 create arrat 클릭<br>
  > 위부분까지 하시면 해당 화면 나옵니다. 해당 사진은 디스크가 1개라서 raid0만 뜨고 있지만,<br>
  > 여기까지 왔으면 실 화면엔 raid 1도 떠있을거에요. 여기서 고객사에서 원하는 내용으로 체크후 Create Logical Drive를 누릅니다.<br>
  > ![5](https://user-images.githubusercontent.com/14309034/43241142-c66216ee-90d4-11e8-80e5-a543e2d97584.jpg)  <br>
  > 피니쉬가 뜨고 Logical Drives에서 잡힌 내역 확인이 가능합니다.<br>



