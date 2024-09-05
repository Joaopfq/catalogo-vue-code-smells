#Catalogo de candidatos a code smells do Vue com TypeScript

| Code smells                                                       | Descrição                                                                                        |
|-------------------------------------------------------------------|--------------------------------------------------------------------------------------------------|
| Large component                                                   | Componente com muitas props, linhas e/ou atributos                                               |
| Duplicated component                                              | Componente dupllicado                                                                            |
| Large Files                                                       | Arquivos grandes                                                                                 |
| Low Cohesion                                                      | Componente com multiplas responsabilidades                                                       |
| Direct DOM Manipulation                                           | Manipular a DOM diretamente                                                                      |
| Prop Drilling                                                     | Passar props através de vários níveis de uma hierarquia de componentes                           |
| Force Update                                                      | Forçar o update de um componente ou página                                                       |
| Lack of HTML semantic                                             | Falta do uso da semântica do HTML                                                                |
| Misuse of handlers                                                | Uso indevido dos manipuladores                                                                   |
| Variables with any type                                           | Se refere a variáveis que não possuem um tipo explicito                                          |
| HTTP calls inside components                                      | Consiste no uso excessivo de chamadas HTTP diretamente nos componentes do desenvolvimento web    |
| Reference child component with watcher                            | Consiste em referenciar um componente filho através do uso de um prop/watcher                    |
| Omitting the Key Directive on v-for                               | Omitir a diretiva da chave do v-for                                                              |
| Unintentionally Mutating Props                                    | Consiste em mudar uma prop diretamente ao invês de usar emits para muda-la                       |
| Destructuring Reactive Data                                       | Desestruturar um dado reativo faz com que a reatividade seja perdida                             |
| Calling Composables in the Wrong Place                            | Usar composables em qualquer lugar diferente de diretamente no script setup do componente        |
| Using v-html with User Provided Data                              | Usar v-html com dados providos pelo usuário                                                      |
| Using ternary operator                                            | Usar o operador ternário dificulta a leitura do código e consequentemente sua futura manutenção  |
| Non-null assertions                                               | Evitar o uso do "!"                                                                              |
| Missing Union Type Abstraction                                    | Falta da criação de um tipo unificado                                                            |
| Missing Global Function                                           | Repetição de código pela falta de uma função global                                              |
| Too Many Props                                                    | Passar muitas props para um unico component                                                      |
| JSX outside the render method                                     | Implemenação de markup em multiplos métodos                                                      |
| Uncontrolled Components<br>                                       | A component that does not use props/state to handle form's data                                  |
| Enum Implicit Values                                              | Usando enums sem definir valores explicitos para eles                                            |
| Lack of type predicates                                           | Falta do uso de predicados de tipo.                                                              |
| Ref instead of reactive for complex objects                       | Uso do ref para objetos                                                                          |
| Direct state manipulation                                         | Alterar o estado diretamente sem o uso de funções                                                |
| Lack of use of watch and onMounted for async operations           | Falta do uso do watch ou onMounted para lidar com operações assincronas.                         |
| Share a single reactive instance across multiple composables      | Dividir uma unica instancia reactive para multiplos componentes                                  |
| Unnecessary v-model bindings                                      | Uso desnecessário de v-model bindings                                                            |
| Improper use of watchers                                          | Uso impróprio de watchers                                                                        |
| Large v-for loops without keys                                    | Longos laços v-for sem chaves                                                                    |
| Child component alters parent state directly                      | Componente filho altera estado do pai diretamente                                                |
| Created instead of mounted for animations or network calls        | Usar o create no lugar do mounted para animações e requisições                                   |
