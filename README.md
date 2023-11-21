# SEARCH
## 검색이란?
- 검색은 검색을 하는 대상이 원하는 내용을 찾아내는 행위이다.
- '좋은 검색'이란, 사용자의 의도에 부합하는 검색 결과를 내놓을 확률이 높은 검색이다.
- 이를 위한 것이 검색 엔진이며 검색 엔진의 성능 향상을 통해 사용자들의 사용 경험 향상 및 사용률 증가를 발생시킬 수 있다.

### 검색을 위한 세 가지 과정
1. 색인
2. 검색(또는 질의)
3. 스코어링(또는 랭킹)

### 문서를 추출하는 방법
1. BOW(Bag of Words) : 단어별 카운트를 기반으로 문서로부터 특성을 추출하고 표현하는 방식 (단어의 출현 통계를 이용하는 방식)
   1) 단어의 사용 여부만 표시하는 방법
   2) 단어 수를 표시하는 방법
   3) 단어가 문서에 나타난 수를 반영해 보정하는 방법

## LIBRARY (for Java)
### 정보 검색 라이브러리 - 아파치 루씬
> https://lucene.apache.org/
### 딥러닝 라이브러리 - Deeplearning4j
> https://mgubaidullin.github.io/deeplearning4j-docs/programmingguide/01_intro

## LIBRARY (for Python)
### NLTK (Natural Language ToolKit)
> https://www.nltk.org/
### 사이킷런
> https://scikit-learn.org/stable/

## DATA
### 구텐베르크 프로젝트
> https://www.gutenberg.org/
### 네이버 영화 리뷰 (테스트 파일로 제공)
> https://github.com/e9t/nsmc
### 네이버 뉴스 분류 (NNST 파이썬 라이브러리 형태로 제공)
> https://github.com/jason9693/NNST-Naver-News-for-Standard-and-Technology-Database
### 50 Years of Pop Music Lyrics
> https://github.com/walkerkq/musiclyrics
### 불용어 사전 (한글)
> https://www.ranks.nl/stopwords/korean
### 병렬 말뭉치 (OPUS)
> https://opus.nlpl.eu/
### 외래어 자료
| 자료 이름                     | 링크                                                                                                 |
| -------------------------- | ---------------------------------------------------------------------------------------------------- |
| 외래어 일반용어 (hwp 파일)   | [국립국어원 - 외래어 일반용어](https://www.korean.go.kr/front/etcData/etcDataView.do?mn_id=46&etc_seq=322&pageIndex=1) |
| 외래어 표기법 (xlsx 파일)    | [국립국어원 - 외래어 표기법](https://kornorms.korean.go.kr//example/exampleList.do)                    |
| 외래어 <-> 한글 표기 변환기  | [외래어 <-> 한글 표기 변환기](http://loanword.cs.pusan.ac.kr/)                                       |

### 한글 단어 자료
| 자료 이름                     | 링크                                                                                                 |
| -------------------------- | ---------------------------------------------------------------------------------------------------- |
| hunspell 한국어 맞춤법 사전   | [hunspell 한국어 맞춤법 사전](https://github.com/spellcheck-ko/hunspell-dict-ko)                     |
| 국립 국어원 사전              | [국립 국어원 사전](https://github.com/spellcheck-ko/korean-dict-nikl)                                 |

### 영어 단어 자료
| 자료 이름                     | 링크                                                                                                 |
| -------------------------- | ---------------------------------------------------------------------------------------------------- |
| Word frequency              | [Word frequency](https://www.wordfrequency.info/samples.asp)                                          |
| kaggle                       | [kaggle - English Word Frequency](https://www.kaggle.com/datasets/rtatman/english-word-frequency/)   |
| google research              | [Google Research - All Our N-gram Are Belong to You](https://blog.research.google/2006/08/all-our-n-gram-are-belong-to-you.html?source=post_page-----bd8767957a84--------------------------------) |


### 머신러닝 자료
- 언어 정보 나눔터
> https://corpus.korean.go.kr/

## 분석기
### 한글 형태소 분석기
| 형태소 분석기               | 링크                                        |
| -------------------------- | ------------------------------------------ |
| 아리랑 분석기               | [https://github.com/korlucene](https://github.com/korlucene) |
| 꼬꼬마 형태소 분석기        | [http://kkma.snu.ac.kr/](http://kkma.snu.ac.kr/)        |
| 코모란 형태소 분석기        | [https://www.shineware.co.kr/products/komoran](https://www.shineware.co.kr/products/komoran/#demo?utm_source=komoran-kr&utm_medium=Referral&utm_campaign=github-demo) |
| 바른 한글 형태소 분석기    | [https://github.com/bareun-nlp/korean-ambiguity-data](https://github.com/bareun-nlp/korean-ambiguity-data) |


## ALGORITHM
### 문자열 일치
#### 레벤스타인 거리
#### 자카드 척도
### TF-IDF
> https://blog.naver.com/divdivdiv

## About Spell Check
### 검색어 제안, 맞춤법 검사(단어교정)
> https://heegyukim.medium.com/%EA%B2%80%EC%83%89%EC%96%B4-%EC%A0%9C%EC%95%88-%EB%A7%9E%EC%B6%A4%EB%B2%95-%EA%B2%80%EC%82%AC-%EB%8B%A8%EC%96%B4%EA%B5%90%EC%A0%95-bd8767957a84
### Wolf garbe's blog
#### 1000x faster Spelling Correction
> https://towardsdatascience.com/symspellcompound-10ec8f467c9b
#### 1000x Faster Spelling Correction algorithm (2012)
> https://wolfgarbe.medium.com/1000x-faster-spelling-correction-algorithm-2012-8701fcd87a5f
#### SymSpell vs. BK-tree: 100x faster fuzzy string search & spell checking
> https://towardsdatascience.com/symspell-vs-bk-tree-100x-faster-fuzzy-string-search-spell-checking-c4f10d80a078
#### BK-Tree
> https://en.wikipedia.org/wiki/BK-tree
#### Unlocking the Power of NLP: A Deep Dive into Text Preprocessing Steps
> https://blog.stackademic.com/unlocking-the-power-of-nlp-a-deep-dive-into-text-preprocessing-steps-8eb5dfe8b94

## 파일
### json
#### JSON is incredibly slow: Here’s What’s Faster!
> https://medium.com/data-science-community-srm/json-is-incredibly-slow-heres-what-s-faster-ca35d5aaf9e8

## 유틸
### KoreanPostPositionUtil
> https://github.com/inkyfox/KoreanPostPositionUtil

## 도전할 만한 과제
- 검색 기능이 들어간 사이트들의 검색 기능 점검 및 개선점 파악
- 랭킹 작업에 사용되는 알고리즘 개선

## 관련 읽을 만한 책
| 번호  | 제목  | 사용 언어  | 난이도  |
|--------|--------|--------|--------|
| 1  | 검색을 위한 딥러닝  | 자바  | ⭐️⭐️ |
| 2  | 파이썬 텍스트 마이닝  | 파이썬  | ⭐️ |


