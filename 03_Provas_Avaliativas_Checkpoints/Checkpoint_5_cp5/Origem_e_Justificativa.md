# Origem e Justificativa do Problema

**Disciplina:** Engenharia de Software
**Ano Letivo:** 2024 | **Turma:** 3ECR
**Avaliação:** Checkpoint 5

### Enunciado do Problema
Criar Dockerfile multi-stage build para compilar e empacotar microsserviços Java/Node.js com imagem final Alpine mínima e sem vulnerabilidades de segurança (CVEs).

### Formulação Formal
$$\text{FROM maven:3-jdk AS builder} \dots \text{FROM eclipse-temurin:17-jre-alpine AS runner}$$
