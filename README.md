# ↔️ EasyUnits - Biblioteca Para Converter Unidades

Este projeto, EasyUnits, fornece uma biblioteca para conversão de unidades de medida, dentre elas: unidades de temperatura, unidades de distância, unidades de massa, unidades de volume e unidades de tempo. Esta solução abrangente facilita o desenvolvimento de aplicações que envolvem a manipulação e conversão de diferentes unidades, oferecendo métodos simples e de fácil utilização.

⚠️ Os resultados retornados pela biblioteca são valores aproximados.

## 🚀 Features

Aqui estão os recursos da biblioteca EasyUtils:

| Função       | Ordem dos Parâmetros                                  | Descrição                      |
|-------------------------------|------------------------------------------------------|-------------------------------------------------|
| `CelsiusToFahrenheit()`         | <span style="color:blue">`double`</span> celsius | Converte a temperatura de Celsius para Fahrenheit. |
| `FahrenheitToCelsius()`         | <span style="color:blue">`double`</span> fahrenheit | Converte a temperatura de Fahrenheit para Celsius. |
| `CelsiusToKelvin()`             | <span style="color:blue">`double`</span> celsius | Converte a temperatura de Celsius para Kelvin.   |
| `KelvinToCelsius()`             | <span style="color:blue">`double`</span> kelvin  | Converte a temperatura de Kelvin para Celsius.   |
| `FahrenheitToKelvin()`          | <span style="color:blue">`double`</span> fahrenheit | Converte a temperatura de Fahrenheit para Kelvin. |
| `KelvinToFahrenheit()`          | <span style="color:blue">`double`</span> kelvin  | Converte a temperatura de Kelvin para Fahrenheit. |
| `MetersToKilometers()`        | <span style="color:blue">`double`</span> meters     | Converte a distância de metros para quilômetros.       |
| `KilometersToMeters()`        | <span style="color:blue">`double`</span> kilometers | Converte a distância de quilômetros para metros.       |
| `MilesToMeters()`             | <span style="color:blue">`double`</span> miles      | Converte a distância de milhas para metros.            |
| `MetersToMiles()`             | <span style="color:blue">`double`</span> meters     | Converte a distância de metros para milhas.            |
| `KilometersToMiles()`         | <span style="color:blue">`double`</span> kilometers | Converte a distância de quilômetros para milhas.       |
| `MilesToKilometers()`         | <span style="color:blue">`double`</span> miles      | Converte a distância de milhas para quilômetros.       |
| `FootsToMeters()`             | <span style="color:blue">`double`</span> foots      | Converte a distância de pés para metros.              |
| `MetersToFoots()`             | <span style="color:blue">`double`</span> meters     | Converte a distância de metros para pés.              |
| `CentimetersToMeters()`       | <span style="color:blue">`double`</span> centimeters | Converte a distância de centímetros para metros.      |
| `MetersToCentimeters()`       | <span style="color:blue">`double`</span> meters     | Converte a distância de metros para centímetros.      |
| `MillimetersToCentimeters()`  | <span style="color:blue">`double`</span> millimeters | Converte a distância de milímetros para centímetros.  |
| `CentimetersToMillimeters()`  | <span style="color:blue">`double`</span> centimeters | Converte a distância de centímetros para milímetros.  |
| `MillimetersToMeters()`       | <span style="color:blue">`double`</span> millimeters | Converte a distância de milímetros para metros.      |
| `MetersToMillimeters()`       | <span style="color:blue">`double`</span> meters     | Converte a distância de metros para milímetros.      |
| `YardsToCentimeters()`        | <span style="color:blue">`double`</span> yard       | Converte a distância de jardas para centímetros.      |
| `CentimetersToYards()`        | <span style="color:blue">`double`</span> centimeters | Converte a distância de centímetros para jardas.      |
| `YardsToMeters()`             | <span style="color:blue">`double`</span> yard       | Converte a distância de jardas para metros.          |
| `MetersToYards()`             | <span style="color:blue">`double`</span> meters     | Converte a distância de metros para jardas.          |
| `MilligramsToGrams()`         | <span style="color:blue">`double`</span> milligrams | Converte o peso de miligramas para gramas.             |
| `GramsToMilligrams()`         | <span style="color:blue">`double`</span> grams      | Converte o peso de gramas para miligramas.             |
| `GramsToKilograms()`          | <span style="color:blue">`double`</span> grams      | Converte o peso de gramas para quilogramas.            |
| `KilogramsToGrams()`          | <span style="color:blue">`double`</span> kilograms  | Converte o peso de quilogramas para gramas.            |
| `KilogramsToPounds()`         | <span style="color:blue">`double`</span> kilograms  | Converte o peso de quilogramas para libras.            |
| `PoundsToKilograms()`         | <span style="color:blue">`double`</span> pounds     | Converte o peso de libras para quilogramas.            |
| `PoundsToGrams()`             | <span style="color:blue">`double`</span> pounds     | Converte o peso de libras para gramas.                 |
| `GramsToPounds()`             | <span style="color:blue">`double`</span> grams      | Converte o peso de gramas para libras.                 |
| `OuncesToGrams()`             | <span style="color:blue">`double`</span> ounces     | Converte o peso de onças para gramas.                  |
| `GramsToOunces()`             | <span style="color:blue">`double`</span> grams      | Converte o peso de gramas para onças.                  |
| `OuncesToPounds()`            | <span style="color:blue">`double`</span> ounces     | Converte o peso de onças para libras.                  |
| `PoundsToOunces()`            | <span style="color:blue">`double`</span> pounds     | Converte o peso de libras para onças.                  |
| `KilogramsToOunces()`         | <span style="color:blue">`double`</span> kilograms  | Converte o peso de quilogramas para onças.             |
| `OuncesToKilograms()`         | <span style="color:blue">`double`</span> ounces     | Converte o peso de onças para quilogramas.             |
| `TonsToKilograms()`           | <span style="color:blue">`double`</span> tons       | Converte o peso de toneladas para quilogramas.         |
| `KilogramsToTons()`           | <span style="color:blue">`double`</span> kilograms  | Converte o peso de quilogramas para toneladas.         |
| `LitersToMilliliters()`               | <span style="color:blue">`double`</span> liters       | Converte Litros para Mililitros.               |
| `MillilitersToLiters()`               | <span style="color:blue">`double`</span> milliliters  | Converte Mililitros para Litros.               |
| `LitersToCubicCentimeters()`          | <span style="color:blue">`double`</span> liters       | Converte Litros para Centímetros Cúbicos.      |
| `CubicCentimtersToLiters()`           | <span style="color:blue">`double`</span> cubicCentimetrs | Converte Centímetros Cúbicos para Litros.   |
| `LitersToCubicMeters()`               | <span style="color:blue">`double`</span> liters       | Converte Litros para Metros Cúbicos.           |
| `CubicMetersToLiters()`               | <span style="color:blue">`double`</span> cubicMeters  | Converte Metros Cúbicos para Litros.           |
| `CubicMetersToCubicCentimeters()`     | <span style="color:blue">`double`</span> cubicMeters  | Converte Metros Cúbicos para Centímetros Cúbicos. |
| `CubicCentimetersToCubicMeters()`     | <span style="color:blue">`double`</span> cubicCentimeters | Converte Centímetros Cúbicos para Metros Cúbicos. |
| `SecondsToMinutes()`             | <span style="color:blue">`double`</span> seconds     | Converte Segundos para Minutos.                |
| `MinutesToSeconds()`             | <span style="color:blue">`double`</span> minutes     | Converte Minutos para Segundos.                |
| `MinutesToHours()`               | <span style="color:blue">`double`</span> minutes     | Converte Minutos para Horas.                   |
| `HoursToMinutes()`               | <span style="color:blue">`double`</span> hours       | Converte Horas para Minutos.                   |
| `SecondsToHours()`               | <span style="color:blue">`double`</span> seconds     | Converte Segundos para Horas.                  |
| `HoursToSeconds()`               | <span style="color:blue">`double`</span> hours       | Converte Horas para Segundos.                  |
| `HoursToDays()`                  | <span style="color:blue">`double`</span> hours       | Converte Horas para Dias.                      |
| `DaysToHours()`                  | <span style="color:blue">`double`</span> days        | Converte Dias para Horas.                      |
| `DaysToWeeks()`                  | <span style="color:blue">`double`</span> days        | Converte Dias para Semanas.                    |
| `WeeksToDays()`                  | <span style="color:blue">`double`</span> weeks       | Converte Semanas para Dias.                    |
| `DaysToMonths()`                 | <span style="color:blue">`double`</span> days        | Converte Dias para Meses.                      |
| `MonthsToDays()`                 | <span style="color:blue">`double`</span> months      | Converte Meses para Dias.                      |
| `WeeksToMonths()`                | <span style="color:blue">`double`</span> weeks       | Converte Semanas para Meses.                   |
| `MonthsToWeeks()`                | <span style="color:blue">`double`</span> months      | Converte Meses para Semanas.                   |
| `MonthsToYears()`                | <span style="color:blue">`double`</span> months      | Converte Meses para Anos.                      |
| `YearsToMonths()`                | <span style="color:blue">`double`</span> years       | Converte Anos para Meses.                      |
| `WeeksToYears()`                 | <span style="color:blue">`double`</span> weeks       | Converte Semanas para Anos.                    |
| `YearsToWeeks()`                 | <span style="color:blue">`double`</span> years       | Converte Anos para Semanas.                    |
| `DaysToYears()`                  | <span style="color:blue">`double`</span> days        | Converte Dias para Anos.                       |
| `YearsToDays()`                  | <span style="color:blue">`double`</span> years       | Converte Anos para Dias.                       |



⚠️ Lembre-se, durante o desenvolvimento do seu software, de seguir a ordem dos parâmetros especificada pela biblioteca para garantir o funcionamento adequado.

## 🔧 Como Usar

A biblioteca EasyUnits está disponível para a linguagem ![java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white) .


Para usar a biblioteca EasyUnits em seus projetos Java, siga estas etapas:

1. Faça o download do arquivo EasyUnits.JAR
2. Adicione a biblioteca ao seu projeto seguindo as instruções do seu IDE.
3. Importe a classe 'EasyUnits' no seu código:

   ~~~~java
   import easyunits.EasyUnits;
   ~~~~
5. Utilize os métodos fornecidos para converter temperaturas, distâncias, massas, volumes e medidas de tempo.

## </> Tecnologias Utilizadas

![java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)

## 💻 Autor

👤 Desenvolvido por: João Felipe  
📅 Ano de Desenvolvimento: 2024
