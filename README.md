# sass 사용 거의안함. scss를 사용한다. scss-->사스


# 확장프로그램

![image](https://github.com/jaejae87/sass/assets/129706762/be9ac688-f43b-43ee-9b5f-526e9739ecfe)

# scss 컴파일

![image](https://github.com/jaejae87/sass/assets/129706762/3859bfcd-ef12-4445-a8d4-e7fbe96dcabf)

# css 위치변경

![image](https://github.com/jaejae87/sass/assets/129706762/8d791bfb-6eb5-4aef-ae67-144a3061e4ff)

# saveATH:NULL이면 SCSS파일과 같은 위치에 STYLE.CSS가 생긴다 

![image](https://github.com/jaejae87/sass/assets/129706762/fb7720fb-8162-4f9e-8697-5cc3cad65d0b)

# ~은 style.css를 의미, / style.scss가 있는 폴더를 의미함

![image](https://github.com/jaejae87/sass/assets/129706762/e9045012-35cd-402e-bc56-ec082b4b0ed3)

# scss파일이 있는 폴더의 상위요소에 생성(scss 파일에서 왓칭 눌려야됨)

![image](https://github.com/jaejae87/sass/assets/129706762/ec51aced-7e6c-4874-bce0-c8038afc6e10)

# //주석처리방법은 CSS로 컴파일 되지 않는다.  

# /* */ 주석처리방법은 CSS로 컴파일 되어 나타난다.

![image](https://github.com/jaejae87/sass/assets/129706762/01d8d835-a2b2-425f-8f2b-df2ffa290810)

# 변수 만들기 --> $로 시작함,(영문,숫자,-, _)만 사용용할 수 있음. 숫자로 시작할 수 없음

![image](https://github.com/jaejae87/sass/assets/129706762/32dd8fd3-7c92-4bb1-9222-51e4b6971faf)

# Partials(파샬)

--관련된 것끼리 묶어서 분리 / 소스에 반복되는 부분들을 분리 분산시켜서 모듈화 시키는 기능

*Partials의 파밍명은 _로 시작하며
*불러들일때는 @import '파일명' 이때 파일명에 _는 포함시키지 않고, 확장명도 포함시키지 않는다.

scss는 _로 시작하는 파일은 컴파일 하지 않는다.


![image](https://github.com/jaejae87/sass/assets/129706762/2bbbbbff-5c82-44a5-9da7-2d4f9071d818)

![image](https://github.com/jaejae87/sass/assets/129706762/f13965d3-f91c-4993-9dd6-13cf56446d08)


 # @import --> 변수가  중복될때는 아래의 것이 적용된다.
 
 # @use --> 변수이름이 같을때 에러발생,@use를 사용할때는 앞에 파일명을 추가해서 파일명 , 변수명 
![image](https://github.com/jaejae87/sass/assets/129706762/a7c99c16-93e0-4530-9e13-0b095ea7d5e1)

![image](https://github.com/jaejae87/sass/assets/129706762/762bcadf-133b-4d15-9a04-0b0b194bee61)


![image](https://github.com/jaejae87/sass/assets/129706762/6057c3da-e200-471a-8306-6612fc9eeabb)

# as 뒤에 별명을 붙여서 사용할 수 있다.

![image](https://github.com/jaejae87/sass/assets/129706762/51be06ad-9d95-400d-9400-446acb6eabe8)

