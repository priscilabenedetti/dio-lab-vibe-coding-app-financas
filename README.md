# 💸 App de Planejamento de Finanças Pessoais da Priscila com Vibe Coding

PRD Refinado no Copilot.

...Markdown
gostaria que me ajudasse revisar meu PRD (Product Requirements Document), pois pretendo usá-lo no Loveble para exercitar minhas skills de vibe coding. 
Poderia deixar claro que a solução precisa ter desing universal, ou seja, que possa ser usado com boa experiência pelo máximo de usuários possíveis.
Poderia me ajudar? Como resposta me mande o PDR revisado e sintetize de forma didática os conceitos de Vibe Coding e PRD, pois ainda estou aprendendo sobre eles.

# Contexto
Quero criar um aplicativo de Organização de Finanças Pessoais que funcione por meio de conversas com o usuário em linguagem natural.  
A ideia é facilitar o controle financeiro de forma simples e natural, sem formulários manuais ou planilhas complexas.

# Problema
Muitas pessoas desistem de controlar seus gastos porque os apps atuais exigem muita entrada manual e pouca personalização.  
Quero resolver isso com uma experiência de conversa e recomendações automáticas de economia.

# Público-Alvo
Pessoas que querem começar a organizar suas finanças de forma prática e sem complicação, principalmente iniciantes.

# Funcionalidades-Chave
1. Registrar gastos via chat em linguagem natural.  
2. Classificar automaticamente as transações.  
3. Definir e acompanhar metas financeiras.  
4. Receber dicas de economia do “Agente Financeiro”.  
5. Visualizar relatórios simples e personalizados.

# Entregável da IA
Gerar um plano de MVP com as principais telas, recursos necessários e um esboço de validação inicial.  
Usar tom educativo e linguagem acessível, em português.
...

Interações com Loveble:

> crie um app de finanças pessoais, com base no seguinte PRD (Product Requirements Document): (PRD Refinado)

> preciso que a solução venha com dados em branco, para que eu acrescente os montantes de receitas e despesas

>a solução veio com valores de receitas, despesas e metas já preenchidos. poderia deixar sem preenchimento, para que eu mesma adicione os valores? além disso, adicione um campo onde eu possa incluir data final da meta.


Resultado final com Loveble: https://lovable.dev/projects/1339832b-fa8a-4d33-88e8-3feb874a5575

<img width="1892" height="966" alt="image" src="https://github.com/user-attachments/assets/031627ad-3f94-4ebe-91cf-0642ab38fd16" />



# Resumo das Funcionalidades do Aplicativo

## 1. Conversa Financeira (Chat Interativo)
- Permite registrar transações usando linguagem natural, como:
  - "Gastei R$ 50 no mercado"
  - "Meta: juntar R$ 5000 para viagem"
- O sistema interpreta e categoriza automaticamente as entradas.

## 2. Assistente Financeiro Inteligente
- Dá feedback imediato sobre as transações registradas.
- Corrige valores e sugere ajustes (ex.: corrigindo salário para R$ 3500).
- Oferece dicas e orientações para melhorar a saúde financeira.

## 3. Painel de Saldo Atual
- Mostra o saldo disponível e percentual de economia em relação à renda.
- Exibe **Receitas** e **Despesas** separadamente.

## 4. Gastos por Categoria
- Visualização simples dos gastos organizados por categorias (ex.: Outros, Educação, Alimentação).
- Ajuda a entender onde está sendo gasto mais dinheiro.

## 5. Metas Financeiras
- Permite criar e acompanhar metas personalizadas (ex.: juntar R$ 5000 para viagem).
- Indica quando não há metas definidas e incentiva a criação.

## 6. Relatórios e Configurações
- Menu com opções para acessar relatórios, metas e configurações.
- Interface clara e acessível, alinhada ao conceito de **Design Universal**.

---

### Diferenciais
- **Interação Natural:** Tudo acontece via conversa, sem formulários complexos.
- **Automação:** Classificação automática e sugestões inteligentes.
- **Design Universal:** Interface inclusiva, com linguagem simples e acessível para diferentes perfis de usuários.


# Reflexão

### O que funcionou bem?
O refinamento feito no Copilot foi fundamental

### O que não funcionou como esperado?
Ao tentar adicionar valor com casas decimais após a vírgula EX 3.500,00, o chatbot reconheceu R$3,50
Ao tentar corrigir o valor acima com a seguinte mensagem "corrigindo, o salario foi 3500", o montante de R$3.500,00 acabou sendo considerado como despesa.

### O que aprendeu sobre conversar com IAs?
Aprendi que a conversa precisa ter clareza, para que a interação seja produtiva e tenha o retorno correto.
