## Como conectar un repositorio de Github con el Visual Studio Code

*Todo localizado en mi Github, si deseas que sea en el tuyo, cambia las direciones.*

#### Primero asegurate tener git descargado en tu ordenador

*Si no tienes instalado Git en tu ordenador, para Windows o Linux: [Instalación](https://github.com/rsensomontojo/Instalacion_Git) sino sáltate este paso.*

---

1. Clona el repositorio en tu máquina local:
   ```bash
   git clone https://github.com/rsensomontojo/nombre_respositorio
   ```

2. Agrega nuevos documentos o proyectos a las carpetas correspondientes.

*Trabaja en el código con precaución, si dos o más estáis tocando el mismo documento puede haber perdidas y confusión. Acordar tiempos de trabajo o secciones distintas en la sque trabajar en ese momento.*

*Una buena comunicación con tus compañeros de equipo es fundamental*

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

## 🤝

## Comandos de Git para iniciar el repositorio

### Crear un nuevo repositorio en la línea de comandos

```bash
echo "# nombre" >> README.md
git init
git add README.md
git commit -m "Descripción de los cambios"
git branch -M main
git remote add origin https://github.com/rsensomontojo/nombre.git
git push -u origin main
```

### Subir un repositorio existente

```bash
git remote add origin https://github.com/rsensomontojo/nombre.git
git branch -M main
git push -u origin main
```
