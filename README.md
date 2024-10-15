## About Dataset

### Context

O objetivo principal é usar esses dados para prever quanta impureza há no concentrado de minério. Como essa impureza é medida a cada hora, se pudermos prever quanta sílica (impureza) está no concentrado de minério, podemos ajudar os engenheiros, dando-lhes informações antecipadas para tomar ações (capacitando!). Assim, eles poderão tomar ações corretivas com antecedência (reduzir a impureza, se for o caso) e também ajudar o meio ambiente (reduzindo a quantidade de minério que vai para os rejeitos à medida que você reduz a sílica no concentrado de minério).

### Content

A primeira coluna mostra o intervalo de datas e hora (de março de 2017 a setembro de 2017). Algumas colunas foram amostradas a cada 20 segundos. Outros foram amostrados de hora em hora.

A segunda e a terceira colunas são medidas de qualidade da polpa de minério de ferro antes de ser alimentada na planta de flotação. A coluna 4 até a coluna 8 são as variáveis mais importantes que impactam na qualidade do minério no final do processo. Da coluna 9 até a coluna 22, podemos ver os dados do processo (nível e fluxo de ar dentro das colunas de flotação, que também afetam a qualidade do minério). As duas últimas colunas são a medição final da qualidade da polpa de minério de ferro do laboratório.
O objetivo é prever a última coluna, que é a % de sílica no concentrado de minério de ferro.

## Folder organization

### Code

Contém o *Jupyter Notebook* desenvolvido para o case.

### html

Diretório para os gráficos gerados no formato *.html* para manter a interatividade.