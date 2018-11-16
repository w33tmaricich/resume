# Resume - Versioned.

My resume, version controlled.

## groff

### install
```
$ sudo apt install -y groff
```
### compile
If you need a refresher on how to use ms, check the `groff_ms` man page or
the gist you created.

```
$ ls
myresume.ms
$ groff -m ms myresume.ms -T pdf > myresume.pdf
$ ls
myresume.md myresume.pdf
```
