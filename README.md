# Cron
É uma ferramenta de sistemas que permite a execução de comandos ou programas, agendados para um determinado dia/mês/ano/hora.

**Obs**: cada usuário tem o seu cron, incluindo o **root**

## Editando o Cron
Utilize o comando:

`crontab -e`

Exemplo de formato:

| minutos | horas | dia do mês | mês | dia da semana | comando a ser executado |
|---------|-------|------------|-----|---------------|-------------------------|
|   */5   |   *   | *          | *   | *             | comando                 |

\* (a todo minuto/horas/dia do mês/mês/dia da semana)

*/x (a cada x minutos/horas)

dia do mês (de 1 a 31)

mês (de 1 a 12)

dia da semana (de 0 a 7, onde 0 e 7 é domingo)

No exemplo acima será executado o comando a cada 5 minutos

## Listando o Cron
Utilize o comando:

` crontab -l`