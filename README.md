<header>

# Hello GitHub Actions

_Crea y ejecuta un flujo de trabajo de GitHub Actions._

</header>

## Paso 5: Activar el flujo de trabajo
😎
_¡Ahora has agregado un flujo de trabajo completamente funcional a tu repositorio! :smile:_

El script de shell en el flujo de trabajo se ejecutará cada vez que se abra una nueva pull request.

**Ver tu _acción_ en acción**: El estado de cada ejecución de flujo de trabajo que se activa se muestra en la pull request antes de fusionarse: busca **Todos los controles han pasado** cuando pruebes los pasos a continuación. También puedes ver una lista de todos los flujos de trabajo que se están ejecutando o que han terminado de ejecutarse en la pestaña **Actions** de tu repositorio. Desde allí, puedes hacer clic en cada ejecución de flujo de trabajo para ver más detalles y acceder a los archivos de registro.

![Una captura de pantalla de la pestaña Actions mostrando una lista de ejecuciones de flujo de trabajo.](https://user-images.githubusercontent.com/16547949/62388049-4e64e600-b52a-11e9-8bf5-db0c5452360f.png)

### :keyboard: Actividad: Activar el flujo de trabajo

1. Crea una nueva rama llamada `test-workflow`.
2. Realiza un cambio, como agregar un emoji a tu archivo README.md, y confirma el cambio directamente en tu nueva rama.
3. En la pestaña **Pull requests**, crea una pull request que fusionará `test-workflow` en `stemdo`.
4. Observa el flujo de trabajo en ejecución en la sección de comprobaciones de la pull request.
5. Observa el comentario que el flujo de trabajo agrega a la pull request.
6. Espera unos 20 segundos, luego actualiza esta página (la que estás siguiendo las instrucciones). Otro flujo de trabajo se ejecutará y reemplazará el contenido de este archivo README con instrucciones para el próximo paso.

<footer>

---

Obtén ayuda: [Publica en nuestro foro de discusión](https://github.com/orgs/skills/discussions/categories/hello-github-actions) &bull; [Revisa la página de estado de GitHub](https://www.githubstatus.com/)

&copy; 2023 GitHub &bull; [Código de conducta](https://www.contributor-covenant.org/version/2/1/code_of_conduct/code_of_conduct.md) &bull; [Licencia MIT](https://gh.io/mit)

</footer>
