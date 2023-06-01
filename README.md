**Sobre**

O uso de bicicletas como meio de transporte ganhou muita força nos últimos anos,
seja por questões ambientais, de saúde ou até mesmo de infraestrutura de trânsito. Para
incentivar seu uso, cidades em todo o mundo têm implementado programas de
compartilhamento de bicicleta. Nesses sistemas, elas são retiradas e devolvidas em
quiosques automatizados que ficam espalhados por diversos pontos da cidade.
As plataformas de compartilhamento de bicicletas costumam coletar diversos tipos
de dados, como a duração da viagem, as localizações iniciais e finais dos percursos, entre
outros. Esses dados, em conjunto com informações sobre o clima, o trânsito e o relevo, por
exemplo, possibilitam uma análise mais robusta do compartilhamento de bicicletas.
Segue um descritivo dos dados coletados:

- **rec_id**: índice do registro de locação;
- **datetime** : data;
- **season** : estação do ano (1: inverno, 2: primevera, 3: verão, 4: outono). Relativo ao
  hemisfério norte;
- **year** : ano (0: 2011, 1:2012);
- **month** : mês (1 a 12);
- **hour** : hora do dia (0 a 23);
- **is_holiday** : booleano indicando feriado;
- **weekday** : dia da semana (0: domingo, 1: segunda-feira, ..., 6: sábado);
- **is_workingday** : booleano indicando dia útil;
- **weather_condition**: (1: limpo, 2: nublado, 3: chuva leve, 4: chuva forte);
- **temp** : Temperatura escalada entre 0 e 1. Valor original em graus Celsius: -8 a 39;
- **atemp**: Sensação térmica escalada entre 0 e 1. Valor original em graus Celsius: -16 a 50;
- **humidity**: Humidade relativa (0 a 1);
- **windspeed**: Velocidade do vento escalada entre 0 e 1 (máximo original: 67);
- **casual**: número de locações para usuários casuais;
- **registered**: número de locações para usuários registrados;
- **total_count**: contador total de aluguéis (casual+registered).

---

**Esta atividade tem como objetivo analisar os dados de compartilhamento de bicicletas em uma cidade, coletados pela Universidade do Porto.**
