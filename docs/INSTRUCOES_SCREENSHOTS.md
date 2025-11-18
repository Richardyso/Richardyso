# 📸 Como Adicionar Screenshots dos Projetos

Para substituir os placeholders pelas imagens reais dos seus sites, siga estas instruções:

## 📋 Método 1: Usar Imagens Hospedadas

### Passo 1: Tirar Screenshots
1. Acesse cada um dos seus sites:
   - https://amigoscuidadores.vercel.app/ (DESTAQUE - Sistema Full Stack)
   - https://cleoneide.netlify.app/
   - https://babidesign.netlify.app/
   - https://brasriocg.netlify.app/

2. Tire screenshots de cada site (tecla `Print Screen` ou `Win + Shift + S`)
3. Salve as imagens com nomes descritivos:
   - `amigos-cuidadores-screenshot.jpg`
   - `armarinho-screenshot.jpg`
   - `babidesign-screenshot.jpg`
   - `calculadora-screenshot.jpg`

### Passo 2: Hospedar as Imagens

**Opção A - Usar ImgBB (Gratuito):**
1. Acesse: https://imgbb.com/
2. Faça upload de cada screenshot
3. Copie o link "Direct Link" de cada imagem

**Opção B - Usar GitHub:**
1. Crie uma pasta `images` no repositório
2. Faça upload das screenshots nesta pasta
3. Use URLs como: `https://raw.githubusercontent.com/SEU_USUARIO/REPO/main/images/brasrio-screenshot.jpg`

**Opção C - Usar Imgur:**
1. Acesse: https://imgur.com/
2. Faça upload das imagens
3. Copie o link direto de cada imagem

### Passo 3: Atualizar o HTML

Abra o arquivo `index.html` e substitua as URLs dos placeholders:

```html
<!-- ANTES (linha ~132) -->
<img src="https://via.placeholder.com/400x250/dc2626/ffffff?text=BrasRio+Website" alt="BrasRio Website">

<!-- DEPOIS -->
<img src="SUA_URL_AQUI" alt="BrasRio Website">
```

**Substitua nas linhas:**
- Linha ~132: Amigos Cuidadores (Projeto em Destaque)
- Linha ~156: Armarinho Cleoneide
- Linha ~178: Babi Design
- Linha ~200: Calculadora BrasRio

---

## 📋 Método 2: Usar Imagens Locais

### Passo 1: Criar Pasta de Imagens
```bash
# No terminal, dentro da pasta do projeto:
mkdir images
```

### Passo 2: Mover Screenshots
1. Coloque os screenshots na pasta `images/`
2. Renomeie para:
   - `images/amigos-cuidadores.jpg`
   - `images/armarinho.jpg`
   - `images/babidesign.jpg`
   - `images/calculadora.jpg`

### Passo 3: Atualizar HTML
Substitua as URLs no `index.html`:

```html
<!-- Amigos Cuidadores (Destaque) -->
<img src="images/amigos-cuidadores.jpg" alt="Amigos Cuidadores">

<!-- Armarinho -->
<img src="images/armarinho.jpg" alt="Armarinho Cleoneide">

<!-- Babi Design -->
<img src="images/babidesign.jpg" alt="Babi Design">

<!-- Calculadora -->
<img src="images/calculadora.jpg" alt="Calculadora BrasRio">
```

---

## 📱 Screenshots dos Apps Android

Para adicionar screenshots dos apps **Eletricarlos** e **BrasRio**:

### Localização no HTML (linhas ~230 e ~246):

```html
<!-- Substituir esta div -->
<div class="android-placeholder">
    <i class="fas fa-mobile-alt"></i>
    <span>Screenshot do App</span>
</div>

<!-- Por esta -->
<img src="images/eletricarlos-app.jpg" alt="App Eletricarlos" style="width: 100%; max-width: 300px; border-radius: 10px; margin-top: 1rem;">
```

---

## 🎨 Dicas para Screenshots Perfeitos

### Tamanho Recomendado:
- **Largura:** 800px - 1200px
- **Altura:** 500px - 750px
- **Proporção:** 16:10 ou 16:9

### Ferramentas para Captura:
- **Windows:** Ferramenta de Captura (`Win + Shift + S`)
- **Online:** https://www.screencapture.com/
- **Extensão Chrome:** Full Page Screen Capture

### Otimização de Imagens:
- Comprima as imagens antes de usar
- Ferramentas: https://tinypng.com/ ou https://squoosh.app/
- Formato recomendado: JPG ou WebP

---

## ✅ Checklist Final

- [ ] Screenshots tirados dos 4 sites (Amigos Cuidadores, Armarinho, Babi Design, Calculadora)
- [ ] Imagens otimizadas e comprimidas
- [ ] URLs atualizadas no `index.html`
- [ ] Screenshots dos apps Android adicionados
- [ ] Testado no navegador
- [ ] Verificado responsividade mobile
- [ ] Badge "Destaque" aparecendo no Amigos Cuidadores

---

## 🚀 Exemplo Completo

```html
<!-- Seção de Projetos Web - ANTES -->
<div class="project-image">
    <img src="https://image.thum.io/get/width/800/crop/600/https://amigoscuidadores.vercel.app/" alt="Amigos Cuidadores">
    ...
</div>

<!-- Seção de Projetos Web - DEPOIS -->
<div class="project-image">
    <img src="https://i.imgur.com/EXEMPLO123.jpg" alt="Amigos Cuidadores">
    ...
</div>
```

---

## 📞 Precisa de Ajuda?

Se tiver dúvidas, entre em contato pelo WhatsApp: (21) 99922-4864

**Desenvolvido por Richardyson** ❤️

