# Rprogram_night
R 프로그래밍 활용 빅데이터 분석(2025-01-21 ~ 2025-03-04)

연락처 : kennysy@naver.com


## Kaggle Jupyter Note 한글 처리

    # 한글 폰트 설치 (나눔고딕)
    system("apt-get update")
    system("apt-get install -y fonts-nanum")
    
    # 폰트 캐시 리셋
    system("fc-cache -fv")
    
    library(showtext)
    font_files <- system("fc-list :lang=ko", intern = TRUE)
    
    # 폰트 등록
    font_add("NanumGothic", "/usr/share/fonts/truetype/nanum/NanumGothic.ttf")
    showtext_auto(enable = TRUE)
