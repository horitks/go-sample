# go-sample

## Description
- 個人用としてgolangで手軽に実行できるように最小のコンテナサンプルを用意

## Usage
### 構築(build)

```
docker-compose up --build -d
```

### 起動(start up)

```
docker-compose up -d
```

### 確認(ps)

```
docker-compose ps
```

or

```
docker ps
```

### 実行(exec)

```
docker-compose exec golang go run main.go
```


