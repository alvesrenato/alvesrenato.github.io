# Renato Alves - Currículo Digital

Currículo web profissional multilíngue (Português, Inglês, Italiano) com design moderno e responsivo.

## 🌟 Features

- **Multilíngue**: Suporte completo para PT, EN e IT com persistência no localStorage
- **Tema Escuro/Claro**: Alternância suave entre temas com detecção automática de preferência do sistema
- **Design Responsivo**: Mobile-first, adaptável a todos os dispositivos
- **Animações Suaves**: Scroll reveal, hover effects e transições elegantes
- **Performance**: CSS moderno, sem frameworks pesados, carregamento rápido
- **SEO Friendly**: Meta tags semânticas e estrutura HTML5 otimizada
- **Acessibilidade**: Navegação por teclado, ARIA labels, contraste adequado

## 🚀 Deploy no Vercel

### Opção 1: Deploy via Interface Web (Recomendado)

1. Acesse [vercel.com](https://vercel.com) e faça login (pode usar GitHub)
2. Clique em **"Add New..."** → **"Project"**
3. Selecione **"Import Git Repository"** (se for usar Git) ou **"Upload"** para upload direto
4. Se fizer upload do ZIP:
   - Compacte todos os arquivos (`index.html`, `style.css`, `script.js`)
   - Faça upload no Vercel
5. O Vercel detectará automaticamente como projeto estático
6. Clique em **"Deploy"**
7. Pronto! Seu currículo estará online em segundos

### Opção 2: Deploy via CLI

```bash
# Instalar Vercel CLI
npm i -g vercel

# Navegar até a pasta do projeto
cd renato-cv-website

# Deploy
vercel

# Ou para deploy direto em produção
vercel --prod
```

### Opção 3: GitHub + Vercel (Recomendado para atualizações futuras)

1. Crie um repositório no GitHub
2. Faça upload dos arquivos:
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/SEU_USUARIO/renato-cv.git
   git push -u origin main
   ```
3. No Vercel, importe o repositório GitHub
4. O deploy será automático a cada push

## 📁 Estrutura do Projeto

```
renato-cv-website/
├── index.html          # Estrutura principal e conteúdo
├── style.css           # Estilos, tema escuro/claro, responsividade
├── script.js           # Internacionalização, interatividade, animações
└── README.md           # Este arquivo
```

## 🎨 Personalização

### Cores
Edite as variáveis CSS em `style.css`:

```css
:root {
    --accent: #00d4ff;        /* Cor principal */
    --gradient-start: #00d4ff;
    --gradient-end: #7b2cbf;
}
```

### Conteúdo
Para atualizar informações, edite diretamente no `index.html` ou modifique o objeto `i18n` em `script.js` para alterações multilíngue.

### Idiomas
Para adicionar um novo idioma:
1. Adicione um botão no HTML (seção `.lang-switcher`)
2. Adicione as traduções no objeto `i18n` em `script.js`
3. Atualize a função `setLanguage` se necessário

## 📱 Visualização Local

```bash
# Navegar até a pasta
cd renato-cv-website

# Python 3
python -m http.server 8000

# Ou Node.js
npx serve

# Ou PHP
php -S localhost:8000
```

Acesse `http://localhost:8000` no navegador.

## 🔧 Tecnologias Utilizadas

- **HTML5** semântico
- **CSS3** moderno (Grid, Flexbox, Custom Properties, backdrop-filter)
- **JavaScript** vanilla (ES6+)
- **Google Fonts** (Inter, Space Grotesk)
- **localStorage** para persistência de preferências

## 📄 Licença

Projeto pessoal - Renato Alves de Oliveira

---

**Contato**: alves.renato@gmail.com  
**LinkedIn**: [linkedin.com/in/alvesrenato](https://www.linkedin.com/in/alvesrenato)
