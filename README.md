<h1 align="center">Hi 👋, I'm Adi Khoiron Hasan</h1>

```go
package main

import "fmt"

type Profile struct {
	Name         string
	Role         string
	Hobbies      []string
	Databases    []string
	Technologies []string
}

func (se *Profile) sayHi() {
	fmt.Println("Thank you for stopping by, Hope you found something interesting and useful. :)")
}

func main() {
	me := &Profile{
		Name:         "Adi Khoiron Hasan",
		Role:         "Backend Engineer",
		Hobbies:      []string{"Coding", "Music", "Game"},
		Databases:    []string{"MySQL", "PostgreSQL", "Redis"},
		Technologies: []string{"Golang", "Laravel", "Docker", "gRPC", "Kafka"},
	}

	me.sayHi()
}
```
### Contact
- [adikhoironhasan@gmail.com](mailto:adikhoironhasan@gmail.com) on Email
- [linkedin.com/in/adi-khoiron-hasan](https://linkedin.com/in/adi-khoiron-hasan) on LinkedIn
