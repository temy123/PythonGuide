

# 파일을 업로드 하는 방법

``` 
  files = {'files': ('name.jpg', binary, 'image/jpg')} 

  requests.post(URL, headers=headers, files=files)
```

## files 에 보내는 튜플 정보
첫번째 인수 : 이름
두번째 인수 : 바이너리 (bytes)
세번째 인수 : MIME TYPE


### 참고자료
http://daplus.net/python-%ED%8C%8C%EC%9D%B4%EC%8D%AC%EC%9C%BC%EB%A1%9C-%EC%9A%94%EC%B2%AD%EA%B3%BC-%ED%95%A8%EA%BB%98-multipart-form-data%EB%A5%BC-%EB%B3%B4%EB%82%B4%EB%8A%94-%EB%B0%A9%EB%B2%95%EC%9D%80/
