# **Desafio Mobile \- Aplicativo de Mesas e Comandas**

Um cliente do setor de restaurantes entrou em contato solicitando o desenvolvimento de um aplicativo para gerenciamento de mesas e comandas, compatível com iOS e Android. O objetivo principal é listar todas as mesas disponíveis e ocupadas, oferecendo filtros que agilizem o processo de atendimento.

O projeto deve ter inicialmente as seguintes funcionalidades:

## **Requisitos do Projeto**

1. **Listagem de mesas:** Exibição de todas as mesas, indicando seu status (ocupada, livre, reservada, etc.).  
2. **Pesquisa avançada:** Busca por nome do cliente, número da mesa e nome do atendente.  
3. **Filtros das mesas**: Opções para filtrar mesas por visão geral, em atendimento, ocupadas e ociosas.  
4. **Mostrar informações da mesa e das comandas na listagem:** Implementar a visualização rápida de quem está atendendo a mesa, o nome do cliente, quantidade de comandas, há quanto tempo está sem fazer novo pedido, etc.

## **Ferramentas e Tecnologias Utilizadas**

* **Linguagem:** Typescript  
* **Framework:** React native  
* **Estado global:** Redux  
* **Arquitetura:** MVVM ou MVC  
* **Controle de versão:** Git

## **Entrega do Desafio envolve**

1. **Código-fonte do projeto** hospedado em um repositório Git privado.  
2. **Documentação da aplicação**, explicando as funções, o que cada componente faz e exemplos de uso.  
3. **Scroll Infinito:** O aplicativo deve ter uma rolagem infinita onde a cada chegada no fim da lista, será renderizado mais 20 mesas.  
4. **Utilizar referências nas listagens:** Quando o usuário clicar em algum filtro, esse filtro não pode ficar cortado para fora da tela, ele tem que ficar centralizado ao mesmo tempo que a cada clique do filtro, deve ser feito um scroll pro início da listagem de mesas.  
5. **Otimização:** O aplicativo deverá funcionar no mínimo em dispositivos de 1gb de ram e 8gb de armazenamento, por isso a otimização é um dos pilares do projeto.  
6. **Responsividade:** O aplicativo deverá rodar no IOS e no Android onde a densidade de pixels varia muito, o aplicativo não deverá quebrar em nenhum momento.  
7. **Não utilizar Expo ou frameworks parecidos:** o aplicativo deverá ser CLI e cada configuração de lib deverá ser feita nos módulos nativos se assim a lib precisar.  
8. **Utilizar API Rest para pegar todas as mesas.**  
9. **Utilizar Redux:** a aplicação deverá pegar todas as mesas e armazenar as mesas no redux(o redux deverá ser integrado com asyncstorage).  
10. **Componentização:** A componentização é essencial para manter um padrão de design consistente no aplicativo. O uso de componentes globais não só garante uniformidade na interface, mas também melhora a reutilização de código, a manutenção e a escalabilidade da aplicação.

Opcional: **Utilizar Jest e React Native Testing Library:** O aplicativo deve conter 2 testes, o primeiro vai testar as funções de filtros e pesquisa e o segundo teste deverá ser para testar a renderização de uma mesa(cores, informações da mesa, etc).

[PROTÓTIPO](https://www.figma.com/design/rQuxZuO2oZ7Vm8JLGCaLAD/Desafio-Pigz-Mobile-2025.1---Comanda-Mobile---Tempo-de-Inatividade?node-id=0-1&p=f&t=7r6a1Y8T0YnKBXEK-0)

