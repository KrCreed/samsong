엑셀 번호 

A = 0, B = 1, C = 2, D = 3, E = 4, F = 5, G = 6, H = 7, I = 8, J = 9
K = 10, L = 11, M = 12, N = 13, O = 14, P = 15, Q = 16, R = 17, S = 18, T = 19
U = 20, V = 21, W = 22, X = 23, Y = 24, Z = 25, AA = 26, AB = 27, AC = 28, AD = 29
AE = 30, AF = 31, AG = 32, AH = 33, AI = 34, AJ = 35, AK = 36

엑셀에 맞게 코드 655-669 부분 변경 필요합니다. (주석에 맞게 row[] 대괄호 안 숫자 변경)![image](https://github.com/user-attachments/assets/87d481a9-00e4-4ec8-afbf-8f32d12588c4) ex) 경도가 N 열이면 row[13]




엑셀명 url 부분
깃허브에 업로드한 엑셀명으로 코드 수정할 필요 있습니다.

https://raw.githubusercontent.com/사용자명/리포지토리명/main/파일경로/파일명.xlsx

![image](https://github.com/user-attachments/assets/78553b7a-9b06-4c1f-8471-0477165764ce)

ex) https://raw.githubusercontent.com/KrCreed/samsong/main/테슬라전국데이터_2%20-%20복사본.xlsx

엑셀에 맞게 코드 646 부분 변경 필요합니다.

구글 maps api key 변경

코드 13번째 행

<script src="https://maps.googleapis.com/maps/api/js?key=AIzaSyD8UBtKnkeivt08HnA9nRuqQZ6QIYTVSZ0" async defer></script>

![image](https://github.com/user-attachments/assets/23ab747b-a500-4417-a98c-c0e07ac78c4a)


여기서 key 이후 부분 변경 ex) <script src="https://maps.googleapis.com/maps/api/js?key=@@@@@@@@@@@@@@@" async defer></script>

이후 구글 클라우드 콘솔 api 설정에서 제한 설정으로 api 키가 코드에 노출되어도 다른 사용자나 홈페이지에서 사용 제한하도록 설정

![image](https://github.com/user-attachments/assets/7c4791ab-1152-44ad-81c3-5584afcb0134)

파이어 베이스 api key 변경

코드 523-529 부분 변경필요합니다.
파이어 베이스 프로젝트 설정에서 복사해서 사용합니다.

![image](https://github.com/user-attachments/assets/0ef08864-b531-4e9e-a0c0-57cebe5ca877)

![image](https://github.com/user-attachments/assets/17d03ba2-fc37-46c8-b247-25e2f6ca652f)

ex)   
      apiKey: "AIzaSyAFYyFvuv04dKVKkz4hYq8on_JYlbtw_F4",
      authDomain: "samsong-28f4f.firebaseapp.com",
      projectId: "samsong-28f4f",
      storageBucket: "samsong-28f4f.firebasestorage.app",
      messagingSenderId: "840121036484",
      appId: "1:840121036484:web:b57eedc456b3beb236a391",
      measurementId: "G-Z00YP5N303"
      
부분 변경 필요합니다.

로그인 할 수 있는 계정 설정
![image](https://github.com/user-attachments/assets/ee8dab34-f79d-4453-9cb7-d8b4667fe145)
파이어 베이스 콘솔에서 로그인 방법 설정 후 사용자 추가




