# 🚀 MINECALC - Bitcoin Mining Financial Model
## Calculadora Profissional de Mineração Bitcoin

![Status](https://img.shields.io/badge/status-active-success)
![License](https://img.shields.io/badge/license-MIT-blue)
![Version](https://img.shields.io/badge/version-3.0-brightgreen)

---

## 📌 Visão Geral

**MINECALC** é uma plataforma completa de análise financeira para operações de mineração de Bitcoin. Desenvolvido com análise em tempo real, cenários múltiplos, sensibilidade 3D e simulação Monte Carlo.

### ✨ Funcionalidades

✅ **Simple Payback** - Cálculo rápido de período de retorno  
✅ **Gráfico Breakeven** - Visualização do ponto de equilíbrio  
✅ **Cenários Múltiplos** - Análise otimista/pessimista/base  
✅ **Sensibilidade 2D** - Matriz interativa  
✅ **Sensibilidade 3D** - Visualização com Plotly  
✅ **Monte Carlo** - 1000+ simulações  
✅ **Múltiplos Mineradores** - Gerencie frota completa  
✅ **Comparação de Pools** - F2Pool, Foundry, Antpool, etc  
✅ **Histórico Bitcoin** - 5 anos de dados  
✅ **Exportar PDF** - Relatórios profissionais  
✅ **API Real-time** - Dados atualizados do CoinGecko  
✅ **100% Offline** - Funciona sem internet após carregar  

---

## 🌐 Acesso Online

### Versão ULTIMATE (Recomendada)
🔗 **https://rafaelrogel.github.io/minecalc/**

- 📊 Todos os recursos premium
- 📱 Responsivo para mobile
- ⚡ Carrega em < 2 segundos
- 🔒 100% seguro (dados locais)

### Versões Alternativas
- 🥇 **PRO**: mining-pro.html
- 📊 **SIMPLE**: mining-simple.html

---

## 🚀 Como Usar

### Opção 1: Usar Online (Recomendado)
Simplesmente abra: **https://rafaelrogel.github.io/minecalc/**

Nenhuma instalação necessária!

### Opção 2: Usar Localmente
```bash
# Clone o repositório
git clone https://github.com/rafaelrogel/minecalc.git

# Abra no navegador
open minecalc/index.html
# ou
firefox minecalc/index.html
# ou
chrome minecalc/index.html
```

### Opção 3: Modificar e Deploy
```bash
# Clone
git clone https://github.com/rafaelrogel/minecalc.git
cd minecalc

# Faça mudanças no código
# Commit e push
git add .
git commit -m "Atualizações"
git push origin main

# Seu site será atualizado automaticamente!
```

---

## 📊 Guia de Funcionalidades

### 1️⃣ **Simple Payback**
Calcule em segundos quanto tempo leva para recuperar seu investimento.

**Dados necessários:**
- Network Hash Rate
- Preço do Bitcoin
- Custo/Hashrate do minerador
- Custo de eletricidade
- Taxa da pool

**Resultado:**
- Payback em dias
- Receita/custo diário
- ROI anual

---

### 2️⃣ **Múltiplos Mineradores**
Gerencie uma frota inteira de equipamentos.

**Funcionalidades:**
- ➕ Adicione quantos mineradores quiser
- 📊 Configure quantidade de cada modelo
- 📈 Veja resultados agregados
- 💡 Otimize sua mix de equipamentos

---

### 3️⃣ **Sensibilidade 3D**
Visualize como 3 variáveis impactam simultaneamente.

**Variáveis:**
- Preço do Bitcoin (Eixo X)
- Custo de Eletricidade (Eixo Y)
- Hashrate da Rede (Eixo Z)

**Como usar:**
- Ajuste os sliders
- Veja o gráfico 3D em tempo real
- Rotacione e zoom para explorar

---

### 4️⃣ **Comparação de Pools**
Escolha a pool mais rentável.

**Pools incluídas:**
- F2Pool (2.5% taxa)
- Foundry USA (1.5% taxa)
- Antpool (2.5% taxa)
- Mining Pool Hub (0.5% taxa)
- LitecoinPool (1% taxa)

**Impacto:** Diferença de 1-2% no lucro anual!

---

### 5️⃣ **Histórico Bitcoin**
Analise 5 anos de dados.

**Estatísticas:**
- Preço mínimo/máximo
- Preço médio
- Volatilidade
- Tendência

---

### 6️⃣ **Monte Carlo**
1000+ simulações para prever cenários possíveis.

**Resultados:**
- Distribuição de probabilidade
- Min/Máx/Média de payback
- Desvio padrão
- Probabilidade de sucesso

---

## 🔧 Tecnologias Utilizadas

- **HTML5** - Estrutura
- **CSS3** - Design moderno e responsivo
- **JavaScript ES6+** - Lógica e cálculos
- **Chart.js** - Gráficos 2D
- **Plotly.js** - Gráficos 3D
- **html2pdf.js** - Exportar PDF
- **CoinGecko API** - Dados Bitcoin real-time

---

## 📋 Estrutura de Arquivos

```
minecalc/
├── index.html              # Versão ULTIMATE (Principal)
├── mining-pro.html         # Versão PRO
├── mining-simple.html      # Versão SIMPLE
├── README.md              # Esta documentação
├── LICENSE                # MIT License
└── .gitignore
```

---

## 🌍 Dados em Tempo Real

O site conecta automaticamente com:

**CoinGecko API** (Grátis, sem autenticação)
- Preço Bitcoin atualizado
- Variação 24h
- Histórico completo

Nenhum dado é armazenado em servidores. Tudo é local no seu navegador!

---

## 🔒 Segurança & Privacidade

✅ **100% Seguro**
- Nenhum dado é enviado para servidores
- Tudo é processado localmente no seu navegador
- Sem cookies ou rastreamento

✅ **Código Aberto**
- Você pode ver e modificar o código
- Sem código obscuro ou malicioso
- Fácil de auditar

---

## 📱 Compatibilidade

| Navegador | Desktop | Mobile |
|-----------|---------|--------|
| Chrome | ✅ | ✅ |
| Firefox | ✅ | ✅ |
| Safari | ✅ | ✅ |
| Edge | ✅ | ✅ |
| Opera | ✅ | ✅ |

---

## 🎯 Casos de Uso

### Cenário 1: Investidor Individual
"Vou comprar 1 Antminer S21, é viável?"
→ Use **Simple Payback**

### Cenário 2: Pequeno Operador
"Tenho 5 mineradores diferentes, qual mix é melhor?"
→ Use **Múltiplos Mineradores**

### Cenário 3: Análise de Risco
"Qual é a probabilidade de sucesso?"
→ Use **Monte Carlo**

### Cenário 4: Decisão Estratégica
"Qual pool escolho?"
→ Use **Comparação de Pools**

### Cenário 5: Due Diligence
"Preciso de um relatório profissional"
→ Use **Exportar PDF**

---

## 💡 Dicas Pro

1. **Sempre use cenários pessimistas** para planejamento conservador
2. **Compare pools** - pode economizar 1-2% ao ano
3. **Monitore volatilidade** do Bitcoin - afeta muito seu ROI
4. **Atualizar dados** regularmente (preço BTC, hashrate rede)
5. **Exportar resultados** para documentar decisões

---

## 🐛 Relatório de Problemas

Encontrou um bug?

1. Teste no navegador console (F12)
2. Verifique sua conexão (APIs externas)
3. Limpe cache (Ctrl+Shift+Delete)
4. Tente outro navegador

---

## 📞 Suporte

**Dúvidas sobre mineração?**
- 📧 Documentação: Veja README.md
- 💬 Comunidades: Reddit r/bitcoinmining
- 🔗 Recursos: Bitcoin.org, Blockchain.info

---

## 📄 Licença

MIT License - Livre para usar, modificar e distribuir!

---

## 👨‍💻 Desenvolvedor

Criado por: **Rafael Rogel**  
Email: rrogel arroba gmail ponto com  
GitHub: @rafaelrogel  
Localização: Portugal 🇵🇹

---

## 🎉 Agradecimentos

- ❤️ Obrigado por usar MINECALC!
- 📣 Compartilhe com amigos
- ⭐ Dê uma estrela no GitHub
- 💬 Deixe feedback

---

## 📈 Roadmap

### v4.0 (Próxima)
- [ ] App Mobile (React Native)
- [ ] Sincronização em nuvem
- [ ] Alertas de preço
- [ ] Integração com exchanges
- [ ] Dashboard múltiplos usuários

### v3.0 (Atual) ✅
- [x] Gráficos 3D
- [x] Monte Carlo
- [x] Múltiplos mineradores
- [x] Comparação pools
- [x] Histórico BTC
- [x] Guia hospedagem

---

## 🚀 Como Hospedar Você Mesmo

### GitHub Pages (Grátis, Recomendado)

```bash
# 1. Clone o repositório
git clone https://github.com/rafaelrogel/minecalc.git
cd minecalc

# 2. Edite conforme necessário
# (abra index.html em seu editor favorito)

# 3. Commit e push
git add .
git commit -m "Meus customizações"
git push origin main

# 4. Seu site estará em:
# https://rafaelrogel.github.io/minecalc/
```

### Netlify (Alternativo)

```bash
# 1. Criar conta em netlify.com
# 2. Conectar repositório GitHub
# 3. Deploy automático em cada push
# 4. Receber link tipo: minecalc.netlify.app
```

---

## 📊 Versões Disponíveis

| Versão | Features | Ideal Para |
|--------|----------|-----------|
| **SIMPLE** | Payback básico | Iniciantes |
| **PRO** | Payback + Cenários + Sensibilidade + Monte Carlo | Profissionais |
| **ULTIMATE** | Tudo + 3D + Pools + Múltiplos mineradores + Histórico | Especialistas |

---

## ✉️ Feedback

Quer sugerir uma funcionalidade?  
Tem uma ideia?  
Achou um bug?

Mande um email: **rrogel arroba gmail ponto com**

---

**Última atualização:** Novembro 2025  
**Status:** ✅ Produção  
**Versão:** 3.0 ULTIMATE

Aproveite! 🚀⛏️📊
