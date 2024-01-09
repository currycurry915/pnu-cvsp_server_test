# pnu-cvsp_server_test

서버를 이용하는 방법을 실습하기 위해 만들었습니다.

먼저 이 repository를 다운로드한 후 서버로 파일을 옮겨 주세요.

직접 다운로드도 가능하지만, "git clone" 명령어를 통해 서버에서 직접 다운로드 받을 수 있습니다.

``` bash
git clone https://github.com/currycurry915/pnu-cvsp_server_test.git
```
이 명령어 뒤에 따로 디렉토리 주소를 작성하지 않는다면, 현재 디렉토리에 다운로드가 진행됩니다.



다음으로는 가상환경을 생성 해주세요. 가상환경은 아래의 코드들 중 하나를 선택하여 생성할 수 있습니다.

``` bash
# 1: 가상환경 생성 후 필요한 package 설치

conda create -n server-test python=3.8
conda activate server-test

pip install -r requirements.txt
```

``` bash
# 2: conda 명령어를 통해 가상환경과 필요 package를 한번에 생성 및 설치

conda env create -f environment.yaml
conda activate server-test
```
