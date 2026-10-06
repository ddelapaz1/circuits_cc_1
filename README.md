# Circuits de corrent continu

Aplicació web per a l'alumnat de 1r d'EEB0 (Automatització i Robòtica Industrial) per practicar circuits mixtos de corrent continu.

- Genera un circuit amb una font de tensió contínua i entre 4 i 10 resistències etiquetades (R1, R2…) amb valors comercials, connectades de forma mixta: trams en sèrie, grups en paral·lel i agrupacions niades (sèrie dins de paral·lel dins de sèrie…).
- L'alumnat ha de calcular la resistència equivalent, la intensitat total, la caiguda de tensió, la intensitat i la potència de cada resistència, i la potència total subministrada per la font.
- Amb el botó **Resoldre** fa una resolució guiada pas a pas: reducció del circuit de dins cap a fora (amb l'esquema equivalent a cada pas), intensitat total, repartiment de tensions i intensitats de fora cap a dins (amb comprovació de les lleis de Kirchhoff), potències i balanç de potències.
- Permet comprovar les respostes (marge del 2 %) i avisa si un valor sembla escrit en mA, kΩ o mW.
- Es pot triar el nombre de resistències: 4–5, 6–7, 8–10 o qualsevol.
- Cada exercici té un codi (p. ex. `CC-6-4821`: 6 resistències, llavor 4821) perquè tota la classe pugui fer el mateix. El codi també queda a l'adreça (`index.html#CC-6-4821`), i el botó **Copia l'enllaç** permet compartir-lo.

## Ús

És un únic fitxer: obre `index.html` en qualsevol navegador. No cal instal·lar res.
