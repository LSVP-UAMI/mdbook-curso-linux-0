# mdbook-base
base para proyectos de mdbook

## Para actualizar el submódulo
- Editar branch en .gitmodules
- Actualizar submódulo

```
git checkout main
git pull
git submodule update --remote
git add src
git commit -m "submodule hash update"
git push
```
