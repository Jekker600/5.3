# 5.3
- Проблема с заданием 3
- Пытаюсь запустить контейнер с примонтированной папка из под Windows, но docker выдает ошибку
```
C:\Users\e.parshin>docker run -v C:\info:\share\info -d centos
a92c37cc38b86743f8d486f5f60aef4a4ec76a801429fa2e52e0bc84ae79caa8
docker: Error response from daemon: OCI runtime create failed: invalid mount {Destination:\share\info Type:bind Source:/run/desktop/mnt/host/c/info Options:[rbind rprivate]}: mount destination \share\info not absolute: unknown.
```
- Или из под windows нельзя примонтировать папку на centos?
