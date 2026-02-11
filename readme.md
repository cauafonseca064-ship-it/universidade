# projeto universidade

modelagem em Orientação à Objetos das Entidades Alunos, Curso e turmas.

## caso de uso
```mermaid
flowchart LR
    usuario([secretaria])

    UC1((Cadastrar Alunos))
    UC2((Editar Alunos))
    UC3((Transferir Alunos))
    usuario --> UC1
    usuario --> UC2
    usuario --> UC3
```
## Diagrama de Classe 
```mermaid 
classDiagram
    class aluno{
        - nome
        - Email
        - CPF
        - Telefone
        - Endereço
        - Matrìcula
        + Cadastrar()
        + Editar()
        +transfirir()
    }
```
## Dependências**:
- **VSCode**: IDE(interface de desnvolvimento)

- **Mermaind**: Linguagem para confecção de Diagramas em documentos MD (Mark Dow)

- **Material Icon Theme**: Tema para colorir as pastas.

- **Gitlens Lens**: Interface grafica para o vercionamento .git integrada no VScode.