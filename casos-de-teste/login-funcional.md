# Casos de Teste — Funcionalidade: Login

**Sistema:** Aplicação Web Genérica  
**Versão:** 1.0  
**Autor:** Giullia Fernandes  
**Data:** Mai/2026  

---

## CT-001 — Login com credenciais válidas

| Campo | Detalhes |
|---|---|
| **ID** | CT-001 |
| **Título** | Login com usuário e senha válidos |
| **Pré-condição** | Usuário cadastrado e ativo no sistema |
| **Prioridade** | Alta |
| **Tipo** | Funcional |

**Passos:**
1. Acessar a página de login
2. Inserir email válido no campo "Email"
3. Inserir senha correta no campo "Senha"
4. Clicar em "Entrar"

**Resultado Esperado:** Usuário redirecionado para a tela inicial autenticado.  
**Resultado Obtido:** ✅ Conforme esperado  
**Status:** ✅ Passou

---

## CT-002 — Login com senha incorreta

| Campo | Detalhes |
|---|---|
| **ID** | CT-002 |
| **Título** | Login com senha inválida |
| **Pré-condição** | Usuário cadastrado no sistema |
| **Prioridade** | Alta |
| **Tipo** | Funcional |

**Passos:**
1. Acessar a página de login
2. Inserir email válido
3. Inserir senha incorreta
4. Clicar em "Entrar"

**Resultado Esperado:** Mensagem de erro "Usuário ou senha inválidos".  
**Resultado Obtido:** ✅ Conforme esperado  
**Status:** ✅ Passou

---

## CT-003 — Login com campos em branco

| Campo | Detalhes |
|---|---|
| **ID** | CT-003 |
| **Título** | Tentativa de login sem preencher campos |
| **Pré-condição** | Nenhuma |
| **Prioridade** | Média |
| **Tipo** | Funcional / Borda |

**Passos:**
1. Acessar a página de login
2. Deixar os campos em branco
3. Clicar em "Entrar"

**Resultado Esperado:** Campos destacados em vermelho com mensagem "Campo obrigatório".  
**Resultado Obtido:** ✅ Conforme esperado  
**Status:** ✅ Passou

---

## CT-004 — Login com email inválido

| Campo | Detalhes |
|---|---|
| **ID** | CT-004 |
| **Título** | Login com formato de email inválido |
| **Pré-condição** | Nenhuma |
| **Prioridade** | Média |
| **Tipo** | Borda |

**Passos:**
1. Acessar a página de login
2. Inserir "giullia@" no campo email
3. Inserir qualquer senha
4. Clicar em "Entrar"

**Resultado Esperado:** Mensagem "Formato de email inválido".  
**Resultado Obtido:** ✅ Conforme esperado  
**Status:** ✅ Passou
