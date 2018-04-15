### Elastic Stack을 활용한 Dashboard 만들기
---

#### 안내

* 이 repository는 지속적으로 업데이트가 진행됩니다. (`<>Code`, `Issues`, `Wiki`)
* repository 요소별 안내
    * `Code` : Elastic Stack 흐름에 관한 전반적인 설명
    * `Issues` : 자주 들어온 질문 정리
    * `Wiki` : Elastic Stack 사용법에 초점을 맞춘 간단 사용 설명서

#### 설치

[![elastic stack install guide](https://asciinema.org/a/176392.png)](https://asciinema.org/a/176392)

| Type        | Protocol           | Port Range  | Source | Description
| :------------- |:-------------:| :-----:| :----: | :---|
| SSH      | TCP | 22 | Custom 0.0.0.0/0 | ssh
| Custom TCP      | TCP | 9200 | Custom 0.0.0.0/0 | elasticsearch REST
| Custom TCP      | TCP | 9300 | Custom 0.0.0.0/0 | elasticsearch node communication
| Custom TCP      | TCP | 5601 | Custom 0.0.0.0/0 | kibana

#### 기타

* 내용에 대한 피드백(틀린 내용, 설명의 애매함, version upgrade 등)은 언제든지 편하게 알려주세요.
* 데이터는 랜덤으로 생성했으니 참고 바랍니다.
