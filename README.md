
# Projeto: Conceitos do Databricks em Python

## Descrição

Este projeto foi desenvolvido como parte do curso na DIO (Digital Innovation One) com o objetivo de fixar os principais conceitos relacionados ao Databricks, utilizando Python para criar um sistema simples de consulta. Ao inserir o nome de um conceito, o sistema retorna sua descrição correspondente.

Este tipo de exercício é muito eficaz para consolidar conhecimentos e treinar lógica de programação.

---

## Funcionalidades

- Entrada de um conceito via terminal
- Verifica qual conceito foi informado
- Retorna uma descrição explicativa do conceito

---

## Tecnologias Utilizadas

- Python 3.x

---

## Conceitos Implementados

- **DBFS**: Sistema de Arquivos do Databricks
- **Lakehouse**: Integra Data Lake e Data Warehouse
- **Delta Lake**: Camada de armazenamento de dados open-source
- **Workspace**: Ambiente colaborativo para dados e código

---

## Código Fonte

```python
# Recebe a entrada do usuário e armazena na variável "entrada"
entrada = input()

# Função responsável por receber um conceito e retornar sua respectiva descrição.
def descrever_conceito(conceito):
    if conceito == "DBFS":
        return "Sistema de Arquivos do Databricks"
    elif conceito == "Lakehouse":
        return "Integra Data Lake e Data Warehouse"
    elif conceito == "Delta Lake":
        return "Camada de armazenamento de dados open-source"
    elif conceito == "Workspace":
        return "Ambiente colaborativo para dados e código"

# Imprime a descrição do conceito recebido na "entrada" através da função "descrever_conceito".
print(descrever_conceito(entrada))
```

---

## Possíveis Melhorias

- Tratar letras maiúsculas/minúsculas para tornar a entrada mais flexível
- Implementar uma interface gráfica (GUI) com Tkinter ou Web com Flask
- Adicionar novos conceitos relacionados ao ecossistema Databricks
- Testes automatizados para garantir o correto funcionamento

---

## Prints da Execução

Inclua aqui imagens semelhantes ao código mostrado, mostrando entradas e saídas diferentes sendo testadas com sucesso.

---

## Conclusão

Esse pequeno projeto reforçou a compreensão de conceitos-chave do Databricks, além de mostrar como podemos utilizar Python para criar sistemas de apoio ao aprendizado. Também serve como exemplo de projeto para compor o portfólio no GitHub.

---

**Autor:** Maria Eduarda Nunes Prado  
**LinkedIn:** [madu21nprado](https://github.com/madu21nprado)  
**GitHub:** [madu21nprado/projeto_analise](https://github.com/madu21nprado/projeto_analise)
