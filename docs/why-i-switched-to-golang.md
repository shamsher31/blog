# Why I switched to Golang
> Posted on Feb 24, 2016 by Shamsher

We live in the world where [programming languages are born everyday](https://en.wikipedia.org/wiki/List_of_programming_languages). Each programming language solves a specific problem. We can use the power of the language to build truley amazing things that people care about. [Choosing language](http://blog.teamtreehouse.com/choose-programming-language) to build something you care about, depends on several different factors.

I always wanted to build software that are easy to write, easy to maintain and can be easily understood by others. In the beginning this looks fantastic when you are writing small software but what about large projects with distributed team and huge codebase.
It will become very difficult to maintain large codebase and difficult to understand for developer who recently join the team.

Based on my past experince with [PHP](http://php.net/) and [NodeJs](https://nodejs.org/en/), I found it difficult to maintain and debug code specially when the product is used in a production. If you want to fix small bug or add some feature like changing button color from blue to white. The deployement which includes fetching module dependency, running unit test and end-to-end test takes hell lot of time to build and deploy new changes to production. Which will be pain for both the developers and customers to quickly get the new and updated feature.

In the war of new [programming languages](https://en.wikipedia.org/wiki/List_of_programming_languages) Google released [Golang or Go](https://golang.org/) which say's *Go is an open source programming language that makes it easy to build simple, reliable, and efficient software.*

First thing that came to my mind is write a `Hello World` program which will tell me how expressive and concise a language is.

```go
package main
import (
  "fmt"
)
func main() { 
  fmt.Println("Hello World")
}
```

But `Hello World` does not add any value to your product or website. *So why I choose golang ?* Well following are the list which suits what I want to achieve with golang.

* The most important feature that I like about golang is [cross compilation](https://github.com/mitchellh/gox) for multiple platform including Linux, Mac, Windows and many more. Add some sugar on top of it and you can easily [upload all your binaries to github](https://github.com/tcnksm/ghr).
* You can [compile and run go programes faster](https://www.youtube.com/watch?v=FTl0tl9BGdc) then some interpreter can even start.
* Statically linked single binary so deployement is faster and easy.
* Golang takes [less system resources](http://www.iron.io/how-we-went-from-30-servers-to-2-go/) which saves lot of your valuable money so you can buy things that your family needs.

Lot of companies around the world [succeeded with golang](https://github.com/golang/go/wiki/SuccessStories). If you really intrested to see what you can do with golang you can checkout my [next blog post](./what-you-can-do-with-golang.md).
