# Introdução ao TDD

TDD (Test-Driven Development) é uma abordagem de desenvolvimento de software em que os testes são criados antes mesmo de o código funcional ser implementado. Essa metodologia ajuda a garantir que o software atenda aos requisitos especificados desde o início, promovendo código mais confiável e de alta qualidade.

<p align="center">
  <img alt="Teste Modelo Agil" src="./img/TDD.png" width="100%">
</p>

### Red (Escrever o Teste)

* O desenvolvedor escreve um teste que descreve o comportamento esperado do código.
* O teste inicialmente falha, pois a funcionalidade ainda não foi implementada. Essa etapa garante que o teste seja válido e relevante.

### Green (Implementar o Código)
* O código mínimo necessário para passar no teste é implementado.
* O objetivo aqui é fazer o teste passar com a solução mais simples possível, sem se preocupar com otimizações ou refatorações.

### Refactor (Refatorar o Código)

* Com o teste passando, o código é revisado para melhorar sua qualidade (ex.: legibilidade, eficiência, ou simplicidade).
* Durante a refatoração, todos os testes existentes devem continuar passando, garantindo que nenhuma funcionalidade anterior seja comprometida.

## Benefícios do TDD

1. Qualidade do Código:
    * Força o desenvolvedor a pensar nos requisitos antes de escrever o código, resultando em um design mais robusto.
2. Facilidade de Manutenção:
    * Código bem testado é mais fácil de modificar e refatorar, pois os testes detectam rapidamente erros introduzidos.
3. Menos Bugs:
    * Ao testar constantemente, erros são identificados e corrigidos no início do desenvolvimento.
4. Documentação Automática:
    * Os testes funcionam como uma forma de documentação para entender o comportamento esperado do código.
5. Agilidade no Desenvolvimento:
    * Embora possa parecer mais lento no início, o TDD reduz retrabalho e acelera a entrega de software de qualidade.

