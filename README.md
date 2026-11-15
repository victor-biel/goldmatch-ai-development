# GoldMatch AI

GoldMatch AI é uma aplicação baseada em Inteligência Artificial que ajuda profissionais a avaliar rapidamente sua compatibilidade com oportunidades de emprego.

A plataforma compara um currículo com uma descrição de vaga, identifica pontos fortes, lacunas de competências, riscos de reprovação em processos seletivos e gera uma versão ATS Friendly do currículo para aumentar as chances de conseguir uma entrevista.

---

# Problema

Adaptar um currículo para cada vaga é um processo manual, demorado e muitas vezes baseado em tentativa e erro.

Os candidatos frequentemente não sabem:

- Se possuem aderência suficiente para a vaga.
- Quais requisitos estão faltando.
- Quais palavras-chave ATS devem incluir.
- Quais pontos do currículo precisam ser destacados.
- Qual a probabilidade de avançar para uma entrevista.

---

# Solução

GoldMatch AI automatiza esse processo através de Inteligência Artificial.

O utilizador apenas:

1. Faz upload do currículo.
2. Cola a descrição da vaga.
3. Recebe uma análise detalhada da compatibilidade.

---

# Funcionalidades

## Resume Parsing

Extração automática de:

- Competências técnicas
- Competências comportamentais
- Experiência profissional
- Formação académica
- Certificações
- Idiomas

---

## Job Description Analysis

Extração automática dos requisitos da vaga:

- Hard Skills
- Soft Skills
- Senioridade
- Tecnologias
- Certificações
- Idiomas
- Experiência exigida

---

## Match Score

Cálculo de compatibilidade entre o candidato e a vaga.

Exemplo:

```text
Overall Match: 87%
```

---

## Skills Match

Avalia a compatibilidade das competências técnicas.

Exemplo:

```text
Skills Match: 92%
```

---

## Experience Match

Avalia a aderência da experiência profissional.

Exemplo:

```text
Experience Match: 84%
```

---

## ATS Score

Avalia a qualidade do currículo para sistemas ATS.

Exemplo:

```text
ATS Score: 89%
```

---

## Strong Matches

Exibe os pontos fortes identificados.

Exemplo:

```text
✓ React
✓ TypeScript
✓ AWS
✓ SQL
✓ Docker
```

---

## Missing Skills

Exibe competências que aparecem na vaga mas não foram identificadas no currículo.

Exemplo:

```text
• Kubernetes

• Terraform

• Azure DevOps
```

---

## Risk Analysis

Identifica possíveis motivos de rejeição.

Exemplos:

- Experiência insuficiente com liderança.
- Certificações obrigatórias ausentes.
- Pouca evidência de experiência prática numa tecnologia específica.
- Keywords relevantes não encontradas.

---

## AI Recommendations

Sugestões de melhoria para aumentar as chances de aprovação.

Exemplos:

- Destacar resultados quantitativos.
- Adicionar competências presentes na vaga.
- Melhorar o resumo profissional.
- Evidenciar experiência de liderança.

---

## Interview Probability

Estimativa da probabilidade de obtenção de entrevista com base na compatibilidade identificada.

Exemplo:

```text
Interview Probability: 78%
```

---

## ATS Resume Generator

Geração automática de uma versão otimizada do currículo.

A IA pode:

- Reorganizar conteúdo.
- Melhorar descrições.
- Destacar competências relevantes.
- Otimizar palavras-chave ATS.

A IA NÃO pode:

- Inventar experiências.
- Inventar formações.
- Inventar certificações.
- Inventar competências inexistentes.

---

# Fluxo da Aplicação

```text
Upload Resume

↓

Parse Resume

↓

Paste Job Description

↓

Analyze Compatibility

↓

Generate Report

↓

Generate ATS Resume

↓

Download Result
```

---

# Design System

## Framework

- Shadcn UI
- TailwindCSS

## Estilo

Premium SaaS

Inspirado em:

- Linear
- Stripe
- Vercel
- Raycast
- Notion

---

## Paleta

### Gold

```css
#D4AF37
```

### Dark Gold

```css
#B8860B
```

### Background

```css
#0B0B0C
```

### Surface

```css
#131316
```

### Primary Text

```css
#FFFFFF
```

### Secondary Text

```css
#A1A1AA
```

---

# Stack Tecnológica

## Frontend

- Next.js
- TypeScript
- TailwindCSS
- Shadcn UI
- Framer Motion

## IA

- OpenAI
- OpenRouter

## Document Processing

- PDF Parser
- DOCX Parser

---

# Estrutura do MVP

O MVP foi desenhado para ser extremamente simples.

A aplicação possui apenas três etapas:

```text
1. Upload CV

↓

2. Colar Vaga

↓

3. Obter Resultado
```

Sem:

- Login
- Cadastro
- Histórico
- Dashboard
- Banco de dados
- Funcionalidades complexas

O objetivo é validar rapidamente a proposta de valor e permitir que um utilizador obtenha uma análise útil em menos de dois minutos.

---

# Roadmap Futuro

## V2

- Cover Letter Generator
- LinkedIn Import
- Histórico de análises
- Entrevistas simuladas com IA
- Career Coach
- Aplicação automática a vagas
- Integração com LinkedIn Jobs
- Integração com Indeed
- Sugestões de aprendizagem personalizadas

---

# Objetivo do Projeto

Transformar uma candidatura de emprego em um processo guiado por IA, fornecendo ao utilizador uma visão clara das suas probabilidades, dos seus pontos fortes e das melhorias necessárias antes de enviar uma candidatura.
