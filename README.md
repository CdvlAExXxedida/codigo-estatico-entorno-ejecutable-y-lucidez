# Código estático, entorno ejecutable y lucidez

Autor: Diego Armando Alfaro Reséndiz

Repositorio contenedor de la publicación comprimida.

El workspace no existe expandido en este repositorio. Existe únicamente dentro de:

```text
codigo_estatico_workspace_comprimido.tar.gz
```

## Descompresión

```bash
tar -xzf codigo_estatico_workspace_comprimido.tar.gz
cd codigo_estatico_workspace
```

## Ejecución verificable

```bash
./run.sh
```

SHA256 esperado del manuscrito generado por la ejecución:

```text
99834a37d771792667492e0e27b5c1442618de5ea6128dc66c6ae29305ac6a68
```

## Verificación del comprimido

```bash
sha256sum -c codigo_estatico_workspace_comprimido.tar.gz.sha256
```

## Nota de integridad

El archivo comprimido contiene el workspace completo, incluyendo:

- `dist/manifest.json`
- `EXECUTION_SHA256.txt`
- `SHA256SUMS.txt`
- `build.py`
- `run.sh`
- `sections/`

El repositorio funciona como contenedor público fechado. La obra y su mecanismo de ejecución aparecen al descomprimir.
