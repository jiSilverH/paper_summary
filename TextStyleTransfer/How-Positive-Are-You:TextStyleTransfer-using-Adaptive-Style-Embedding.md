## How Positive Are You: Text Style Transfer using Adaptive Style Embedding
* link: [pdf](https://www.aclweb.org/anthology/2020.coling-main.191.pdf)

### Ⅰ. Introduction
### Ⅱ. Related Works
### Ⅲ. Methodology
**A. overview**  
* 목적: style embedding 을 통해서 다양한 문장을 생성하는 것  
* 모델 구조: 2가지 모듈로 구성
  * style module
  * sentence generation module
* 모델 구성의 장점 :: 모델을 단순하게
  * 모델을 분리하면 각 모듈은 자신의 할 일만 하면 됨
  * back-propagation에서 각 모델이 서로에서 영향을 주지 않음    

**B. Style Module**
* 구성: style embedding, style classifier
* 