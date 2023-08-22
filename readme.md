Why

I am learning backend developement using go.

I am recreating a backend app I made while learning Express

Features

- docker
- postgres
- picocss-v2

---

| method | url pattern        | handler         | action                     |
| ------ | ------------------ | --------------- | -------------------------- |
| ANY    | /                  | home            | display home page          |
| ANY    | /message/view?id=1 | `messageView`   | display a specific message |
| POST   | /message/create    | `messageCreate` | create a new message       |

```go
type Message struct {
  Text string
  User string
  added string
}
```
