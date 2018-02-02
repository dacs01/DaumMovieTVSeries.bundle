[다음영화](http://movie.daum.net)에서 영화, TV 드라마, TV 드라마 시리즈 정보를 가져오는 Plex용 Metadata Agent입니다


https://github.com/hojel/DaumMovie.bundle 를 참조하여 만들었습니다.

영화는 https://github.com/hojel/DaumMovie.bundle 과 동일한 로직을 사용합니다.

시리즈 이름 설정
==============
다음영화의 시리즈 정보 규칙에 따라서 파일 이름을 설정하는 것이 좋다.

폴더 구조는 다음과 같다.

최상위 폴더/시즌 폴더/에피소드 S01E01

삼시세끼를 예를 들면 다음과 같이 파일이름과 폴더명을 정하면 된다.

삼시세끼/삼시세끼 정선편 시즌 1/삼시세끼 정선편 시즌 1 S01E01.mp4  
삼시세끼/삼시세끼 어촌편 시즌 1/삼시세끼 어촌편 시즌 1 S02E01.mp4  
삼시세끼/삼시세끼 정선편 시즌 2/삼시세끼 정선편 시즌 2 S03E01.mp4  


영화나 TV의 경우 검색후의 목록에서 맞는 것을 선택하고

시리즈의 경우에는 검색후에 나온 목록에서 시리즈 중 아무거나 선택해도 관계없습니다.


시리즈의 경우 시즌이 다 없거나 에피소드가 다 없는 경우에도 아래와 같이 하면 됩니다.

1번 시즌, 3번 시즌만 있다면  
1번 시즌/에피소드 이름 S01E01.mp4  
1번 시즌/에피소드 이름 S01E02.mp4  
1번 시즌/에피소드 이름 S01E03.mp4  
1번 시즌/에피소드 이름 S01E04.mp4  

3번 시즌/에피소드 이름 S03E02.mp4  
3번 시즌/에피소드 이름 S03E04.mp4  
3번 시즌/에피소드 이름 S03E07.mp4  
로 하면 됩니다.
