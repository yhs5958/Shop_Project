개인 블로그 주소 : https://blog.naver.com/yhs5958_2/223218925977
# Shop_Project

⊙스프링 부트 쇼핑몰 기능 애플리케이션 제작.

● GITHUB : https://github.com/yhs5958/Shop_Project.git

● 사용 프로그램 : Intelli_J community

● PC 개발 환경 : Windows10, java 17.0.8 (jdk17)

● 프로젝트 기간 : 2023.08.15 ~ 2023.09.22

    ○ 프로젝트 설정

     - 빌드툴 : maven

     - 언어 : java 11

     - 스프링 부트 : version 2.7.1 (생성은 3.1.2)

     - 의존성 :spring web

     - 데이터 베이스(SQL) : Mysql (8.0.31), H2Database 

● 애플리케이션 구동 후 접속 주소는 localhost

● 프로젝트를 실행할 시 필요 세팅

     1. c 드라이브 안에 별도 shop/item 폴더 생성.

     2. mysql로 shop 데이터베이스 생성.

     3. maven메뉴에서 complie 빌드.

     4. application.properties에서 mysql 비밀번호 PC에 맞게 변경.

          4-1. 최초 구동 시 spring.jpa.hibernate.ddl-auto 값을 create로 두고  애플리케이션 구동.

          4-2. 구동 후 validate으로 변경 후 구동.
          4-3. 재시작 후 
