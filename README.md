# 👟 SyntaxWear - Ecommerce de Tênis e Sneakers

> Uma plataforma de ecommerce moderna e responsiva para compra de tênis e sneakers online.

![Status](https://img.shields.io/badge/Status-Em%20Desenvolvimento-yellow)
![HTML5](https://img.shields.io/badge/HTML5-FFA500?style=flat)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat)

## 📋 Sobre o Projeto

**SyntaxWear** é uma plataforma de ecommerce especializada em tênis e sneakers de alta qualidade. O projeto oferece uma experiência de compra intuitiva com design responsivo, navegação clara e uma estrutura CSS bem organizada e escalável.

### Público-Alvo
- Entusiastas de tênis e sneakers
- Clientes que buscam qualidade e estilo
- Usuários em dispositivos desktop e mobile

---

## 🎯 Funcionalidades Principais

✅ **Navegação Responsiva** - Menu adaptável para desktop e mobile  
✅ **Seção Hero** - Banner destacado com chamadas à ação  
✅ **Catálogo de Produtos** - Cards informativos com imagens  
✅ **Design Moderno** - Interface intuitiva e acessível  
✅ **Estrutura CSS Escalável** - Componentes reutilizáveis  
✅ **Compatibilidade Multi-Dispositivo** - Funciona em desktop, tablet e mobile  

---

## 📂 Estrutura de Pastas

```
ecommerce-syntaxwear/
│
├── 📄 index.html                 # Página principal
├── 📄 README.md                  # Documentação do projeto
│
├── 📁 css/                       # Arquivos de estilo
│   ├── 📁 base/                  # Estilos base e globais
│   │   ├── reset.css            # Reset de estilos padrão do navegador
│   │   ├── variable.css         # Variáveis CSS (cores, fontes, etc)
│   │   ├── base.css             # Estilos base globais
│   │   ├── global.css           # Estilos globais adicionais
│   │   └── typography.css       # Estilos de tipografia
│   │
│   ├── 📁 components/           # Componentes reutilizáveis
│   │   ├── buttons.css          # Estilo de botões
│   │   ├── cards.css            # Estilo de cards/cartões
│   │   ├── forms.css            # Estilo de formulários
│   │   └── hero.css             # Estilo da seção hero
│   │
│   ├── 📁 layout/               # Layout geral da página
│   │   ├── header.css           # Estilo do cabeçalho
│   │   ├── footer.css           # Estilo do rodapé
│   │   └── grid.css             # Sistema de grid responsivo
│   │
│   ├── 📁 pages/                # Estilos específicos de páginas
│   │   └── home.css             # Estilos da página inicial
│   │
│   └── 📄 style.css             # Arquivo principal de importação CSS
│
├── 📁 img/                       # Arquivos de mídia
│   ├── 📁 banners/             # Imagens de banners promocionais
│   ├── 📁 favicon/             # Ícone do site (favicon)
│   ├── 📁 icons/               # Ícones do site (user, help, menu, etc)
│   ├── 📁 logo/                # Logo da marca
│   └── 📁 products/            # Imagens de produtos
│
└── 📁 .git/                      # Controle de versão Git
```

---

## 🎨 Organização do CSS

O projeto utiliza uma **arquitetura CSS modular e escalável** com separação de responsabilidades:

### 📦 Camadas CSS

| Camada | Arquivo | Propósito |
|--------|---------|----------|
| **Base** | `reset.css` | Remove estilos padrão do navegador |
| **Base** | `variable.css` | Define variáveis CSS (cores, espaçamentos, etc) |
| **Base** | `base.css` | Estilos fundamentais e reset |
| **Base** | `typography.css` | Tipografia e estilos de texto |
| **Componentes** | `buttons.css` | Buttons e elementos interativos |
| **Componentes** | `cards.css` | Cards e containers de conteúdo |
| **Componentes** | `forms.css` | Formulários e inputs |
| **Componentes** | `hero.css` | Seção destaque (hero section) |
| **Layout** | `header.css` | Cabeçalho e navegação |
| **Layout** | `footer.css` | Rodapé |
| **Layout** | `grid.css` | Sistema de grid e layout responsivo |
| **Pages** | `home.css` | Estilos específicos da página inicial |
| **Principal** | `style.css` | Importação centralizada de todos os CSS |

### ✨ Benefícios da Arquitetura

- 🔧 **Manutenção Fácil** - Cada componente em seu próprio arquivo
- 📈 **Escalável** - Fácil adicionar novos componentes
- 🔄 **Reutilizável** - Componentes podem ser usados em múltiplas páginas
- 📱 **Responsivo** - Media queries centralizadas no `grid.css`

---

## 🚀 Como Usar

### Pré-requisitos
- Navegador web moderno (Chrome, Firefox, Safari, Edge)
- Editor de código (VS Code, Sublime Text, etc) - opcional

### Instalação

1. **Clone o repositório**
   ```bash
   git clone https://github.com/Theux-Zill/ecommerce-syntaxwear.git
   cd ecommerce-syntaxwear
   ```

2. **Abra no navegador**
   - Navegue até a pasta do projeto
   - Clique duas vezes no arquivo `index.html`
   - Ou use um servidor local (Live Server no VS Code)

### Servidor Local (Recomendado)

#### Opção 1: VS Code Live Server
1. Instale a extensão "Live Server" no VS Code
2. Clique direito em `index.html`
3. Selecione "Open with Live Server"

#### Opção 2: Python SimpleHTTP
```bash
# Python 3
python -m http.server 8000

# Acesse no navegador: http://localhost:8000
```

#### Opção 3: Node.js http-server
```bash
# Instale globalmente
npm install -g http-server

# Execute
http-server

# Acesse no navegador: http://localhost:8080
```

---

## 📱 Responsividade

O projeto é otimizado para os seguintes breakpoints:

| Dispositivo | Largura | Breakpoint |
|-------------|---------|-----------|
| Mobile | até 768px | `max-width: 768px` |
| Tablet | 768px a 1024px | `768px to 1024px` |
| Desktop | acima de 1024px | `min-width: 1024px` |

Consulte o arquivo `css/layout/grid.css` para mais detalhes sobre as media queries.

---

## 🛠️ Tecnologias Utilizadas

- **HTML5** - Estrutura semântica e acessível
- **CSS3** - Estilização com variáveis CSS, Grid e Flexbox
- **JavaScript** (em preparação) - Interatividades futuras
- **Git** - Controle de versão

---

## 📝 Convenções de Nomenclatura

### Classes CSS
- Use `kebab-case` para nomes de classes: `.site-header`, `.nav-container`
- Nomes descritivos: `.primary-button`, `.product-card`
- Modificadores BEM quando aplicável: `.button--primary`, `.card--featured`

### Estrutura HTML
- Use tags semânticas: `<header>`, `<nav>`, `<main>`, `<footer>`
- Use `aria-label` para melhor acessibilidade
- Mantenha hierarquia apropriada de headings

---

## 🔗 Navegação do Site

### Menu Principal
- **Masculino** - Produtos para homens
- **Feminino** - Produtos para mulheres
- **Outlet** - Produtos com desconto

### Menu Secundário
- **Nossas Lojas** - Localização de lojas físicas
- **Sobre** - Informações da marca
- **Perfil** - Conta do usuário
- **Ajuda** - Suporte ao cliente

---

## 📦 Assets (Imagens)

### Categorias de Imagens

```
img/
├── banners/        # Imagens promocionais (ex: banners de campanha)
├── favicon/        # Ícone do site (favicon.ico)
├── icons/          # Ícones SVG (menu, user, help, busca, etc)
├── logo/           # Logo da marca SyntaxWear
└── products/       # Imagens dos produtos (tênis, sneakers)
```

**Recomendações para imagens:**
- Use formato WebP para melhor compressão
- Fallback para JPG/PNG para navegadores antigos
- Comprima imagens com TinyPNG ou similar
- Tamanho máximo recomendado: 1MB por imagem

---

## 🎯 Próximas Funcionalidades

- [ ] Carrinho de compras funcional
- [ ] Sistema de login/cadastro
- [ ] Filtros de produtos
- [ ] Sistema de avaliações
- [ ] Busca de produtos
- [ ] Integração de pagamento
- [ ] Gestão de pedidos
- [ ] Mix de PWA (Progressive Web App)

---

## 🤝 Como Contribuir

1. Faça um fork do projeto
2. Crie uma branch para sua feature (`git checkout -b feature/AmazingFeature`)
3. Commit suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. Push para a branch (`git push origin feature/AmazingFeature`)
5. Abra um Pull Request

### Diretrizes
- Mantenha o padrão de código existente
- Documente mudanças significativas
- Teste em múltiplos navegadores e dispositivos
- Use nomes descritivos para commits

---

## 📞 Suporte e Contato

- **Issues** - Reporte bugs e sugira melhorias via GitHub Issues
- **Email** - [seu-email@exemplo.com]
- **Redes Sociais** - [Links para redes sociais]

---

## 📄 Licença

This project is licensed under the MIT License - see the LICENSE file for details.

---

## 👨‍💻 Autores

- **Seu Nome** - Desenvolvedor Responsável

---

## 🙏 Agradecimentos

- Inspiração de grandes plataformas de ecommerce
- Comunidade dev por feedback e sugestões
- Designers pelo conceito visual

---

**Desenvolvido com ❤️ para os amantes de tênis e sneakers**

Última atualização: Março de 2026