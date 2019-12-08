# go-snowflake

golang 雪花算法实现

```go
g := NewIdGenerator(1)

for i := 0; i < 100; i ++ {
    now := g.NextId()
}
```
