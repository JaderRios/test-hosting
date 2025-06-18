# 🧩 Guía para Pull Requests (PR)

Esta guía define el flujo que seguimos en ETÉREO IT para crear, revisar y aprobar Pull Requests de forma organizada y eficiente.

---

## ✅ 1. Antes de crear un PR

- [ ] Asegúrate de haber hecho `pull` de la rama base (`main` o `develop`)
- [ ] Verifica que tu código **compila y funciona localmente**
- [ ] Revisa que no subas archivos innecesarios (.env, imágenes de pruebas, logs, etc.)
- [ ] Asegúrate de que el código sigue nuestras convenciones (`lint`, `formato`, estructura)

---

## 🛠️ 2. Crear el PR

- Crea una rama descriptiva: `feature/header`, `fix/bug-form-contact`
- Título del PR: **qué hace tu cambio**
  - Ej: `✅ Agrega animación a sección Hero`
- Descripción clara:
  - Qué se hizo
  - Qué se modificó
  - Si es parte de un issue: `Closes #12`
  - Screenshots si aplica

---

## 🔎 3. Durante la revisión

- Asigna al revisor correcto
- No hagas "force push" sin avisar
- Responde los comentarios del revisor
- No des “merge” sin aprobación (mínimo 1 aprobación)

---

## 🚀 4. Una vez aprobado

- Verifica que no haya conflictos
- Mergea la rama solo cuando estés seguro
- Elimina la rama si ya no será usada

---

## 🧠 Buenas prácticas adicionales

- Mantén los PRs pequeños y específicos
- Usa etiquetas como `feature`, `bugfix`, `hotfix`
- Comenta tu código cuando sea necesario

---

**¡Gracias por mantener la calidad del proyecto!**