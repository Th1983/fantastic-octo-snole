---
title: Crear una contraseña segura
intro: 'Secure your account on {% ifversion ghae %}{% data variables.product.product_name %}{% else %}{% data variables.product.product_location %}{% endif %} with a strong and unique password using a password manager.'
redirect_from:
  - /articles/what-is-a-strong-password/
  - /articles/creating-a-strong-password
  - /github/authenticating-to-github/creating-a-strong-password
  - /github/authenticating-to-github/keeping-your-account-and-data-secure/creating-a-strong-password
versions:
  fpt: '*'
  ghes: '*'
  ghec: '*'
topics:
  - Identity
  - Access management
shortTitle: Crear una contraseña fuerte
---

You must choose or generate a password for your account on {% ifversion ghae %}{% data variables.product.product_name %}{% else %}{% data variables.product.product_location %}{% endif %} that is at least:
- Una longitud de {% ifversion ghes %}siete{% else %}ocho{% endif %}caracteres, si incluye un número y una letra minúscula, o
- 15 caracteres de largo con cualquier combinación de caracteres

Para preservar la seguridad de tu cuenta, te recomendamos que sigas estas buenas prácticas:
- Utiliza un administrador de contraseñas, tal como [LastPass](https://lastpass.com/) o [1Password](https://1password.com/), para generar una contraseña de por lo menos 15 caracteres.
- Genera una contraseña que sea única para {% data variables.product.product_name %}. If you use your {% data variables.product.product_name %} password elsewhere and that service is compromised, then attackers or other malicious actors could use that information to access your account on {% ifversion ghae %}{% data variables.product.product_name %}{% else %}{% data variables.product.product_location %}{% endif %}.

- Configura la autenticación de dos factores para tu cuenta personal. Para obtener más información, consulta "[Acerca de la autenticación de dos factores](/articles/about-two-factor-authentication)".
- Nunca compartas tu contraseña con nadie, aunque se trate de un potencial colaborador. Cada persona debe usar su propia cuenta personal en {% data variables.product.product_name %}. Para obtener más información acerca de cómo colaborar, consulta: "[Invitar colaboradores a un repositorio personal](/articles/inviting-collaborators-to-a-personal-repository)," "[Acerca de los modelos de desarrollo colaborativos](/articles/about-collaborative-development-models/)," o "[Colaborar con los grupos en las organizaciones](/organizations/collaborating-with-groups-in-organizations/)".

{% data reusables.repositories.blocked-passwords %}

Solo puedes utilizar tu contraseña para ingresar en {% data variables.product.product_name %} a través de tu buscador. Cuadno te atutenticas en {% data variables.product.product_name %} con otros medios, tales como la línea de comandos o la API, debes utilizar otras credenciales. Para obtener más información, consulta la sección "[Acerca de la autenticación en {% data variables.product.prodname_dotcom %}](/github/authenticating-to-github/about-authentication-to-github)".

{% ifversion fpt or ghec %}{% data reusables.user_settings.password-authentication-deprecation %}{% endif %}

## Leer más

- [Almacenar tus credenciales de {% data variables.product.product_name %} en la caché en Git](/github/getting-started-with-github/caching-your-github-credentials-in-git/)"
- "[Preservar la seguridad de tu cuenta y tus datos](/articles/keeping-your-account-and-data-secure/)"
