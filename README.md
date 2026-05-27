# ateliê ✦ — Site Artesanal

> Site institucional para ateliê de **cerâmica fria** e **velas artesanais** feitas à mão.  
> Desenvolvido com HTML, CSS e JavaScript puros — sem frameworks, sem dependências.

-----

## ✨ Visão Geral

Landing page completa e responsiva para divulgar o trabalho artesanal do ateliê, apresentar coleções, linha de velas, história da marca e facilitar o contato para encomendas.

-----

## 📸 Seções

|Seção        |Descrição                                                                 |
|-------------|--------------------------------------------------------------------------|
|**Hero**     |Chamada principal com imagem em destaque e botões de ação                 |
|**Features** |4 diferenciais da marca (feito à mão, qualidade, personalizado, com amor) |
|**Coleções** |Grade com 5 coleções de cerâmica (Fé, Afeto, Família, Memórias, Florescer)|
|**Sobre**    |História do ateliê com foto da artesã                                     |
|**Velas**    |Linha de velas artesanais em fundo escuro elegante                        |
|**Instagram**|Grade de fotos linkando ao perfil                                         |
|**Rodapé**   |Navegação, contato e informações                                          |

-----

## 🛠️ Tecnologias

- **HTML5** semântico
- **CSS3** puro — variáveis, grid, clamp(), animações, backdrop-filter
- **JavaScript** vanilla — scroll reveal, menu hambúrguer, nav ativa
- **Google Fonts** — Cormorant Garamond + Jost

Sem bibliotecas externas. Sem build step. Abre direto no navegador.

-----

## 📱 Responsividade

Três breakpoints com layout adaptado:

```
Desktop  → 2 colunas, 5 coleções, 7 fotos no Instagram
Tablet   → hero empilhado, coleções em 3, velas em 2, menu hambúrguer
Mobile   → coluna única, Instagram com 3 fotos, drawer de navegação
```

-----

## 🎨 Paleta de Cores

```css
--cream:      #F7F2EC   /* fundo seções */
--warm-white: #FDFAF6   /* fundo principal */
--clay:       #C4784A   /* cor de destaque / terracota */
--clay-light: #D9956A   /* variação clara */
--clay-dark:  #9E5A30   /* variação escura */
--linen:      #E8DDD0   /* placeholders / imagens */
--charcoal:   #2C2420   /* fundo seção velas */
--text:       #3D2E26   /* texto principal */
--muted:      #9C8878   /* texto secundário */
--border:     #DDD0C4   /* divisores */
```

-----

## 🚀 Como usar

```bash
# Clone o repositório
git clone https://github.com/seu-usuario/atelie.git

# Entre na pasta
cd atelie

# Abra no navegador
open index.html
```

Ou simplesmente faça o download do `index.html` e abra no browser.

-----

## 📂 Estrutura

```
atelie/
├── index.html      # arquivo único com HTML + CSS + JS
└── README.md
```

> As fotos dos produtos ainda serão adicionadas.  
> Cada espaço está marcado com 📸 no código para facilitar a substituição.

-----

## 📝 Como adicionar fotos

Procure as marcações `📸 Foto aqui` no código e substitua a `<div class="col-img">` (ou equivalente) por uma tag `<img>`:

```html
<!-- Antes -->
<div class="col-img">
  <div class="col-placeholder">...</div>
  <div class="photo-label">📸 Foto aqui</div>
</div>

<!-- Depois -->
<div class="col-img">
  <img src="fotos/afeto.jpg" alt="Coleção Afeto — peças de cerâmica fria">
</div>
```

-----

## 🔧 Personalização rápida

|O que mudar        |Onde no código                                                            |
|-------------------|--------------------------------------------------------------------------|
|Nome do ateliê     |Altere `ateliê ✦` no `<nav>`, `<footer>` e `<title>`                      |
|Cor de destaque    |Altere `--clay: #C4784A` no `:root`                                       |
|Handle do Instagram|Substitua `@seuatelie` no rodapé                                          |
|Número do WhatsApp |Adicione link `href="https://wa.me/55XXXXXXXXXXX"` nos botões de encomenda|
|Aromas das velas   |Edite os cards na seção `#velas`                                          |
|Coleções           |Edite os cards na seção `#colecoes`                                       |

-----

## 📄 Licença

Uso pessoal — desenvolvido com ♡ para o ateliê da família.
