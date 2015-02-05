# Simple Service

```
system: sysmodel
visible: true

image: spotify:80/something

description: |
  some arbitrary text here with bla bla bla
  that can span multiple lines
  and: look like yaml
    foo: 111

dependencies:
  db:
    id: sysmodel:db

facts:
  foo: bar
  bax: quax
  structured:
    data: in here
    and: 1928
    with: true
```

And this is only an example service, with more lipsum here...
