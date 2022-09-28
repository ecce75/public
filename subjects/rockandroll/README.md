## rockandroll

### Instructions

Write a function called `RockAndRoll()` that takes an `int` and returns a `string`.

- If the number is divisible by 2, print `rock` followed by a newline `\n`.
- If the number is divisible by 3, print `roll` followed by a newline `\n`.
- If the number is divisible by 2 and 3, print `rock and roll` followed by a newline `\n`.

### Expected function

```go
func RockAndRoll(n int) string {

}
```
### Usage

Here is a possible program to test your function:

```go
package main

import (
        "fmt"
        "piscine"
)

func main() {
        fmt.Println(piscine.RockAndRoll(4))
        fmt.Println(piscine.RockAndRoll(9))
        fmt.Println(piscine.RockAndRoll(6))
}
```
And its output:

```console
rock$
$
roll$
$
rock and roll$
$
```