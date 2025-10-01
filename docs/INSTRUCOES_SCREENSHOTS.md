# 📸 Como Adicionar Screenshots dos Projetos

Para substituir os placeholders pelas imagens reais dos seus sites, siga estas instruções:

## 📋 Método 1: Usar Imagens Hospedadas

### Passo 1: Tirar Screenshots
1. Acesse cada um dos seus sites:
   - https://brasrio.netlify.app/
   - https://brasriocg.netlify.app/
   - https://cleoneide.netlify.app/
   - https://planejagro.netlify.app/

2. Tire screenshots de cada site (tecla `Print Screen` ou `Win + Shift + S`)
3. Salve as imagens com nomes descritivos:
   - `brasrio-screenshot.jpg`
   - `calculadora-screenshot.jpg`
   - `armarinho-screenshot.jpg`
   - `planejagro-screenshot.jpg`

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
- Linha ~132: BrasRio
- Linha ~154: Calculadora BrasRio  
- Linha ~176: Armarinho Cleoneide
- Linha ~198: PlanejAgro

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
   - `images/brasrio.jpg`
   - `images/calculadora.jpg`
   - `images/armarinho.jpg`
   - `images/planejagro.jpg`

### Passo 3: Atualizar HTML
Substitua as URLs no `index.html`:

```html
<!-- BrasRio -->
<img src="images/brasrio.jpg" alt="BrasRio Website">

<!-- Calculadora -->
<img src="images/calculadora.jpg" alt="Calculadora BrasRio">

<!-- Armarinho -->
<img src="images/armarinho.jpg" alt="Armarinho Cleoneide">

<!-- PlanejAgro -->
<img src="images/planejagro.jpg" alt="PlanejAgro">
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

- [ ] Screenshots tirados de todos os 4 sites
- [ ] Imagens otimizadas e comprimidas
- [ ] URLs atualizadas no `index.html`
- [ ] Screenshots dos apps Android adicionados
- [ ] Testado no navegador
- [ ] Verificado responsividade mobile

---

## 🚀 Exemplo Completo

```html
<!-- Seção de Projetos Web - ANTES -->
<div class="project-image">
    <img src="https://via.placeholder.com/400x250/dc2626/ffffff?text=BrasRio+Website" alt="BrasRio Website">
    ...
</div>

<!-- Seção de Projetos Web - DEPOIS -->
<div class="project-image">
    <img src="https://i.imgur.com/EXEMPLO123.jpg" alt="BrasRio Website">
    ...
</div>
```

---

## 📞 Precisa de Ajuda?

Se tiver dúvidas, entre em contato pelo WhatsApp: (21) 99922-4864

**Desenvolvido por Richardyson** ❤️

