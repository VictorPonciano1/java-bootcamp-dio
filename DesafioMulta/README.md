# 🚗 Desafio Multa

> 🧑🏻 Autor: Victor Ponciano — https://github.com/VictorPonciano1  
> 🧑🏽 Desenvolvedor Parceiro: Rian Rodrigues — https://github.com/rianexe

## 📌 Enunciado

A prefeitura da cidade B, inspirada por uma cidade A, decidiu implementar um sistema de câmeras que iria verificar se os carros estão acima de 80km/h. Porém, eles queriam também anotar a placa dos carros no banco de dados para que, a partir de 3 multas, os motoristas perdessem pontos diretamente na carteira de habilitação. Para isso, contrataram você para realizar esse programa, logo que você fez um trabalho tão bom para a cidade A.

Lembrando que toda vez que um carro é pego pela câmera e está acima da velocidade permitida automaticamente já é contabilizado uma multa para ele.

### Entrada
A entrada será a velocidade que o veículo está e quantas multas ele já recebeu. Se ele estiver acima da velocidade, deve ser somado mais uma multa.

### Saida
A saída deverá ser quantas multas o motorista já tem e se ele irá receber pontuação na carteira de habilitação.

### Exemplo
| Velocidade | Multas Anteriores | Saída                                      |
|------------|-------------------|--------------------------------------------|
| 80         | 1                 | "1 multas. Nao levou pontos na carteira"   |
| 85         | 1                 | "2 multas. Nao levou pontos na carteira"   |
| 95         | 2                 | "3 multas. Levou pontos na carteira"       |

## 🎯 Objetivo da Solução
Calcular a multa de trânsito com base na velocidade informada, aplicando as regras descritas no enunciado.

## 🛠️ Estratégia Utilizada
- Leitura de número usando `Scanner`;
- Estrutura de decisão para aplicar a penalidade correta;
- Cálculo baseado na diferença entre a velocidade e o limite;
- Exibição do valor da multa conforme o padrão esperado.

## 💻 Como Executar
1. Carregue o projeto em sua IDE Java;
2. Utilize **Java 17+**;
3. Execute a classe principal;
4. Forneça a velocidade conforme solicitado no desafio.

## 📚 Conceitos Praticados
- Decisões condicionais;
- Lógica de programação;
- Operadores aritméticos;
- Formatação de saída.

## 📝 Licença
Este projeto segue a licença MIT. Consulte o arquivo [LICENSE](../LICENSE) na raiz do repositório.