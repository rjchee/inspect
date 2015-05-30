inspect is a collection of operating system/application monitoring
analysis libraries and utilities. 

#### Installation
  1. get go
  2. go get -u -v github.com/square/inspect/...
  
The above commands should install three binaries.

1. inspect 
2. inspect-mysql (work in progress)
3. inspect-postgres (work in progress)

Please see subdirectories for more detailed documentation

#### Glossary
* cmd - Directory for command line programs based on the below libraries

<img src="https://raw.githubusercontent.com/square/inspect/master/cmd/inspect/screenshots/summary.png" height="259" width="208">

* os      - Operating system metric measurement libraries used by inspect.
* mysql   - MySQL metric reporting libraries.
* postgres  - Postgres metric reporting libraries.
* metrics/metricscheck - Simple metrics libraries for golang.
