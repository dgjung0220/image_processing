#### 영상 인식 (전통적인 방법)
제한된 환경 내에서 여러 가지 가정 하에서 인식을 수행.  
- 영상의 종류를 알 경우 : 문자, 번호판, 지문, 얼굴 등
- 단순한 배경
- 실내와 같이 제한된 환경
- 단순한 객체의 texture
- 물체의 겹침이 없는 경우

#### 영상 인식의 과정 (Preprocessing → Segmentation, Feature Extract → 영상 인식)
``Image → Low-level processing → Intermediate-level processing → high-level processing → Recognition``
- Low-level processing : 전처리 (eg: Contrast 개선, 잡음 제거(denoise) ..)
- Intermediate-level processing : 영상분할, 특징 추출 (Segmentation, Feature Extraction)
- High-level processing : 영상 인식 (eg: Face Recogntion, Text Recognition ..)

#### 영상 분할
영상에 존재하는 서로 다른 영역들을 구분. (eg. 영역역로 라벨링을 수행) 이진화, Connected Component Labeling 등의 방법이 있다.  
- 이진화(Thresholding) : 물체와 배경을 분리 ※[Threshold 값 결정 방법](#1)
- Connected component labeling :

#### References
- [Hanyang university lecture note](http://166.104.231.121/ysmoon/stm2017/lecture_note/chap7.pdf)

<hr>
#1
※ Threshold 값 결정 방법



