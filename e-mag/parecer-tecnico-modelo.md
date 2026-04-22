# Modelo de Parecer Técnico de Acessibilidade Digital

Estrutura de parecer técnico de acessibilidade web. Este arquivo é um modelo de referência.

> Este arquivo é um resumo navegável. A versão completa e oficial está disponível em PDF, na seção de releases deste repositório. Licença: CC BY-NC-ND 3.0 BR.

---

## 1. Identificação

| Campo | Preenchimento |
|---|---|
| **Cliente** | [nome da organização] |
| **Produto analisado** | [URL ou nome do sistema/site/app] |
| **Data da análise** | [dd/mm/aaaa] |
| **Analista** | Jorge Fiore de Oliveira Junior |
| **Referências técnicas** | WCAG 2.1, ABNT NBR 17225, E-MAG 3.1, Lei 13.146/2015 (LBI) |

---

## 2. Objetivo

Descrever de forma objetiva o propósito da análise. Exemplo:

> Realizar avaliação de conformidade de acessibilidade digital do produto [nome], com base nos critérios do E-MAG 3.1 (nível [A/AA/AAA]) e nos princípios das Diretrizes de Acessibilidade para Conteúdo Web (WCAG 2.1).

---

## 3. Escopo da Análise

| Item | Descrição |
|---|---|
| **Páginas avaliadas** | [listar URLs ou telas] |
| **Tecnologias envolvidas** | [ex.: HTML, CSS, JavaScript, React, etc.] |
| **Tecnologias assistivas testadas** | [ex.: NVDA, leitor de tela nativo, ampliação de tela] |
| **Navegadores testados** | [ex.: Chrome, Firefox] |
| **Nível de conformidade alvo** | [ex.: E-MAG nível A] |

---

## 4. Metodologia

A análise foi conduzida com base em:

- **Revisão de código:** inspeção do HTML, CSS e JavaScript para identificar barreiras de acessibilidade.
- **Teste com leitor de tela:** navegação com NVDA para verificar a experiência de pessoas cegas.
- **Navegação por teclado:** verificação de focos visíveis, ordem de tabulação e ausência de armadilhas de foco.
- **Verificação de contraste:** uso de ferramentas para avaliar a relação de contraste de cores.
- **Conformidade normativa:** comparação com os critérios do E-MAG 3.1 e WCAG 2.1.

---

## 5. Critérios Avaliados

### 5.1 Perceptível

| Critério | Status | Observação |
|---|---|---|
| Alternativas textuais para imagens | [ ] Conforme [ ] Parcial [ ] Não conforme | [descrição] |
| Contraste de cores (mínimo 4.5:1) | [ ] Conforme [ ] Parcial [ ] Não conforme | [descrição] |
| Texto redimensionável sem perda de funcionalidade | [ ] Conforme [ ] Parcial [ ] Não conforme | [descrição] |
| Identificação de campos de formulário | [ ] Conforme [ ] Parcial [ ] Não conforme | [descrição] |

### 5.2 Operável

| Critério | Status | Observação |
|---|---|---|
| Navegação completa por teclado | [ ] Conforme [ ] Parcial [ ] Não conforme | [descrição] |
| Foco visível em elementos interativos | [ ] Conforme [ ] Parcial [ ] Não conforme | [descrição] |
| Ausência de armadilhas de foco | [ ] Conforme [ ] Parcial [ ] Não conforme | [descrição] |
| Tempo suficiente para interação | [ ] Conforme [ ] Parcial [ ] Não conforme | [descrição] |

### 5.3 Compreensível

| Critério | Status | Observação |
|---|---|---|
| Idioma da página declarado | [ ] Conforme [ ] Parcial [ ] Não conforme | [descrição] |
| Rótulos claros em formulários | [ ] Conforme [ ] Parcial [ ] Não conforme | [descrição] |
| Mensagens de erro identificáveis | [ ] Conforme [ ] Parcial [ ] Não conforme | [descrição] |

### 5.4 Robusto

| Critério | Status | Observação |
|---|---|---|
| HTML válido e semântico | [ ] Conforme [ ] Parcial [ ] Não conforme | [descrição] |
| Compatibilidade com tecnologias assistivas | [ ] Conforme [ ] Parcial [ ] Não conforme | [descrição] |

---

## 6. Barreiras Identificadas

| # | Barreira | Critério | Severidade | Recomendação |
|---|---|---|---|---|
| 1 | [descrição] | [ex.: E-MAG 3.1 - 1.1.1] | Alta/Média/Baixa | [ação sugerida] |
| 2 | [descrição] | [ex.: E-MAG 3.1 - 2.1.1] | Alta/Média/Baixa | [ação sugerida] |
| 3 | [descrição] | [ex.: E-MAG 3.1 - 1.4.3] | Alta/Média/Baixa | [ação sugerida] |

> **Severidade:**
> - **Alta:** impede o uso do produto por pessoas com deficiência.
> - **Média:** dificulta o uso, mas não impede totalmente.
> - **Baixa:** causa desconforto ou reduz a eficiência.

---

## 7. Conclusão

Com base na análise realizada, o produto [nome] apresenta [X] barreiras de acessibilidade, sendo [X] de severidade alta, [X] média e [X] baixa.

O nível de conformidade atual é **[não conforme / parcial / conforme]** ao E-MAG 3.1, nível [A/AA].

Recomenda-se a implementação das correções descritas na seção 6, priorizando as barreiras de severidade alta, que impactam diretamente a autonomia de pessoas com deficiência visual no uso do sistema.

---

## 8. Assinatura

**Jorge Fiore de Oliveira Junior**

Consultor e Auditor em Acessibilidade Digital

Especialista em WCAG, ABNT NBR 17225 e E-MAG

Rio de Janeiro, [dd/mm/aaaa]

---

## 9. Referências

- Diretrizes de Acessibilidade para Conteúdo Web (WCAG) 2.1 — https://www.w3.org/TR/WCAG21/
- E-MAG — Modelo de Acessibilidade em Governo Eletrônico 3.1 — https://www.gov.br/governodigital/pt-br/acessibilidade-digital/e-mag
- ABNT NBR 17225:2022 — Requisitos de acessibilidade em ambientes virtuais
- Lei 13.146/2015 — Lei Brasileira de Inclusão da Pessoa com Deficiência (LBI)
