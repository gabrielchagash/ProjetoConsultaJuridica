# ProjetoConsultaJuridica
 
O projeto consiste em automatizar o processo de consultas jurídicas em sites utilizando a biblioteca Selenium, webdriver. Importando a base de dados através do pandas e através disso, poder abrir uma página na internet automatizada, movendo e clicando com o mouse, escrevendo nos campos e depois criar uma planilha em excel com os Processos atualizados.

Através disso utilizei também a biblioteca Time para esperar o resultado da pesquisa e agir de acordo com o resultado, juntamento com um while true, para agir de acordo com o resultado. O if é para o alerta que aparece na tela de acordo com a pesquisa e através disso agir de acordo com o alerta que aparecer e também automatizar esse processo.

Após a pesquisa feita de forma automática, uso um navegador.quit() para fechar a tela e depois visualizar o dataframe final com os resultados da pesquisa.
