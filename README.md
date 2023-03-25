```go
package main

import "fmt"

type Profile struct {
	Name         string
	Email        string
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
		Email:        "adikhoironhasan@gmail.com",
		Role:         "Backend Engineer",
		Hobbies:      []string{"Coding", "Music", "Game"},
		Databases:    []string{"MySQL", "PostgreSQL", "Redis"},
		Technologies: []string{"Golang", "Laravel", "Docker", "gRPC", "Kafka"},
	}

	me.sayHi()
}
```
