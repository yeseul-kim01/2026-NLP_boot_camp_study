# HuggingFace와 SentencePiece 비교 목적
Subword 방식의 토크나이징의 대표적인 알고리즘은 BPE, WordPiece, Unigram입니다.

아래 수순을 따라 대표적인 Subword Tokenizer 라이브러리인 HuggingFace Tokenizer와 SentencePiece를 비교해봅시다.

데이터 준비 : 네이버 영화 리뷰 [링크]
Sentencepiece/HuggingFace를 사용하여 단어사전 구축 및 속도 측정
1과 2 결과물의 상위 빈도 30개의 서브워드 분석
학습 속도(단어사전 구축 속도), 단일 문장 변환 속도, 코퍼스 변환 속도 차이 특정
기타 추가 실험
사용성과 장단점 분석