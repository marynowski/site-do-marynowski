# 💰 FinanceiroApp — Painel Financeiro Pessoal

Site financeiro pessoal com login, dashboard, controle de gastos, parcelamentos e fixos. Hospedado no GitHub Pages — acessível de qualquer lugar do mundo.

---

## 🚀 Como hospedar no GitHub Pages (passo a passo)

### 1. Crie um repositório no GitHub
- Acesse [github.com](https://github.com) e faça login
- Clique em **"New repository"** (botão verde)
- Nome sugerido: `financeiro` (ou qualquer nome)
- Deixe como **Public**
- Clique em **"Create repository"**

### 2. Faça upload do arquivo
- Dentro do repositório criado, clique em **"Add file" → "Upload files"**
- Arraste o arquivo `index.html` para a área de upload
- Clique em **"Commit changes"**

### 3. Ative o GitHub Pages
- Vá em **Settings** (aba no topo do repositório)
- No menu lateral, clique em **Pages**
- Em **Branch**, selecione `main` e pasta `/ (root)`
- Clique em **Save**

### 4. Acesse seu site
Após ~1 minuto, seu site estará disponível em:
```
https://SEU_USUARIO.github.io/financeiro/
```

---

## 🔑 Login padrão

| Campo | Valor |
|-------|-------|
| Usuário | `admin` |
| Senha | `financeiro2026` |

> **⚠️ Importante:** Altere a senha logo após o primeiro acesso em **Configurações → Alterar Senha**

---

## 📱 Funcionalidades

- **Dashboard** — Visão geral com entradas, fixos, parcelas, gastos e saldo
- **Gastos do Mês** — Lançar e visualizar gastos no crédito por mês
- **Parcelamentos** — Controle de parcelamentos ativos com projeção por mês
- **Gastos Fixos** — Lista de despesas fixas recorrentes
- **Entradas** — Receitas mensais
- **Configurações** — Alterar senha e exportar/importar dados (JSON)

---

## 💾 Sobre os dados

Os dados ficam salvos no **localStorage** do navegador. Isso significa:
- Funcionam offline
- Ficam no dispositivo/navegador que você usou
- Para transferir entre dispositivos: use **Exportar JSON** e depois **Importar JSON** no outro dispositivo

---

## 📊 Dados importados da sua planilha

Já estão pré-carregados:
- **Gastos de Abril** (18 lançamentos)
- **Parcelas ativas**: Apple Watch, Monitor do Breno, Tênis, Baú GIVI, Sahara (Nubank + Sicredi), Resident's Evil
- **Fixos**: TIM, Academia, Faculdade, Toyota Etios, AppleCare+
- **Entradas**: Salário + Aux. Mãe + Ticket Etios para todos os meses
