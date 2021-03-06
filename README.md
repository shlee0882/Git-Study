## Git-Study

#### 제목 크기 작성하기

#### h4 특수문자 샵4개

```text
// git 로컬 레파지토리 생성 이후 원격 레파지토리 push 방법
git init
git status
git add .
git status
git commit -m "test commit"
git remote add origin "your github remote repository url"
git push origin master
```

```text
// git 원격 레파지토리 clone 이후 수정사항 push 방법
git clone "your github remote repository url"
git status
git add .
git status
git commit -m "test commit"
git push
```


_이탤릭체는 언더바 사용_

`#`는 숫자키 1 옆에 single quote로 특수문자 표시가 가능함


#### 소스코드 작성하기

```java

public class MyClass{
  public static void main(String args[]){
    System.out.println("소스코드 블럭지정 방법 ");
    System.out.println("```java");
    System.out.println("소스코드내용 ");
    System.out.println("```");
  }
}

```

#### 링크 작성하기

[블로그 링크는 [블로그 제목]와 (블로그 url) 을 붙여서 만들수 있습니다.](https://shlee0882.tistory.com)

#### 인용구문 작성하기

> 인용구문은 ">" 기호를 사용합니다.

#### 테이블 작성하기

이름 | 나이 | 직업
--- | --- | --- |
이상현 | 30 | 코더 |
김길동 | 28 | 디자이너 |
조현영 | 29 | 기획자 |
김지숙 | 26 | 테스터 |

#### 순서있는 리스트 작성하기

- 동물
  1. 포유류
  2. 양서류

#### 순서없는 리스트 작성하기

* 과일
  * 딸기
    * 빨간색
    * 상큼하다.
  * 바나나
    * 노란색
    * 달다.
  * 블루베리
    * 파란색
    * 시원하다.
    * 리스트는 *을 사용하여 만듭니다.
    
#### 체크 박스 작성하기

- [x] 체크박스1
- [ ] 체크박스2
- [ ] 체크박스3
    
#### 강조 표현하기

**강조표현은 별2개를 사용하여 표현합니다. 조지아 맥스** ~~최애커피 물결표시 2개로 표현합니다.~~ 맛있어요!!!
    
[Git 관련 명령어 모음](https://shlee0882.tistory.com/190)


#### 이미지 넣기
    
![강아지](https://i.pinimg.com/originals/79/a9/41/79a941de1bfe8d9fbea2369fef8c2e35.jpg)

#### 이모티콘 사용하기

:smile:
