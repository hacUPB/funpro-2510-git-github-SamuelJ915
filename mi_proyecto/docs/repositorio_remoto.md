# Como crear un repositorio remoto en Github y sincronizarlo con tu repositorio local
hasta ahora, supongo que ya sabras como crear un repositorio local, vamos a ver ahora como sincronizarlo con la nube, voy a enseñarte el metodo que el profesor me ha explicado a mi y que no implica descargar Github CLI, con este ultimo es mas facil despues subir las cosas a la nube, aunque con el segundo metodo no pierdes tiempo descargando e instalando programas. :+1:

1. en tu repositorio raiz vas a crear un arhivo README.md, github incluso te lo pide hacer aunque esto es opcional, sirve mas para darle presentacion a tu repositorio en la pagina Github. 

![alt text](../images/touchReadme.PNG)

2. tienes que estar en la branch (main), de lo contrario puede que no se te suban los archivos, para asegurarte de esto vas a ingresar el comando siguiente: git branch -M main.

![alt text](../images/branchmain.PNG)

3. ahora, vas a ir a github y le vas a dar en la pestaña de  __tus repositorios__ y ahi le vas a dar a __crear nuevo repositorio__ 

4. en esta pestaña el mismo github te va a guiar pero lo que tienes que hacer es darle al __link__ que esta resaltado en azul y vas a copiar el primer link que te dan

![alt text](../images/gitdemo.PNG)

5. ahora vas a copiar el siguiente codigo en git bash y despues de __origin__ vas a pegar el link que github te dio: git remote add origin "https://github/username/nombredirectorio" este hipervinculo es simplemente un ejemplo pero debe coincidir con tus datos

![alt text](../images/gitremote.PNG)

6. ahora ya habras creado el repositorio en remoto en Github, lo ultimo que queda es subir lo que tengas en el repositorio local, para estos vas a usar el comando "__git push -u origin main__", si es primera vez que lo haces, te va a pedir que inicies sesion en github y despues le vuelves a dar al comando y ya deberias ver tu repositorio en github.

![alt text](../images/gitpush.PNG)