# Markdown
```mermaid
    graph LR;
	Inicio --> id1[/Ingrese su numero/];
	id1 --> id2> "tu numero es"+ num];
	id2 --> id3[num=num-1];
	id3 --> id2;
	id3 --> terminacion[termino]
	
	
	



```
1,2-

hago un    git clone https://github.com/damiancastelao/examenDAM.git   dentro de una carptea que ya especifique para su uso
creo un repositorio en github
entro en el clonado con   cd examenDAM
hago un   git init
modifico el README.md con el nano y le escribo "modificacion hecha con nano"
agrego el README.md con el   git add README.md
hago el commit con   git commit -m "punto 2"
cambioi la rama usando el   git branch -M main
hago un   git remote rm origin    para poder usar bien el git
hago un   git remote add origin https://github.com/LidierRaccioppe/codprimero2do.git    para establecer este lugar como mi repositorio en github
hago un   git push -u origin main  para llevar todo esto hasta ahi

3-

le hice una copia en un codigo que tenia y lo envie a la carpeta del examen con   cp -r examencod1/ /home/dam1/codejers/examencod1/examenDAM
agrego el ejericisio con     git add examencod1/
hago un cambio de nombre de usuario con   git config user.name "maximon´t"
hago el commit con git commit -m "punto 3"
ahora lo vuelvo a subir con   git push -u origin main


3-

hago el commit con   git commit -m "punto 4"
hago la etiqueta con   git tag -a 1.0 -m "la 1.0"
hago el push   con    git push -u origin main


6-


utilizar el File Structure, agregar un
Artifact, eligiendo el JAR, con un codigo ya existente, ahora se selecciona el main de
nuestro codigo, ahora se debe de darle al aplicar y okey, una vez con eso debe de irse al
Build, seccion Build Artifact y darle a build.

ahora lo llevo a github y lo pongo como release

