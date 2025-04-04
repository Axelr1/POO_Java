lista de atividades - programação orientada a objetos em java

universidade estácio unimeta - curso de sistemas de informação

professor: érick fernandes

estudante

joão gabriel wisnievski

atividade 1: gerenciamento de frota

elabore um sistema para administrar os veículos de uma concessionária. os veículos serão classificados em dois tipos: carros e motos. ambos possuem os atributos marca, modelo, ano de fabricação e valor, com as seguintes diferenças:

carros devem armazenar a quantidade de portas.

motos devem conter informações sobre a capacidade do motor em cilindradas.

especificações:

implemente encapsulamento (atributos privados e métodos acessores - getters e setters).

crie uma classe base abstrata chamada "veiculo", contendo um método exibirInformacoes(), responsável por exibir os dados do veículo.

estabeleça herança para as classes "carro" e "moto".

utilize polimorfismo para permitir que exibirInformacoes() seja chamado de maneira genérica para os dois tipos de veículo.

(extra) desenvolva uma interface "promocao" com um método aplicarDesconto(double percentual) e a implemente nas classes correspondentes.

na classe principal (main), crie instâncias de um carro e de uma moto, exibindo suas informações.

atividade 2: cálculo de formas geométricas

desenvolva um programa que permita calcular área e perímetro de figuras planas, bem como volume de figuras espaciais. as formas a serem implementadas incluem: círculo, retângulo, triângulo, esfera, cubo e cone.

especificações:

defina uma classe abstrata "forma" com o método exibirInformacoes(), para apresentar detalhes sobre a figura.

crie uma interface "formaPlana" que contenha os métodos calcularArea() e calcularPerimetro().

desenvolva uma interface "formaEspacial" com o método calcularVolume().

implemente classes individuais para cada tipo de figura geométrica.

atribua a interface correta a cada classe correspondente.

utilize encapsulamento para os atributos necessários, como raio (círculo), altura/largura (retângulo) e lados (triângulo).

no programa principal (main), crie objetos de cada tipo de figura e exiba seus detalhes.

