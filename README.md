# Call Center Power BI Dashboard

Un dashboard creado en Power BI, con funciones DAX, que permite visualizar el resultado de los KPI's de call center más importantes para el negocio.

![image](https://github.com/iamsanbarb/CallCenterDashboard/assets/67486683/a3b5c919-dbea-4307-9ed5-67f4c2bca4fa)

## Utilidad del dashboard

Este dahboard permite conocer los resultados del trabajo de dos colaboradores de call center desde la implementación de un CRM. Ayuda a identificar las virtudes y debilidades de cada uno, cuál es la efectividad de ambos, cuál es el tipo de clientes al que más se contacta y qué clientes son los que responden.

### Página : Resumen
En esta página se muestra un resumen de todos los KPI's más importantes para gerencia general. Estos son:

1) Total de llamadas: Indica la cantidad de llamadas realizadas en conjunto dentro del intervalo de tiempo analizado.

![Captura de pantalla 2024-07-09 201450](https://github.com/iamsanbarb/CallCenterDashboard/assets/67486683/fc2c52f0-da25-455a-91d4-34a1256849d2)

2) Promedio llamadas diarias: Indica el promedio de llamadas realizadas en conjunto día a día dentro del intervalo de tiempo analizado.

![Captura de pantalla 2024-07-09 201827](https://github.com/iamsanbarb/CallCenterDashboard/assets/67486683/4be1d18b-cbbc-4d27-b900-1d0417d9a405)

**Nota: Los KPI's 1) y 2) se miden respecto a la _cantidad de llamadas_, las cuales llevan la siguiente fórmula:**

$Cantidad De Llamadas = [Cantidad de Llamadas atendidas] + [Cantidad de Llamadas no atendidas] + [Cantidad de llamadas rechazadas]$

3) Ratio conversión: Indica el porcentaje de clientes que agendaron una cita.

$Tasa De Conversion =\frac{[Cantidad De Contactos Efectivos]}{[Cantidad De Llamadas Atendidas]}$

![image](https://github.com/iamsanbarb/CallCenterDashboard/assets/67486683/9a358feb-b831-4230-9e0e-6e0e5dba4fb7)

4) Ratio contactabilidad: Indica el porcentaje de llamadas que han sido atendidas.

$Tasa De Contactabilidad =\frac{[Cantidad De Llamadas Atendidas]}{[Cantidad De Llamadas]}$

![image](https://github.com/iamsanbarb/CallCenterDashboard/assets/67486683/ab1c4d82-a917-4614-8009-506d81f0b738)

5) Ratio Rechazo: Indica el porcentaje de llamadas que no han sido respondidas.

$Tasa De Rechazo =\frac{[Cantidad De Llamadas Rechazadas]}{[Cantidad De Llamadas]}$

![image](https://github.com/iamsanbarb/CallCenterDashboard/assets/67486683/8f659375-a531-44ac-ac17-2750868e8bc6)

6) Ratio Directos: Indica el porcentaje de llamadas que han sido atendidas por el mismo cliente.

$Tasa De Contactos Directos = \frac{[Cantidad De Contactos Directos]}{[Cantidad De Llamadas Atendidas]}$

![image](https://github.com/iamsanbarb/CallCenterDashboard/assets/67486683/0a08653a-e050-4ac7-85f8-97905449ad38)

7) Ratio Indirectos: Indica el porcentaje de llamadas que han sido atendidas por alguien que no es el mismo cliente.

$Tasa De Contactos Indirectos = \frac{[Cantidad De Contactos Indirectos]}{[Cantidad De Llamadas Atendidas]}$

![image](https://github.com/iamsanbarb/CallCenterDashboard/assets/67486683/0f5b35f5-82a1-4a28-96ac-bfea307fc15e)

8) *Gráfico - Cantidad de llamadas por responsable:* Comparativa de la cantidad de llamadas realizadas por cada colaborador dentro del intervalo de tiempo analizado.

![image](https://github.com/iamsanbarb/CallCenterDashboard/assets/67486683/57d7a9a5-e777-45fd-b919-f18d2ac0eb68)

9) *Gráfico - Cantidad de llamadas atendidas por responsable:* Comparativa de la cantidad de llamadas atendidas que tiene colaborador dentro del intervalo de tiempo analizado.

![image](https://github.com/iamsanbarb/CallCenterDashboard/assets/67486683/025366be-1b82-497e-a700-3e8eaac2f848)

10) *Gráfico - Ratio contactabilidad:* Comparativa del ratio de contactabilidad que tiene colaborador dentro del intervalo de tiempo analizado.

![image](https://github.com/iamsanbarb/CallCenterDashboard/assets/67486683/3d7bea1f-d80c-4d40-9111-3522fb702ef4)

11) *Gráfico - Ratio conversión:* Comparativa del ratio de conversión que tiene colaborador dentro del intervalo de tiempo analizado.

![image](https://github.com/iamsanbarb/CallCenterDashboard/assets/67486683/4ffb5535-377b-4ee0-a21f-9397ed298e42)
