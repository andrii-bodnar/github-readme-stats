<p align="center">
 <img width="100px" src="https://res.cloudinary.com/anuraghazra/image/upload/v1594908242/logo_ccswme.svg" align="center" alt="GitHub Readme Stats" />
 <h2 align="center">GitHub Readme Stats</h2>
 <p align="center">Adicione suas estatísticas no GitHub geradas dinamicamente em seus readmes!</p>
</p>
  <p align="center">
    <a href="https://github.com/anuraghazra/github-readme-stats/actions">
      <img alt="Testes aprovados" src="https://github.com/anuraghazra/github-readme-stats/workflows/Test/badge.svg" />
    </a>
    <a href="https://github.com/anuraghazra/github-readme-stats/graphs/contributors">
      <img alt="GitHub Contributors" src="https://img.shields.io/github/contributors/anuraghazra/github-readme-stats" />
    </a>
    <a href="https://codecov.io/gh/anuraghazra/github-readme-stats">
      <img src="https://codecov.io/gh/anuraghazra/github-readme-stats/branch/master/graph/badge.svg" />
    </a>
    <a href="https://github.com/anuraghazra/github-readme-stats/issues">
      <img alt="Solicitações" src="https://img.shields.io/github/issues/anuraghazra/github-readme-stats?color=0088ff" />
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
    <a href="#demonstração">Ver demonstração</a>
    ·
    <a href="https://github.com/anuraghazra/github-readme-stats/issues/new/choose">Reportar erros</a>
    ·
    <a href="https://github.com/anuraghazra/github-readme-stats/issues/new/choose">Solicitar recursos</a>
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
    <a href="/docs/readme_np.md">नेपाली</a>
    .
    <a href="/docs/readme_tr.md">Tuapatalk</a>
  </p>
</p>

<p align="center">Gostou do projeto? Por favor considere <a href="https://www.paypal.me/anuraghazra">fazer uma doação</a> para ajudar a melhorá-lo!</p>

<a href="https://indiafightscorona.giveindia.org">
  <img src="https://indiaspora.org/wp-content/uploads/2021/04/give-India-logo.png" alt="Dar logotipo india" width="200" />
</a>

Você está pensando em apoiar o projeto doando? Por favor, NÃO!!

Em vez disso, ajude a Índia a combater a segunda onda mortífera do COVID-19. Milhares de pessoas estão morrendo na Índia por causa da falta de Oxigênio & também devido à infraestrutura relacionada ao COVID.

Visite <https://indiafightscorona.giveindia.org> e faça uma pequena doação para nos ajudar a combater o COVID e a superar esta crise. Uma pequena doação vai muito longe. :heart:

</p>

# Características

-   [Cartão de estatísticas do GitHub](#github-stats-card)
-   [Pins extras do GitHub](#github-extra-pins)
-   [Cartão de principais linguagens de programação](#top-languages-card)
-   [Estatística semanal Wakatime](#wakatime-week-stats)
-   [Temas](#themes)
    -   [Tema de Cartão Responsivo](#responsive-card-theme)
-   [Personalização](#customization)
    -   [Opções comuns](#common-options)
    -   [Opções exclusivas do cartão de estatísticas:](#stats-card-exclusive-options)
    -   [Opções exclusivas do cartão de repositórios:](#repo-card-exclusive-options)
    -   [`hide_border` - Esconde a borda do cartão _(boleano)_](#language-card-exclusive-options)
    -   [Opção Exclusiva de Cartão Wakatime](#wakatime-card-exclusive-options)
-   [Faça suas próprias implantações](#deploy-on-your-own-vercel-instance)
    -   [Mantenha seu fork atualizado](#keep-your-fork-up-to-date)

# Cartão de estatísticas do GitHub

Copie e cole isso no seu conteúdo de remarcação e é isso. Simples!

Mude o valor de `?username=` para o seu nome de usuário no GitHub.

```md
[![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra)](https://github.com/anuraghazra/github-readme-stats)
```

> **Nota** ranks disponíveis são S+ (top 1%), S (top 25%), A++ (top 45%), A+ (top 60%), e B+ (todos todos). Os valores são calculados usando a [função de distribuição cumulativa](https://en.wikipedia.org/wiki/Cumulative_distribution_function) usando commits, contribuições, issues, estrelas, pull requests, seguidores e repositórios possuídos. A implementação pode ser investigada em [src/calculateRank.js](./src/calculateRank.js). .

### Ocultando estatísticas específicas

Para ocultar estatísticas individualmente, você pode passar um parâmetro de consulta `?hide=` com valores separados por vírgula.

> Opções: `&hide=stars,commits,prs,issues,contribs`

```md
![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&hide=contribs,prs)
```

### Adicionando contagem de contribuições privadas à contagem total de commits

Adicione a contagem de todas as suas contribuições privadas à contagem total de confirmações usando o parâmetro de consulta `?count_private=true`.

> **Nota** Se você estiver implantando este projeto você mesmo, as contribuições privadas serão contadas por padrão. Se você estiver usando a instância pública da Vercel, é necessário escolher [compartilhar suas contribuições privadas](https://docs.github.com/en/account-and-profile/setting-up-and-managing-your-github-profile/managing-contribution-settings-on-your-profile/showing-your-private-contributions-and-achievements-on-your-profile).

> Opções: `&count_private=true`

```md
![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&count_private=true)
```

### Exibindo ícones

Para habilitar ícones, basta utilizar o parâmetro `show_icons=true` na sua requisição, da seguinte forma:

```md
![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true)
```

### Temas

Com temas predefinidos, pode personalizar a aparência dos cartões sem precisar fazer nenhuma [configuração manual](#personalização).

Utilize o parâmetro `?theme=THEME_NAME`, da seguinte forma:

```md
![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&theme=radical)
```

#### Todos os temas predefinidos :

dark, radical, merko, gruvbox, tokyonight, onedark, cobalt, synthwave, highcontrast, dracula

<img src="https://res.cloudinary.com/anuraghazra/image/upload/v1595174536/grs-themes_l4ynja.png" alt="GitHub Readme Stat Themes" width="600px" />

Visualize [todos o temas disponíveis](../themes/README.md) ou o [arquivo de configuração de tema](../themes/index.js), além de **também poder contribuir com novos temas**, se desejar :D

#### Tema de Cartão Responsivo

[![Anurag's GitHub stats-Dark](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&theme=dark#gh-dark-mode-only)](https://github.com/anuraghazra/github-readme-stats#gh-dark-mode-only) [![Selecione <code>Import Git Repository</code>](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&theme=default#gh-light-mode-only)](https://github.com/anuraghazra/github-readme-stats#gh-light-mode-only)

Uma vez que o GitHub irá re-carregar os cartões e servi-los a partir do [CDN](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/about-anonymized-urls), não podemos inferir o tema do navegador / GitHub no lado do servidor. No entanto, existem quatro métodos que você pode usar para criar temas dinâmicos no lado do cliente.

##### Use o tema transparente

Nós incluímos um tema `transparente` que tem um fundo transparente. Este tema é otimizado para parecer bom nos temas padrão escuro e claro do GitHub. Você pode habilitar este tema usando o parâmetro `&tema=transparente` assim:

```md
![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&theme=transparent)
```

<details>
<summary>:eyes: Mostrar exemplo</summary>

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&theme=transparent)

</details>

##### Adicione um canal alfa transparente a um tema bg_color

Você pode usar o parâmetro `bg_color` para tornar qualquer um dos [temas disponíveis](./themes/README.md) transparente. Isto é feito definindo a `bg_color` para uma cor com um canal alfa transparente (ou seja, `bg_├00000000`):

```md
![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&bg_color=00000000)
```

<details>
<summary>:eyes: Mostrar exemplo</summary>

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&bg_color=00000000)

</details>

##### `theme` - Nome do tema, escolha em [todos os temas disponíveis](../themes/README.md)

Você pode usar [tags do tema](https://github.blog/changelog/2021-11-24-specify-theme-context-for-images-in-markdown/) do GitHub para alternar o tema com base no tema do usuário do GitHub automaticamente. Isto é feito ao adicionar `#gh-dark-mode-only` ou `#gh-light-mode-only` ao final de uma URL da imagem. Esta tag definirá se a imagem especificada no markdown só é mostrada aos espectadores usando um tema claro ou no GitHub:

```md
[![GitHub stats-Dark do Anurag](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&theme=dark#gh-dark-mode-only)](https://github.com/anuraghazra/github-readme-stats#gh-dark-mode-only)
[![Status do GitHub do Anurag](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&theme=default#gh-light-mode-only)](https://github.com/anurhazra/github-readme-stats#gh-light-mode-only)
```

<details>
<summary>:eyes: Mostrar exemplo</summary>

[![Anurag's GitHub stats-Dark](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&theme=dark#gh-dark-mode-only)](https://github.com/anuraghazra/github-readme-stats#gh-dark-mode-only) [![Nota: As principais linguagens de programação não fazem declarações sobre habilidades pessoais ou similares, é apenas uma figura-chave com base nas estatísticas do GitHub do usuário indicando a frequência com que cada uma foi utilizada.](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&theme=default#gh-light-mode-only)](https://github.com/anuraghazra/github-readme-stats#gh-light-mode-only)

</details>

##### Use o novo recurso de mídia do GitHub

Você pode usar [o novo recurso de mídia](https://github.blog/changelog/2022-05-19-specify-theme-context-for-images-in-markdown-beta/) do GitHub para especificar se deseja exibir imagens para temas claros ou escuros. Isso é feito utilizando o elemento HTML `<picture>` em combinação com o recurso de mídia `preferir color-scheme`.

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
<summary>:eyes: Mostrar exemplo</summary>

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

### Personalização

Personalize a aparência do seu `Stats Card` ou `Repo Card` da maneira que desejar com os parâmetros de URL.

#### Todas as demonstrações

-   `title_color` - Cor do título do cartão _(hex color)_ Default: `2f80ed`.
-   `text_color` - Cor de texto do conteúdo _(hex color)_ Padrão: `434d58`.
-   `icon_color` - Cor dos ícones (se disponível) _(hex color)_ Padrão: `4c71f2`.
-   `border_color` - Cor da borda do cartão _(cor hexadecimal)_. Padrão: `e4e2e2` (Não se aplica quando `hide_border` está ativado).
-   `bg_color` - Cor de fundo do cartão _(hex color)_ Padrão: `fffefe`
-   `hide_border` - Oculta a borda _(booleano)_ do cartão. Padrão: `false`
-   `tema` - nome do tema, escolha entre [todos os temas disponíveis](./themes/README.md). Padrão: `tema` padrão.
-   `cache_seconds` - Defina o cabeçalho do cache manualmente _(min: 1800, max: 86400)_ Padrão: `14400 segundos (4 horas)`.
-   `locale` - defina o idioma no cartão _(por exemplo. cn, de, es, etc.)_
-   `border_radius` - Arredondamento das bordas no cartão. Padrão: `4.5`.

> **Aviso** Usamos cache para diminuir o carregamento em nossos servidores (veja <https://github.com/anuraghazra/github-readme-stats/issues/1471#issuecomment-1271551425>). Nossos cartões têm um cache padrão de 4 horas (14400 segundos). Note também que o cache é limitado a um mínimo de 30 minutos e um máximo de 24 horas.

##### Gradiente no bg_color

Você pode fornecer vários valores separados por vírgulas na opção bg_color para renderizar um gradiente com o seguinte formato:

    &bg_├DEG,COLOR1,COLOR2,COLOR3...COLOR10

#### `card_width` - Define a largura do cartão manualmente _(number)_

-   `ocultar` - Oculta os [itens especificados](#hiding-individual-stats) das estatísticas _(valores separados por vírgula)_. Padrão: `[] (array em branco)`.
-   `hide_title` - _(booleano)_. Padrão: `false`.
-   `card_width` - Defina a largura da carta manualmente _(número)_. Padrão: `500px (approx.)`.
-   `hide_rank` - Ocultar a classificação _(boolean)_ Padrão: `false`.
-   `show_icons` - _(boolean)_. Padrão: `false`.
-   `include_all_commits` - Contabiliza todos os commits ao invés de apenas os atual ano _(boolean)_ Padrão: `false`.
-   `count_private` - Contabiliza commits privados _(boolean)_ Padrão: `false`.
-   `line_height` - Define a altura da linha entre o texto _(número)_. Padrão: `25`.
-   `exclude_repo` - Excluir estrelas dos repositórios _(valores separados por vírgula)_. Padrão: `[] (array em branco)`.
-   `custom_title` - Define um título personalizado para o cartão. Default:  `<username> GitHub Stats`.
-   `text_negrito` - Use texto em negrito _(booleano)_. Padrão: `verdadeiro`.
-   `disable_animations` - Desabilita todas as animações no cartão _(booleano)_. Padrão: `false`.
-   `ring_color` - Cor do círculo de ranque _(cor hexadecimal)_. O padrão é a cor de toque do tema se existir e de outra forma a cor do título.

> **Nota** Quando hide_rank=`true`, a largura mínima do cartão é 270 px + o comprimento do título e preenchimento.

#### Opções exclusivas do cartão de linguagens:

-   `show_owner` - Exibir o nome da pessoa a quem o repositório pertence _(boolean)_ Padrão: `false`.

#### `hide` - Oculta linguagens específicas _(Valores separados por vírgulas)_

-   `Ocultar` - Ocultar os idiomas especificados no cartão _(valores separados por vírgula)_. Padrão: `[] (array em branco)`.
-   `hide_title` - _(booleano)_. Padrão: `false`.
-   `layout` - Alterne entre dois layouts disponíveis `padrão` & `compact`. Padrão: `padrão`.
-   `card_width` - Defina a largura da carta manualmente _(número)_. Padrão `300`.
-   `langs_count` - Mostrar mais idiomas no cartão, entre 1-10 _(número)_. Padrão `5`.
-   `exclude_repo` - Excluir repositórios _(valores separados por vírgula)_. Padrão: `[] (array em branco)`.
-   `custom_title` - Define um título personalizado para o cartão _(string)_. Padrão `Idiomas Mais Usados`.
-   `disable_animations` - Desabilita todas as animações no cartão _(booleano)_. Padrão: `false`.

> :warning: **Importante:** Nomes de linguagens devem ser uma sequência escapada de URI, como específicado em [Codificação por cento](https://pt.wikipedia.org/wiki/Codificação_por_cento) (Ou seja: `c++` deve se tornar `c%2B%2B`, `jupyter notebook` deve se tornar `jupyter%20notebook`, etc.) Você pode usar [urlencoder.org](https://www.urlencoder.org/) para ajudá-lo a fazer isso automaticamente.

#### Opções Exclusivas do Wakatime Card

-   `Ocultar` - Ocultar os idiomas especificados no cartão _(valores separados por vírgula)_. Padrão: `[] (array em branco)`.
-   `hide_title` - Oculta o título _(boolean)_ Padrão `false`.
-   `line_height` - Define a altura do espaçamento entre o texto _(number)_ Padrão `25`.
-   `hide_title` - Ocultar o título _(boolean)_ Padrão `false`.
-   `custom_title` - Define um título personalizado para o cartão _(string)_. Default `Wakatime Stats`.
-   `layout` - Alterna entre os dois layouts disponíveis `default` & `compact`  Padrão ``.
-   `langs_count` - Limita o número de idiomas no cartão, o padrão é todos os idiomas relatados _(número)_.
-   `api_domain` - Defina um domínio de API personalizado para o cartão, por exemplo para utilizar serviços como [Hakatime](https://github.com/mujx/hakatime) ou [Wakapi](https://github.com/muety/wakapi) _(string)_. `API Waka padrão`.
-   `range` - Solicite um intervalo diferente de seu padrão WakaTime, por exemplo, `last_7_days`. Consulte [a documentação da API WakaTime](https://wakatime.com/developers#stats) para ver uma lista das opções disponíveis. _(AAAA-MM, last_7_days last_30_days last_6_months, last_year, or all_time)_. `Toda _time` padrão.

* * *

# Pins extras do GitHub

Os Pins extras do GitHub permitem fixar mais de 6 repositórios no seu perfil usando um perfil README.me do GitHub.

Uhu! Você não está mais limitado a 6 repositórios fixados.

### Utilização

Copie e cole esse código no seu README.md e altere os atributos.

Endpoint: `api/pin?username=anuraghazra&repo=github-readme-stats`

```md
[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=anuraghazra&repo=github-readme-stats)](https://github.com/anuraghazra/github-readme-stats)
```

### Demonstração

[![Leia-me Cartão](https://github-readme-stats.vercel.app/api/pin/?username=anuraghazra&repo=github-readme-stats)](https://github.com/anuraghazra/github-readme-stats)

Utilize a variável [show_owner](#personalização) para incluir o nome de usuário do proprietária do repositório

[![Leia-me Cartão](https://github-readme-stats.vercel.app/api/pin/?username=anuraghazra&repo=github-readme-stats&show_owner=true)](https://github.com/anuraghazra/github-readme-stats)

# Cartão de principais linguagens de programação

Exibe uma métrica de linguagens de programação mais usadas pelo usuário do GitHub.

> **Observe** Idiomas Principais não indicam meu nível de habilidade nem nada parecido; É uma métrica do GitHub para determinar quais idiomas têm o maior código no GitHub. É uma nova característica dos atributos de leitura de github.

### Utilização

Copie e cole esse código no seu README.md e altere os atributos.

Endpoint: `api/top-langs?username=anuraghazra`

```md
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=anuraghazra)](https://github.com/anuraghazra/github-readme-stats)
```

### Excluir repositórios individuais

Você pode usar o parâmetro `&exclude_repo=repo1,repo2` para excluir repositórios individuais.

```md
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=anuraghazra&exclude_repo=github-readme-stats,anuraghazra.github.io)](https://github.com/anuraghazra/github-readme-stats)
```

### Ocultar linguagens individualmente

Utilize o parâmetro `?hide=language1,language2` para ocultar linguagens específicas.

```md
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=anuraghazra&hide=javascript,html)](https://github.com/anuraghazra/github-readme-stats)
```

### Mostrar mais idiomas

Você pode usar a opção `&langs_count=` para aumentar ou diminuir o número de idiomas mostrados no cartão. Valores válidos são inteiros entre 1 e 10 (inclusive), e o padrão é 5.

```md
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=anuraghazra&langs_count=8)](https://github.com/anuraghazra/github-readme-stats)
```

### Layout de cartão de linguagens compacto

Utilize a opção `&layout=compact` para mudar o layout do cartão.

```md
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=anuraghazra&layout=compact)](https://github.com/anuraghazra/github-readme-stats)
```

### Demonstração

[![Línguas superiores](https://github-readme-stats.vercel.app/api/top-langs/?username=anuraghazra)](https://github.com/anuraghazra/github-readme-stats)

-   Layout compacto

[![Línguas superiores](https://github-readme-stats.vercel.app/api/top-langs/?username=anuraghazra&layout=compact)](https://github.com/anuraghazra/github-readme-stats)

# Estatística semanal Wakatime

Altere o valor de `?username=` para o seu username do Wakatime.

```md
[![willianrod's wakatime stats](https://github-readme-stats.vercel.app/api/wakatime?username=willianrod)](https://github.com/anuraghazra/github-readme-stats)
```

> **Nota**: Por favor, esteja ciente de que atualmente só mostramos dados de perfis de Wakatime que são públicos.

### Demonstração

[![estatísticas do despertador do willianrod](https://github-readme-stats.vercel.app/api/wakatime?username=willianrod)](https://github.com/anuraghazra/github-readme-stats)

[![estatísticas do despertador do willianrod](https://github-readme-stats.vercel.app/api/wakatime?username=willianrod&hide_progress=true)](https://github.com/anuraghazra/github-readme-stats)

-   Padronizado

[![estatísticas do despertador do willianrod](https://github-readme-stats.vercel.app/api/wakatime?username=willianrod&layout=compact)](https://github.com/anuraghazra/github-readme-stats)

* * *

### Todas as Demonstrações

-   Padrão

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra)

-   Ocultando estatísticas específicas

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&hide=contribs,issues)

-   Mostrando ícones

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&hide=issues&show_icons=true)

-   Personalizar Cor da Borda

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&border_color=2e4058)

-   Incluir todos os commits

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&include_all_commits=true)

-   Temas

Escolha entre um dos [temas predefinidos](#temas)

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&theme=radical)

-   Degradê

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&bg_color=30,e96443,904e95&title_color=fff&text_color=fff)

-   Personalizando o cartão de estatísticas

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api/?username=anuraghazra&show_icons=true&title_color=fff&icon_color=79ff97&text_color=9f9f9f&bg_color=151515)

-   Definindo localidade do cartão

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api/?username=anuraghazra&locale=es)

-   Customizando o cartão de repositório

![Cartão personalizado](https://github-readme-stats.vercel.app/api/pin?username=anuraghazra&repo=github-readme-stats&title_color=fff&icon_color=f9f9f9&text_color=9f9f9f&bg_color=151515)

-   Principais linguagens

[![Línguas superiores](https://github-readme-stats.vercel.app/api/top-langs/?username=anuraghazra)](https://github.com/anuraghazra/github-readme-stats)

-   Cartão WakaTime

[![estatísticas do despertador do willianrod](https://github-readme-stats.vercel.app/api/wakatime?username=willianrod)](https://github.com/anuraghazra/github-readme-stats)

* * *

### Dica (Alinhandos os cartões de repositório)

Por padrão, você não poderá organizar as imagens lado a lado. Para fazer isso, você pode usar a seguinte abordagem:

```html
<a href="https://github.com/anuraghazra/github-readme-stats">
  <img align="center" src="https://github-readme-stats.vercel.app/api/pin/?username=anuraghazra&repo=github-readme-stats" />
</a>
<a href="https://github.com/anuraghazra/convoychat">
  <img align="center" src="https://github-readme-stats.vercel.app/api/pin/?username=anuraghazra&repo=convoychat" />
</a>
```

## Implante em sua própria instância do Vercel

#### Check Out Step By Step Video Tutorial By @codeSTACKr

> **Avisar** Se você estiver no [hobby (ou seja, grátis)](https://vercel.com/pricing) Plano Vercel por favor, certifique-se de alterar o parâmetro `maxDuration` no [vercel. arquivo son](https://github.com/anuraghazra/github-readme-stats/blob/master/vercel.json) de `30` a `10` (veja [#1416](https://github.com/anuraghazra/github-readme-stats/issues/1416#issuecomment-950275476) para mais informações).

Como a API do GitHub permite apenas 5 mil solicitações por hora, é possível que minha `https://github-readme-stats.vercel.app/api` atinja a cota limite. Se hospedar em seu próprio servidor Vercel, não precisará se preocupar com nada. Clique no botão de implantação para começar!

> Nota: Desde [#58](https://github.com/anuraghazra/github-readme-stats/pull/58) há possibilidade de lidar com mais de 5 mil chamadas por hora, sem interrupções :D

[![Implantar para Vercel](https://vercel.com/button)](https://vercel.com/import/project?template=https://github.com/anuraghazra/github-readme-stats)

<details>
 <summary><b>:hammer_and_wrench: Guia passo-a-passo sobre a criação de sua própria instância Vercel</b></summary>

1.  Acesse [vercel.com](https://vercel.com/)
2.  Clique em `Login` ![](https://files.catbox.moe/pcxk33.png)
3.  Acesse com o GitHub clicando em `Continue with GitHub` ![](https://files.catbox.moe/b9oxey.png)
4.  Entre no GitHub e permita acesso a todos os repositórios, se solicitado
5.  Faça Fork neste repositório
6.  Depois de bifurcar o repositório, abra o arquivo [`vercel.json`](https://github.com/anuraghazra/github-readme-stats/blob/master/vercel.json#L5) e altere o campo `Duração` para `10`.
7.  Volte ao seu [painel principal do Vercel](https://vercel.com/dashboard)
8.  Selecione `Import Project` ![](https://files.catbox.moe/3n76fh.png)
9.  Clique no botão `Continuar no GitHub` , procure o Git repositório necessário e importe-o clicando no botão `importar`. Como alternativa, é possível importar um repositório Git de terceiros usando o `Importar o repositório Git Git de terceiros ->` link na parte inferior da página. ![](https://files.catbox.moe/mg5p04.png)
10. Selecione a raiz e mantenha tudo como está, basta adicionar sua variável de ambiente chamada PAT_1 (que será exibida), que conterá um token de acesso pessoal (PAT), que você pode criar facilmente [aqui](https://github.com/settings/tokens/new) (deixe tudo como está, apenas dê um nome, que pode ser o que você quiser)
11. Adicione o PAT como uma variável de ambiente chamada `PAT_1` (como mostrado). ![](https://files.catbox.moe/0yclio.png)
12. Clique em `deploy` e já estará tudo pronto. Veja seus domínios para usar a API!

</details>

### Mantenha seu fork atualizado

Você pode manter seu fork e, assim, sua instância privada do Vercel atualizada com o upstream usando o [botão Sync Fork do GitHub](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/syncing-a-fork) dos GitHub. Você também pode usar o [pull](https://github.com/wei/pull) pacote criado por [@wei](https://github.com/wei) para automatizar esse processo.

## :sparkling_heart: Apoie o projeto

Disponibilizo como código aberto quase tudo o que posso e tento responder a todos que precisam de ajuda para utilizar esses projetos. Claro, isso demanda tempo. Utilize este serviço gratuitamente.

No entanto, se você utilizar este projeto e estiver satisfeito com ele, ou apenas quiser me encorajar a continuar criando coisas, existem algumas formas fazê-lo:

-   Dando os devidos créditos ao usar github-readme-stats no seu README.me, adicionando uma referência ao projeto :D
-   Dando uma estrela (Starring) e compartilhando o projeto 🚀
-   [![paypal.me/anuraghazra](https://ionicabizau.github.io/badges/paypal.svg)](https://www.paypal.me/anuraghazra) - Você pode fazer doações únicas via PayPal. Provavelmente vou comprar um ~~café~~ chá. :tea:

Obrigado! :heart:

* * *

[![https://vercel.com?utm_source=github_readme_stats_team&utm_campaign=oss](./powered-by-vercel.svg)](https://vercel.com?utm_source=github_readme_stats_team&utm_campaign=oss)

Contribuições são bem-vindas! <3

Feito com :heart: e JavaScript.
