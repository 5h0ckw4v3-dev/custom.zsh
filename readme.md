# ZSH Personalizado

![](https://github.com/5h0ckw4v3-dev/custom.zsh/blob/main/img/zsh.png)

Como podeis ver en la imagen, en este theme de ZSH podemos tener el nombre de usuario, nombre de máquina y la ruta actual, además de una visual parecida a la del terminal de ParrotOS. Espero que lo disfruten tanto como yo.

Para instalar este theme de ZSH es muy simple.

1.- Instalamos ZSH, en mi caso lo he hecho en Ubuntu basado en WSL.

```plaintext
sudo apt install zsh
```

2.- Una vez instalado, editamos el archivo .zshrc con vi, nano o lo que useis normalmente y copiamos el contenido del archivo zshrc de este repositorio.

```plaintext
nano .zshrc
```
Tambien se puede clonar y sustituir, como prefirais.

3.- Guardamos y ejecutamos

```plaintext
zsh
```

4.- Si el resultado final es de vuestro agrado y quereis sustituir bash solo hay que ejecutar este comando y cerrar sesión.

```plaintext
chsh -s $(which zsh)
```


PD: El final del archivo contiene código compartido por S4vitar, aprovecho para agradecerle su trabajo y compromiso con la comunidad.
