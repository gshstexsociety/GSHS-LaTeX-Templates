gshs-format 레포지토리의 outdate된 양식들을 개정/수정하여 업로드하고 있습니다.

아래의 양식 사용법을 참고바라며, 그럼에도 발생하는 오류는 24035 김한서(@rnfql)에게 문의해주시면 도와드리겠습니다.
<br /> <br />
현재 업로드된 양식의 목록은 다음과 같습니다.

1. R&E 보고서 양식
2. 휴먼테크 논문대상 초록 양식
3. 
<br />
 << 양식 사용법 >> <br /> <br />
위의 양식들은 모두 .zip 파일의 형식으로 .zip_Files 폴더에 저장되어 있습니다. <br />
원하는 양식의 .zip 파일을 다운로드 받은 후, overleaf에 업로드하여 사용합니다. <br />
  (new project - upload project - .zip 파일 업로드) <br /> <br />
이렇게 업로드 된 파일을 열어 좌측 상단의 Menu에서 컴파일러를 변경합니다. <br />
  (Menu - compiler - XeLaTeX 선택) <br /> <br />
이후 다시 문서 편집 화면으로 돌아와서 Menu 버튼 아래 3개의 나란한 버튼 중 <br />
가운데 버튼을 눌러 'fonts' 폴더를 만듭니다. <br /> <br />
다시 본 github의 fonts 폴더에서 4개의 폰트 파일을 모두 다운로드 받습니다. <br />
4개의 폰트 파일은 .zip 파일로 저장되어 있으니 모두 압축을 해제해 줍니다. <br />
  (HCRBatang, HCRBatang-Bold, HCRDotum, HCRDotum-Bold ; 모두 .ttf 확장자로 저장) <br /> <br />
다시 overleaf의 문서 편집 화면으로 돌아와 앞서 만든 'fonts' 폴더를 클릭합니다. <br />
폴더 만들기 버튼 오른쪽의 업로드 버튼을 눌러 4개의 .ttf 파일을 모두 업로드합니다. <br /> <br /> <br />

이제 양식을 사용할 준비가 완료되었습니다. main.tex 파일을 선택한 후 ctrl+Enter로 recompile 합니다.

내용은 sub 폴더 안의 각 부분에 해당하는 .tex 파일에 작성하면 됩니다.

관리 : 24035 김한서 (@rnfql)
