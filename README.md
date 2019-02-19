# Monthly Employee Payslip Processor

---

### Prerequisites

  - Java 8
  - Gradle 3.3+

### Installation (OSX)

```
$ brew update && brew tap caskroom/versions && brew cask install java8
$ brew install gradle
```

### Build

`$ gradle build`

### Test

`$ gradle test`

### Run

`gradle run -Pmargs="['arg1', 'arg2']"`

(Note all quotations required)

**Run Example** :rocket:

`$ gradle run -Pmargs="['Matt', 'Witherow']"`

`$ Hello Matt Witherow`
