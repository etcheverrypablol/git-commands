# Git Commands

## Use multples git accounts

See first the next [tutorial](https://platzi.com/tutoriales/1557-git-github/4067-configurar-llaves-ssh-en-git-y-github/)

Then see the [next one](https://www.damianculotta.com.ar/control-de-versiones/usando-multiples-cuentas-en-github/)

Example of my git config (github.como for the work - github-personal for personal github):

```
#Default GitHub
Host github.com
HostName github.com
User git
IdentityFile ~/.ssh/id_rsa


#Default GitHub
Host github-personal
HostName github.com
User git
IdentityFile ~/.ssh/id_rsa_personal
```
