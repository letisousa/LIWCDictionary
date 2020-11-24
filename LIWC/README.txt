>> O LIWC é um software de análise de texto que calcula o grau de uso de diferentes categorias de palavras em uma ampla variedade de textos.
	http://www.liwc.net/

>> Basicamente, ele lê um determinado texto e conta a porcentagem de palavras que refletem diferentes emoções, estilos de pensamento, preocupações sociais e até
mesmo classes gramaticais.Como o LIWC foi desenvolvido por pesquisadores com interesses em psicologia social, clínica, saúde e cognitiva, as categorias de linguagem
foram criadas para capturar os estados sociais e psicológicos das pessoas.

>> O dicionário identifica quais palavras estão associadas a quais categorias psicologicamente relevantes.

>> Depois que o módulo de processamento lê e contabiliza todas as palavras em um determinado texto, ele calcula a porcentagem do total de palavras que correspondem
a cada uma das categorias do dicionário. Por exemplo, se o LIWC analisou um único discurso de 2.000 palavras e as comparou com o dicionário integrado do LIWC2015, 
pode descobrir que foram usados ​​150 pronomes e 84 palavras de emoção positiva. Ele converteria esses números em porcentagens, 7,5% de pronomes e 4,2% de palavras de 
emoção positiva.

>> Enquanto o módulo de análise de texto identifica e categoriza palavras, o coração do programa é um grupo de dicionários que informam ao módulo de análise de texto 
quais palavras identificar e classificar.

>> Para cada palavra do dicionário, há uma entrada de dicionário correspondente que define uma ou mais categorias de palavras. Por exemplo, a palavra chorou faz parte 
de cinco categorias de palavras: Tristeza, Emoção negativa, Afeto geral, Verbo e Foco no passado. Conseqüentemente, se a palavra chorado fosse encontrada no texto de 
destino, cada uma dessas cinco pontuações na escala do subdicionário seria incrementada. Todas as palavras de tristeza, por definição, serão categorizadas como emoção 
negativa e palavras de afeto geral.

>> RESUMO: 
	Primeira parte: cada número associado a uma categoria;
	Segunda parte: cada palavra associada as categorias as quais pertence.

>> Quant. conteúdo: 127.161 palavras; 64 classificações; (quantidade de palavras para cada classificação no arquivo jupyter);

>> Fontes:
	http://liwc.wpengine.com/how-it-works/
	http://www.languageinquiry.com/LIWC2007LanguageManual.pdf