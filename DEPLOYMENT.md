# Guia de Deployment - Kaique Eletricista

## 🚀 Deploy Rápido em 3 Minutos

### Opção 1: GitHub Pages (GRÁTIS)

1. **Criar repositório no GitHub**
   - Acesse github.com e faça login
   - Clique em "New repository"
   - Nome: `kaique_eletricista`
   - Selecione "Public"
   - Clique em "Create repository"

2. **Fazer upload dos arquivos**
   ```bash
   cd /home/ubuntu/kaique_eletricista
   git init
   git add .
   git commit -m "Initial commit - Kaique Eletricista website"
   git branch -M main
   git remote add origin https://github.com/seu-usuario/kaique_eletricista.git
   git push -u origin main
   ```

3. **Ativar GitHub Pages**
   - Vá em Settings > Pages
   - Source: Deploy from a branch
   - Branch: main, folder: / (root)
   - Salve
   - Seu site estará em: `https://seu-usuario.github.io/kaique_eletricista`

---

### Opção 2: Netlify (GRÁTIS + FÁCIL)

1. **Conectar repositório**
   - Acesse netlify.com
   - Clique em "New site from Git"
   - Selecione GitHub
   - Autorize o Netlify
   - Selecione o repositório `kaique_eletricista`

2. **Configurar build**
   - Build command: deixe em branco
   - Publish directory: `.` (raiz)
   - Clique em "Deploy site"

3. **Seu site estará online em minutos!**
   - URL: `https://seu-site-aleatorio.netlify.app`
   - Você pode customizar o domínio

---

### Opção 3: Vercel (GRÁTIS + RÁPIDO)

1. **Conectar repositório**
   - Acesse vercel.com
   - Clique em "New Project"
   - Selecione GitHub
   - Autorize o Vercel
   - Selecione o repositório

2. **Deploy automático**
   - Vercel detectará automaticamente
   - Clique em "Deploy"
   - Seu site estará online em segundos!

---

### Opção 4: Hospedagem Compartilhada (Hostinger, Bluehost, etc)

1. **Fazer upload via FTP**
   - Conecte via FTP com as credenciais da hospedagem
   - Faça upload de todos os arquivos para `public_html/`
   - Aguarde o upload completar

2. **Configurar domínio**
   - Aponte o domínio para o servidor
   - Aguarde propagação DNS (até 24h)

3. **Seu site estará online!**

---

## 📝 Checklist Pré-Deployment

- [ ] Verificar se todos os links funcionam
- [ ] Testar formulário de contato
- [ ] Verificar responsividade em mobile
- [ ] Testar links de WhatsApp
- [ ] Verificar redes sociais
- [ ] Testar em diferentes navegadores
- [ ] Verificar velocidade de carregamento
- [ ] Adicionar Google Analytics (opcional)

---

## 🔧 Configurações Pós-Deployment

### 1. Adicionar Google Analytics
Adicione este código antes de `</head>` em `index.html`:
```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-XXXXXXXXXX"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'G-XXXXXXXXXX');
</script>
```

### 2. Adicionar Domínio Customizado
- **Netlify**: Site settings > Domain management > Add custom domain
- **Vercel**: Settings > Domains > Add domain
- **GitHub Pages**: Settings > Pages > Custom domain

### 3. Ativar HTTPS
- Todos os serviços acima oferecem HTTPS gratuito automaticamente

### 4. Configurar Email de Contato
Atualmente o formulário redireciona para WhatsApp. Para adicionar email:
1. Integre um serviço como Formspree, EmailJS ou Getform
2. Atualize o script em `js/script.js`

---

## 🌍 Domínio Customizado

### Registrar Domínio
1. Acesse registradores como:
   - Namecheap.com
   - GoDaddy.com
   - Registro.br (para domínios .com.br)

2. Registre seu domínio (ex: kaique-eletricista.com.br)

3. Configure os nameservers conforme seu provedor de hospedagem

---

## ⚡ Otimizações Recomendadas

1. **Compressão GZIP**: Ativada automaticamente em Netlify/Vercel
2. **Cache**: Configurado em netlify.toml
3. **CDN**: Incluído em Netlify/Vercel
4. **Minificação**: CSS e JS já otimizados

---

## 📊 Monitoramento

### Ferramentas Recomendadas
- **Google Analytics**: Rastreamento de visitantes
- **Google Search Console**: Indexação e SEO
- **Lighthouse**: Auditoria de performance
- **Uptime Robot**: Monitoramento de disponibilidade

---

## 🆘 Troubleshooting

### Site não aparece no Google
- Aguarde 1-2 semanas para indexação
- Submeta o sitemap no Google Search Console
- Verifique se robots.txt permite indexação

### Domínio não resolve
- Aguarde propagação DNS (até 24h)
- Verifique os nameservers configurados
- Limpe o cache DNS do seu computador

### Formulário não funciona
- Verifique a conexão com internet
- Teste em outro navegador
- Verifique console (F12) para erros

---

## 📞 Suporte

Para dúvidas sobre deployment:
- Netlify: support.netlify.com
- Vercel: vercel.com/support
- GitHub: github.community

---

**Última atualização**: Fevereiro 2024
