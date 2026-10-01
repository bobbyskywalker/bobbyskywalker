### About Me

```go
package main

import "fmt"

type bobbyskywalker struct{}

func (b bobbyskywalker) introduce() {
	fmt.Println("Hi there, I'm Olek")
	fmt.Println("Software Developer from Poland 🇵🇱")
	fmt.Println("42 Warsaw Alumni 🎓")
}

func (b bobbyskywalker) listLanguages() {
	fmt.Println("I code professionally in Java, though I am keen especially on: C, C++ & Go)
}

func (b bobbyskywalker) showHobbies() {
	fmt.Println("I love basketball and retro games")
}

func main() {
	me := bobbyskywalker{}
	me.introduce()
	me.listLanguages()
	me.showHobbies()
}
```
### want to connect?

LinkedIn: https://www.linkedin.com/in/aleksander-garbacz-6495522a4/
