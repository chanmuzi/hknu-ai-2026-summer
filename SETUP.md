# 실습 환경 세팅 가이드 (1차시)

설치 없이 **Google Colab**에서 바로 실행합니다. 아래 순서대로 따라오세요.
> 이미지는 저장소 `images/` 폴더에 캡쳐를 넣으면 아래에 표시됩니다.

## 1. Google 계정 준비
Colab을 쓰려면 Google 계정이 필요합니다. **이미 있으면 그대로** 쓰고, 없으면 [가입](https://accounts.google.com/signup)하세요.

![Google 계정 만들기](images/google_signup.png)

> GitHub 계정은 **필수가 아닙니다.** 공개 저장소의 노트북은 로그인 없이 Colab으로 열 수 있어요. (직접 수정본을 저장·fork 할 때만 필요)

## 2. Colab 접속 & 새 노트
1. <https://colab.research.google.com> 접속
2. **새 노트** 만들기

![Colab 새 노트북](images/colab_new_notebook.png)

## 3. 첫 코드 실행
코드 셀에 입력하고 **▶ (Shift + Enter)** 로 실행:
```python
print("Hello, AI!")
```

![첫 코드 실행](images/colab_hello_ai.png)

## 4. 환경 설정
### 4-1. 런타임 유형 (GPU)
상단 **런타임 → 런타임 유형 변경 → 하드웨어 가속기에서 GPU** 선택. (딥러닝 차시에서 사용)

![런타임 유형 변경](images/colab_runtime_2.png)

### 4-2. 구글 드라이브 마운트
좌측 **폴더 아이콘 → 드라이브 마운트**. 작업한 노트와 데이터를 저장·불러올 수 있습니다.

![드라이브 마운트](images/colab_drive_mount.png)

## 5. GitHub에서 실습 파일 열기
1. 강의 저장소 접속: <https://github.com/chanmuzi/hknu-ai-2026-summer>
2. README의 **Open in Colab** 배지를 클릭하면 해당 노트북이 Colab에서 열립니다.

![강의 저장소 README의 Open in Colab 배지](images/github_repo.png)

## 6. 첫 실습 노트 실행
`session-1-ai-intro/s1-01-첫파이썬-실습.ipynb` 가 Colab에서 열리면 위에서부터 **▶ 실행** → "환경 준비 완료"가 나오면 끝!

![Colab에서 열린 1차시 노트북](images/colab_s1.png)
