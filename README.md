# SEARCH



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
