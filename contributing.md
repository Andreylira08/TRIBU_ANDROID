flujo de trabajo más organizado para nuestros commits y PRs en GitHub
⚠️  Commits Correctos

• Usa ramas en lugar de trabajar en main y develop:
Una vez posicionados en la rama develop, crear una nueva en la que se trabajará la nueva funcionalidad:

git checkout -b feat/historiaUsuario/nombreFeature-caracteristica

• Agregar cambios y commits 

git add -A
git commit -m "mensaje"


⚠️  Subir cambios

• Después de realizar commits, sube TU rama:

git push origin feat/historiaUsuario/nombreFeature-caracteristica


🛑 3. Ir al repositorio en GitHub y crear un PR

ASEGURARSE QUE ES HACIA DEVELOP
develop  ⬅️  tu rama
agregar la información pertinente: 

Descripción:

Archivos cambiados: 

Checklist con definición de DONE:
- [x] Completado
- [ ] Faltante

Notas o Imágenes:


✅  MERGE: Hasta que se tenga el checklist completo y asegurarse que la versión funciona