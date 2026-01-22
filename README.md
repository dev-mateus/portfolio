# 🎨 Portfólio Profissional - Página Pessoal

Uma página de portfólio moderna, responsiva e profissional desenvolvida com **HTML5, CSS3 e JavaScript puro** (sem frameworks).

## ✨ Características

- ✅ **Design Responsivo** - Funciona perfeitamente em desktop, tablet e mobile
- ✅ **HTML Semântico** - Estrutura acessível e SEO-friendly
- ✅ **CSS Moderno** - Gradientes, animações suaves e layout flex/grid
- ✅ **JavaScript Puro** - Sem dependências externas
- ✅ **Tema Escuro Profissional** - Cores modernas e confiáveis
- ✅ **Animações Fluidas** - Efeitos visuais elegantes
- ✅ **Menu Mobile** - Hamburger menu responsivo
- ✅ **Form de Contato** - Validação e feedback visual
- ✅ **Scroll Animations** - Elementos aparecem ao scroll
- ✅ **Links Ativos** - Navegação inteligente

## 📁 Estrutura do Projeto

```text
portfolio/
├── index.html           # Arquivo principal HTML
├── css/
│   └── style.css       # Estilos CSS completos
├── js/
│   └── script.js       # JavaScript com interatividades
└── assets/             # Pasta para imagens e recursos
```

## 🚀 Como Usar

1. **Baixar/Clonar o projeto**

```bash
cd portfolio
```

1. **Abrir no navegador**

- Clique duplo em `index.html` ou
- Use um servidor local: `python -m http.server 8000`

1. **Personalizar**

- Edite o HTML com suas informações
- Substitua dados genéricos pelos seus dados reais
- Atualize as seções conforme necessário

## 📝 Seções Incluídas

### 1. Navegação (`<nav>`)

- Logo com gradiente
- Menu responsivo
- Hamburger menu para mobile
- Indicador de seção ativa

### 2. Hero Section (`#home`)

- Apresentação principal
- Botões de ação
- Avatar placeholder
- Efeitos de fundo animados

### 3. Sobre Mim (`#about`)

- Descrição profissional
- Estatísticas com contadores animados
- Cards informativos com hover

### 4. Experiência (`#experience`)

- Timeline visual
- Histórico profissional
- Responsabilidades por cargo
- Animações ao hover

### 5. Projetos (`#projects`)

- Grid responsivo
- Cards com imagem, descrição e tags
- Links para projetos
- Hover effects elegantes

### 6. Habilidades (`#skills`)

- Categorias de competências
- Grid de badges de skills
- Animações interativas

### 7. Contato (`#contact`)

- Formulário com validação
- Links para redes sociais
- Notificações de envio
- Email direto

### 8. Rodapé (`<footer>`)

- Copyright e créditos
- Design minimalista

## 🎨 Cores do Tema

```css
--primary-color: #0066ff       /* Azul principal */
--secondary-color: #00d4ff     /* Ciano */
--accent-color: #ff6b35        /* Laranja */
--dark-bg: #0a0e27             /* Fundo escuro */
--light-text: #e0e0e0          /* Texto claro */
```

## 📱 Responsividade

- **Desktop**: Layout completo com 2 colunas onde apropriado
- **Tablet** (≤ 768px): Ajustes de grid e tamanhos
- **Mobile** (≤ 480px): Layout single column, menu hamburger

## ⚙️ Funcionalidades JavaScript

### 1. Menu Mobile

Ativa/desativa menu hamburger com animação das linhas

### 2. Scroll Animations

Elementos aparecem conforme scroll com IntersectionObserver

### 3. Validação de Formulário

Valida email e campos obrigatórios com feedback visual

### 4. Navbar Inteligente

Detecta seção ativa durante scroll e atualiza link automaticamente

### 5. Smooth Scroll

Navegação suave entre seções

## 🔧 Customização

### Adicionar Projetos

No HTML, copie um bloco de projeto e modifique as informações:

```html
<div class="project-card">
    <div class="project-image">
        <div class="image-placeholder">Seu Projeto</div>
    </div>
    <div class="project-info">
        <h3>Nome do Projeto</h3>
        <p>Descrição...</p>
        <div class="project-tags">
            <span class="tag">Tecnologia</span>
        </div>
        <a href="#" class="project-link">Ver Projeto →</a>
    </div>
</div>
```

### Adicionar Skills

```html
<div class="skill-category">
    <h3>Categoria</h3>
    <div class="skill-list">
        <span class="skill-item">Skill 1</span>
        <span class="skill-item">Skill 2</span>
    </div>
</div>
```

### Mudar Cores

No `css/style.css`, atualize as variáveis CSS:

```css
:root {
    --primary-color: sua-cor;
    --secondary-color: sua-cor;
}
```

## 📞 Conectar Formulário de Contato

Por padrão, o formulário mostra uma notificação. Para enviar emails realmente:

### Opção 1: EmailJS

```javascript
emailjs.send('service_id', 'template_id', {
    name: name,
    email: email,
    message: message
});
```

### Opção 2: Backend Node.js

```javascript
fetch('seu-servidor.com/api/contact', {
    method: 'POST',
    body: JSON.stringify({ name, email, message })
});
```

## 🌐 Fazer Deploy

### GitHub Pages

1. Crie um repositório `seu-nome.github.io`
2. Faça push dos arquivos
3. Site disponível em `https://seu-nome.github.io`

### Vercel

1. Conecte seu repositório
2. Deploy automático a cada push

### Netlify

1. Drag and drop da pasta `portfolio`
2. Site ao vivo instantaneamente

## ♿ Acessibilidade

- Estrutura HTML semântica
- Atributos alt para imagens
- Contraste de cores adequado
- Navegação por teclado suportada

## 📊 Performance

- Sem frameworks pesados
- CSS otimizado
- JavaScript minimalista
- Carregamento rápido
- Pronto para PWA

## 🎓 O que Você Aprendeu

Este projeto demonstra:

- ✅ HTML5 semântico
- ✅ CSS3 avançado (Grid, Flexbox, Animations)
- ✅ JavaScript vanilla (ES6+)
- ✅ Responsive Design
- ✅ User Experience (UX)
- ✅ Web Performance

## 📚 Tecnologias

- **HTML5** - Estrutura semântica
- **CSS3** - Estilos e animações
- **JavaScript ES6+** - Interatividade
- **Google Fonts** - Tipografia (Inter)
- **Sem dependências externas** ✨

## 💡 Dicas

1. **Adicione uma foto real** em vez do avatar placeholder
2. **Configure o email** para receber mensagens de contato
3. **Atualize links de redes sociais**
4. **Adicione seus projetos reais** com links para GitHub/Demo
5. **Customize cores** conforme sua identidade visual

## 📄 Licença

Livre para usar, modificar e distribuir conforme desejar.

---

Desenvolvido com ❤️ - HTML, CSS e JavaScript puro

Bom luck! 🚀
