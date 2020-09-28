El {{ site.data.variables.product.prodname_component_kit }} te habilita para configurar un componente interactivo para que aparezca en un informe de problemas o en una solicitud de extracción. Los componentes interactivos habilitan a las personas para activar y administrar las tareas que aparecen en la {{ site.data.variables.product.prodname_dotcom }} cuando una {{ site.data.variables.product.prodname_github_app }} o una acción realizan las tareas solicitadas y comparten actualizaciones.

Utilizando la terminal "[Crear un comentario estructurado](/hidden/github-component-kit/composable-comments#create-composable-comment)", una {{ site.data.variables.product.prodname_github_app }} o una acción pueden crear un comentario estructurado en un informe de problemas o en una solicitud de extracción. El comentario estructurado puede incluir un componente interactivo, tal como un botón personalizado. Cuando alguien interactúa con el comentario la {{ site.data.variables.product.prodname_github_app }} recibirá el evento de webhook `interactive_component`.