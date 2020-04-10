# 카카오의 신입 개발자가 된 존나팸!

# OT가 끝난 직후 한통의 [**메일**](https://github.com/joshua-dev/kakao-cafe/blob/master/com/kakao/cafe/README.md)을 받게 되는데...

[![thumbnail](https://t1.daumcdn.net/tvpot/thumb/v0431dmoadPdi6PH44oFHci/thumb.png?time=1490071671642)](https://boyzmsc.github.io/kakao-cafe/)

<br>

[![GitHub license](https://img.shields.io/badge/license-MIT-green)](https://github.com/joshua-dev/kakao-cafe/blob/master/LICENSE)
[![Slack](https://img.shields.io/badge/chat%20on-Slack-4A154B)](https://jonnafamily.slack.com/)
[![Notion](https://img.shields.io/badge/spec-Notion-000000)](https://www.notion.so/jonnafamily)

<br>

## Result

<img width="857" alt="kakao_cafe_start" src="https://user-images.githubusercontent.com/29545214/78376232-fd514880-7608-11ea-8e9a-10d6a28d489e.png">

<img width="857" alt="kakao_cafe_order" src="https://user-images.githubusercontent.com/29545214/78376289-0fcb8200-7609-11ea-8a8f-cd28fd1565bf.png">

<img width="857" alt="kakao_cafe_end" src="https://user-images.githubusercontent.com/29545214/78376330-1f4acb00-7609-11ea-9f07-264e5e47879f.png">

<br><br>

## Run

```shell
$ make
```

<br><br>

## :pushpin: Tips

### Python virtualenv, virtualenvwrapper 설치

```shell
$ pip3 install --upgrade pip
$ pip install virtualenv virtualenvwrapper
```

### 가상환경 생성

```shell
$ virtualenv venv --python=python3
```

### 가상환경 활성화/비활성화

- #### 활성화

  ```shell
  $ source venv/bin/activate
  ```

- #### 비활성화
  ```shell
  (venv) $ deactivate
  ```

<br>

### 의존성 패키지 관리

- #### 현재 설치된 패키지들을 저장

  ```shell
  (venv) $ pip freeze > requirements.txt
  ```

- #### requirements.txt에 저장된 패키지 설치

  ```shell
  (venv) $ pip install -r requirements.txt
  ```

<br>

### make를 이용한 구동 및 테스트 단순화

- #### Python 단위 테스트

  - 모든 테스트 실행
    
    ```shell
    (venv) $ make test
    ```
    <br><br>
  - CafeMenu 테스트

    ```shell
    (venv) $ make cafemenu
    ```
    <br><br>
  - Espresso 및 하위 클래스 테스트

    ```shell
    (venv) $ make espresso
    ```
    <br><br>
  - Smoothie 및 하위 클래스 테스트
  
    ```shell
    (venv) $ make smoothie
    ```
    <br><br>
  - Tea 및 하위 클래스 테스트

    ```shell
    (venv) $ make tea
    ```
    <br><br>
  - Ade 및 하위 클래스 테스트
  
    ```shell
    (venv) $ make ade
    ```
    <br><br>
  - Dessert 및 하위 클래스 테스트

    ```shell
    (venv) $ make dessert
    ```
    <br><br>
  - Module 및 구현 클래스 테스트

    ```shell
    (venv) $ make module
    ```
  
  <br>


## :white_check_mark: TODO

#### 카페 메뉴 클래스

- [x] 추상 클래스 CafeMenu 구현 및 테스트 코드 작성

<br>

- [x] Espresso 클래스 구현 및 테스트 코드 작성
- [x] Americano 클래스 구현 및 테스트 코드 작성
- [x] Latte 클래스 구현 및 테스트 코드 작성
- [x] VanillaLatte 클래스 구현 및 테스트 코드 작성
- [x] CaramelMacchiato 클래스 구현 및 테스트 코드 작성
- [x] Cappuccino 클래스 구현 및 테스트 코드 작성
- [x] CafeMocha 클래스 구현 및 테스트 코드 작성
- [x] GreenTeaLatte 클래스 구현 및 테스트 코드 작성

<br>

- [x] 추상 클래스 Smoothie 구현 및 테스트 코드 작성
- [x] BerryBerrySmoothie 클래스 구현 및 테스트 코드 작성
- [x] PineappleSmoothie 클래스 구현 및 테스트 코드 작성
- [x] YogurtSmoothie 클래스 구현 및 테스트 코드 작성

<br>

- [x] 추상 클래스 Tea 구현 및 테스트 코드 작성
- [x] IceTea 클래스 구현 및 테스트 코드 작성
- [x] GreenTea 클래스 구현 및 테스트 코드 작성
- [x] ChamomileTea 클래스 구현 및 테스트 코드 작성
- [x] PeppermintTea 클래스 구현 및 테스트 코드 작성
- [x] LavenderTea 클래스 구현 및 테스트 코드 작성
- [x] RooibosTea 클래스 구현 및 테스트 코드 작성
- [x] HibiscusTea 클래스 구현 및 테스트 코드 작성
- [x] 추상 클래스 MilkTea 구현 및 테스트 코드 작성
- [x] RoyalMilkTea 클래스 구현 및 테스트 코드 작성
- [x] MatchaMilkTea 클래스 구현 및 테스트 코드 작성

<br>

- [x] 추상 클래스 Ade 구현 및 테스트 코드 작성
- [x] StrawberryAde 클래스 구현 및 테스트 코드 작성
- [x] LemonAde 클래스 구현 및 테스트 코드 작성
- [x] OrangeAde 클래스 구현 및 테스트 코드 작성

<br>

- [x] 추상 클래스 Dessert 구현 및 테스트 코드 작성
- [x] NewYorkCheeseCake 클래스 구현 및 테스트 코드 작성
- [x] TiramisuCake 클래스 구현 및 테스트 코드 작성
- [x] RedVelvetCheeseCake 클래스 구현 및 테스트 코드 작성
- [x] RainbowCheeseCake 클래스 구현 및 테스트 코드 작성
- [x] 추상 클래스 Waffle 구현 및 테스트 코드 작성
- [x] BelgianWaffle 클래스 구현 및 테스트 코드 작성
- [x] IceWaffle 클래스 구현 및 테스트 코드 작성
- [x] FruitsWaffle 클래스 구현 및 테스트 코드 작성

<br>

- [x] Branch 간 Merge 및 Comflict 해결

<br>

#### 결제 모듈 클래스

- [x] 인터페이스 CafeWorker 구현 및 테스트 코드작성
- [x] MenuPrinter 클래스 구현 및 테스트 코드 작성
- [x] OrderTaker 클래스 구현 및 테스트 코드 작성
- [x] OrderChecker 클래스 구현 및 테스트 코드 작성
- [x] PaymentManager 클래스 구현 및 테스트 코드 작성
- [x] ReceiptPrinter 클래스 구현 및 테스트 코드 작성
- [x] 메인 모듈 구현

<br>

#### 기타

- [x] 예외 처리

<br><br>

## :octocat: Git

#### Git config settings

<pre>
$ git config --global user.name <b><i>"Your Name"</i></b>
$ git config --global user.email <b><i>"you@your-domain.com"</i></b>
$ git config --global core.precomposeunicode true
$ git config --global core.quotepath false
</pre>

<br>

#### Git 프로젝트 디렉토리 생성 및 원격 저장소 연결

<pre>
$ mkdir <b><i>YOUR_DIRECTORY_NAME</i></b>
$ cd <b><i>YOUR_DIRECTORY_NAME</i></b>
$ git init
$ git remote add origin <b><i>YOUR_GIT_REPOSITORY_ADDRESS</i></b>
$ git pull origin master
</pre>

<br>

#### Git branch 생성

<pre>
$ git branch <b><i>YOUR_BRANCH_NAME</i></b>
</pre>

<br>

#### Git branch 변경

<pre>
$ git checkout <b><i>YOUR_BRANCH_NAME</i></b>
</pre>

<br>

#### 현재 Git 레포지토리 상태 확인

```shell
$ git fetch
```

<br>

#### 현재 Git 디렉토리 상태 확인

```shell
$ git status
```

<br>

#### Git에 커밋하기

<pre>
$ git add .
$ git commit -m <b><i>"COMMIT_MESSAGE"</i></b>
$ git push origin <b><i>YOUR_BRANCH_NAME</i></b>
</pre>

<br><br>

## [LICENSE](https://github.com/joshua-dev/kakao-cafe/blob/master/LICENSE)
