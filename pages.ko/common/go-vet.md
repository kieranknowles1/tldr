# go vet

> Go 소스 코드를 검사하고 의심스러운 구조를 보고합니다 (예: Go 소스 파일을 린트).
> 문제가 발견되면 go vet는 0이 아닌 종료 코드를 반환하고, 문제가 없으면 0 종료 코드를 반환합니다.
> 더 많은 정보: <https://pkg.go.dev/cmd/vet>.

- 현재 디렉토리의 Go 패키지 검사:

`go vet`

- 지정된 경로의 Go 패키지 검사:

`go vet {{경로/대상/파일_또는_폴더}}`

- go vet로 실행할 수 있는 사용 가능한 검사 목록 나열:

`go tool vet help`

- 특정 검사의 세부정보 및 플래그 보기:

`go tool vet help {{검사_이름}}`

- 문제 있는 줄과 그 주변의 N 줄을 표시:

`go vet -c={{N}}`

- 분석 결과와 오류를 JSON 형식으로 출력:

`go vet -json`
