# Desafio de Engenharia de Qualidade de Software🚀

Bem-vindo(a) ao nosso Desafio de Engenharia de Qualidade de Software!

Estamos animados para conhecer suas habilidades e ver como você enfrenta este desafio de programação. Abaixo, detalhamos as expectativas e os requisitos para o teste.

## Objetivo

Este teste visa avaliar sua aptidão em Engenharia de Qualidade. Procuramos Engenheiros(as) de Qualidade que tenham uma sólida base em engenharia de software e estejam familiarizados(as) com as melhores práticas de desenvolvimento. Queremos conhecer suas habilidades através de um desafio de programação simples que abrange implementação geral, documentação e testabilidade.

## Avaliação 📋 

A avaliação abrangerá os seguintes aspectos:

1. **Implementação Geral:**
   - Precisão
   - Legibilidade


2. **Documentação:**
   - Qualidade do código-fonte
   - Clareza do arquivo README


3. **Testabilidade:**
   - Estrutura de testes
   - Cobertura de testes

4. **Git Skills:**
    - Controle de Versão
    - Tags
    - Commit

## Desafio: Análise de log 📚

### Funcionalidades a serem implementadas:

1. **Leitura do Arquivo de Log:**
   - Implemente a leitura do arquivo .log gerado através do logcat de um POS.

2. **Agrupamento dos Dados das Funções:**
   - Agrupe os dados provenientes das funções, indicando qual erro ocorreu e a quantidade.

3. **Coleta de Dados de Erro:**
   - Gerar um report agrupando quais erros e quantidade de erros apresentados por cada função.
   

### Exemplo linha de erro:
```
Exception Gedi: 20 00001 a função GEDI_USB_Open retornou GEDI_RET_FUNCTION_NOT_FOUND
```   

### Exemplo de estrutura:


```
"GEDI_USB_Open" {
  "quantidade de erros": 8,
  "erros": {
    "GEDI_RET_FUNCTION_NOT_FOUND": 5,
    "GEDI_RET_BUFFER_NOT_ENOUGH": 3
  }
}
```
# Report 📊
Crie um script que imprima um relatório com as informações agrupadas para cada função, exibindo os erros correspondentes e suas quantidades.



# Entrega 🤖

Espera-se que você envie um repositório git compactado por e-mail ou que compartilhe o acesso ao seu repositório privado com: gertec.qe@outlook.com
