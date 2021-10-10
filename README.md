# Eureka-server
Eureka-Server Basic test


Maven project 생성 후, 
spring initailizer를 통해 eureka-server의 dependency 주입(pom.xml에 의존성 주입후 maven reload를 해야한다) 
Eureka-server를 구동시킬 javaClass를 생성해 main메소드와 어노테이션들을 주입시켜 만든 후, application.yml에 서버의 포트 설정을 한다

eureka의 기본 포트는 8761
기본적으로 eureka서버도 client가 될 수 있기 때문에 register-with-eureka와 fetch-registry를 fasle로 설정해야한다.
서버를 구동시킨 후 http://localhost:8761로 이동해 Eureka Dashboard를 확인한다.
