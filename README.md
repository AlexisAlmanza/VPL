# VPL

# Pasos para empezar en github

## Tener instalado git en tu computadora
Revisar si esta instalado git, colocar el siguiente comando en tu terminal.
```
  input: git --version
  output: git version 2.34.0.windows.1
```
sino te da un output parecido, instalar git.

## Si es windows
Con que instales git bash se instala git y con git bash podras administrar tus repositorios.

## Configurar tus credenciales de github
  **Configurar tu nombre en git**
  - Abre gitbash
```
  git config --global user.name "Nombre de usuario"  
```
  - Confirmar que este el nombre se establecio correctamente
```
  git config --global user.name 
```
  o puedes revisar el archivo **cat ./gitconfig**

  **Confirmar credenciales en github**
  Moverte al path donde esta tu usuario y buscar la carpeta **./shh** sino esta crearla, si esta acceder a la carpeta.
```
  El path seria similar:
  cd /c/Users/Alexis Eduardo/.ssh
```
  **Revisar el sguiente link**
  https://docs.github.com/es/account-and-profile/setting-up-and-managing-your-github-user-account/managing-email-preferences/setting-your-commit-email-address

## Clonar un repositorio en github
  **Si es un repositorio privado** necesitaras estar inivitado al proyecto
