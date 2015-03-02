# go-detect-race

Check if the race detector is running.

I didnt find a variable to check quickly enough so I made this.


## Usage

```go
import (
  detectrace "github.com/jbenet/go-detect-race"
)

func main() {
  if detectrace.WithRace() {
    // running with -race
  } else {
    // running without -race
  }
}
```
