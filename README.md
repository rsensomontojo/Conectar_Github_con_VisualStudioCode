## Como conectar mi repositorio de Github con mi Visual Studio Code

####Primero asegurate tener git descargado en tu ordenador


1. Clona el repositorio en tu máquina local:
   ```bash
   git clone https://github.com/rsensomontojo/Documentos.git
   ```

2. Agrega nuevos documentos o proyectos a las carpetas correspondientes.

3. Para actualizar el repositorio, sigue estos pasos:
   ```bash
   git add .
   git commit -m "Descripción de los cambios"
   git push origin main
   ```

## Contribuciones

Si deseas contribuir a este repositorio, por favor sigue estos pasos:

1. Haz un fork del repositorio.
2. Crea una nueva rama:
   ```bash
   git checkout -b nueva-rama
   ```
3. Realiza tus cambios y haz un commit:
   ```bash
   git commit -am 'Descripción de los cambios'
   ```
4. Envía un pull request.

## Licencia

Este repositorio está bajo la Licencia [Nombre de la Licencia] - consulta el archivo LICENSE para más detalles.

## Comandos de Git para iniciar el repositorio

### Crear un nuevo repositorio en la línea de comandos

```bash
echo "# Documentos" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/rsensomontojo/Documentos.git
git push -u origin main
```

### Subir un repositorio existente

```bash
git remote add origin https://github.com/rsensomontojo/Documentos.git
git branch -M main
git push -u origin main
```
