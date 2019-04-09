# My Resume - Versioned.

I got tired of loosing track of what was the most up to date on my resume. This
project holds a template of my resume that can be exported in any format
supported by groff.

## Setup

Install [groff](https://www.gnu.org/software/groff/)

```
$ sudo apt install -y groff
```

## Build resume.
If you need a refresher on how to use ms, check the `groff_ms` man page or
[this gist](https://gist.github.com/w33tmaricich/34711cffb9d9f16a9ac1c73fd59b101b)

```
$ ls
myresume.ms
$ groff -m ms myresume.ms -T pdf > myresume.pdf
$ ls
myresume.md myresume.pdf
```
