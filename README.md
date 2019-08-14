
# Projeto de Refatoramento

## Aplicações
| Design Patten  | Aplicação |
| ------------- | ------------- |
|Factory |  [FactoryFuncionario.java](https://github.com/hgms00/Projeto-de-Refatoramento/blob/master/src/main/FactoryFuncionario.java) |
|Template | [TemplatedoCopy()](https://github.com/hgms00/Projeto-de-Refatoramento/blob/master/src/main/FactoryFuncionario.java) |
|Command | [CommandSet.java](https://github.com/hgms00/Projeto-de-Refatoramento/blob/master/src/commands/CommandSet.java)|
|Singleton |[Singleton.java]( https://github.com/hgms00/Projeto-de-Refatoramento/blob/master/src/commands/Singleton.java) |
|Memento | [Memento.java](https://github.com/hgms00/Projeto-de-Refatoramento/blob/master/src/commands/Memento.java) |
---


- Factory : Utilizado na classe FactoryFuncionario e seus extends FactoryHorista,FactorySalariado,FactoryComissionado com o auxílio da interface Manager.
- Template: Utilizado na função TemplatedoCopy() presente em FactoryFuncionario que dependendo do tipo do funcionário, irá diferenciar no que a funçaõ também presente nas classe de horista,comissionado e salariado, irá fazer.
- Command : Utilizado em quase todas as classes dentro do pacote "commands" com o auxílio da interface Command.
- Singleton : Utilizado nas classes MementoOriginator,Memento e Mementocaretaker.
- Memento : Utilizado nas classes com prefixo Memento dentro do pacote "commands".
