# Praceando - Tratamento de Dados

## Descrição

Este repositório contém o script de tratamento de dados para o aplicativo **Praceando**, utilizado para organizar e padronizar as respostas dos formulários coletados. O tratamento de dados garante a consistência e integridade da base, tornando-a adequada para análises de Business Intelligence (BI).

## Objetivo

Transformar a base bruta de respostas do Praceando em um conjunto de dados limpo e estruturado para BI. As etapas de tratamento incluem remoção de colunas irrelevantes, preenchimento de valores nulos com respostas contextuais, e padronização de nomes de colunas e valores textuais.

## Principais Tratamentos

- **Remoção de Colunas**: `nome`, `email`, `hora_de_modificação`
- **Substituição de Nulos**:
  - `"não participa de eventos"` para `você_tem_dificuldade_em_encontrar_eventos?`
  - `"não anuncia eventos"` para `você_se_considera_um_microempreendedor?`
  - `"não gostaria de ser notificado"` para `deixe_seu_e-mail_para_ser_notificado!`
- **Padronização**: Nomes de colunas em minúsculas e com `_`; valores textuais normalizados.

## Equipe
Enviando nossos melhores insights com 95% de confiança - equipe de dados🎲!
- [Fernanda Leão](https://github.com/fernandaleaoleita)
- [Guilherme Barbosa](https://github.com/guii-barbosa)

