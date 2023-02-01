<p align="center">
 <img width="100px" src="https://res.cloudinary.com/anuraghazra/image/upload/v1594908242/logo_ccswme.svg" align="center" alt="GitHub Readme Stats" />
 <h2 align="center">GitHub Readme Stats</h2>
 <p align="center">¡Obtén tus estadísticas de GitHub generadas dinámicamente en tu README!</p>
</p>
  <p align="center">
    <a href="https://github.com/anuraghazra/github-readme-stats/actions">
      <img alt="Pasando pruebas" src="https://github.com/anuraghazra/github-readme-stats/workflows/Test/badge.svg" />
    </a>
    <a href="https://github.com/anuraghazra/github-readme-stats/graphs/contributors">
      <img alt="GitHub Contributors" src="https://img.shields.io/github/contributors/anuraghazra/github-readme-stats" />
    </a>
    <a href="https://codecov.io/gh/anuraghazra/github-readme-stats">
      <img src="https://codecov.io/gh/anuraghazra/github-readme-stats/branch/master/graph/badge.svg" />
    </a>
    <a href="https://github.com/anuraghazra/github-readme-stats/issues">
      <img alt="Problemas" src="https://img.shields.io/github/issues/anuraghazra/github-readme-stats?color=0088ff" />
    </a>
    <a href="https://github.com/anuraghazra/github-readme-stats/pulls">
      <img alt="GitHub pull requests" src="https://img.shields.io/github/issues-pr/anuraghazra/github-readme-stats?color=0088ff" />
    </a>
    <br />
    <br />
    <a href="https://a.paddle.com/v2/click/16413/119403?link=1227">
      <img src="https://img.shields.io/badge/Supported%20by-VSCode%20Power%20User%20%E2%86%92-gray.svg?colorA=655BE1&colorB=4F44D6&style=for-the-badge"/>
    </a>
    <a href="https://a.paddle.com/v2/click/16413/119403?link=2345">
      <img src="https://img.shields.io/badge/Supported%20by-Node%20Cli.com%20%E2%86%92-gray.svg?colorA=61c265&colorB=4CAF50&style=for-the-badge"/>
    </a>
  </p>

<p align="center">
    <a href="#ejemplo">Ver un ejemplo</a>
    ·
    <a href="https://github.com/anuraghazra/github-readme-stats/issues/new/choose">Reportar un bug</a>
    ·
    <a href="https://github.com/anuraghazra/github-readme-stats/issues/new/choose">Solicitar una mejora</a>
  </p>
  <p align="center">
    <a href="/docs/readme_fr.md">Français</a>
    ·
    <a href="/docs/readme_cn.md">简体中文</a>
    ·
    <a href="/docs/readme_es.md">Español</a>
    ·
    <a href="/docs/readme_de.md">Deutsch</a>
    ·
    <a href="/docs/readme_ja.md">日本語</a>
    ·
    <a href="/docs/readme_pt-BR.md">Português Brasileiro</a>
    ·
    <a href="/docs/readme_it.md">Italiano</a>
    ·
    <a href="/docs/readme_kr.md">한국어</a>
    .
    <a href="/docs/readme_nl.md">Nederlands</a>
.
    <a href="/docs/readme_tr.md">Türkçe</a>
    .
    <a href="/docs/readme_np.md">नेपाली</a>
  </p>
</p>

<p align="center">¿Te gusta el proyecto? ¿Te gusta este proyecto? ¡Por favor, considera <a href="https://www.paypal.me/anuraghazra">donar</a> para ayudar a mejorarlo!</p>

<a href="https://indiafightscorona.giveindia.org">
  <img src="https://indiaspora.org/wp-content/uploads/2021/04/give-India-logo.png" alt="Dar logotipo de India" width="200" />
</a>

¿Estás considerando apoyar el proyecto mediante una donación? Por favor NO!!

En cambio, ayude a India a luchar contra la segunda ola mortal de COVID-19. Miles de personas están muriendo en la India debido a la falta de Oxígeno & también de infraestructura relacionada con COVID.

Visita <https://indiafightscorona.giveindia.org> y haz una pequeña donación para ayudarnos a luchar contra COVID y superar esta crisis. Una pequeña donación va muy lejos. :heart:

</p>

# Características

-   [Tarjeta de estadísticas de GitHub](#github-stats-card)
-   [Pins adicionales de GitHub](#github-extra-pins)
-   [Tarjeta de Lenguajes Principales](#top-languages-card)
-   [Estadísticas de la Semana de Wakatime](#wakatime-week-stats)
-   [Temas](#themes)
    -   [Tema de tarjeta de respuesta](#responsive-card-theme)
-   [Personalización](#customization)
    -   [Por defecto](#common-options)
    -   [Opciones exclusivas de la Tarjeta de Estadísticas:](#stats-card-exclusive-options)
    -   [Personalizando Tarjeta de Repo](#repo-card-exclusive-options)
    -   [`hide` - Oculta de la tarjeta los lenguajes especificados  _(valores separados por comas)_](#language-card-exclusive-options)
    -   [Opciones exclusivas de la Tarjeta de Wakatime:](#wakatime-card-exclusive-options)
-   [Desplázate a ti mismo](#deploy-on-your-own-vercel-instance)
    -   [Mantén tu bifurcación actualizada](#keep-your-fork-up-to-date)

# Tarjeta de estadísticas de GitHub

Copia y pega esto en el contenido de tu README.md y listo. ¡Simple!

Cambia el valor de `?username=` al nombre de tu usuario de GitHub.

```md
[![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra)](https://github.com/anuraghazra/github-readme-stats)
```

> Nota: Los rangos disponibles son S+ (top 1%), S (top 25%), A++ (top 45%), A+ (top 60%) y B+ (todos). Los valores se calculan utilizando la [función de distribución acumulada](https://es.wikipedia.org/wiki/Funci%C3%B3n_de_distribuci%C3%B3n) utilizando commits, contribuciones, issues, estrellas, pull request, seguidores y repositorios propios. Puedes investigar más sobre la implementación en [src/calculateRank.js](../src/calculateRank.js).

### Ocultar estadísticas individualmente

Para ocultar alguna estadística específica, puedes utilizar el parámetro `?hide=` con los elementos que quieras ocultar separados por comas.

> Opciones: `&hide=stars,commits,prs,issues,contribs`

```md
![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&hide=contribs,prs)
```

### Agregar contribuciones privadas al total de commits contados

Puedes agregar el recuento de todas sus contribuciones privadas al recuento total de commits utilizando el parámetro `?count_private=true`.

> **Nota** Si estás implementando este proyecto tú mismo, las contribuciones privadas se contarán por defecto. Si estás usando la instancia pública de Vercel, tienes que elegir [compartir tus contribuciones privadas](https://docs.github.com/en/account-and-profile/setting-up-and-managing-your-github-profile/managing-contribution-settings-on-your-profile/showing-your-private-contributions-and-achievements-on-your-profile).

> Opciones: `&count_private=true`

```md
![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&count_private=true)
```

### Mostrar íconos

Para habilitar los íconos, puedes utilizar `show_icons=true` como parámetro, de esta manera:

```md
![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true)
```

### Temas

Puedes personalizar el aspecto de la tarjeta sin realizar ninguna [personalización manual](#personalización) con los temas incorporados.

Utiliza el parámetro `?theme=THEME_NAME`, de esta manera:

```md
![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&theme=radical)
```

#### Todos los temas incorporados

dark, radical, merko, gruvbox, tokyonight, onedark, cobalt, synthwave, highcontrast, dracula

<img src="https://res.cloudinary.com/anuraghazra/image/upload/v1595174536/grs-themes_l4ynja.png" alt="GitHub Readme Stat Themes" width="600px" />

Puedes ver una vista previa de [todos los temas disponibles](../themes/README.md) o ver el [archivo de configuración](../themes/index.js) del tema y también **puedes contribuir con nuevos temas** si lo deseas :D

#### Tema de tarjeta de respuesta

[![Anurag's GitHub stats-Dark](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&theme=dark#gh-dark-mode-only)](https://github.com/anuraghazra/github-readme-stats#gh-dark-mode-only) [![<code>count_private</code> - Cuenta los commits privadas <em x-id="4">(boolean)</em>](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&theme=default#gh-light-mode-only)](https://github.com/anuraghazra/github-readme-stats#gh-light-mode-only)

Como GitHub volverá a subir las tarjetas y las servirá desde su [CDN](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/about-anonymized-urls), no podemos infer el tema del navegador/GitHub en el lado del servidor. Sin embargo, hay cuatro métodos que puede utilizar para crear temas dinámicos en el lado del cliente.

##### Usar el tema transparente

Hemos incluido un tema `transparente` que tiene un fondo transparente. Este tema está optimizado para que se vea bien en los oscuros y claros temas por defecto de GitHub. Puede activar este tema usando el parámetro `&theme=transparent` así:

```md
![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&theme=transparent)
```

<details>
<summary>:eyes: Mostrar ejemplo</summary>

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&theme=transparent)

</details>

##### Añadir un canal alfa transparente a un color bg_themes

Puede utilizar el parámetro `bg_color` para hacer transparente [cualquiera de los temas disponibles](./themes/README.md). Esto se hace configurando el color `bg_color` a un color con un canal alfa transparente (por ejemplo, `bg_color=00000000`):

```md
![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&bg_color=00000000)
```

<details>
<summary>:eyes: Mostrar ejemplo</summary>

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&bg_color=00000000)

</details>

##### `theme` - Nombre del tema, elige uno de [todos los temas disponible ](../themes/README.md)

Puede usar [etiquetas de contexto del tema de GitHub](https://github.blog/changelog/2021-11-24-specify-theme-context-for-images-in-markdown/) para cambiar el tema basado en el tema de GitHub automáticamente. Esto se hace añadiendo `#gh-dark-mode-only` o `#gh-light-mode-only` al final de una URL de la imagen. Esta etiqueta definirá si la imagen especificada en el markdown sólo se muestra a los espectadores usando un tema de GitHub claro o oscuro:

```md
[![Anurag's GitHub stats-Dark](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&theme=dark#gh-dark-mode-only)](https://github.com/anuraghazra/github-readme-stats#gh-dark-mode-only)
[![Anurag's GitHub stats-Light](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&theme=default#gh-light-mode-only)](https://github.com/anuraghazra/github-readme-stats#gh-light-mode-only)
```

<details>
<summary>:eyes: Mostrar ejemplo</summary>

[![Anurag's GitHub stats-Dark](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&theme=dark#gh-dark-mode-only)](https://github.com/anuraghazra/github-readme-stats#gh-dark-mode-only) [![Selecciona <code>Import Git Repository</code>](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&theme=default#gh-light-mode-only)](https://github.com/anuraghazra/github-readme-stats#gh-light-mode-only)

</details>

##### Usar la nueva característica multimedia de GitHub

Puede utilizar [la nueva característica multimedia de GitHub](https://github.blog/changelog/2022-05-19-specify-theme-context-for-images-in-markdown-beta/) en HTML para especificar si mostrar imágenes para temas claros o oscuros. This is done using the HTML `<picture>` element in combination with the `prefers-color-scheme` media feature.

```html
<picture>
<source 
  srcset="https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&theme=dark"
  media="(prefers-color-scheme: dark)"
/>
<source
  srcset="https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true"
  media="(prefers-color-scheme: light), (prefers-color-scheme: no-preference)"
/>
<img src="https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true" />
</picture>
```

<details>
<summary>:eyes: Mostrar ejemplo</summary>

<picture>
<source 
  srcset="https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&theme=dark"
  media="(prefers-color-scheme: dark)"
/>
<source
  srcset="https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true"
  media="(prefers-color-scheme: light), (prefers-color-scheme: no-preference)"
/>
<img src="https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true" />
</picture>

</details>

### Personalización

Puedes personalizar el aspecto de tu `Tarjeta de Estadísticas` o `Tarjeta de Repo` de la manera que desees con los parámetros URL.

#### Opciones Comunes:

-   `title_color` - Color del título _(hex color)_ Default: `2f80ed`.
-   `text_color` - Color del contenido _(hex color)_ Predeterminado: `434d58`.
-   `icon_color` - Color de icono si esta disponible _(hex color)_ Predeterminado: `4c71f2`.
-   `borde_color` - Color del borde de la tarjeta _(color hexadecimal)_. Por defecto: `e4e2e2` (No aplica cuando `esconder borde` está activado).
-   `bg_color` - Color de fondo _(hex color)_ Predeterminado: `fffefe`
-   `hide_border` - Oculta el borde de la tarjeta _(booleano)_ Predeterminado: `false`
-   `tema` - nombre del tema, elija de [todos los temas disponibles](./themes/README.md). Predeterminado: `tema` por defecto.
-   `cache_seconds` - Cache _(min: 1800, max: 86400)_ Predeterminado: `14400 segundos (4 horas)`.
-   `locale` - configurar el idioma en la tarjeta _(p.ej. cn, de, es, etc.)_
-   `border_radio` - Rondeo de esquina en la tarjeta. Predeterminado: `4.5`.

> **Advertencia** Utilizamos la caché para disminuir la carga en nuestros servidores (ver <https://github.com/anuraghazra/github-readme-stats/issues/1471#issuecomment-1271551425>). Nuestras tarjetas tienen un caché por defecto de 4 horas (14400 segundos). También ten en cuenta que la caché está sujeta a un mínimo de 2 horas y un máximo de 24 horas

##### Gradiente en `bg_color`

Puedes pasar mútliples valores separados por coma en la opción `bg_color` para dibujar un gradiente, el formato del gradiente es:

    &bg_color=DEG,COLOR1,COLOR2,COLOR3...COLOR10

#### Opciones exclusivas de la Tarjeta de Repo:

-   `ocultar` - Oculta los elementos [especificados](#hiding-individual-stats) de estadísticas _(valores separados por comas)_. Predeterminado: `[] (array en blanco)`.
-   `hide_title` - _(booleano)_ Predeterminado: `false`.
-   `card_width` - Establece el ancho de la tarjeta manualmente _(número)_. Predeterminado: `500px (approx.)`.
-   `hide_rank` - _(booleano)_ oculta el rango y cambia el tamaño de la tarjeta automáticamente. Predeterminado: `false`.
-   `show_icons` - _(booleano)_ Predeterminado: `false`.
-   `include_all_commits` - Cuenta el total de commits en lugar de solo los commits del año actual _(boolean)_ Predeterminado: `false`.
-   `count_private` - Contar commits privados _(boolean)_. Predeterminado: `false`.
-   `line_height` - Establece el alto de línea entre texto _(número)_ Predeterminado: `25`.
-   `exclude_repo` - Excluir estrellas de los repositorios especificados _(valores separados por comas)_ Predeterminado: `[] (array en blanco)`.
-   `custom_title` - Establece un título personalizado Default:  `<username> GitHub Stats`.
-   `text_bold` - Usar texto en negrita _(booleano)_. Predeterminado: `true`.
-   `disable_animations` - Desactiva todas las animaciones en la tarjeta _(boolean)_. Predeterminado: `false`.
-   `ring_color` - Color del círculo de rango _(color hexadecimal)_. Por defecto el color de anillo del tema si existe y de lo contrario el color del título.

> **Nota** Cuando se oculta_rank=`verdadero`, el ancho mínimo de la tarjeta es 270 px + la longitud y el relleno del título.

#### Opciones exclusivas de la Tarjeta de Lenguajes:

-   `show_owner` - Mostrar el nombre del propietario del repositorio _(booleano)_ Predeterminado: `false`.

#### Estableciendo Idioma de la tarjeta

-   `ocultar` - Ocultar los idiomas especificados de la tarjeta _(valores separados por comas)_. Predeterminado: `[] (array en blanco)`.
-   `hide_title` - _(booleano)_ Predeterminado: `false`.
-   `layout` - Cambia entre los dos diseños disponibles `default` & `compact` Predeterminado: `por defecto`.
-   `card_width` - Establece el ancho de la tarjeta manualmente _(número)_. Por defecto `300`.
-   `langs_count` - Limita el número de idiomas que aparecen en el mapa Por defecto `5`.
-   `exclude_repo` - Excluye los repositorios especificados  _(valores separados por comas)_ Predeterminado: `[] (array en blanco)`.
-   `custom_title` - Establece un título personalizado para la tarjeta _(cadena)_. Predeterminado `Idiomas más utilizados`.
-   [`disable_animations`] - Desactiva todas las animaciones _(booleano)_ Predeterminado: `false`.

> **Advertencia** Los nombres de idioma deben ser escape de URI, como se especifica en [Codificación por ciento](https://en.wikipedia.org/wiki/Percent-encoding) (i. : `c++` debería convertirse en `c%2B%2B`, `cuaderno de jupyter` debería convertirse en `jupyter%20notebook`, etc.) Puedes usar [urlencoder.org](https://www.urlencoder.org/) para ayudarte a hacerlo automáticamente.

#### Estadísticas de la semana de Wakatime

-   `ocultar` - Ocultar los idiomas especificados de la tarjeta _(valores separados por comas)_. Predeterminado: `[] (array en blanco)`.
-   `hide_title` - _(booleano)_ `falso` por defecto.
-   `line_height` - Establece el alto de línea entre texto _(número)_ Por defecto `25`.
-   `hide_rank` - _(booleano)_ `falso` por defecto.
-   `custom_title` - Establece un título personalizado para la tarjeta _(cadena)_. Default `Wakatime Stats`.
-   `layout` - Cambia entre los dos diseños disponibles `default` & `compact`  Predeterminado `por defecto`.
-   `langs_count` - Muestra más lenguajes en la tarjeta, entre 1-10, por defecto 5 _(número)_
-   `api_domain` - Establece un dominio API personalizado para la tarjeta, p.e. para usar servicios como [Hakatime](https://github.com/mujx/hakatime) o [Wakapi](https://github.com/muety/wakapi) _(cadena)_. Predeterminado `Waka API`.
-   `rango` – Solicitud un rango diferente de su valor predeterminado de WakaTime, por ejemplo `last_7_days`. Vea [WakaTime API docs](https://wakatime.com/developers#stats) para una lista de opciones disponibles. _(YYYY-MM, last_7_days, last_30_days, last_6_mes, last_year, or all_time)_. Por defecto `all_time`.

* * *

# Pines adicionales de GitHub

Los pines adicionales de GitHub le permiten fijar más de 6 repositorios en su perfil utilizando un perfil readme de GitHub.

¡Yay! ¡Yey! Ya no está limitado a 6 repositorios pinneados.

### Utilización

Copia y pegua este código en tu Readme y cambia los enlaces.

Endpoint: `api/pin?username=anuraghazra&repo=github-readme-stats`

```md
[![Tarjeta Readme](https://github-readme-stats.vercel.app/api/pin/?username=anuraghazra&repo=github-readme-stats)](https://github.com/anuraghazra/github-readme-stats)
```

### Demo

[![Leer tarjeta](https://github-readme-stats.vercel.app/api/pin/?username=anuraghazra&repo=github-readme-stats)](https://github.com/anuraghazra/github-readme-stats)

Utiliza la variable [show_owner](#customización) para incluir el nombre de usuario del propietario del repositorio.

[![Leer tarjeta](https://github-readme-stats.vercel.app/api/pin/?username=anuraghazra&repo=github-readme-stats&show_owner=true)](https://github.com/anuraghazra/github-readme-stats)

# Tarjeta de Lenguajes Principales

La tarjeta de lenguajes principales muestra los lenguajes principales del usuario de GitHub que se han utilizado principalmente.

> NOTA: los lenguajes principales no indican mi nivel de habilidad o algo así, es una métrica de GitHub de los lenguajes que tengo más código en GitHub. Es una nueva característica de github-readme-stats

### Utilización

Copia y pegua este código en tu Readme y cambia los enlaces.

Endpoint: `api/top-langs?username=anuraghazra`

```md
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=anuraghazra)](https://github.com/anuraghazra/github-readme-stats)
```

### Excluir repositorios individualmente

Puedes usar el parámetro `?exclude_repo=repo1,repo2` para ocultar repositorios individualmente.

```md
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=anuraghazra&exclude_repo=github-readme-stats,anuraghazra.github.io)](https://github.com/anuraghazra/github-readme-stats)
```

### Ocultar lenguajes individualmente

Puedes usar el parámetro `?hide=language1,language2` para ocultar lenguajes individualmente.

```md
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=anuraghazra&hide=javascript,html)](https://github.com/anuraghazra/github-readme-stats)
```

### Mostrar más lenguajes

Puedes usar el paramétro `&langs_count=` para incrementar o decrementar el número de lenguajes mostrados en la tarjeta. Los valores admitidos son los números enteros entre 1 y 10 (inclusive), y el valor por defecto es 5.

```md
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=anuraghazra&langs_count=8)](https://github.com/anuraghazra/github-readme-stats)
```

### Diseño Compacto de Tarjeta de Lenguaje

Puedes usar la opción `& layout = compact` para cambiar el diseño de la tarjeta.

```md
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=anuraghazra&layout=compact)](https://github.com/anuraghazra/github-readme-stats)
```

### Demo

[![Mejores colmillos](https://github-readme-stats.vercel.app/api/top-langs/?username=anuraghazra)](https://github.com/anuraghazra/github-readme-stats)

-   Diseño compacto

[![Mejores colmillos](https://github-readme-stats.vercel.app/api/top-langs/?username=anuraghazra&layout=compact)](https://github.com/anuraghazra/github-readme-stats)

# Estadísticas de la Semana de Wakatime

cambia el valor del parámetro `?username=` a tu username en [Wakatime](https://wakatime.com).

```md
[![willianrod's wakatime stats](https://github-readme-stats.vercel.app/api/wakatime?username=willianrod)](https://github.com/anuraghazra/github-readme-stats)
```

> **Nota**: Tenga en cuenta que actualmente sólo mostramos datos de perfiles de Wakatime que son públicos.

### Demo

[![estadísticas willianrod de wakatime](https://github-readme-stats.vercel.app/api/wakatime?username=willianrod)](https://github.com/anuraghazra/github-readme-stats)

[![estadísticas willianrod de wakatime](https://github-readme-stats.vercel.app/api/wakatime?username=willianrod&hide_progress=true)](https://github.com/anuraghazra/github-readme-stats)

-   Diseño compacto

[![estadísticas willianrod de wakatime](https://github-readme-stats.vercel.app/api/wakatime?username=willianrod&layout=compact)](https://github.com/anuraghazra/github-readme-stats)

* * *

### Todos Demos

-   Por defecto

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra)

-   Ocultando ciertas estadísticas

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&hide=contribs,issues)

-   Mostrando íconos

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&hide=issues&show_icons=true)

-   Personalizar color del borde

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&border_color=2e4058)

-   Incluyendo todos los commits

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&include_all_commits=true)

-   Temas

Escoja cualquiera de los [temas por defecto](#themes)

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&theme=radical)

-   Gradiente

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&bg_color=30,e96443,904e95&title_color=fff&text_color=fff)

-   Personalizando Tarjeta de Estadísticas

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api/?username=anuraghazra&show_icons=true&title_color=fff&icon_color=79ff97&text_color=9f9f9f&bg_color=151515)

-   `card_width` - Establece el ancho de la tarjeta manualmente _(número)_

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api/?username=anuraghazra&locale=es)

-   `api_domain` - Establece un dominio de API personalizado para la tarjeta

![Tarjeta personalizada](https://github-readme-stats.vercel.app/api/pin?username=anuraghazra&repo=github-readme-stats&title_color=fff&icon_color=f9f9f9&text_color=9f9f9f&bg_color=151515)

-   Lenguajes Top

[![Mejores colmillos](https://github-readme-stats.vercel.app/api/top-langs/?username=anuraghazra)](https://github.com/anuraghazra/github-readme-stats)

-   Tarjeta de Wakatime

[![estadísticas willianrod de wakatime](https://github-readme-stats.vercel.app/api/wakatime?username=willianrod)](https://github.com/anuraghazra/github-readme-stats)

* * *

### Consejo rápido (para alinear las tarjetas de repositorio)

Por lo general, no podrás acomodar las imágenes una al lado de la otra. Para hacerlo, puede usar este enfoque:

```html
<a href="https://github.com/anuraghazra/github-readme-stats">
  <img align="center" src="https://github-readme-stats.vercel.app/api/pin/?username=anuraghazra&repo=github-readme-stats" />
</a>
<a href="https://github.com/anuraghazra/convoychat">
  <img align="center" src="https://github-readme-stats.vercel.app/api/pin/?username=anuraghazra&repo=convoychat" />
</a>
```

## Despliega tu propia instancia de Vercel

#### :film_projector: [Compruebe paso a paso el video Tutorial por @codeSTACKr](https://youtu.be/n6d4KHSKqGk?t=107)

> **Advertencia** Si estás en el hobby [(i.e. Gratis)](https://vercel.com/pricing) Plan Vercel, por favor asegúrese de cambiar el parámetro `maxDuration` en la versión [. son](https://github.com/anuraghazra/github-readme-stats/blob/master/vercel.json) archivo de `30` a `10` (ver [#1416](https://github.com/anuraghazra/github-readme-stats/issues/1416#issuecomment-950275476) para más información).

Desde que la API de GitHub permite solo 5k peticiones por hora, es posible que mi `https://github-readme-stats.vercel.app/api` pueda llegar al límite. Si lo alojas en tu propio servidor de Vercel, no tendrás que preocuparte de nada. ¡Clickea en el botón "Deploy" para comenzar!

> NOTA: Debido a [#58](https://github.com/anuraghazra/github-readme-stats/pull/58) podríamos manejar más de 5k peticiones sin tener ningún problema con el downtime :D

[![Desplegar a Vercel](https://vercel.com/button)](https://vercel.com/import/project?template=https://github.com/anuraghazra/github-readme-stats)

<details>
 <summary><b>:hammer_and_wrench: Guía paso a paso para configurar su propia instancia de Vercel</b></summary>

1.  Ve a [vercel.com](https://vercel.com/)
2.  Clickea en `Log in` ![](https://files.catbox.moe/pcxk33.png)
3.  Inicia sesión con GitHub presionando `Continue with GitHub` ![](https://files.catbox.moe/b9oxey.png)
4.  Permite el acceso a todos los repositorios (si se te pregunta)
5.  Haz un Fork de este repositorio
6.  Después de bifurcar el repositorio, abre el archivo [`vercel.json`](https://github.com/anuraghazra/github-readme-stats/blob/master/vercel.json#L5) y cambia el campo `maxDuration` a `10`.
7.  Dirígete de nuevo a tu [Vercel dashboard](https://vercel.com/dashboard)
8.  Selecciona `Import Project` ![](https://files.catbox.moe/3n76fh.png)
9.  Haga clic en el botón `Continuar con GitHub` , busque el repositorio de Git requerido e importe haciendo clic en el botón `Importar`. Alternativamente, puedes importar un repositorio Git de terceros usando el enlace `Importar repositorio Git de terceros ->` en la parte inferior de la página. ![](https://files.catbox.moe/mg5p04.png)
10. Selecciona "root" y matén todo como está, simplemente añade tu variable de entorno llamada PAT_1 (como se muestra), la cual contendrá un token de acceso personal (PAT), el cual puedes crear fácilmente [aquí](https://github.com/settings/tokens/new) (mantén todo como está, simplemente asígnale un nombre, puede ser cualquiera que desees)
11. Agregue el PAT como una variable de entorno llamada `PAT_1` (como se muestra). ![](https://files.catbox.moe/0yclio.png)
12. Clickea "Deploy" y ya está listo. ¡Ve tus dominios para usar la API!

</details>

### Mantén tu bifurcación actualizada

Puede mantener su bifurcación y, por lo tanto, su instancia privada de Vercel actualizada con el upstream usando el botón [Sincronizar Fork](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/syncing-a-fork) de GitHubs. También puedes usar el paquete [pull](https://github.com/wei/pull) creado por [@wei](https://github.com/wei) para automatizar este proceso.

## :sparkling_heart: Apoya al proyecto

Casi todos mis proyectos son de código abierto e intento responder a todos los usuarios que necesiten ayuda con alguno de estos proyectos. Obviamente, esto toma tiempo. Puedes usar este servicio gratis.

No obstante, si estás utilizando este proyecto y estás feliz con él o simplemente quieres animarme a que siga creando cosas, aquí tienes algunas maneras de hacerlo:

-   Darme créditos cuando estés utilizando github-readme-stats en tu README, añadiendo un link a este repositorio :D
-   Dándole una estrella y compartiendo el proyecto :rocket:
-   [![paypal.me/anuraghazra](https://ionicabizau.github.io/badges/paypal.svg)](https://www.paypal.me/anuraghazra) - Puedes hacerme una única donación a través de PayPal. Probablemente me compraré un ~~café~~ té. :tea:

¡Gracias! :heart: :heart:

* * *

[![https://vercel.com?utm_source=github_readme_stats_team&utm_campaign=oss](./powered-by-vercel.svg)](https://vercel.com?utm_source=github_readme_stats_team&utm_campaign=oss)

¡Las contribuciones son bienvenidas! <3 &lt;3

Hecho con :heart: y JavaScript.
