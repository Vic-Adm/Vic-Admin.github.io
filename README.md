# 🍃 Du Farol - Site de Cachaça de Jambu

Um site moderno e responsivo para a marca Du Farol, especializada em cachaça de jambu artesanal da Amazônia.

## ✨ Características

- **Design Moderno e Responsivo**: Adaptável a todos os dispositivos
- **Paleta de Cores Rústica**: Baseada nas cores da logo da marca
- **Textura de Fundo**: Padrões sutis que remetem à tradição da cachaça
- **Destaque para Imagens**: As fotos dos produtos têm grande visibilidade
- **Navegação Suave**: Scroll suave entre seções
- **Animações Interativas**: Efeitos visuais elegantes
- **Otimizado para SEO**: Estrutura semântica e meta tags

## 🎨 Paleta de Cores

- **Primária**: Marrom escuro rústico (#8B4513)
- **Secundária**: Marrom dourado (#D2691E)
- **Destaque**: Dourado (#FFD700)
- **Texto**: Marrom muito escuro (#2C1810)
- **Claro**: Bege claro (#F5F5DC)

## 📁 Estrutura de Arquivos

```
Site-vic/
├── index.html          # Página principal
├── styles.css          # Estilos CSS
├── script.js           # Funcionalidades JavaScript
├── README.md           # Este arquivo
└── images/             # Pasta com imagens
    ├── logo.jpg        # Logo normal
    ├── logo_transparente.png  # Logo transparente
    ├── foto1.jpg       # Imagem do produto 1
    ├── foto2.jpg       # Imagem do produto 2
    ├── foto3.jpg       # Imagem do produto 3
    └── foto4.jpg       # Imagem do produto 4
```

## 🚀 Como Usar

1. **Visualização Local**:
   - Abra o arquivo `index.html` em um navegador
   - Ou use um servidor local: `python -m http.server 8000`

2. **Personalização**:
   - Edite as descrições dos produtos no arquivo `index.html`
   - Modifique cores no arquivo `styles.css` (variáveis CSS)
   - Ajuste funcionalidades no arquivo `script.js`

3. **Deploy**:
   - Faça upload dos arquivos para seu servidor web
   - Certifique-se de que a pasta `images/` está incluída

## 📱 Seções do Site

### Header
- Logo da marca
- Menu de navegação responsivo
- Efeito de transparência no scroll

### Hero Section
- Título principal com destaque
- Imagem principal do produto (foto3.jpg)
- Botão de call-to-action
- Textura de fundo sutil

### Sobre
- História da marca
- Missão e valores
- Imagem ilustrativa (foto2.jpg)

### Produtos
- Cards com 4 produtos diferentes
- Cada card com imagem e descrição
- Tags de características
- Efeitos hover interativos

### Galeria
- Grid responsivo de imagens
- Overlay com informações ao hover
- Efeitos de zoom e transição

### Footer
- Informações de contato
- Links para redes sociais
- Logo da marca

## 🛠️ Tecnologias Utilizadas

- **HTML5**: Estrutura semântica
- **CSS3**: Estilos modernos com variáveis CSS
- **JavaScript ES6+**: Funcionalidades interativas
- **Font Awesome**: Ícones
- **Google Fonts**: Tipografia Poppins

## 📱 Responsividade

O site é totalmente responsivo e funciona perfeitamente em:
- Desktop (1200px+)
- Tablet (768px - 1199px)
- Mobile (até 767px)

## 🎯 Funcionalidades JavaScript

- **Scroll Suave**: Navegação entre seções
- **Header Dinâmico**: Transparência no scroll
- **Animações de Entrada**: Elementos aparecem com fade-in
- **Efeitos Hover**: Interações nos cards e imagens
- **Menu Mobile**: Navegação responsiva para dispositivos móveis
- **Scroll to Top**: Botão para voltar ao topo
- **Lazy Loading**: Carregamento otimizado de imagens

## 🔧 Personalização

### Alterar Cores
Edite as variáveis CSS no arquivo `styles.css`:

```css
:root {
    --primary-color: #8B4513;    /* Cor principal */
    --secondary-color: #D2691E;  /* Cor secundária */
    --accent-color: #FFD700;     /* Cor de destaque */
    /* ... outras cores */
}
```

### Adicionar Produtos
Para adicionar mais produtos, duplique a estrutura no HTML:

```html
<div class="product-card">
    <div class="product-image">
        <img src="images/nova-foto.jpg" alt="Novo Produto">
    </div>
    <div class="product-info">
        <h3>Nome do Produto</h3>
        <p class="product-description">Descrição do produto...</p>
        <div class="product-features">
            <span class="feature">Característica 1</span>
            <span class="feature">Característica 2</span>
        </div>
    </div>
</div>
```

### Modificar Texturas
As texturas de fundo podem ser ajustadas no CSS:

```css
body {
    background: 
        linear-gradient(135deg, rgba(139, 69, 19, 0.03) 25%, transparent 25%),
        /* ... outras texturas */
}
```

## 📞 Informações de Contato

- **E-mail**: dufarol@gmail.com
- **Telefone**: (91) 99190-9333
- **Endereço**: Salinas - PA

## 📄 Licença

Este projeto foi criado especificamente para a marca Du Farol. Todos os direitos reservados.

## 🤝 Suporte

Para dúvidas ou sugestões sobre o site, entre em contato através dos canais oficiais da Du Farol.

---

**Du Farol** - Tradição Amazônica em Cada Gota 🍃
