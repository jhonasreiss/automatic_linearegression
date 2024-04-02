Esse software foi desenvolvido com a função de ajudar os usuários que usam regressão linear para economizar tempo, facilitando assim a vida dos usuários.


=======================================================================================

POR QUE NESSE FORMATO?
- escolhi o formato .ipynb porque a plotagem é mais amigavel
- isso não impede de copiar e colar o código no formato .py

OBS: ao executar o script no formato ipynb certifique-se de quando executar pela segunda vez comentar o trecho 'app = QApplication()'


========================================================================================

COMO FUNCIONA?
- Ao executar o software aparecerá a tela de carregamento
- após o carregamento a interface irá aparece

- clique em 'carregar dados' para carregar o arquivo (.xlsx)
- e depois clique em 'selecionar coluna'

- o software foi programado para detectar as colunas dentro da planilha
- escolha a coluna independente e a coluna dependente
obs: ao clicar irá aparecer no display no canto inferior direito a coluna selecionada

- depois clique em aplicar
- se você sabe que a coluna em que escolheu possui dados faltando (Nan ou None)
- escolha no dropdown da interface principal o método de imputação

- caso queira colocar um título no seu gráfico preencha o campo 'título do gráfico' na interface principal
- o xlabel e o ylabel já são preenchidos automáticamente usando o nome das colunas

- ao final clique em 'plotar'

======================================================================================


OBS: o software ainda está em desenvolvimento faltando adicionar as funcionalidades de:
- rotular
- normalizar / scaler
- tratamento de erro
