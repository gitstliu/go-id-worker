# go-id-worker

IdWorker in golang.

[HTTP Interface Open source project](https://github.com/gitstliu/idservice)
https://github.com/gitstliu/idservice

go-id-worker is an id creator, for generating a global unique id. The type of id is int64.

## You can get it like this.
```
go get "github.com/gitstliu/go-id-worker"
```

## And import it like this.
```
import (
  "github.com/gitstliu/go-id-worker"
)
```

## Create and use an idWorker like this.
```
currWoker := &idworker.IdWorker{} 
currWoker.InitIdWorker(1000, 1)
newId , newIdErr:= currWoker.NexiId()
......
```




	
