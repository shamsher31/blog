# Why I switched to Golang
> Posted on Feb 24, 2016 by Shamsher

We live in the world where [programming languages are born everyday](https://en.wikipedia.org/wiki/List_of_programming_languages). Each programming language solves a specific problem. We can use the power of the language to build truley amazing things that people care about. [Choosing language](http://blog.teamtreehouse.com/choose-programming-language) to build something you care about, depends on several different factors.

I always wanted to build software that are easy to write, easy to maintain and can be easily understood by others. In the beginning this looks fantastic when you are writing small software but what about large projects with distributed team and huge codebase.
It will become very difficult to maintain large codebase and difficult to understand for developer who recently join the team.

First thing that we do while learning any programming language is write `Hello World`.
This is the quickest way of getting started with any language. It gives us opportunity
to check how expressive and concise a language is. 

```go
package main
import (
  "fmt"
)
func main() { 
  fmt.Println("Hello World")
}
```
