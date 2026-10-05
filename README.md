# TCC — Desenvolvimento de um Mini SaaS
## Trilhas 5

---

## 📋 Informações Gerais

- **Formato:** grupo de 4 pessoas
- **Etapa 1 (Documentação + Apresentação):** 3 pontos
- **Etapa 2 (Sistema funcionando):** 5 pontos

| Etapa | Período | Entrega |
|-------|---------|---------|
| **Etapa 1 — Documentação** | 05/10 a 12/11/2026 | Documento + apresentação em **12/11** |
| **Etapa 2 — Desenvolvimento** | 12/11 a 11/12/2026 | Sistema entregue até **11/12** |
| **Apresentação Final** | — | **15/12/2026** |

---

## 🎯 A Proposta

Vocês vão criar um **mini SaaS**: um sistema web onde uma pessoa **cria uma conta, faz login e usa algo útil**.

Não precisa ser grande. Precisa ter **uma ideia de verdade**, resolver **um problema real** (mesmo que pequeno) e **funcionar**.

O objetivo não é entregar um sistema perfeito. É ter uma ideia, tentar construir, errar, corrigir e **aprender no caminho**. Erros fazem parte do trabalho e serão valorizados quando vocês mostrarem o que aprenderam com eles.

### O mínimo que o sistema precisa ter

1. **Cadastro e login** de usuário
2. **Uma funcionalidade principal** que resolve o problema (ex: registrar, listar, editar e excluir algo)
3. **Cada usuário vê apenas os próprios dados** (essa é a ideia central de um SaaS)
4. **Layout responsivo** (funciona bem no computador e no celular)
5. **Estar online**, acessível por um link público (não vale rodar só no `localhost`)
6. **Ser instalável como PWA**, ou seja, o usuário consegue adicionar o sistema à tela inicial do celular ou do computador e abrir como se fosse um aplicativo

> 📱 **Exemplo de PWA:** https://github.com/ProfessorDurvaldo/PwaCompleto

### Exemplos de ideias do tamanho certo

- Controle de gastos pessoais
- Agenda de clientes para um pequeno negócio (barbearia, manicure, personal)
- Controle de estoque de uma loja pequena
- Organizador de tarefas e prazos escolares
- Registro de treinos na academia
- Lista de empréstimos (livros, ferramentas, dinheiro entre amigos)

Todas seguem a mesma lógica: **o usuário entra, cadastra coisas, consulta e organiza**.

---

## 📝 ETAPA 1: DOCUMENTAÇÃO (05/10 a 12/11)

O documento deve ser **objetivo**. Não precisa ser longo, precisa ser claro.

### 1. Identificação
- Nome do sistema e por que escolheram esse nome
- Integrantes e a função de cada um

### 2. O Problema (seção mais importante)
Respondam em poucos parágrafos:
- **Qual problema** o sistema resolve?
- **Para quem?** Sejam específicos ("donos de barbearias pequenas", não "pessoas")
- **Como essas pessoas resolvem isso hoje?** (caderno, WhatsApp, planilha...)
- **Por que o sistema de vocês ajuda?**

> Dica: conversem com pelo menos uma pessoa que tenha esse problema. Isso deixa a ideia muito mais forte.

### 3. Funcionalidades
Separem em duas listas:

- **MVP (obrigatório):** o que precisa estar pronto em 11/12. Login, cadastro e a funcionalidade principal. Entre **3 e 5 itens**.
- **Extras (se der tempo):** ideias para depois.

Exemplo:
```
MVP:
1. Cadastro e login
2. Cadastrar gasto (valor, categoria, data)
3. Listar, editar e excluir gastos
4. Ver total gasto no mês

EXTRAS:
5. Gráfico por categoria
6. Filtro por mês
```

### 4. Telas
Descrevam ou desenhem (Figma, papel, wireframe) as telas do sistema. **Mínimo de 4 telas**, por exemplo:
- Login
- Cadastro
- Tela principal (onde o usuário usa o sistema)
- Formulário de cadastro/edição do item

Para cada tela, digam **o que tem nela** e **para onde ela leva**.

### 5. Tecnologias e Hospedagem
Digam o que vão usar no front-end, back-end e banco de dados, e **por que**.

Digam também **onde o sistema vai ficar online** (hospedagem do sistema e do banco de dados). Existem serviços com planos gratuitos que atendem bem um projeto desse tamanho, como Vercel, Netlify, Render, Supabase, Neon e InfinityFree. A escolha depende da tecnologia do grupo, então pesquisem qual combina com a stack de vocês e confiram os limites do plano gratuito.

> Usem o que o grupo já conhece. Este não é o momento de aprender um framework do zero.

### 6. Cronograma da Etapa 2
Dividam as tarefas entre os integrantes. Sugestão:

| Período | Atividade |
|---------|-----------|
| 12/11 - 18/11 | Ambiente, banco de dados, login, **primeira publicação online** e manifest do PWA |
| 19/11 - 02/12 | Funcionalidade principal (front e back) |
| 03/12 - 08/12 | Responsividade, testes e correções |
| 09/12 - 11/12 | Ajustes finais e entrega do link |
| 12/12 - 14/12 | Preparar apresentação |

---

## 🎤 Apresentação da Etapa 1 (12/11)

Apresentem para a turma:
1. O problema e para quem é
2. A solução e as funcionalidades do MVP
3. As telas (protótipo ou rascunho)
4. As tecnologias e o cronograma

Todos os integrantes devem falar.

---

## 🛠️ ETAPA 2: DESENVOLVIMENTO (12/11 a 11/12)

### Diário de Bordo

Durante o desenvolvimento, o grupo mantém um **diário de bordo** simples (pode ser um documento compartilhado ou o README do projeto). Registrem:

- **O que deu errado** (um erro, uma dificuldade, algo que não funcionou)
- **Como resolveram** (ou por que decidiram mudar o plano)
- **O que aprenderam**

Não precisa ser formal. Algumas linhas por semana bastam. Isso será mostrado na apresentação final e **conta na nota**.

### Publiquem cedo

Coloquem o sistema online **na primeira semana**, mesmo que seja só a tela de login, e já testem se ele instala como PWA. Publicar costuma dar problemas que não aparecem no computador de vocês (banco de dados, variáveis de ambiente, caminhos de arquivo). É muito melhor descobrir isso no início do que no último dia. Depois, a cada avanço, atualizem a versão online.

### Mudanças no plano

Mudar o que foi planejado na Etapa 1 é normal. Só registrem no diário **o que mudou e por quê**.

---

## 🏁 Apresentação Final (15/12)

1. Demonstrar o sistema **pelo link público**: instalar como PWA no celular, criar conta, fazer login e usar a funcionalidade principal
2. Mostrar o que mudou em relação ao planejado
3. Contar **pelo menos um erro** que o grupo enfrentou e o que aprenderam com ele

---

## ✅ Checklist da Etapa 1

- [ ] Nome do sistema e integrantes com funções
- [ ] Problema bem explicado, com público específico
- [ ] Lista do MVP (3 a 5 itens) e extras
- [ ] Mínimo de 4 telas descritas ou desenhadas
- [ ] Tecnologias com justificativa
- [ ] Hospedagem definida (onde o sistema e o banco vão ficar online)
- [ ] Nome curto, cores e ícone do PWA definidos
- [ ] Cronograma com divisão de tarefas
- [ ] Texto revisado
- [ ] Apresentação ensaiada

---

**Bom trabalho! 🚀**

*Uma ideia simples que funciona vale mais que uma ideia enorme pela metade.*

*Documento atualizado: Outubro/2026 — Trilhas 5*
