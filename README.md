# hailey-springboot-webservice
## Project Name: My-WebService
This Project is my personal webservice

*[스프링부트와 AWS로 혼자 구현하는 웹 서비스] 도서 참조

[Project Setting]
- Java 11 (jdk 1.8)
- Gradle 4.10.2
- Springboot 2.1.9
- DB : h2 (Inmemory Database)

[Use Skills]

- Spring Data Jpa, ORM
- Java
- Springboot
- mustache (HTML template engine)
- Spring Security Oauth2
- Travis CI ->  설정파일 : .travis.yml
- AWS CodeDeploy -> 설정파일 : appspec.yml

[WebService]

- AWS EC2 (Linux AMI2)
- ssh Hostname -> EC2 접속
- MariaDB 10.4.13

## 전체구조
<img width="769" alt="image" src="https://user-images.githubusercontent.com/26623530/117125510-8f132280-add4-11eb-92de-a2c348988eaf.png">

## 무중단 배포 전체 구조
<img width="787" alt="image" src="https://user-images.githubusercontent.com/26623530/118348442-4fdb9300-b585-11eb-9729-dabe5e1aca16.png">
