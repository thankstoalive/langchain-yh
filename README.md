# langchain-yh

## 환경 설정

### 1. conda 가상환경 생성
- python 3.11 버전의 conda 가상환경을 생성합니다.

```sh
conda create --name langchain-yh python=3.11
```

### 2. 필수 패키지 설치
- 기본적으로 필요한 패키지를 설치합니다.

```sh
pip install python-dotenv
```

- 환경 변수를 관리를 위해 `.env` 파일을 생성하고 API 키 등을 저장합니다.

### 3. 테디노트의 requirments 파일로 패키지 설치
테디노트가 정리한 패키지 목록을 사용하여 추가 패키지를 설치합니다.

```sh
!pip install -r https://raw.githubusercontent.com/teddylee777/langchain-kr/main/requirements.txt
```

테스트