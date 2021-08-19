# Faker
![badge](https://github.com/walkersumida/faker/actions/workflows/test.yml/badge.svg)

## Getting Started
### Download

```
go get -u github.com/walkersumida/faker
```

### Usage

```golang
import 	"github.com/walkersumida/faker"

profile := faker.Profile

fmt.Println(profile.EnCompany)
// => "Suzuki Capital Partners, Inc."

fmt.Println(profile.JaKanjiFullName)
// => "鈴木 一郎"

fmt.Println(profile.EnFullName)
// => "Ichiro Suzuki"

fmt.Println(profile.Email)
// => "ichiro.suzuki@example.com"

fmt.Println(faker.Uuid)
// => "add0de95-6d27-44de-ab7a-d45998bc6b05"

fmt.Println(faker.Text("abcあいう", 10))
// => "abcあいうabcあ"
```
