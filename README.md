# T-academy---TIL
Today I Learn at T academy
*180920*

전 배포형태 :
톰캣 같은 was에 war 배포분을 업로드하면 톰캣이 읽어서 실행했다면

요즘 배포형태 : 
톰캣과 한번 묶어서 패키징하는 부트 리패키징 -> springboot.jar 로 바로 실행 
작은 단위의 컨테이너 단위에서 실행 할 수 있도록 해주고 있다. 

가급적 스프링 부트2.0 부터 시작하자 => 1.5 몇년뒤 없앨 계획이라고.. 

어노테이션 중 @SpringBootApplication 
이 어노 붙은 곳을 기준으로 하향으로 읽어 내려간다.. 

spring boot stater = spring boot autoconfigure + spring boot dependencies 
: 이것을 이용하면 많은 디펜던시(의존성)을 한 줄로 줄여줌 !
: 개발자가 신경써야할 것 ; 스프링 부트 버전 / 사용하려는 라이브러리를 부트가 지원하는지 / 라이브러리 등록방법 만 신경쓰면 된다. 

- H2DB 
- JPA 쓰자
- 그레이들 래퍼

@Bean 
: 생명주기를 관리하는 스프링 빈 객체를 관리하는 어노테이션. 

@Conponent
: 

라이브러리와 프레임워크의 차이

