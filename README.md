### About Me 🤓

```go
package main

import "fmt"

type bobbyskywalker struct{}

func (b bobbyskywalker) introduce() {
	fmt.Println("Hi there 👋 I'm Olek!")
	fmt.Println("I'm a Software Developer from Poland currently studying at 42 Warsaw 🇵🇱🎓")
}

func (b bobbyskywalker) listLanguages() {
	fmt.Println("💻 I code in: C, C++, Go, Java & Python)
}

func (b bobbyskywalker) showHobbies() {
	fmt.Println("🎯 When I'm not coding, I'm probably during a flight, gaming or playing basketball!")
}

func (b bobbyskywalker) funFact() {
	fmt.Println("💡 Fun fact: my cat hates me for debugging stuff out loud lol")
}

func main() {
	me := bobbyskywalker{}
	me.introduce()
	me.listLanguages()
	me.showHobbies()
	me.funFact()
}
```
### 👨‍💻 Want to connect?

LinkedIn: https://www.linkedin.com/in/aleksander-garbacz-6495522a4/
