# Kaique Eletricista - Website Profissional

Um website moderno e responsivo para Kaique Eletricista, apresentando serviços de eletricidade residencial, predial e comercial.

## 📋 Características

- **Design Responsivo**: Totalmente adaptado para dispositivos móveis, tablets e desktops
- **Identidade Visual**: Cores preto e laranja conforme o branding do cliente
- **Seções Completas**:
  - Hero Section com chamada para ação
  - Sobre o profissional
  - Serviços detalhados (Residencial, Predial, Comercial)
  - Galeria de Projetos
  - Depoimentos de clientes
  - Formulário de contato integrado com WhatsApp
  - Redes sociais flutuantes
  - Footer com links rápidos

- **Funcionalidades**:
  - Integração com WhatsApp para orçamentos
  - Formulário de contato funcional
  - Menu mobile responsivo
  - Animações suaves de scroll
  - Botões flutuantes de redes sociais
  - SEO otimizado
  - Performance otimizada

## 🚀 Como Usar

### Opção 1: Abrir Localmente
1. Extraia os arquivos do projeto
2. Abra o arquivo `index.html` em seu navegador
3. O website carregará completamente

### Opção 2: Servir com um Servidor Local

#### Com Python 3:
```bash
python3 -m http.server 8000
```

#### Com Node.js (http-server):
```bash
npx http-server
```

#### Com Live Server (VS Code):
1. Instale a extensão "Live Server"
2. Clique com botão direito em `index.html`
3. Selecione "Open with Live Server"

## 📁 Estrutura de Arquivos

```
kaique_eletricista/
├── index.html          # Arquivo HTML principal
├── css/
│   └── styles.css      # Estilos CSS
├── js/
│   └── script.js       # Scripts JavaScript
└── README.md           # Este arquivo
```

## 🎨 Personalização

### Alterar Cores
Edite as variáveis CSS em `css/styles.css`:
```css
:root {
    --primary-color: #ff6600;      /* Laranja */
    --secondary-color: #1a1a1a;    /* Preto */
    --text-color: #333;
    --light-bg: #f8f9fa;
    --white: #ffffff;
}
```

### Adicionar Projetos
Adicione novos cards na seção "Projetos" em `index.html`:
```html
<div class="projeto-card">
    <div class="projeto-image">
        <i class="fas fa-[icone]"></i>
    </div>
    <h3>Nome do Projeto</h3>
    <p>Descrição do projeto</p>
</div>
```

### Adicionar Depoimentos
Adicione novos depoimentos na seção "Depoimentos":
```html
<div class="depoimento-card">
    <div class="stars">
        <i class="fas fa-star"></i>
        <!-- Adicione 5 estrelas -->
    </div>
    <p>"Seu depoimento aqui"</p>
    <h4>Nome do Cliente</h4>
    <span>Tipo de Cliente</span>
</div>
```

## 📞 Informações de Contato

- **Telefone**: (11) 98784-2983
- **WhatsApp**: (11) 98784-2983
- **Instagram**: @kaique.cesar.5076
- **Facebook**: kaique.cesar.5076
- **YouTube**: kaique eletricista

## 🌐 Deploy Online

### Opção 1: GitHub Pages
1. Crie um repositório no GitHub
2. Faça upload dos arquivos
3. Vá em Settings > Pages
4. Selecione a branch `main` e pasta `root`
5. Seu site estará disponível em `https://seu-usuario.github.io/kaique_eletricista`

### Opção 2: Netlify
1. Acesse [netlify.com](https://netlify.com)
2. Clique em "New site from Git"
3. Conecte seu repositório GitHub
4. Configure o build (deixe em branco para site estático)
5. Deploy automático realizado!

### Opção 3: Vercel
1. Acesse [vercel.com](https://vercel.com)
2. Clique em "New Project"
3. Importe seu repositório GitHub
4. Vercel detectará automaticamente o projeto
5. Deploy realizado!

### Opção 4: Hospedagem Compartilhada
1. Faça upload dos arquivos via FTP
2. Configure o domínio
3. Seu site estará online!

## 📱 Responsividade

O website foi testado e otimizado para:
- Desktop (1920px e acima)
- Tablet (768px a 1024px)
- Mobile (320px a 767px)

## ⚡ Performance

- Carregamento rápido
- Otimizado para SEO
- Imagens otimizadas
- CSS e JavaScript minificados
- Lazy loading implementado

## 🔒 Segurança

- Validação de formulário no cliente
- Proteção contra XSS
- Links de WhatsApp seguros
- HTTPS recomendado para produção

## 📊 Analytics

O website está pronto para integração com:
- Google Analytics
- Facebook Pixel
- Hotjar
- Outras ferramentas de rastreamento

Para adicionar, insira o código de rastreamento antes do `</body>` em `index.html`.

## 🐛 Troubleshooting

### O website não carrega
- Verifique se todos os arquivos estão na mesma pasta
- Limpe o cache do navegador (Ctrl+Shift+Delete)
- Tente em outro navegador

### WhatsApp não abre
- Verifique se o número está correto
- Certifique-se de que o WhatsApp está instalado
- Tente acessar via navegador do celular

### Formulário não funciona
- Verifique a conexão com a internet
- Certifique-se de que o JavaScript está habilitado
- Verifique o console do navegador (F12) para erros

## 📄 Licença

Este projeto é fornecido como está para uso do cliente Kaique Eletricista.

## 👨‍💻 Suporte

Para dúvidas ou alterações, entre em contato com o desenvolvedor.

---

**Última atualização**: Fevereiro 2024
**Versão**: 1.0.0
