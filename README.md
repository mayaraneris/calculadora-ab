# Calculadora de Teste A/B 🧪📊

> Uma calculadora bem simples de Teste A/B focada em times de Produto e Growth. Calcule a amostra mínima, tempo de validação e tome decisões baseadas em dados com facilidade ✨

## O problema
Rodar um teste A/B sem calcular a amostra mínima antes é o caminho mais rápido para desperdiçar tráfego e tempo. Analisar o resultado sem rigor estatístico é o caminho mais rápido para tomar decisões erradas. 

Esta calculadora de arquivo único (Single-Page) resolve as duas pontas da rotina de testes A/B, de forma visual e direto no navegador.

## Funcionalidades

* **Passo 1: Planejamento (Pré-teste)**
  * Calcula o tamanho da amostra (Sample Size) por variante.
  * Estima os dias necessários para conclusão do teste baseado no tráfego diário.
  * Avalia se a sua meta de *lift* faz sentido e gera cenários alternativos automaticamente.

* **Passo 3: Análise (Pós-teste)**
  * Calcula a conversão de cada variante.
  * Aponta o vencedor com base em **Significância Estatística** (Z-test de duas proporções).
  * Exibe P-valor, Z-statistic e Lift relativo de forma fácil de entender.

* **Integração com IA (Exportação de Contexto)**
  * Botões de "Copiar pra Claude / ChatGPT" que geram *prompts* estruturados automaticamente com os seus dados, prontos para você debater hipóteses, analisar riscos e documentar aprendizados com a IA.

* **Educação Embutida**
  * Traz explicações acessíveis sobre *Guard Rails*, *Peeking*, KPIs primários e os fundamentos de um bom teste de produto.

## Como rodar (Zero Setup)

Esqueça o `npm install`! O projeto foi desenhado para ser super leve e rodar diretamente no navegador sem nenhum processo de *build*.

1. Faça o clone do repositório ou baixe o arquivo `index.html`.
2. Dê um duplo-clique no arquivo `index.html` para abri-lo em qualquer navegador (Chrome, Safari, Firefox).
3. Pronto! A calculadora já está funcionando.

## Tecnologias utilizadas

O projeto utiliza uma abordagem *vanilla/CDN* para máxima portabilidade:
* **HTML5** (Estrutura em arquivo único)
* **React 18** (via CDN, para reatividade dos estados)
* **Tailwind CSS** (via CDN, para estilização rápida e responsiva)
* **Babel Standalone** (para compilação do JSX em tempo real no navegador)
* **Fontes:** Fraunces (Serifada) e IBM Plex (Sans/Mono) via Google Fonts.

## Privacidade e segurança

**100% Local (Client-side):** Toda a matemática da calculadora roda localmente no seu navegador. 
Nenhum dado financeiro, volume de tráfego ou taxa de conversão é enviado para servidores externos. Você pode abrir o arquivo `.html` e desligar a internet que a ferramenta continuará funcionando perfeitamente.

---
*Desenvolvido com foco na experiência de times de Produto.*
