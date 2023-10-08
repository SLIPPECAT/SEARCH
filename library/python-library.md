### hwp 전처리
```Python
!pip install olefile
import olefile
```

```Python
path = "/파일위치/파일이름.hwp"
f = olefile.OleFileIO(path)
# 미리 보기 뷰로 내용 훑어보기
encoded_txt = f.openstream("PrvText").read()
text = encoded_txt.decode("utf-16, errors="ignore")
print(text)
```
