# Sistema de Locadora de Veículos
Desenvolva uma aplicação em __Java Swing__ para cadastrar veículos de uma locadora.

Crie uma classe abstrata `Veiculo` com os atributos `placa`, `modelo` e `ano`, além de um método abstrato para informar o tipo do veículo.

Crie a interface `Alugavel` com métodos para __alugar__ e __devolver__ um veículo.

Implemente as classes `Carro`, `Moto` e `Caminhao`, cada uma com um atributo específico. Todas devem herdar de `Veiculo` e implementar `Alugavel`.

Sobrescreva o método `toString()` para exibir os dados completos do veículo.

A interface deve possuir campos para cadastro dos dados, uma seleção do tipo de veículo e os botões `Cadastrar`, `Alugar` e `Devolver`. As informações e o status do veículo devem ser exibidos em uma área de texto.
