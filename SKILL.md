---
name: "Calculos Trabalhistas Completos"
version: "1.0"
description: "Skill para cálculos trabalhistas completos com fluxo automático ou assistido."
author: "Carlos A. A. Oliveira - OAB/PA 33996"
---

# Skill: Cálculos Trabalhistas Completos

## Sobre o Criador
Carlos A. A. Oliveira é um advogado comprometido com a excelência técnica e a defesa qualificada dos direitos de seus clientes.  
Inscrito na OAB/PA sob o nº **33996**, atua com seriedade, ética e profundo domínio jurídico, sempre buscando soluções estratégicas e fundamentadas para cada demanda.

Sua trajetória é marcada pela dedicação ao estudo constante, pela habilidade em interpretar cenários complexos e pela capacidade de transformar conhecimento jurídico em resultados concretos.

Além da atuação profissional, mantém presença ativa nas redes sociais como **@oliveiraCarlosADV**, onde compartilha conteúdo jurídico, orientações e reflexões sobre o Direito contemporâneo.

Reconhecido pela postura responsável e pela comunicação clara, Carlos se destaca como um profissional que alia técnica, humanidade e compromisso com a justiça, consolidando uma atuação sólida e confiável no cenário jurídico paraense.

Contato profissional: **(91) 9 9827-7601**

**Avante!**

---

## Objetivo da Skill
Realizar **cálculos trabalhistas completos**, incluindo:
- Verbas rescisórias  
- Horas extras  
- Adicional noturno  
- Insalubridade  
- Comissões  
- FGTS + Multa  
- Férias + 1/3  
- 13º salário  
- Integrações  
- Reflexos  

A skill deve perguntar ao usuário se deseja:
- **Cálculo Automático**  
- **Cálculo Assistido**

---

## Fluxo Inicial

Ao iniciar, a skill deve perguntar:

**"Você deseja realizar o cálculo de forma AUTOMÁTICA ou ASSISTIDA?"**

---

## Dados obrigatórios a serem solicitados

### Dados básicos
- Data de admissão  
- Data de demissão  
- Salário  
- Função  
- Tipo de aviso prévio  
- Variáveis (se houver)

### Perguntas obrigatórias antes do cálculo
1. Recebia horas extras? Quanto  
2. Trabalhava entre 22h e 5h  
3. Recebia comissão  
4. Recebia algum valor por fora  
5. Fez algum acordo por fora  

---

## Lógica Geral da Skill

### Se o usuário escolher **Cálculo Automático**:
- Solicitar todos os dados de uma vez  
- Processar automaticamente  
- Exibir relatório final detalhado  

### Se o usuário escolher **Cálculo Assistido**:
- Perguntar item por item  
- Confirmar cada etapa  
- Somente ao final realizar o cálculo  

---

## Estrutura de Resposta
A skill deve sempre entregar:

### 1. Resumo dos dados informados  
### 2. Cálculo detalhado  
### 3. Tabelas de valores  
### 4. Explicações jurídicas  
### 5. Observações técnicas  
### 6. Possíveis teses aplicáveis  

---

## Finalização
Ao concluir o cálculo, a skill deve dizer:

**"Cálculo finalizado! Caso deseje gerar uma petição, relatório ou PDF, posso ajudar."**

