# log4j-scanner

Script em Python para scanear diretórios afim de encontrar falhas no log4j.

## Como Executar o script em seu servidor

Exemplo de uso para scanear um path (por padrão /):

```python
$ python3 log4j-finder.py /caminho/do/scan
```

Ou diretamente um arquivo JAR:

```python
$ python3 log4j-finder.py /caminho/do/jarfile.jar
```

Ou Mutiplos diretórios:

```python
$ python3 log4j-finder.py /caminho/do/dir1 /caminho/do/dir2
```
