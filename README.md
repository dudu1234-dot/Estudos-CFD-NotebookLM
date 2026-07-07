# Estudos-CFD-NotebookLM
Caderno Temático construído para estudar uma introdução às simulações fluidodinâmicas computacionias

## Contexto e Objetivos
Este repositório foi criado como um caderno temático sobre Introdução à CFD (Simulação Fluidodinâmica Computacional), reunindo conceitos fundamentais, aplicações e materiais de apoio para o estudo da área.

O objetivo é organizar conteúdos confiáveis, registrar os principais aprendizados obtidos durante o BootCamp e construir uma base de conhecimento que facilite futuras consultas e o aprofundamento dos estudos em CFD.

## Curadoria de Fontes
### Algumas das fontes selecionados e upadas no NotebookLM
https://sites.icmc.usp.br/rfausas/pmwiki/uploads/Main/MFC2025_notes.pdf

https://www.mr-cfd.com/cfd-for-beginners-concepts/
https://volupe.com/support/basic-cfd-concepts-fluid-dynamics/

## Engenharia de Prompts e "Cicatrizes"
#### Prompts utilizados na conversa com a IA do NotebookLM:
"Explique-me, de maneira simples, como é o princípio de funcionamento de uma simulação fluidodinâmica computacional. Considere que você está explicando para alguém que entende pouco do assunto, logo, seja claro e objetivo em suas explicações."

"Como a inteligência artificial está sendo integrada às simulações de CFD?"

"Achei muito interessante o conceito de Gêmeos Digitais. Aprofunde-se mais nesse conceito, explicando de forma clara e objetiva o que são e como funcionam. Lembre-se de que você está explicando para alguém que é leigo no assunto."

#### Raciocínio utilizado:
Busquei utilizar as técnicas de Engenharia de Prompt aprendidas no BootCamp, como o uso de: Contexto (quando pedi para a IA considerar que estaria explicando para alguém leigo no assunto), Intruções Claras (quando pedi, ao final do primeiro prompt, para ser claro e objetivo) e Repetição de Intruções no Final (quando, ao final do terceiro prompt, reforcei uma orientação dada no primeiro prompt, para que a IA mantenha uma linha de raciocínio sem desvios).

## Miniguia de Estudo
#### Resumo estruturado: 
1. Princípios de Funcionamento do CFD
A Fluidodinâmica Computacional (CFD) funciona como um laboratório virtual que utiliza computadores para prever o comportamento de fluidos. O processo segue cinco etapas principais:
- A Malha (Mesh): O espaço é dividido em milhões de pequenas células. Em vez de resolver um problema global complexo, o computador resolve as equações em cada pequena célula;
- Condições de Contorno: Definem-se as regras nas extremidades, como onde o fluido entra (Inlet), sai (Outlet) ou encontra superfícies sólidas (Walls);
- Leis da Física: O "motor" da simulação (o Solver) garante o respeito às leis de conservação de massa, movimento e energia, expressas pelas equações de Navier-Stokes;
- Iteração e Convergência: O cálculo é repetido exaustivamente até que os resultados parem de mudar significativamente, atingindo a convergência;
- Pós-processamento: Os dados numéricos são transformados em visualizações, como mapas de cores, vetores de velocidade e linhas de corrente.

2. Integração da Inteligência Artificial (IA)
A IA está transformando o CFD em uma ferramenta mais rápida e precisa através de:
- Modelos Substitutos (Surrogate Models): O aprendizado de máquina identifica padrões para aproximar resultados quase em tempo real, reduzindo o custo computacional;
- Melhoria na Modelagem: Algoritmos de IA otimizam a geração de malhas e aprimoram modelos de turbulência, aprendendo com grandes volumes de dados de alta fidelidade;
- Automação e Assistência: Ferramentas como o SuperCFD utilizam IA para oferecer interfaces inteligentes, reduzindo a curva de aprendizado e automatizando configurações complexas;
- Otimização de Design: A IA itera automaticamente sobre variações de projeto para encontrar a solução ideal de forma muito mais eficiente que um humano.

3. Gêmeos Digitais (Digital Twins)
Um Gêmeo Digital é um "espelho virtual" vivo e dinâmico de um sistema físico real. Ele se diferencia de uma simulação comum por sua conexão contínua:
- Funcionamento: Sensores inteligentes (IoT) no objeto físico coletam dados em tempo real (temperatura, pressão) e os enviam para modelos de CFD que espelham o comportamento virtualmente;
- Manutenção Preditiva: Permite prever falhas antes que ocorram, analisando o desgaste simulado versus o real;
- Otimização Instantânea: Ajusta sistemas (como o ar-condicionado de um prédio inteligente) em tempo real para maximizar o conforto e economizar energia;
- Segurança: Utilizado em setores críticos, como aeroespacial e energia, para simular condições extremas sem colocar o equipamento físico em risco.

#### Glossário: 
- Malha (Mesh/Grid);
- Condições de Contorno (Boundary Conditions);
- Condição de Não-Deslizamento (No-slip);
- Modelos Substitutos (Surrogate Models);
- Gêmeos Digitais (Digital Twins).

#### Prompts reutilizáveis:
"Explique-me, de maneira simples, como é o princípio de funcionamento de uma simulação fluidodinâmica computacional. Considere que você está explicando para alguém que entende pouco do assunto, logo, seja claro e objetivo em suas explicações."

"Achei muito interessante o conceito de Gêmeos Digitais. Aprofunde-se mais nesse conceito, explicando de forma clara e objetiva o que são e como funcionam. Lembre-se de que você está explicando para alguém que é leigo no assunto."
