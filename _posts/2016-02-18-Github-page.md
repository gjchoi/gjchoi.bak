### Github page로 블로그 호스팅하기
github에서 githib에 html혹은 markdown .md 파일을 commit하는것만으로 본 블로그처럼 웹페이지를 별도의 서버와 도메인을 갖고 있지 않아도 사용 할 수 있게 해준다.

1. Github가입하기
> 제일먼저 github에 계정을 가지고 있어야 한다. www.github.com에서 unique한 id를 선택하고 email인증통해서 가입완료한다.
> 가입을 완료하면 repository를 만들면 내 git 저장소를 사용할 수 있게된다. 향후 jekyll기능을 사용위해 repository이름은 {계정이름}.github.io로 생성한다.(계정repository) 그래야 Context path없이 저 이름 규칙대로 url을 사용 할 수 있다.(만약 저거 외에 다른 이름을 주면 project url이라고해서 http://{계정이름}.github.io/{repsitory이름} 으로 사용할 수 있지만 github에 내장된 page서비스인 jekyll 기능을 사용에 제약이있다)

[레파지토리그림]

2. 이때 github에서 제공해주는 jekyll이라는 static 웹페이지 서비스를 이용하여 손쉽게 미리만들어진 템플릿을 사용하면 .md파일만 작성해서 github에 commit하는 것만으로 블로그 글을 올릴 수 있다.
> 계정 repository에 setting 메뉴에 들어가보면 auto generation page와 menually html, jekyll사용을 고를 수 있는 메뉴가 나오는데 자동생성하면 github markdown을 사용하여 내용물을 만들고 템플릿도 바로 선택해서 사용 가능하여 편리하지만 메인페이지에 국한되고 블로그처럼 기능을 이용하기에는 제약이 따르므로 jekyll기능을 사용하기로하자.
[setting그림]

3. jekyll은 ruby기반으로 만들어진 


