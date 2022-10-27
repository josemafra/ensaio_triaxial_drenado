# ensaio_triaxial_drenado
Ensaio de compressão triaxial consolidado drenado em solo - (consolidated drained triaxial test)
Este script recebe os arquivos de dados de laboratório referentes à moldagem, saturação (percolação e contrapressão), adensamento isotrópico e da fase de cisalhamento. Processa os cálculos necessários à interpretação do ensaio e à definição dos parâmetros de resistência do solo. São apresentadas as curvas: tensão versus deformação axial, deformação volumétrica versus deformação axial, poropressão versus deformação axial, trajetória de tensões, envoltórias de resistência (máxima tensão de desvio) e o gráfico com os Circulos de Mohr.

Para cada corpo de prova do ensaio, devem ser preparados os arquivos de dados. São fornecidos: arquivo com os dados da fase de moldagem e arquivo com dados da fase de cisalhamento, ambos no formato .csv. Após o processamento, o script gera os arquivos com os dados calculados, que podem ser exportados para o Excel. Para todas as fases do ensaio, são geradas tabelas formatadas, constantes no script, que podem ser copiadas e levadas para os relatórios técnicos.
Para o traçado da envoltória dos Círculos de Mohr, deverão ser fornecidos os valores de c (coesão) e phi (ângulo de atrito) até ajustar a melhor reta tangente aos círculos de Mohr. Deverá, também, ser fornecido o valor de sig para ajustar a envoltória no intervalo de tensões do ensaio. As instruções estão no item Traçado da Envoltória de Mohr-Coulomb.

Preparado por: Eng. José Mário Queiroga Mafra

Outubro/2022
