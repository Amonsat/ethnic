# ethnic
Go lib for determine ethnic group of familyname.
## Use

### Instalation
```
	go get github.com/amonsat/ethnic
```
### Basic Use

```go
package main
import "github.com/amonsat/ethnic"

func main() {
    prefLangs, suffLangs := ethnic.ParseFamilyname("de la Vega")
	println("familyname: %v | prefLangs: %v | suffLangs: %v\n", familyname, prefLangs, suffLangs)
}
```

## Credits and precursors

My thanks to Wikipedia and authors of this article.

List of family name affixes
https://en.wikipedia.org/wiki/List_of_family_name_affixes