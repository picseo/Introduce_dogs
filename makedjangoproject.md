# 쟝고 프로젝트 만들기

  -쟝고를 이용해서 프로젝트를 한다는데 나는 쟝고를 모른다.
  -장고로 작은 프로젝트를 만들어야겠다.
  
  1. 쟝고 개발 환경 세팅
    참고 페이지 : https://developer.mozilla.org/ko/docs/Learn/Server-side/Django/development_environment
    
    1. 파이썬 가상 환경 만들기
      * 윈도우 : virtualenvwrapper-win
      
      *설치하기
        pip3 install virtualenvwrapper-win
        cmd 창에서 입력하여 설치한다.
      
        mkvirtualenv name_of_environment - 가상 환경 만들기        
        deactivate — 활성화된 파이썬 가상 환경을 비활성화한다
        workon — 사용가능한 가상 환경 목록을 보여준다
        workon name_of_environment — 특정 파이썬 가상 환경을 활성화한다
        rmvirtualenv name_of_environment — 특정 환경을 제거한다.
        
      * 가상환경에서 python 설치하기
        pip3 install django - 쟝고를 설치한다.
        py -m django --version  - 쟝고 버전 확인한다.
        
             
