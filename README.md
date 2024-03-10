```
// Test all but taged
go test -v .

// Test all and taged (each)
go test -v -tags integration
go test -v -tags db

// Test all and taged (two tags)
go test -v -tags integration,db
```