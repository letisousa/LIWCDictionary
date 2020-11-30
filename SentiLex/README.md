# SentiLex

### SentiLex-lem-PT02.txt
Cada linha inclui informações sobre:
- Lema (convencionalmente, a forma masculina singular para adjetivos, a forma singular para substantivos que são flexionados para número e a forma infinitiva 
  para verbos e expressões idiomáticas),
- Part-of-speech (ADJ(adjetijo), N(substantivo), V(verbp) e IDIOM(~entendo que seja uma expressão~), e
- Atributos de sentimento:
  * Polaridade (POL), que pode ser positiva (1), negativa (-1) ou neutra (0);
  * Alvo de polaridade (TG), que corresponde a um substantivo humano (HUM), funcionando como sujeito (N0) e / ou complemento (N1) do predicado;
  * Anotação de polaridade (ANOT), que foi realizada manualmente (MAN) ou automaticamente, pela ferramenta Judgment Analysis Lexicon Classifier (JALC), 
    desenvolvida pela equipe do projeto.
  * Algumas entradas também incluem um código adicional (REV), que se refere a notas específicas incluídas pelo anotador. Neste ponto, podemos encontrar as 
    seguintes notações:
- REV = AMB, o que significa que a entrada é ambígua com outras palavras transmitindo polaridades diferentes, e
- REV: POL, o que significa que o código de polaridade atribuído anteriormente à entrada em SentiLex-PT01 foi revisado.

Abaixo estão cinco entradas de SentiLex-lem-PT02.txt:

	aberração.PoS = N; TG = HUM: N0; POL: N0 = -1; ANOT = MAN
	bonito.PoS = Adj; TG = HUM: N0; POL: N0 = 1; ANOT = MAN
	castigado; PoS = Adj; TG = HUM: N0; POL: N0 = -1; ANOT = JALC
	estimado.PoS = Adj; TG = HUM: N0; POL: N0 = 1; ANOT = JALC; REV = AMB
	enganar.PoS = V; TG = HUM: N0: N1; POL: N0 = -1; POL: N1 = 0; ANOT = MAN
	engolir em seco.PoS = IDIOM; TG = HUM: N0; POL: N0 = -1; ANOT = MAN

### SentiLex-flex-PT02.txt
- Em cada linha, as formas flexionadas são associadas a seu lema correspondente. Além das informações linguísticas descritas no dicionário de lemas, cada 
  adjetivo e substantivo é classificado de acordo com sua inflexão (FLEX) em gênero (masculino(m) ou feminino(f)) e número (singular(s) ou plural(p)); 
- Os atributos morfológicos que caracterizam verbos e expressões idiomáticas correspondem a tempo, pessoa e número. As formas flexionadas e os atributos 
  correspondentes foram extraídos automaticamente do LABEL-LEX-sw.

Abaixo estão dez entradas de SentiLex-flex-PT02.txt:

	aberração, aberração.PoS = N; FLEX = fs; TG = HUM: N0; POL: N0 = -1; ANOT = MAN
	bonita, bonito.PoS = Adj; FLEX = fs; TG = HUM: N0; POL: N0 = 1; ANOT = MAN
	bonitas, bonito.PoS = Adj; FLEX = fp; TG = HUM: N0; POL: N0 = 1; ANOT = MAN
	bonito, bonito.PoS = Adj; FLEX = ms; TG = HUM: N0; POL: N0 = 1; ANOT = MAN
	bonitos, bonito.PoS = Adj; FLEX = mp; TG = HUM: N0; POL: N0 = 1; ANOT = MAN
	engoliste em seco, engolir em seco.PoS = IDIOM; Flex = J2p | J2s; TG = HUM: N0; POL: N0 = -1; ANOT = MAN
	engolistes em seco, engolir em seco.PoS = IDIOM; Flex = J2p; TG = HUM: N0; POL: N0 = -1; ANOT = MAN
	engoliu em seco, engolir em seco.PoS = IDIOM; Flex = J4s | P3s; TG = HUM: N0; POL: N0 = -1; ANOT = MAN
	engulam em seco, engolir em seco.PoS = IDIOM; Flex = Y4p | S4p | S3p; TG = HUM: N0; POL: N0 = -1; ANOT = MAN
	engulamos em seco, engolir em seco.PoS = IDIOM; Flex = Y1p | S1p; TG = HUM: N0; POL: N0 = -1; ANOT = MAN

Quantidade de dados: lem - 7014 termos; flex - 82347 termos;
