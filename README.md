 # 🍬 L&J Doces - Gestão Inteligente & Cardápio Digital

![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white)
![ODS 8](https://img.shields.io/badge/ODS%208-Trabalho%20Decente-A21942?style=for-the-badge)

Aplicação móvel desenvolvida para modernizar a operação da microempresa **L&J Doces**, focando em eficiência operacional, sustentabilidade financeira e melhoria da experiência do cliente no ambiente universitário.

---

## 👥 Equipe e Empresa
* **Integrantes:**
  - Guilherme Portilho<br>
  - Gabrielly Cristina dos Reis<br>
  - Vitória Karolina Santos Silva<br>
  - Leonardo Delfino Vieira
* **Empresa Beneficiada:**
  - L&J Doces.
* **Justificativa Extensionista:**
  - Promoção da modernização tecnológica local e alinhamento ao **ODS 8 (Trabalho Decente e Crescimento Econômico)**.

---

## 📝 Documento de Visão

### 📌 O Problema
Atualmente, a L&J Doces opera de forma presencial e manual. Isso gera:
* Incerteza na reposição de insumos.
* Dificuldade em prever a demanda diária.
* Perda de tempo informando sabores e preços repetidamente aos alunos.

### 🎯 Solução Proposta
Um aplicativo em **Flutter** estruturado em três pilares:
1.  **Módulo de Gestão (Dono):** Controle total de estoque, vendas e cadastro.
2.  **Módulo de Consulta (Cliente):** Cardápio digital em tempo real.
3.  **Diferencial de IA:** Modelo preditivo para análise de tendências e sugestão de produção.

---

## 🚀 Funcionalidades (Backlog Rascunho)

### [Épico] Gestão de Inventário e Produtos
- **RF-01:** Cadastro de produtos.
- **RF-02:** Edição e exclusão de produtos.
- **RF-05:** Alertas automáticos de estoque crítico.

### [Épico] Experiência do Cliente
- **RF-03:** Catálogo digital em tempo real para verificação de disponibilidade.
- Sistema de fidelização digital
- Pagamento via QR Code ou ChavePix.

### [Épico] Financeiro e Operacional
- **RF-06:** Registro de vendas.
- **RF-07:** Registro de vendas a prazo ("Penduricalhos").
- **RF-08:** Cálculo automático de lucro real.
- **RF-09:** Modo Offline com sincronização posterior.

### [Épico] Inteligência de Dados
- **RF-10:** Modelo preditivo para análise de tendências e sugestão de produção diária.

---

## 📏 Regras de Negócio (RN)
* **RN-01:** Produto sem estoque deve aparecer como indisponível no cardápio.
* **RN-04:** Venda a prazo deve ter identificação do cliente e data prevista de pagamento.
* **RN-05:** Toda venda finalizada deve atualizar automaticamente o saldo de estoque.
* **RN-08:** Sugestão da IA é recomendação e exige confirmação do usuário.

---

## ⚙️ Requisitos Não Funcionais (RNF)
* **RNF-01:** Desenvolvimento obrigatório em framework Flutter.
* **RNF-02:** Design responsivo para múltiplos dispositivos móveis.
* **RNF-03:** Atualização de estoque/disponibilidade em até 2 segundos.
* **RNF-05:** Operação offline sem perda de dados locais.
* **RNF-06:** Proteção de dados com boas práticas e comunicação segura (HTTPS).

---

## 🧪 Estratégia de Testes e Qualidade
A qualidade do software será garantida através das seguintes camadas de teste:
* **Testes Unitários:** Validação das funções lógicas de cálculo e estoque.
* **Testes de Interface (Widget Tests):** Verificação da navegação e interatividade do cardápio.
* **Ferramentas:** Uso do pacote nativo `flutter_test`.

---

## 📚 Documentação de Requisitos e Colaboração
- Requisitos Funcionais: `docs/RF.md`
- Regras de Negócio: `docs/RN.md`
- Requisitos Não Funcionais: `docs/RNF.md`
- Guia de contribuição: `CONTRIBUTING.md`
- Template de Pull Request: `.github/PULL_REQUEST_TEMPLATE.md`
- Templates de Issue: `.github/ISSUE_TEMPLATE/`

---

## 🛠️ Tecnologias Utilizadas
* **Framework:** Flutter
* **Linguagem:** Dart

