Simulador Tennessee Eastman
==========================================
1) Instalar, compilar
2) Editar arquivo de configuração (pasta 'cfg')
3) rodar: te ../cfg/config1.csv , experimentando várias falhas diferentes = modificar arquivo de configuração
4) Inspecionar resultados: python TE.py

Diagnóstico de Falhas
=================
Experimentar pelo menos dois classificadores diferentes
1) Gaussiano Quadrático (https://scikit-learn.org/stable/modules/generated/sklearn.discriminant_analysis.QuadraticDiscriminantAnalysis.html#sklearn.discriminant_analysis.QuadraticDiscriminantAnalysis)
2) Vizinho-Mais-Próximo (em anexo)

Determinar indicadores de desempenho (Acurária, F-measure, ....), usando validação cruzada 

acurácia

Para experimentar um classificador
tem que ler a saída do simulador ('all.csv')
com a função labelledcsvread
