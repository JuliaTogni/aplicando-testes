# Testes de Software com .NET

Este README detalha a implementação e os resultados dos testes recomendados na atividade ponderada, utilizando os frameworks xUnit, NUnit e MSTest no ambiente .NET 5. Os testes foram desenvolvidos para validar a funcionalidade de conversão de temperaturas de Fahrenheit para Celsius.

## Frameworks de Teste

### xUnit
xUnit é um framework de teste open-source desenvolvido especificamente para .NET, ideal para desenvolvedores que buscam simplicidade e extensibilidade. Com uma API intuitiva, o xUnit facilita a escrita e manutenção de testes, permitindo também a adição de plugins para personalizar o comportamento do framework conforme as necessidades de cada projeto. Ele suporta testes orientados a dados (data-driven tests) e oferece paralelismo por padrão, possibilitando a execução simultânea de múltiplos testes, o que pode acelerar significativamente o processo de teste.

#### Evidência Teste com xUnit
![plot](./assets/Captura%20de%20tela%202024-05-28%20092142.png)

#### Resultado
Os testes foram executados com sucesso, conforme indicado na imagem, mostrando que todos os 6 testes passaram em 2 ms.

### nUnit
NUnit é um framework de teste open-source para .NET, amplamente reconhecido por sua flexibilidade e robustez, especialmente em testes orientados a dados. Ele permite a criação de testes unitários que podem ser facilmente executados e mantidos, sendo uma excelente escolha para projetos que exigem testes extensivos e detalhados. Neste exemplo demonstro como o NUnit facilita a criação de testes orientados a dados, pois é possível validar a conversão de temperaturas com diferentes entradas.

#### Evidência Teste com nUnit
![plot](./assets/Captura%20de%20tela%202024-05-28%20094345.png)

#### Resultados
Os testes foram executados com sucesso, conforme mostrado na imagem, indicando que todos os 6 testes passaram em 7 ms.

### MSTest

O MSTest é um framework de testes integrado com o Visual Studio, ideal para quem utiliza este ambiente de desenvolvimento. É menos flexível em testes orientados a dados em comparação com xUnit e NUnit, mas oferece boas opções para execução paralela de testes.

#### Evidência Teste com MSTest
![plot](./assets/Captura%20de%20tela%202024-05-28%20095502.png)

#### Resultados
Os testes foram executados com sucesso, conforme indicado na imagem, mostrando que todos os 6 testes passaram em 11 ms.

## Conclusão

Os testes de conversão de temperatura foram realizados com sucesso utilizando os frameworks xUnit, NUnit e MSTest. Cada framework demonstrou suas características e funcionalidades particulares, garantindo a confiabilidade do código testado. A partir desses testes podemos visualizar melhor a escolha do framework, deve ser baseada nas necessidades específicas do projeto e no ambiente de desenvolvimento utilizado.