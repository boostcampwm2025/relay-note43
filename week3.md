# 3주차 릴레이 프로젝트

## 토론하기

### week2 퀘스트 1 - 아이스브레이킹 질문으로 분위기를 살리고, 경험을 공유하자!
- 피어피드백 시간에 매일 아이스브레이킹이 필요할까?
  - 아이스브레이킹을 하면 어색함은 줄겠지만 피어 피드백 1시간도 부족했는데 매일 가능할까?
- 경험 상 처음 만났을때 힘든 점을 공유해도 어색함이 사라지는데 AI에게 아이스브레이킹 내용을 맞겨야할까? 
- 아이스브레이킹 추천 받아서 실행한 내용이 성공적인 대화법으로 커뮤니티에 공유할 내용일까?
- 취지는 좋지만 매일하기에는 별로인 것 같다.
  
### week2 퀘스트 2 - AI를 통해 핵심 학습 키워드를 뽑고 학습하기
- 미션에 관한 학습 키워드는 이미 제공되는데 다시 AI한테 받아야할까?
- AI는 문제를 해결하기 위한 수단으로 사용해야하는데 이 퀘스트가 수단으로 쓰는 방법인가?
    - 프롬프트에 따라 다를 수 있다. 개인적으로 야크털깍기를 방지하는 도구(학습 범위를 제한하는 도구)로 사용하면 괜찮을 것 같다.
    - 누가 질문하느냐에 따라 다르다. 아무 지식이 없는 사람은 중요한 것을 판가름 불가능해서 AI에게 끌려다닌다.
- 길잡이 자료와 AI가 만든 학습키워드를 비교하면서 AI를 학습시켜 사용해볼 수는 없을까?
- 달성 기준에서 실행 검증이 막히는 부분이 현저히 줄어듦? 판단이 불가능한 것 같다.

### week2 퀘스트 3 - 학습 내용을 기반으로 AI 만화 생성
- 아하 모먼트에 대한 만화가 개념의 이해에 도움이 되는건가?
  - 만화가 부정확한지 확인 하는 과정이 학습이다.
- 만화가 아닌 다른 방법은 없을까?
- 아하 모먼트를 공유하는 것은 커뮤니티 활성화에 의미가 있는 행동이다.
- 이전 분들이 왜 아무도 안했을까? 어떤 어려움이 있을까?
  - 난이도가 높아서 수행하기 힘들어서 그런것 같다
    - 4컷 만화 직접 만들어봤는데 클로드는 생성이 안된다.
    - GPT는 영어면 생각보다 잘 만드는 데 대사가 한글이면 이상한 글을 작성해서 피그마로 대사를 수정했다(예시에서도 깨진다)
      - 직접 대사를 수정을 하면 AI 활용하는 의미가 희석되지 않을까?

### week2 퀘스트 4 - 학습 내용을 기반으로 모의 면접 진행하기
- 진짜 도움이 될 것 같은 퀘스트인 것 같다.
  - 상황극처럼 AI와 면접을 진행하면 더 좋지 않을까?
- 잘 모르는 데 부정확한 AI의 답을 믿는 문제가 생길 수 있지 않을까?
  - 이러한 제약을 줄이기 위해 "학습 정리 마크 다운"을 업로드 해서 내가 공부한 내용을 바탕으로 퀴즈를 내면 된다
  - AI의 답이 부정확한 것이 문제라면 답의 출처를 알려달라고 해도 괜찮을 것 같다.
  - AI 모델을 퍼플렉시티를 사용하면 좀 더 정확하게 할 수 있을 것 같다.
      - 퍼플렉시티를 쓰더라도 링크를 타고 들어가야 검증 가능한데 시간이 없어서 힘들었다.
      - 나중에 실제로 사용한다면 크로스 체킹까지 하면 좋을 것 같다.
- 인터넷에서 공신력있는 자료가 있을까?
  - 공식 문서는 공신력이 있다.
  - AI에게 공식 문서에 대한 내용 위주로 답을 하게 하자

## 조사하기

### 학습 내용을 기반으로 모의 면접 더 잘 쓸 수 있는 방법이 뭐가 있을까?
- 방법1. 페르소나 부여하기(역할 설정)
- 방법2. 자신의 정보를 주입하기(백엔드 개발자, 자바스크립트 사용자 등)
- 방법3. 학습 내용에 대한 근거가져오기(AI와 사람 둘 다)
  
#### 프롬프트
```markdown
목적: 면접 대비 및 개념 설명력 향상

내가 공부한 내용은 아래에 정리돼 있어.
이 내용을 바탕으로 모의 면접을 진행해줘. 아래의 조건을 반드시 따라줘.

---
[내 학습 정리 내용]
<여기에 정리 내용을 붙여넣어줘>
---

역할 설정:
너는 “면접관 역할”을 맡아.  
면접관의 타입은 “고수 면접관” / “압박 면접관” / “모르는 친구” 중에서 무작위로 선택해 진행해줘.

진행 흐름:
1. 정리 내용을 바탕으로, 2~3개의 면접 질문을 순차적으로 출제해줘.
2. 내가 답변하면, 답변에 대해 구조, 정확성, 표현력, 오해 가능성 등을 기준으로 상세 피드백을 줘.
3. 그 후, 내 답변의 부족한 점 또는 연계 개념을 기반으로 “꼬리 질문”을 해줘.
4. 내가 답하면, 반박 질문이나 실제 상황 기반 질문으로 확장해줘 (예: 실무 시나리오, 도구 사용, 오류 분석 등).
5. 마지막엔 내가 놓친 개념/표현을 중심으로 전체 요약과 “오답노트” 항목을 제안해줘.

 주의할 점:
- 내 답변이 틀리거나 애매하면 무조건 부드럽게 짚어주되, 왜 그런지를 꼭 설명해줘.
- 너의 설명이 애매하거나 최신 정보가 아닌 경우, “검증 필요” 마크를 붙여줘.
- 너의 설명을 확인할 수 있는 출처를 같이 표시해줘.(참고문헌 표시, 인용부분 표시)

준비됐으면 질문부터 시작해줘
```

### AI 만화에서 한글이 안깨지도록 대사를 만들게 할 수 있을까?
- [ChatGPT 이미지 생성에서 한글 깨짐을 줄이고 완성도 높은 만화를 만드는 방법](https://tilnote.io/pages/67f59afb780f909dbb896df9)
  - GPT 만화 프롬프트 생성기를 활용해 만화 스타일, 컷수, 스토리 아이디어를 통해 프롬프트 생성
  - 생성된 프롬프트로 만화 생성

#### 프롬프트
```markdown
Create a 4-panel comic in Studio Ghibli style, characterized by soft painterly textures, warm and nostalgic lighting, expressive character designs, and lush detailed backgrounds. The comic follows three characters: Dana, a calm and responsible 10-year-old girl with medium-length black hair in braids and wearing a yellow cardigan with a floral skirt; Shia, her cheerful 6-year-old sister with short brown hair and a pink dress with overalls; and Chamchi, a plump calico cat with a small red backpack. All characters must remain visually consistent across all panels.

The setting is a peaceful, magical countryside with vibrant nature and small fantasy elements. Each panel should include natural Korean dialogue text, clearly visible and accurately rendered in a warm, rounded Korean font (similar to “Jeju Gothic”), placed as part of the scene or in small speech bubbles.
...
Panel 4: The three sit at a tree stump table, happily eating cake together under dappled sunlight. Peaceful and heartwarming mood.
Korean text (narration, top corner):
“이 순간만큼은 세상에서 제일 달콤했어요.”
```
#### 프롬프트 실행 결과

<img width="1024" height="1536" alt="image" src="https://github.com/user-attachments/assets/63c4de8f-9470-4e04-9fb9-c2400028155f" />

### 아하 모먼트 만화가 아닌 다른 방법으로 공유하는 방법이 뭐가 있을까?
- 1. AI로 요약하고 쉽게 설명하기
    이점: "초등학생도 이해할 수 있게 요약"을 하여 공유하고자 하는 정보를 보다 많은 사람들에게 공유할 수 있음.
    단점: 공유하는 정보가 지나치게 "전문적"인 영역이라면, 쉽게 풀이하는 과정에서 내용의 본질이 흐려질 수 있음.

- 2. AI가 만들어주는 시각 자료 (만화 제외)
    이점: 숫자나 데이터가 많은 정보라면 "그래프/차트" 등을 제작하여 공유할 수 있음.

- 3. AI 목소리로 듣는 정보
    이점: 글로된 정보를 AI의 목소리 TTS로 바꿔서 오디오 파일로 변환하여 공유할 수 있음. (시각장애인에 대한 배려)
    단점: 이어폰 또는 스피커와 같은 오디오를 듣기 위한 장비가 필요함, 또한 오디오를 재생해도 지장이 없는 적합한 장소여야함.

### 퀘스트 2에서 키워드 제한을 어떻게 활용하면 좋을까? 
- 구체적인 프롬프팅 가이드를 제공하면 좋을 것 같다.
  
#### 프롬프팅 템플릿
  
```markdwon
"다음 미션을 수행하는 데 필요한 핵심 CS 개념을 3-5개만 추천해주세요.
- 미션 내용: [미션 설명 붙여넣기]
- 조건: 구현에 직접적으로 필요한 개념만 포함
- 형식: 키워드명 + 한 줄 설명
- 난이도: 신입 개발자 수준"
```
- 예시 결과
  
```markdown
1. HTTP 통신 - 웹 요청/응답 구조와 상태코드
2. DOM 조작 - HTML 요소 선택과 데이터 추출  
3. 비동기 처리 - Promise/async-await 패턴
```

## 퀘스트 제작하기


