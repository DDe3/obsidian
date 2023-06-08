
# Inicializar repositorio

~~~ cmd
git init
git add .
git commit -m "msg"
git remote add "name" "giturl"
git push -u master/main
~~~


# Checar si un archivo esta en gitignore

~~~ cmd
git check-ignore -v path/to/missing/ressource
~~~

Para añadirle saltandose el gitignore:
~~~ cmd
git add -f path/to/missing/*
~~~

