# tasks-go

### Iniciar projeto:
##### 1. `touch tasks.db`

##### 2. `sqlite3 tasks.db`
    CREATE TABLE IF NOT EXISTS  tasks {
        id INTEGER PRIMARY KEY AUTOINCREMENT,
        title TEXT,
        description TEXT,
        status TEXT,
        created-at DATETIME
    }


##### 3. `go run main.go`
