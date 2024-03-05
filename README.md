# CORE INITIALLIZER 
golang модуль для быстрого развертывания сервисов. Совместим с sql/mysql базами данных, брокерами сообщений rabbitMQ/kafka и noSQL DB Redis.
## How to install 
go get github.com/KA1251/CoreModule
## Example of usage
```go
func main() {
	var testCon core.ConnectionHandler
	core.Initiallizing(&testCon)
}
```
