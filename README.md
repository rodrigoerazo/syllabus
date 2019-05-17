# Syllabus para la Olimpiada Chilena de Informática

## Compilar documento
```bash
$ make
```

## Publicar una nueva version


1. Instalar `publish-release` si no está instalado
```bash
$ npm i -g publish-release
```
1. Generar un token personal para github (https://github.com/settings/tokens) y guardarlo en el archivo `.github-token` (este archivo está en el `.gitignore`).
1. Correr script para publicar. El token de github es opcional, en caso de no ser provisto se interá leerlo del archivo `.github-token`. El `tag` debe ser el nombre del año antecedido por una `v`, por ejemplo, para el 2019 el tag debiese ser `v2019`.
```bash
$ ./publish <tag> [github-token]
```
