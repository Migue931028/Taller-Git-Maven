**Taller Git Maven**
-------
---
**Autor:** Miguel Angel Ortega 

**Descripcion:** Taller de programacion para conocer las bases de git/github 

**Aprendizajes**
-------
- git init
- git status
- git branch --show-current
- git branch -M main
- git commit -m "Mensaje del commit"
- git log --oneline — Muestra el historial resumido.
- git diff — Muestra cambios todavía no agregados a staging.
- git add src/main/java/Main.java
- git switch -c feature/mensaje-despedida — Crea la rama y cambia a ella
- git switch main
- git merge feature/mensaje-despedida — Integra la rama de trabajo en main
- git branch -d feature/mensaje-despedida — Elimina la rama local ya integrada
- git log --oneline --graph --decorate --all — Visualiza el historial y las ramas
- git restore src/.../Main.java — Reemplace la ruta por la ubicación real del archivo 
- git remote add origin <URL_HTTPS_DEL_REPOSITORIO>
- git remote -v
- git push -u origin main
- **Hacer un cambio remoto y recuperarlo:**
  - git pull origin main 
  - git log --oneline --all