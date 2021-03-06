---
title: Agregar administradores de App GitHub a tu organización
intro: 'Los propietarios de la organización pueden conceder a los usuarios la capacidad para administrar alguna o todas las {% data variables.product.prodname_github_apps %} que le pertenecen a la organización.'
redirect_from:
  - /articles/adding-github-app-managers-in-your-organization
  - /github/setting-up-and-managing-organizations-and-teams/adding-github-app-managers-in-your-organization
versions:
  fpt: '*'
  ghes: '*'
  ghae: '*'
  ghec: '*'
topics:
  - Organizations
  - Teams
shortTitle: Agregar administradores de GitHub Apps
---

For more information about {% data variables.product.prodname_github_app %} manager permissions, see "[Roles in an organization](/organizations/managing-peoples-access-to-your-organization-with-roles/roles-in-an-organization#github-app-managers)."

## Brindar a alguien la posibilidad de administrar todas las {% data variables.product.prodname_github_apps %} que son propiedad de la organización

{% data reusables.profile.access_org %}
{% data reusables.profile.org_settings %}
{% data reusables.organizations.github-apps-settings-sidebar %}
1. En "Management" (Administración), escribe el nombre de usuario de la persona a quien deseas designar como gerente de {% data variables.product.prodname_github_app %} en la organización, y haz clic en **Grant** (Conceder). ![Agregar un administrador de {% data variables.product.prodname_github_app %}](/assets/images/help/organizations/add-github-app-manager.png)

## Brindar a alguien la posibilidad de administrar un {% data variables.product.prodname_github_app %} individual

{% data reusables.profile.access_org %}
{% data reusables.profile.org_settings %}
{% data reusables.organizations.github-apps-settings-sidebar %}
1. Debajo de "{% data variables.product.prodname_github_apps %}s", haz clic en el avatar de la app a la que quieres agregar un administrador de {% data variables.product.prodname_github_app %}. ![Seleccionar {% data variables.product.prodname_github_app %}](/assets/images/help/organizations/select-github-app.png)
{% data reusables.organizations.app-managers-settings-sidebar %}
1. En "App managers" (Administradores de la app), escribe el nombre de usuario de la persona a quien deseas designar como administrador de la App GitHub para la app, y haz clic en **Grant** (Conceder). ![Agregar un administrador de {% data variables.product.prodname_github_app %} para una app específica](/assets/images/help/organizations/add-github-app-manager-for-app.png)

{% ifversion fpt or ghec %}
## Leer más

- "[Acerca de {% data variables.product.prodname_dotcom %} Mercado](/articles/about-github-marketplace/)"
{% endif %}
