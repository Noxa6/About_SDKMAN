# SDKMAN

A veces es necesario tener más de una versión de Java en un ambiente. Cuando esto ocurre siempre podemos instalar SDKMAN. 

Para poder usarlo en S.O Windows debemos instalar:

:white_check_mark: [Git Bash](https://git-scm.com/download/win)

:white_check_mark: [Zip](http://gnuwin32.sourceforge.net/packages/zip.htm)

:white_check_mark: [SDKMAN](https://sdkman.io/install)

## Pasos

1. Instalar Git Bash.

2. Instalar Zip.

3. Instalar SDKMAN.

4. Instalar Versión  de Java necesarias.

### Instalar SDKMAN

Para descargar instalador:

```bash
$ curl -s "https://get.sdkman.io" | bash
```

Para instalar lo descargado.

```bash
$ source "$HOME/.sdkman/bin/sdkman-init.sh"
```

Para ver versión de instalación.

```bash
$ sdk version
```

### Instalar Versión de Java necesaria

---

Para listar versiones y distribución disponibles

```bash
$ sdk list java
```

Para instalar versión estable de Java 11 - Distribución: Open-JDK.

```bash
$ sdk install java 11.0.12-open
```

Para usar versión de Java

```bash
$ sdk use  java 11.0.12-open
```



