Why

I am learning backend developement using go.

I am recreating a backend app I made while learning Express

Features

- docker
- postgres
- tailwindcss

---

2 routes:

- "/": show messages
- "/new": page to create messages

```go
type Message struct {
  Text string
  User string
  added string
}
```
