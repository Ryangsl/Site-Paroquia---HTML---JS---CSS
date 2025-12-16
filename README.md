# Sagrado Coração Uberaba - Site Multi-Página

Um site completo e responsivo para a Paróquia Sagrado Coração em Uberaba, Brasil.

## 📋 Características

- ✅ **Site Multi-Página** - Páginas separadas para cada seção
- ✅ Design responsivo (funciona em desktop, tablet e mobile)
- ✅ Tema branco limpo e profissional
- ✅ Fácil de personalizar através de variáveis CSS
- ✅ **5 Páginas Completas:**
  - 🏠 Início (index.html)
  - ⛪ Sobre Nós (sobre.html)
  - 📅 Horários (horarios.html)
  - 🎉 Eventos (eventos.html)
  - 📞 Contato (contato.html)
- ✅ Formulário de contato funcional
- ✅ Menu de navegação com indicador de página ativa
- ✅ Animações e efeitos visuais
- ✅ Código limpo e bem comentado em Português-BR

## 🚀 Como Usar

1. **Abrir o site**: Simplesmente abra o arquivo `index.html` em seu navegador
2. **Hospedar online**: Faça upload dos arquivos para qualquer serviço de hospedagem web

## 🎨 Como Personalizar

### Mudando Cores e Estilos

Abra o arquivo `styles.css` e edite as variáveis CSS no início do arquivo:

```css
:root {
    /* Cores Principais */
    --primary-color: #ffffff;           /* Cor branca principal */
    --secondary-color: #f8f9fa;         /* Fundo cinza claro */
    --accent-color: #d4af37;            /* Cor de destaque (dourado) */
    --text-primary: #2c3e50;            /* Cor do texto escuro */
    --text-secondary: #5a6c7d;          /* Cor do texto claro */
    
    /* Fontes */
    --font-primary: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    --font-heading: 'Georgia', serif;
    
    /* Espaçamentos */
    --spacing-xs: 0.5rem;
    --spacing-sm: 1rem;
    --spacing-md: 2rem;
    --spacing-lg: 3rem;
    --spacing-xl: 4rem;
}
```

### Exemplos de Mudanças de Cor:

**Para um tema azul:**
```css
--accent-color: #4169E1;  /* Azul royal */
```

**Para um tema vermelho:**
```css
--accent-color: #DC143C;  /* Vermelho carmesim */
```

**Para um tema verde:**
```css
--accent-color: #228B22;  /* Verde floresta */
```

### Editando Conteúdo

Abra o arquivo `index.html` e edite o texto diretamente:

1. **Nome da Igreja**: Procure por "Sagrado Coração" e substitua
2. **Endereço**: Procure por "Uberaba - Minas Gerais" e atualize
3. **Horários das Missas**: Edite os horários na seção `<section id="schedule">`
4. **Eventos**: Atualize os eventos na seção `<section id="events">`
5. **Informações de Contato**: Edite telefone, email e endereço na seção `<section id="contact">`

### Adicionando Imagens

Para adicionar uma imagem real no lugar do placeholder:

1. Coloque sua imagem na mesma pasta dos arquivos
2. No arquivo `index.html`, encontre:
```html
<div class="image-placeholder">
    <span class="cross-icon-large">✟</span>
    <p>Sagrado Coração de Jesus</p>
</div>
```

3. Substitua por:
```html
<img src="sua-imagem.jpg" alt="Sagrado Coração" style="width: 100%; border-radius: 12px;">
```

### Adicionando Mais Eventos

Na página `eventos.html`, para adicionar um novo evento, copie e cole este código dentro da seção de eventos:

```html
<div class="event-card">
    <div class="event-date">
        <span class="day">30</span>
        <span class="month">JAN</span>
    </div>
    <div class="event-info">
        <h3>Nome do Evento</h3>
        <p class="event-time">⏰ 18:00h</p>
        <p class="event-description">Descrição do evento aqui.</p>
    </div>
</div>
```

## 📱 Funcionalidades JavaScript

O arquivo `script.js` inclui:

- Menu mobile responsivo
- Navegação suave entre seções
- Efeito de scroll no header
- Animações ao rolar a página
- Validação básica do formulário de contato

## 🔧 Conectando o Formulário de Contato

O formulário atualmente mostra apenas um alerta. Para conectá-lo a um serviço de email:

### Opção 1: Usar FormSubmit (Gratuito)
1. Vá para https://formsubmit.co/
2. Substitua a tag `<form>` por:
```html
<form action="https://formsubmit.co/seu-email@exemplo.com" method="POST" class="contact-form">
```

### Opção 2: Usar EmailJS (Gratuito)
1. Crie uma conta em https://www.emailjs.com/
2. Siga as instruções para integrar com seu formulário

### Opção 3: Backend Próprio
Se você tem um servidor, edite o arquivo `script.js` na seção de envio do formulário.

## 📂 Estrutura de Arquivos

```
/
├── index.html      # Página inicial
├── sobre.html      # Página Sobre Nós
├── horarios.html   # Página de Horários das Missas
├── eventos.html    # Página de Eventos
├── contato.html    # Página de Contato
├── styles.css      # Estilos e design (compartilhado)
├── script.js       # Funcionalidades JavaScript (compartilhado)
└── README.md       # Este arquivo
```

## 📄 Descrição das Páginas

### 🏠 Página Inicial (index.html)
- Hero section com mensagem de boas-vindas
- Cards de destaque para principais seções
- Informações rápidas (localização, próxima missa, contato)

### ⛪ Sobre Nós (sobre.html)
- História da paróquia
- Missão e valores
- Ministérios e pastorais
- Call-to-action para participação

### 📅 Horários (horarios.html)
- Horários detalhados das missas (matinais e noturnas)
- Horários de confissão
- Celebrações especiais
- Informações sobre sacramentos (batismo, casamento, etc.)
- Notas importantes

### 🎉 Eventos (eventos.html)
- Lista de próximos eventos
- Atividades regulares semanais
- Grupos e ministérios ativos
- Descrições detalhadas de cada atividade

### 📞 Contato (contato.html)
- Formulário de contato completo
- Informações de contato (endereço, telefone, email)
- Horário de atendimento
- Seção de perguntas frequentes (FAQ)
- Placeholder para mapa (Google Maps)

## 🌐 Hospedagem Gratuita

Você pode hospedar este site gratuitamente em:

- **GitHub Pages**: https://pages.github.com/
- **Netlify**: https://www.netlify.com/
- **Vercel**: https://vercel.com/
- **Firebase Hosting**: https://firebase.google.com/docs/hosting

## 🔄 Navegação Entre Páginas

O site possui navegação consistente em todas as páginas:
- Menu de navegação fixo no topo
- Links no rodapé para todas as páginas
- Indicador visual da página atual (link ativo)
- Menu mobile responsivo

## 💡 Dicas

1. **Teste em diferentes dispositivos**: Abra o site em celular, tablet e desktop
2. **Otimize imagens**: Use imagens comprimidas para carregar mais rápido
3. **Atualize regularmente**: Mantenha os horários e eventos sempre atualizados em suas respectivas páginas
4. **Adicione Google Maps**: Na página de contato, substitua o placeholder pelo código embed do Google Maps
5. **SEO**: Cada página tem meta tags apropriadas - personalize conforme necessário
6. **Conteúdo**: Todo o conteúdo está em Português-BR e pode ser facilmente editado

## 📞 Suporte

Para dúvidas ou sugestões sobre a personalização do site, consulte os comentários no código ou procure tutoriais sobre HTML, CSS e JavaScript.

## 📄 Licença

Este projeto é de código aberto e pode ser usado livremente para fins religiosos e comunitários.

## 🎨 Personalização Rápida

### Mudar Cores do Site Inteiro
Edite apenas estas linhas no `styles.css`:
```css
--primary-color: #ffffff;      /* Cor de fundo principal */
--accent-color: #d4af37;       /* Cor de destaque (dourado) */
--text-primary: #2c3e50;       /* Cor do texto */
```

### Atualizar Informações de Contato
Edite o arquivo `contato.html` e procure por:
- Telefones: `(34) XXXX-XXXX`
- Email: `contato@sagradocoracaouberaba.com.br`
- Endereço: `Uberaba - Minas Gerais`

### Adicionar Google Maps
Na página `contato.html`, substitua a seção `.map-placeholder` pelo código embed do Google Maps.

---

**Desenvolvido com ❤️ para a Paróquia Sagrado Coração Uberaba**

**Versão:** 2.0 - Site Multi-Página  
**Última Atualização:** 2024
