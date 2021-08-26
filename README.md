# Raptor Docker

### Usage
```
$ docker run -v $(pwd):/work --rm sparqling/rapper -g -c raptor.rdf
```
Or by defining alias,
```
$ alias d.cmd='docker run -v $(pwd):/work --rm'
$ d.cmd sparqling/rapper -g -c raptor.rdf
```
