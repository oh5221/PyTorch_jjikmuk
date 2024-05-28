# PyTorch_jjikmuk
PyTorch로 시작하는 딥 러닝 입문 (https://wikidocs.net/book/2788) 따라하기


## Github에 Colab 노트북 게시하는 방법
[I am I 님 블로그 참조](https://velog.io/@shong676/Colab%EA%B3%BC-GitHub-%EC%97%B0%EB%8F%99%ED%95%98%EA%B8%B0)

1. Google Drive 접근
     ```python
     from google.colab import drive
     drive.mount('/content/drive')
     ```

2. Commit을 원하는 폴더로 이동
     ```python
     cd /content/drive/MyDrive/Github_Colab_Commit/PyTorch_jjikmuk
     ```

3. 본인 확인
     ```python
     !git config --global user.email '내 이메일'
     !git config --global user.name '내 사용자명'
     ```

4. 폴더 add
     ```python
     !git add '노트북이름'.ipynb
     ```

5. Commit하기
     ```python
     !git commit -m '커밋 메세지'
     !git push
     ```
