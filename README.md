# golang



- go 파일 형식 맞추기

```
gofmt -w <gofile>
```



- 잘못된 import 변경하기

```
goimports -w <gofile>
```



- go 파일 실행하기

```
go run <gofile>
```



- go 파일 설치하고 수행하기

  이미 bin 디렉터리가 PATH에 추가 되었으므로 바로 실행 가능

```
go install github.com/<username>/<repo>/<dir>
<gofile>
```



- 패키지 import

  패키지 안의 **대문자로 시작하는 함수들은 접근이 가능**하다. 

  다른 패키지에서 함수를 이용할 수 없게 하려면 첫 글자를 소문자로 변경해야 한다.

```
import "github.com/<username>/<repo>/<dir>"
```

메인 패키지와 라이브러리 패키지 파일들은 같은 디렉터리에 들어갈 수 없다.



- test

```
go test github.com/<username>/<repo>/<dir>
```





+추가

go 패키지 doc : https://godoc.org



