

# 파일을 업로드 하는 방법

``` 
  files = {'files': ('name.jpg', binary, 'image/jpg')} 

  requests.post(URL, headers=headers, files=files)
```

## files 에 보내는 튜플 정보
첫번째 인수 : 이름
두번째 인수 : 바이너리 (bytes)
세번째 인수 : MIME TYPE

