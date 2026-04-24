# Desafio DevSecOps — Gerenciador de Tarefas

## Sobre o Projeto
Este repositório faz parte do desafio prático do módulo de DevSecOps da ADA Tech.
Você receberá este projeto com vulnerabilidades propositais e uma pipeline incompleta.
Seu objetivo é **implementar a pipeline de segurança** e **corrigir as vulnerabilidades**.

## Estado atual
A pipeline está **incompleta**. Os steps de segurança precisam ser implementados por você.

## Sua missão
1. Implementar os steps de segurança no `pipeline.yml`
2. Fazer a pipeline **quebrar** ao detectar os problemas
3. Corrigir as vulnerabilidades encontradas
4. Fazer a pipeline **passar** com tudo verde ✅
5. Documentar o funcionamento da pipeline neste README

## O que implementar
- [ ] Secrets Scanning com **Gitleaks**
- [ ] SAST com **Semgrep**
- [ ] SCA com **Grype**
- [ ] Deploy com **GitHub Pages**

## Como a pipeline funciona
> Projeto feito após aulas, ma pipeline é um fluxo organizado de etapas que transformam uma entrada em uma saída.

Pipiline
É uma sequência de processos conectados, como uma linha de montagem.

Cada etapa recebe algo, processa e entrega para a próxima.

A pipeline organiza tarefas em sequência, garantindo que o fluxo seja contínuo e eficiente até o resultado final.

Etapas da pipeline e sua importância para a segurança
Build (compilação)

O que faz: transforma o código-fonte em um executável ou pacote.

Por que é importante: garante que apenas código válido e consistente siga adiante, evitando falhas ou dependências maliciosas.

Testes automatizados

O que faz: executa testes unitários, de integração e funcionais.

Por que é importante: detecta erros cedo, reduzindo vulnerabilidades que poderiam ser exploradas em produção.

Análise estática de código (SAST)

O que faz: examina o código sem executá-lo, procurando padrões inseguros.

Por que é importante: identifica falhas como injeções, uso inseguro de bibliotecas e más práticas antes mesmo da execução.

Análise dinâmica (DAST)

O que faz: testa o sistema em execução simulando ataques externos.

Por que é importante: revela vulnerabilidades reais que só aparecem quando o software está rodando.

Verificação de dependências

O que faz: checa bibliotecas externas contra bases de vulnerabilidades conhecidas.

Por que é importante: evita que código de terceiros comprometido seja incluído no produto.

Deploy controlado

O que faz: libera o software em ambientes de teste, homologação e depois produção.

Por que é importante: reduz riscos de liberar código inseguro diretamente ao usuário final.

Monitoramento e logging

O que faz: acompanha o comportamento do sistema e registra eventos.

Por que é importante: permite detectar ataques, anomalias e responder rapidamente a incidentes.

## URL de Produção
> (https://debora-marx.github.io/projeto-devsecops-desafio/);
