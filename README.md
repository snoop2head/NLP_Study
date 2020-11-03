# YBIGTA NLP Study

### [연세대 교환 생활 후기 데이터셋](https://github.com/snoop2head/yonsei-exchange-program)

- [ ] Summarization: textrank가 아닌 다른 방법으로 요약해보기
  * TextRank는 Extractive Summarization. 원문에서 중요한 핵심 문장 또는 단어구를 몇 개 뽑아서 요약문을 만듦.
  * Seq2Seq은 Abstractive Summarization. 추상적 요약은 해서 원문을 요약하는 방법이다. [어텐션을 이용한 아마존 후기 요약 예시](https://wikidocs.net/72820) 
  * 요약 데이터셋은 [AIhub 데이터셋](https://aihub.or.kr/aidata/8054) 이나 [모두의 말뭉치 문서요약 말뭉치](https://corpus.korean.go.kr/) 사용할까? 

- [ ] 여행 및 공부 후기에서 등장하는 Stopwords Dataset 만들어서 배포하기
- [ ] Keyword Extraction: 키워드를 추출하고 worldcloud 대신에 다른 방법으로 visualize 
- [ ] Sentiment Analysis: 네이버 쇼핑 데이터셋으로 train시킨 BERT or  STEAM 후기 데이터셋으로 train 시킨 BERT로 후기 긍부정 평가. OR BERT와 KoBERT로 영어로 작성된 후기와 한국어로 작성된 후기 긍부정 평가 분리하기
- [ ] Search: JS로 서치엔진 만든 서치엔진 React.js 프로젝트에 접붙여보기 

### 수능 빈칸추론 BERT 모델 성능 개선

BERT는 애초에 앞뒤 맥락을 바탕으로 Mask 된 부분을 채워넣는 것. 단일방향인 GPT2나 두 개의 단일 방향을 합친 ELMO 등의 모델보다 훨씬 더 적절한 모델일 것으로 예상.

- [ ] [현재는 수능 & EBS 빈칸추론으로 학습하고 문제를 풂.](https://github.com/om00839/machine-suneung) 그러지말고 Squad 데이터셋으로 학습시킨 BERT로 수능을 풀게 하기.

### Github Stars Topic Classification (or Clustering)
[Implementing TFIDF algorithm for Github Star Topics](https://github.com/lorey/github-stars-by-topic) & [Github Topics for users Website](https://github.com/ezeed/topics-of-stars)

* [ ] 위 프로젝트들과 유사하게 본인이 STAR을 누른 깃헙 README들을 바탕으로 비슷한 주제끼리 정리해주기

### Search Trendy Emoji (Powered by Instagram)
* [ ] instagram 데이터셋 기반으로 키워드 / 문장 입력 시 사용하기 제일 적절한 이모티콘 추천해주기. 
* [ ] Word2VEC 외에도 다른 방법으로 이모티콘 추천하기
* [ ] 인스타그램 데이터셋은 [Instaloader](https://github.com/instaloader/instaloader)로 모으기

### 한국어/영어 Hate Speech Detector 만들기
* [captainnemo9292/womad_hate_speech_detection_through_machine_learning](https://github.com/captainnemo9292/womad_hate_speech_detection_through_machine_learning)
* [pinkeshbadjatiya/twitter-hatespeech](https://github.com/pinkeshbadjatiya/twitter-hatespeech)
* [vedant-95/Twitter-Hate-Speech-Detection](https://github.com/vedant-95/Twitter-Hate-Speech-Detection)
* [monologg/korean-hate-speech-koelectra](https://github.com/monologg/korean-hate-speech-koelectra)
* [captainnemo9292/hate-speech-language-modeling](https://github.com/*captainnemo9292/hate-speech-language-modeling)
* [kocohub/korean-hate-speech](https://github.com/kocohub/korean-hate-speech)
* [ ] 위에 언급된 repository들 이용해서 특정 혐오감 키워드 블라인드 처리 기능을 크롬 익스텐션에 결합하기
* [ ] Hate speech dataset에서 키워드 추출 기반 (혹은 다른 방법으로) Chrome extension 만들기

### 한국어 Speech to Text Model로 신해철 고스트스테이션 Transcript 형성하기

* [KoSpeech Model using AIHub Dataset](https://github.com/sooftware/KoSpeech)
* [clovaai/ClovaCall dataset](https://github.com/clovaai/ClovaCall)
* [Kaldi Zeroth Dataset](https://github.com/goodatlas/zeroth)

### 한국어 OCR 모델 뜯어보기

* [네이버의 CRAFT Text Detector Model](https://github.com/clovaai/CRAFT-pytorch)
* [CRAFT 모델을 기반으로 만든 EasyOCR 라이브러리](https://github.com/JaidedAI/EasyOCR)

### 그 외에도 어려워보이지만 하고 싶은 프로젝트들

- [ ] 한국어 말투 변환 패키지 만들기
- [ ] 종이에 쓰여진 수학공식 -> LaTex로 변환하는 OCR
- [ ] 죽은 사람의 생전 목소리를 모아서 TTS 만들기

### [References from Huffon's recommendation](https://github.com/Huffon/NLP101)

* [한국어 임베딩 - 이기창 저](https://github.com/ratsgo/embedding)
* 텐서플로2와 머신러닝으로 시작하는 자연어처리
* [딥 러닝을 이용한 자연어 처리 입문](https://wikidocs.net/book/2155)
* [Introduction to Natural Language Processing (Jacob Einstein)](https://github.com/jacobeisenstein/gt-nlp-class/blob/master/notes/eisenstein-nlp-notes.pdf)
* [밑바닥부터 시작하는 딥러닝 2](https://github.com/WegraLee/deep-learning-from-scratch-2)
* Neural Network Methods for Natural Language Processing (Yoav Goldberg)
* [Dive into Deep Learning](https://github.com/d2l-ai/d2l-en)
* [Hands on machine learning 2](https://github.com/ageron/handson-ml2)
