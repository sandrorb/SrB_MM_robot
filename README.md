# SrB_MM_robot

Sugestões são bem-vindas.

This is a EA software (robot) written in MQL5 to execute my MM setup on mini index Bovespa Brazil. It is a prototype project and it is not intended to be used in real accounts. It is just for demo accounts and for didactic purpose.

Sandro Roger Boschetti assumes no responsibility whatsoever for its use by other parties, and makes no guarantees, expressed or implied, about its quality, reliability, or any other characteristic.

Este robô faz operações de compra e venda no mercado financeiro. Foi implementado para operar de forma autônoma o método MM no mini-índice Bovespa no tempo gráfico de 15 minutos entre 9h e 12h.

O método MM é uma variante do método Máximas e Mínimas aprendido com o Alexandre Wolwacz (Stormer). É um método que opera explorando a volatilidade do mercado e não tendência. Possui dois stops, um no preço (stop gain na máxima do candle anterior) e outro no tempo, que pode ser tanto no gain quanto no loss e ocorre no fechamento do candle atual que originou a compra na mínima no candle anterior.

ATENÇÃO: é um protótipo de software em fase de testes e não deve ser usado em conta real. OS RESULTADOS de backtests e forward tests parecem incongruentes e tanto o método quanto os testes e simulações precisam ser revistos. Talvez o método precise de um filtro.

Belo Horizonte, Oct, 17, 2020

Sandro Roger Boschetti
