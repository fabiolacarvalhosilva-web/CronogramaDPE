# ⚖️ DPE — Reta Final

> Cronograma de estudos interativo para a Defensoria Pública do Maranhão.  
> Funciona no celular, tablet e computador — inclusive sem internet após o primeiro acesso.

---

## ✨ Funcionalidades

- 📅 **Semana A e B** — alterne entre as duas rotinas com um clique
- ✅ **Blocos clicáveis** — marque cada atividade como concluída
- 📊 **Barra de progresso** com emoji evolutivo (🌱 → 🏆)
- 🎯 **Missão da semana** com checklist
- 📝 **Meta numérica** — questões, acerto, simulado e discursiva
- 📌 **Anotações** e **Reflexão do Domingo**
- 💾 **Salvo automaticamente** no navegador (localStorage)
- 📲 **Instalável como app** no celular (PWA)

---

## 🚀 Como usar no GitHub Pages

### 1. Crie o repositório

```bash
# Crie um repositório público no GitHub com o nome:
dpe-maranhao-reta-final
```

### 2. Faça o upload dos arquivos

Opção A — pela interface do GitHub:
1. Acesse o repositório → clique em **Add file → Upload files**
2. Arraste o arquivo `index.html` para a área de upload
3. Clique em **Commit changes**

Opção B — pelo terminal:
```bash
git clone https://github.com/SEU_USUARIO/dpe-maranhao-reta-final.git
cd dpe-maranhao-reta-final
cp /caminho/para/index.html .
git add index.html
git commit -m "Adiciona cronograma DPE Maranhão"
git push origin main
```

### 3. Ative o GitHub Pages

1. Vá em **Settings → Pages**
2. Em **Source**, selecione **Deploy from a branch**
3. Escolha a branch `main` e a pasta `/ (root)`
4. Clique em **Save**

### 4. Acesse o app

Após alguns minutos, seu app estará disponível em:

```
https://SEU_USUARIO.github.io/dpe-maranhao-reta-final/
```

---

## 📲 Instalar no celular (como app)

### Android (Chrome)
1. Abra o link no Chrome
2. Aguarde o banner **"Instalar no dispositivo"** aparecer
3. Toque em **Instalar** → o app aparecerá na sua tela inicial

### iPhone / iPad (Safari)
1. Abra o link no Safari
2. Toque no ícone de **compartilhar** (quadrado com seta)
3. Selecione **"Adicionar à Tela de Início"**
4. Toque em **Adicionar**

---

## 🖨️ Versão para impressão

O arquivo `DPE_Maranhao_Reta_Final.pdf` contém 4 páginas otimizadas para impressão A4:

| Página | Conteúdo                             |
|--------|--------------------------------------|
| 1      | Capa + Missão da Semana              |
| 2      | Rotina Semanal — Semana A            |
| 3      | Rotina Semanal — Semana B            |
| 4      | Regras do Modo Guerra + Metas + Reflexão |

---

## 🛠️ Tecnologias

- HTML5 + CSS3 + JavaScript puro (sem dependências)
- Google Fonts: Playfair Display + Nunito
- localStorage para persistência de dados
- PWA (Progressive Web App) para instalação offline

---

## 📂 Estrutura do projeto

```
dpe-maranhao-reta-final/
├── index.html                  # App principal
└── DPE_Maranhao_Reta_Final.pdf # PDF para impressão (opcional)
```

---

## 📄 Licença

Uso pessoal. Boa sorte na prova! ⚖️🌿
