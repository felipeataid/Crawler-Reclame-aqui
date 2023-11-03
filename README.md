# Crawler-Reclame-aqui
# Este é um crawler que te ajudará a extrair dados de algumas empresas do Reclameaqui.

# Essa aplicação disponibiliza duas funções diferentes, a primeira é para a situação das empresas, e a segunda é para colher as reclamações.

# Para o uso da mesma é imprescindível que seja passado o cabeçalho da requisição, nesse caso é o User-Agent do navegador e sempre lembrar de deixá-lo atualizado.

# Caso faça requisições pelo Google Chrome igual a mim, você pode abri-lo e escrever na barra de pesquisa "My User Agent", e o seu User Agent aparecera.
# Após isso é só copiar e inseri-lo no código.

# Detalhes de cada função:
# 1. A função situacao() te ajudará a colher as informações das situações da empresa no periodo disponível pelo RA que costuma ser dos ultimos 6 meses, 12 meses, ano passado, ano retrasado (atual) e o Geral.
# 1.1 O Crawler criar um dicionário e adicionrá as informações como a Nota (caso tenha), reclamações totais, as respondidas, data inicial e data final do periodo e por fim o titulo dado de acordo com a nota da empresa no RA. 
# 1.2 Após percorrer tudo, ele salvará os dados da situação em um arquivo CSV que o usuário poderá escolher o nome do mesmo.

# 2. Já a função reclamacoes() percorrerá por todas as reclamações de acordo com a empresa que o usuario passar deixando algumas funções personalizadas.
# 2.1 O Crawler criará um dicionário e adicionará as informações de cada reclamação, como o texto, titulo, link, há quanto tempo foi feita a reclamação e qual é o status dela (Respondida, Não respondida, Resolvida...)
# 2.2 O usuário poderá passar qual empresa ele deseja extrair as reclamações, o intervalo de tempo (EM SEGUNDOS) das requisições em cada página e qual será o nome do arquivo em que será salvo.
# 2.3 Após percorrer tudo, ele salvará os dados salvos das reclamações em um arquivo CSV que o usuário poderá escolher o nome do mesmo.

# Código explicado, agora é só salvar e usá-lo. :D
