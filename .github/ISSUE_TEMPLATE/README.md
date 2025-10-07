# 📝 Templates de Issues - Guia para Professores

Este guia explica como usar os templates de issues para solicitar mudanças no sistema de forma clara e eficiente.

## 🎯 Por que usar templates?

Os templates de issues ajudam você a:
- **Fornecer todas as informações necessárias** para que o agente Copilot possa executar sua solicitação
- **Evitar idas e vindas** com perguntas de esclarecimento
- **Acelerar o processo** de implementação
- **Garantir qualidade** nas mudanças solicitadas

## 📋 Templates Disponíveis

### 1. 🎯 Nova Atividade
**Quando usar:** Para adicionar uma nova atividade extracurricular ao sistema.

**O que você precisa fornecer:**
- Nome da atividade
- Descrição detalhada
- Categoria (Esportes, Artes, Acadêmico, etc.)
- Dias da semana
- Horário de início e término
- Capacidade máxima de participantes

**Exemplo de uso:**
> "Quero adicionar um Clube de Robótica que acontece às terças e quintas das 15:30 às 17:00, com capacidade para 15 alunos."

---

### 2. ✏️ Modificar Atividade Existente
**Quando usar:** Para alterar informações de uma atividade já cadastrada.

**O que você precisa fornecer:**
- Nome atual da atividade
- O que deseja modificar (nome, descrição, horários, capacidade, categoria)
- Novos valores
- Justificativa da mudança
- Impacto nos participantes já inscritos

**Exemplo de uso:**
> "Preciso mudar o Chess Club para quartas e sextas porque a sala não está disponível nas segundas."

---

### 3. 📊 Alterar Capacidade de Atividade
**Quando usar:** Especificamente para mudar o número máximo de participantes.

**O que você precisa fornecer:**
- Nome da atividade
- Capacidade atual
- Nova capacidade desejada
- Justificativa
- Como lidar com estudantes excedentes (se aplicável)

**Exemplo de uso:**
> "O Art Club precisa aumentar de 20 para 30 vagas porque conseguimos uma sala maior."

---

### 4. 🐛 Reportar Bug
**Quando usar:** Quando algo não está funcionando corretamente.

**O que você precisa fornecer:**
- Descrição do problema
- Onde o bug ocorre (interface, inscrição, login, etc.)
- Passos para reproduzir
- Comportamento esperado vs. atual
- Mensagens de erro (se houver)
- Severidade do problema

**Exemplo de uso:**
> "Quando tento inscrever um aluno no Drama Club, aparece 'atividade cheia' mas ainda há 5 vagas disponíveis."

---

### 5. 🎨 Melhoria de Interface
**Quando usar:** Para sugerir melhorias visuais ou de usabilidade.

**O que você precisa fornecer:**
- Onde a melhoria deve ser aplicada
- Qual problema resolve
- Como deveria funcionar/parecer
- Detalhes visuais (cores, layout)
- Responsividade (desktop, mobile, tablet)

**Exemplo de uso:**
> "Seria útil ter as atividades agrupadas por dia da semana na tela principal, facilitaria encontrar atividades de um dia específico."

---

### 6. ➕ Nova Funcionalidade
**Quando usar:** Para solicitar uma nova funcionalidade ou recurso.

**O que você precisa fornecer:**
- Descrição da funcionalidade
- Problema que resolve
- Como deve funcionar (fluxo de uso)
- Requisitos detalhados
- Interface necessária
- Impacto em funcionalidades existentes

**Exemplo de uso:**
> "Gostaria de poder exportar a lista de participantes de uma atividade para Excel, para facilitar relatórios administrativos."

---

### 7. 🗑️ Remover Atividade
**Quando usar:** Para remover uma atividade do sistema.

**O que você precisa fornecer:**
- Nome da atividade
- Número de participantes inscritos
- Motivo da remoção
- Como lidar com os participantes (notificar, transferir, etc.)
- Tipo de remoção (permanente, temporária, substituição)

**Exemplo de uso:**
> "O Photography Club precisa ser removido porque o professor responsável saiu da escola e temos 12 alunos inscritos que precisam ser notificados."

---

### 8. 👥 Gerenciar Inscrições
**Quando usar:** Para inscrever ou remover estudantes manualmente.

**O que você precisa fornecer:**
- Tipo de operação (inscrever, remover, transferir)
- Nome da atividade
- E-mail do estudante
- Justificativa
- Se precisa override de validações
- Se deve notificar o estudante

**Exemplo de uso:**
> "Preciso inscrever manualmente o aluno joao.silva@mergington.edu no Chess Club porque ele perdeu o prazo de inscrição por motivos médicos."

---

## 🚀 Como Usar os Templates

### Passo 1: Criar Nova Issue
1. Vá para a aba **Issues** do repositório
2. Clique em **New Issue**
3. Escolha o template apropriado

### Passo 2: Preencher o Template
1. Leia atentamente cada seção
2. Preencha **todos os campos obrigatórios**
3. Seja específico e detalhado
4. Use exemplos quando possível

### Passo 3: Atribuir ao Copilot
1. Na barra lateral direita, em **Assignees**, selecione `@copilot`
2. Verifique se as labels estão corretas
3. Clique em **Submit new issue**

### Passo 4: Acompanhar o Progresso
1. O agente Copilot será notificado automaticamente
2. Ele começará a trabalhar na sua solicitação
3. Você receberá atualizações na própria issue
4. Revise e aprove quando estiver pronto

## ✅ Boas Práticas

### ✓ Faça:
- **Seja específico**: Quanto mais detalhes, melhor
- **Use exemplos reais**: Facilita o entendimento
- **Preencha todos os campos**: Evita atrasos
- **Revise antes de enviar**: Certifique-se de que está claro
- **Um assunto por issue**: Não misture múltiplas solicitações

### ✗ Evite:
- **Deixar campos obrigatórios vazios**
- **Ser vago**: "Melhore o sistema" não é suficiente
- **Misturar múltiplas solicitações**: Crie issues separadas
- **Pular o template**: Use sempre o template apropriado
- **Esquecer de atribuir ao Copilot**

## 🎯 Exemplos de Issues Bem Escritas

### Exemplo 1: Nova Atividade
```
Título: [NOVA ATIVIDADE] Clube de Programação Python

Nome: Python Programming Club
Descrição: Curso introdutório de programação Python para iniciantes. Os alunos aprenderão conceitos básicos de programação, lógica e desenvolverão pequenos projetos.
Categoria: TECHNOLOGY
Dias: Tuesday, Thursday
Horário: 16:00 - 18:00
Capacidade: 20 alunos
Professor: teacher.silva
```

### Exemplo 2: Bug Report
```
Título: [BUG] Erro ao inscrever estudante com email institucional

Onde: Formulário de inscrição
Passos:
1. Fazer login como professor
2. Clicar em "Inscrever" no Chess Club
3. Digitar email: maria.santos@mergington.edu
4. Clicar em "Inscrever-se"

Esperado: Estudante é inscrito com sucesso
Atual: Aparece erro "Email inválido"
Severidade: Alta - Bloqueando inscrições
```

### Exemplo 3: Melhoria de UI
```
Título: [UI/UX] Adicionar indicador visual de atividades cheias

Onde: Cartões de atividades
Problema: Difícil identificar rapidamente quais atividades estão cheias
Solução: Adicionar badge vermelho "LOTADO" em atividades sem vagas
Cores: Vermelho #FF0000 para atividades cheias, verde #00FF00 para com vagas
Beneficia: Professores e estudantes
```

## 🆘 Precisa de Ajuda?

- **Dúvidas sobre qual template usar?** Escolha o mais próximo da sua necessidade
- **Não sabe alguma informação?** Deixe claro no campo "Observações"
- **Precisa de suporte?** Use as [Discussões](https://github.com/ctlrmuniz-uol/java-copilot-code-agent/discussions)
- **Emergência?** Entre em contato com o administrador do sistema

## 📚 Recursos Adicionais

- [Documentação do Sistema](../docs/README.md)
- [Guia de Copilot](https://docs.github.com/en/copilot)
- [Como escrever boas issues](https://docs.github.com/en/issues/tracking-your-work-with-issues/creating-an-issue)

---

**Lembre-se:** Issues bem escritas resultam em implementações mais rápidas e precisas! 🚀
