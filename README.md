# Simple Service

```yaml
system: sysmodel
visibility: public

description: |
  some arbitrary text here with bla bla bla
  that can span multiple lines
  and: look like yaml
    foo: 111

dependencies:
  db:
    id: sysmodel:db

facts:
  serviceDiscovery: [some-name, and, more]
  image: spotify:80/something
  foo: bar
  bax: quax
  structured:
    data: in here
    and: 1928
    with: true

```

And this is only an example service, with more lipsum here...
