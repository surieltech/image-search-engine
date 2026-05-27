# 🖼️ Image Search Engine

Mecanismo de busca de imagens moderno e rápido que utiliza a API do Unsplash para encontrar fotos de alta qualidade gratuitas.

---

## 🚀 Sobre o Projeto

O **Image Search Engine** é uma ferramenta intuitiva que permite buscar imagens de alta resolução usando palavras-chave. O projeto consome a API oficial do Unsplash para fornecer resultados relevantes e de qualidade, ideal para designers, criadores de conteúdo e qualquer pessoa que precise de imagens gratuitas.

O projeto foi desenvolvido com foco em:

- ✔️ Busca rápida e eficiente
- ✔️ Interface limpa e responsiva
- ✔️ Carregamento infinito com paginação
- ✔️ Links diretos para as imagens originais
- ✔️ Layout em grid profissional
- ✔️ Design moderno e atraente

---

## ✨ Funcionalidades

- 🔍 **Busca por palavras-chave** - Pesquise qualquer tema ou assunto
- ⏯️ **Carregar mais** - Paginação com botão "Mostrar mais"
- 🔗 **Link direto** - Clique na imagem para ver no Unsplash
- ⚡ **Carregamento assíncrono** - Sem recarregar a página
- 📱 **Totalmente responsivo** - Funciona no celular, tablet e desktop
- 🚀 **Alta performance** - Imagens otimizadas (formato small)

---

## 🎮 Como Usar

| Ação | Descrição |
|------|-----------|
| `Digite uma palavra` | Ex: montanha, praia, cachorro, tecnologia |
| `Pressione Enter` | Executa a busca automaticamente |
| `Clique em Pesquisar` | Botão para iniciar a busca |
| `Mostrar mais` | Carrega mais 12 imagens do mesmo tema |

### Exemplos de busca:
- 🌄 `paisagem` - Fotos de natureza e cenários
- 🐱 `gato` - Imagens de felinos adoráveis
- 🚗 `carro esportivo` - Veículos automotivos
- 💻 `programador` - Tecnologia e desenvolvimento
- 🎨 `arte digital` - Ilustrações e criações artísticas

---

## 📊 Resultados por Página

| Quantidade | Descrição |
|------------|-----------|
| 12 imagens | Por padrão, cada busca retorna 12 resultados |
| Paginação | Botão "Mostrar mais" adiciona +12 imagens |
| Ilimitado | Pode carregar quantas páginas desejar |

---

## 🛠️ Tecnologias Utilizadas

- **HTML5** - Estrutura semântica e acessível
- **CSS3** - Estilização com Grid Layout e Flexbox
- **JavaScript (ES6+)** - Async/Await, Fetch API e manipulação do DOM
- **Unsplash API** - Banco de imagens gratuito e de alta qualidade
- **Google Fonts** - Tipografia Poppins

---

## 📁 Estrutura de Pastas

image-search-engine/
│
├── 📄 index.html # Página principal
├── 📁 src/
│ └── 📄 script.js # Lógica de busca e API
│ └── 📄 style.css # Estilos CSS
└── 📄 README.md # Documentação

---

## 🔑 Como Obter sua Própria API Key

1. Acesse [Unsplash Developers](https://unsplash.com/developers)
2. Crie uma conta ou faça login
3. Clique em **"Your Apps"** → **"New Application"**
4. Preencha o formulário e aceite os termos
5. Copie sua **Access Key**
6. Substitua no `script.js`:

```javascript
const accessKey = "SUA_CHAVE_AQUI";
```

## 🐛 Possíveis Problemas e Soluções
Problema //	Causa // Solução
- ❌ Imagens não carregam  // API Key inválida  //  Gerar nova chave no Unsplash
- 🔄 Busca sem resultado  //  Palavra muito específica // Tente termos mais genéricos
- 🐌 Carregamento lento  // Conexão instável  //  Aguarde ou tente novamente
- 🔘 Botão "Mostrar mais" some  // Fim dos resultados //  Não há mais imagens disponíveis
- 📐 Layout quebrado  //  CSS não carregou	//  Verifique o caminho do arquivo