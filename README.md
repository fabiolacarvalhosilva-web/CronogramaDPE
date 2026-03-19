# ⚖️ Defensoria Pública — Reta Final

> Cronograma de estudos interativo para concursos da Defensoria Pública.  
> Funciona no celular, tablet e computador. Salva tudo automaticamente. Gera relatório semanal em PDF.

---

## ✨ Funcionalidades

| Aba | Recursos |
|-----|----------|
| 📅 **Cronograma** | Semana A e B, blocos clicáveis, barra de progresso, missão da semana, regras |
| 📝 **Notas & Metas** | Meta numérica (questões, acerto, simulado, discursiva), anotações, reflexão do domingo |
| 📊 **Relatório** | Resumo visual da semana com stats, progresso por dia, missões, metas — exportável em PDF |

- 💾 **Salvo automaticamente** no navegador (sem login, sem servidor)
- 📲 **Instalável como app** no celular (PWA)
- 🖨️ **Exportar relatório semanal em PDF** com um clique

---

## 🚀 Subir no GitHub Pages

### Passo 1 — Criar repositório

Acesse [github.com/new](https://github.com/new) e crie um repositório **público**.  
Sugestão de nome: `defensoria-reta-final`

### Passo 2 — Fazer upload

**Pela interface web (mais fácil):**
1. Abra o repositório → clique em **Add file → Upload files**
2. Arraste o arquivo `index.html`
3. Clique em **Commit changes**

**Pelo terminal:**
```bash
git clone https://github.com/SEU_USUARIO/defensoria-reta-final.git
cd defensoria-reta-final
# copie o index.html para esta pasta
git add index.html
git commit -m "Adiciona app Defensoria Pública — Reta Final"
git push origin main
```

### Passo 3 — Ativar GitHub Pages

1. Vá em **Settings → Pages**
2. Em **Source** → selecione **Deploy from a branch**
3. Branch: **main**, pasta: **/ (root)**
4. Clique em **Save**

### Passo 4 — Acessar

Após 1–2 minutos, seu app estará em:

```
https://SEU_USUARIO.github.io/defensoria-reta-final/
```

---

## 📲 Instalar como app no celular

### Android (Chrome)
1. Abra o link no Chrome
2. Toque no banner **"Adicionar à tela inicial"** ou no menu ⋮ → **"Instalar app"**
3. O app aparecerá na sua tela inicial e funcionará offline

### iPhone / iPad (Safari)
1. Abra o link no Safari
2. Toque no ícone de compartilhar **⬆**
3. Selecione **"Adicionar à Tela de Início"**
4. Toque em **Adicionar**

---

## 🖨️ Exportar Relatório Semanal em PDF

1. Vá na aba **📊 Relatório**
2. Clique em **🖨️ Exportar PDF / Imprimir**
3. Na janela de impressão:
   - **Salvar como PDF** (no computador)
   - **Impressora** (para imprimir em papel)
   - No celular: selecione **"Salvar como PDF"** nas opções

O relatório inclui:
- % de blocos concluídos na semana
- Missões cumpridas
- Metas numéricas (questões, acerto, simulado, discursiva)
- Progresso por dia com barras visuais
- Anotações e pontos fracos
- Reflexão do domingo

---

## 📂 Estrutura

```
defensoria-reta-final/
└── index.html    # App completo (único arquivo, sem dependências)
```

Tudo em um único arquivo HTML. Sem frameworks, sem servidores, sem instalações.

---

## ⚙️ Personalização

Para ajustar as matérias ou blocos, edite as constantes `WEEK_A` e `WEEK_B` dentro do `<script>` no `index.html`.

---

**Bons estudos! ⚖️🌿**
