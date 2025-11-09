# 🚀 GUIA COMPLETO: HOSPEDAR MINECALC NO GITHUB

## ⚡ Resumo Rápido (5 minutos)

Se você JÁ tem conta GitHub:

```bash
1. Vá para: github.com/new
2. Nome: minecalc
3. Deixe PUBLIC
4. Clique "Create"
5. Upload dos arquivos
6. Settings → GitHub Pages → Main Branch
7. PRONTO! Seu site: https://rafaelrogel.github.io/minecalc/
```

---

## 📝 PASSO 1: Verificar se tem Conta GitHub

### Opção A: Você JÁ tem conta
→ Pule para PASSO 2

### Opção B: Você NÃO tem conta

1. Abra: **github.com**
2. Clique "Sign up" (canto superior direito)
3. Preencha:
   - Email: seu@email.com
   - Password: uma senha forte
   - Username: **rafaelrogel**
4. Complete o CAPTCHA
5. Verifique seu email (clique no link)
6. Done! ✅

---

## 📦 PASSO 2: Criar Repositório

1. **Faça login** em github.com
2. Clique **no seu perfil** (canto superior direito)
3. Clique **"Your repositories"**
4. Clique **botão verde "New"**

### Preencha assim:

```
Repository name: minecalc
Description: Bitcoin Mining Financial Model
Visibility: PUBLIC (IMPORTANTE!)
[ ] Initialize with README
[ ] Add .gitignore
[ ] Add a license

Clique: "Create repository"
```

---

## 📤 PASSO 3: Upload dos Arquivos

### Método 1: Via Navegador (Fácil)

1. Abra seu repositório (você deve estar na página após criar)
2. Clique **"Add file"** → **"Upload files"**
3. Arraste os arquivos:
   - `mining-ultimate.html` → **Renomeie para `index.html`**
   - `mining-pro.html`
   - `mining-simple.html`
   - `README.md`

4. Na caixa "Commit message" escreva:
   ```
   Initial commit: Add MINECALC mining calculator
   ```

5. Clique **"Commit changes"**

### Método 2: Via Git (Profissional)

```bash
# 1. Clone o repositório vazio
git clone https://github.com/rafaelrogel/minecalc.git
cd minecalc

# 2. Copie os arquivos para a pasta
# (mining-ultimate.html, mining-pro.html, etc)

# 3. Renomeie index.html
mv mining-ultimate.html index.html

# 4. Adicione, commit e push
git add .
git commit -m "Initial commit: Add MINECALC mining calculator"
git push origin main
```

---

## ⚙️ PASSO 4: Ativar GitHub Pages

1. Vá para seu repositório no GitHub
2. Clique em **"Settings"** (aba superior)
3. Scroll até encontrar **"Pages"** (no menu esquerdo)
4. Sob "Build and deployment":
   - **Source**: Selecione **"Deploy from a branch"**
   - **Branch**: Selecione **"main"** + **"/ (root)"**
5. Clique **"Save"**

Aguarde 30-60 segundos...

---

## ✅ PASSO 5: Verificar Deploy

1. Volta na aba **"Settings"** → **"Pages"**
2. Você verá uma mensagem verde:
   ```
   ✅ Your site is live at: 
   https://rafaelrogel.github.io/minecalc/
   ```

3. Clique no link para abrir seu site!

---

## 🎉 SEU SITE ESTÁ ONLINE!

```
🔗 https://rafaelrogel.github.io/minecalc/
```

### Versões disponíveis:
- 📊 ULTIMATE: `/` (index.html)
- 🥇 PRO: `/mining-pro.html`
- 📈 SIMPLE: `/mining-simple.html`

---

## 🔄 COMO ATUALIZAR

Se quiser fazer mudanças no site:

### Via Navegador:
1. Entre no repositório
2. Clique no arquivo a editar (ex: `index.html`)
3. Clique lápis (Edit)
4. Faça as mudanças
5. Scroll até fim
6. Clique "Commit changes"
7. **Seu site atualiza automaticamente em 30 segundos!**

### Via Git:
```bash
# Faça mudanças nos arquivos locais
# Depois:
git add .
git commit -m "Descrição das mudanças"
git push origin main
# Atualiza automaticamente!
```

---

## 🌐 ADICIONAR DOMÍNIO PERSONALIZADO (Opcional)

Se quer um domínio tipo `minecalc.com`:

### 1. Comprar Domínio
- Namecheap.com (~$10/ano)
- GoDaddy (~$15/ano)
- RegistroBR (~$40/ano - pt)

### 2. Configurar no GitHub

1. Settings → Pages
2. **Custom domain**: escreva `minecalc.com`
3. Clique "Save"
4. GitHub cria um arquivo `CNAME`

### 3. Configurar DNS do Domínio

Em seu registrador, vá para **DNS Settings** e adicione:

```
CNAME: minecalc.com → rafaelrogel.github.io
```

Aguarde 5-24 horas para propagar.

---

## 🔒 CERTIFICADO SSL/HTTPS

✅ **Automático!**

GitHub Pages fornece HTTPS gratuitamente.

Seu site será:
```
https://rafaelrogel.github.io/minecalc/ ✅
```

Não:
```
http://rafaelrogel.github.io/minecalc/ ❌
```

---

## 📊 MONITORAR TRÁFEGO

1. Settings → Pages
2. Scroll até **"GitHub Pages Analytics"**
3. Veja quantas pessoas visitaram seu site

---

## 🆘 TROUBLESHOOTING

### Problema: Site mostra 404
**Solução:**
- Verifique se Settings → Pages está com "Deploy from a branch" → "main"
- Aguarde 60 segundos (deploy leva tempo)
- Limpe cache (Ctrl+Shift+Delete) e recarregue

### Problema: Arquivo não aparece
**Solução:**
- Verifique se arquivo está em root (não em pasta)
- Renomeie `mining-ultimate.html` → `index.html`
- Commit novamente

### Problema: Mudanças não aparecem
**Solução:**
- Aguarde 30 segundos (deploy automático)
- Limpe cache do navegador
- Recarregue página

### Problema: Gráficos não funcionam
**Solução:**
- Verifique conexão internet (APIs externas)
- Verifique console do navegador (F12)
- Teste em outro navegador

---

## 💡 DICAS PROFISSIONAIS

### ✅ Boas Práticas

1. **Sempre use main branch para produção**
   ```bash
   git branch main  # Sua branch principal
   ```

2. **Crie commits com mensagens claras**
   ```bash
   ❌ git commit -m "fix"
   ✅ git commit -m "Fix: Corrigir cálculo de payback"
   ```

3. **Use .gitignore para arquivos sensíveis**
   ```
   .env
   config/secrets.json
   node_modules/
   ```

4. **Faça backup de alterações importantes**
   ```bash
   git push origin main  # Sempre!
   ```

---

## 🚀 PRÓXIMOS PASSOS

### 1. Compartilhe seu site
Envie este link para amigos:
```
https://rafaelrogel.github.io/minecalc/
```

### 2. Customize conforme necessário
- Edite o README.md
- Adicione seu email de contato
- Mude cores/branding

### 3. Submeta em diretórios
- ProductHunt
- GitHub Trending
- Dev.to

### 4. Procure por Issues/Bugs
Teste todas as funcionalidades e reporte problemas

---

## 📞 PRECISA DE AJUDA?

### Recursos Úteis

- **GitHub Help**: help.github.com
- **GitHub Pages Docs**: docs.github.com/en/pages
- **Stack Overflow**: Tag `github-pages`

### Me contacte:
- Email: rrogel@gmail.com
- GitHub: @rafaelrogel

---

## 🎯 CHECKLIST FINAL

- [ ] Repositório criado no GitHub
- [ ] Arquivos fazem upload com sucesso
- [ ] GitHub Pages ativado
- [ ] Site acessível via https://rafaelrogel.github.io/minecalc/
- [ ] ULTIMATE funciona (index.html)
- [ ] PRO funciona (mining-pro.html)
- [ ] SIMPLE funciona (mining-simple.html)
- [ ] Gráficos carregam corretamente
- [ ] Botões funcionam
- [ ] PDFs exportam
- [ ] APIs real-time carregam (Bitcoin price)

---

## 🎉 SUCESSO!

Parabéns! Seu site MINECALC está:

✅ Online  
✅ Seguro (HTTPS)  
✅ Rápido (CDN global)  
✅ Grátis (sem custos)  
✅ Escalável (sem limite)  

Aproveite! 🚀⛏️📊

---

**Última atualização:** Novembro 2025  
**Versão:** 3.0 ULTIMATE
