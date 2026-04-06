"# Mi primer commit del proyecto" 

# Paso 1: clonar el repositorio

```
git clone https://github.com/6arlos6/qml-siqia.git
cd repo-qml-siqia
```

### Poner su nombre antes de iniciar:
```
<git config --global user.name "Su Nombre">
<git config --global user.email "email_con_el_que_se_registraron_en_github">
```
# Paso 2: ubicarse en su rama
```
git checkout natalia
```

Si no aparece localmente de una vez:
```
git fetch origin
git checkout -b natalia origin/natalia
```

# Paso 3: trabajar normalmente

Por ejemplo: crear un notebook o una carpeta...

Luego:
```
git add .
git commit -m "Avance de Ana en módulo X"
git push origin estudiante-ana
```