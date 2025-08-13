# Landing Page - Meteora

Este projeto é uma landing page responsiva desenvolvida com [Bootstrap 5.3](https://getbootstrap.com/), baseada em um design criado no Figma. A página simula um e-commerce de moda fictício chamado **Meteora**, com banners, categorias, produtos e seções promocionais.

🔗 **Link para o design no Figma**: _[[Meteora](https://www.figma.com/files/team/1486052303828102248/resources/community/file/1416522959494233031?fuid=1486052301688602191)]_  

## 🔧 Tecnologias Utilizadas

- HTML5
- CSS3 (customizações via `custom.css`)
- [Bootstrap 5.3](https://getbootstrap.com/)
- Google Fonts (Inter)

## 🧱 Componentes do Bootstrap utilizados

O projeto faz uso extensivo da estrutura e dos componentes nativos do Bootstrap 5:

### Layout e Grid
- `container-fluid`, `row`, `col-*` para layout responsivo
- Utilização de classes como `p-5`, `m-2`, `g-2`, `mb-4` etc. para espaçamento e margem

### Navegação
- `navbar`, `navbar-expand-lg`, `navbar-toggler`, `collapse`, `nav-item`, `nav-link`

### Formulários
- `form-control`, `form`, `input`, `button`, `btn`, `btn-outline-light`, etc.

### Carousel
- `carousel`, `carousel-inner`, `carousel-item`, `carousel-control-prev/next`, `carousel-indicators`

### Cartões
- `card`, `card-body`, `card-title`, `card-text`, `card-img-top`, usados para exibir produtos e categorias

### Tipografia e Utilitários
- `text-center`, `text-white`, `fw-bold`, `d-flex`, `justify-content-center`, `align-items-center`, `gap-4`, `w-50`, `visually-hidden`

## 📁 Estrutura de Arquivos
````
/src
├── /assets
│ ├── /banner
│ ├── /catergoria
│ ├── /icons
│ └── /img
└── /css
└── custom.css

index.html
````

## 📝 Observações

- O layout é 100% responsivo, com imagens e seções ajustadas para diferentes tamanhos de tela (mobile, tablet, desktop) usando classes utilitárias como `d-none`, `d-sm-block`, `d-lg-none`, etc.
- O projeto é fictício e não possui funcionalidade de backend.
- As cores personalizadas são aplicadas por meio de variáveis CSS e de um arquivo externo `custom.css`.

---

👨‍💻 Feito por **Mozzer** como exercício de HTML + Bootstrap com base em um design no Figma.
