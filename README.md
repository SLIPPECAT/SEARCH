# SEARCH
## 검색이란?
- 검색은 검색을 하는 대상이 원하는 내용을 찾아내는 행위이다.
- '좋은 검색'이란, 사용자의 의도에 부합하는 검색 결과를 내놓을 확률이 높은 검색이다.
- 이를 위한 것이 검색 엔진이며 검색 엔진의 성능 향상을 통해 사용자들의 사용 경험 향상 및 사용률 증가를 발생시킬 수 있다.

### 검색을 위한 세 가지 과정
1. 색인
2. 검색(또는 질의)
3. 스코어링(또는 랭킹)

## LIBRARY
### 정보 검색 라이브러리 - 아파치 루씬
> https://lucene.apache.org/

### 딥러닝 라이브러리 - Deeplearning4j
#### ‼️ M1 Mac의 경우 최신 버전 사용을 권장한다.
#### 하지만, 그렇게 할 경우 과거 버전에서 사용되던 클래스 메소드는 사용하지 못할 수도 있다.
#### ‼️ gradle보다는 maven을 이용하도록 하자. gradle을 이용한 종속성 주입을 할 경우 nd4j path를 읽지 못하는 것으로 보인다.

> https://mgubaidullin.github.io/deeplearning4j-docs/programmingguide/01_intro

- Word2Vec 클래스 관련 종속성 주입
```Maven
   <dependency>
       <groupId>org.deeplearning4j</groupId>
       <artifactId>deeplearning4j-core</artifactId>
       <version>1.0.0-M2.1</version>
   </dependency>
   <dependency>
       <groupId>org.deeplearning4j</groupId>
       <artifactId>deeplearning4j-nlp</artifactId>
       <version>1.0.0-M2.1</version>
   </dependency>
   <dependency>
       <groupId>org.nd4j</groupId>
       <artifactId>nd4j-native-platform</artifactId>
       <version>1.0.0-M2.1</version>
   </dependency>
```

## DATA
### 구텐베르크 프로젝트
> https://www.gutenberg.org/

## ALGORITHM
### 문자열 일치
#### 자카드 척도

## 도전할 만한 과제
- 검색 기능이 들어간 사이트들의 검색 기능 점검 및 개선점 파악
- 랭킹 작업에 사용되는 알고리즘 개선
