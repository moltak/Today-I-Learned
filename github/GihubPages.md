#GithubPages 
Github Page는 3 종류가 있다.
==User, Organization, and Project Pages== User, Organization, Project pages 모두 같지만 Project pasges는 몇 가지 중요한 점이 다르다. 모든 pages는 https가 아닌 http로 커뮤니케이션이 되기 때문에 중요한 정보를 ==전송하면 안된다.==

###User, Organization pages
- 이름은 반드시 username.github.io 혹은 organization.github.io로 해야한다.
- `master` 브랜치에 있는 코드가 ==publish==된다.

###Project pages
- project pages는 page 소스와 제품 소스가 함께 있기때문에 `master` 브랜치가 아닌 `gh-pages` 브랜치에서 ==publish==된다.
- 이때 주소 형식은 `username.github.io/projectname` 가 된다.

###Custom Domain 설정
Custom Domain 설정시 custom subdomain 과 custom apex domain 도메인 두가지로 나뉜다. 

####Sub Domain 설정
자세한 내용은 https://help.github.com/articles/adding-a-cname-file-to-your-repository 를 참고하면 된다.
- User, Organization 페이지는 간단히 CNAME 파일을 추가하고 `blog.example.com` 과 같은 ==Custom Domain== 이름을 적는다.
- DNS provider에 가서 CNAME을 추가한다.
