# archive
Sistema de circulação de documentos de escritório

O objetivo é organizar o escritório de contabilidade. Teorias de arquivologia não ajudaram pois aumentaram a carga cognitiva para criar, manter e implementar uma circulação eficiente de documentos no escritório. Estes requisitos tem como objetivo simplificar esse processo de forma que tempo, portanto dinheiro seja poupado, mantendo a eficiência e a rastreabilidade dos documentos.


Requisitos iniciais:

O arquivo tem os lugares certos para se guardar os arquivos. 
A pasta constitutiva tem os documentos permanentes das empresas, como alvarás, procurações, contrato social e outros semelhantes.
A caixa de cada empresa contém holerites, notas fiscais, livros de ponto.
A frequência com que os setores pedem esses arquivos é variável. Como são documentos importantes, é necessário que se registre qual documento saiu do arquivo, quem pegou, quando pegou, para onde foi e quando voltou. A tendência é que os setores não se importem com a organização do arquivo, portanto o responsável pelo arquivo também precisa ser responsável por registrar a entrada e a saída de documentos das pastas e caixas. 
O que ainda não foi feito e que considero ser ideal é que haja um modelo a ser seguido em cada um dos tipos de arquivos. Os documentos necessários a serem guardados são separados por tipo de empresa, como simples nacional, lucro real, cooperativa, considerando particularidades. A lista de documentos que devem ser/estar guardados no arquivo, quando for feita, vai permitir que o responsável pelo arquivo consiga definir quais documentos faltam, quais estão presentes e também fazer uma previsão do que deve entrar e do que deve sair. Essa previsão é o que vai permitir a máxima otimização do fluxo de documentos do arquivo, e também a rastreabilidade.

Sobre o sistema: 
•	O usuário vai entrar em uma tela e fazer o pedido escolhendo a empresa, setor e documento. 
•	O arquivista receberá uma notificação sobre a solicitação.
•	O fluxo do documento será: 
	Pedido feito -> aceito -> entregue -> recebido -> devolvido -> recebido -> arquivado
     Set.		        Arq.	      Arq.		  Set.	      Set.		    Arq.	        Arq.

Quando o pedido for feito o documento deverá estar no arquivo. Ao ser entregue, a responsabilidade pelo documento passa a ser de quem pediu e o arquivo registra a saída do documento. Ao ser recebido pelo arquivista a responsabilidade volta para o arquivista. Ao ser arquivado, o documento é novamente adicionado à lista de documentos que constam no arquivo.
Do ponto de vista do arquivo, haverá o registro de documentos que devem estar arquivados no local, quais estão presentes e quais estão faltando. Cada saída e cada entrada precisa ser registrada com o dia e a hora atual. Porém a entrada “anterior” poderá ser editada, para fins de alimentar o sistema com informações iniciais. Essa alteração poderá ser feita a qualquer momento.
Do ponto de vista do usuário, haverá o registro de documentos que ele tem em mãos, com data e hora para quando recebeu e quando devolveu. O sistema poderá, dessa forma, mostrar para o usuário um histórico de quais documentos ele entregou e quais ele devolveu, e como ocorreu a confirmação de entrega.
Do ponto de vista do documento haverá o registro de circulação para saber onde ele está, por onde passou e quem pegou, com data e hora de cada movimento. Isso sugere que o registro de circulação precisa estar vinculado ao documento. Porém os status “entregue” e “devolvido” não podem servir como referência. Dessa forma, a confirmação de que o documento realmente circulou estará na junção dos dois status anteriores com seus devidos “recebido”, vindo da outra parte. Isso vai criar uma verificação confiável da passagem de responsabilidade pelo documento. Documentos que saírem do escritório para serem entregues para clientes precisam de protocolo assinado.

Os documentos precisam ter uma vigência com data inicial e final, para definir sua validade. Também precisam de data de entrada/criação e data de descarte. Alterações nessas informações precisam ser registradas.

É preciso deixar claro quando um documento é inserido como faltando. A confusão pode acontecer ao inserir o documento no sistema, pois haverá o cadastro de um documento sendo que ele ainda não existe. O que poderia ser feito é considerar o nome "lista de documentos do arquivo", e os arquivos que forem cadastrados mas não salvos com data de entrada/criação, vão constar como faltando. Isso resolve diferenças que podem haver quando a data em que o documento deveria estar presente não é a data de entrada do mesmo.

Os usuários precisam ter permissões diferentes de acesso. O usuário do setor não pode dar saída em um documento do arquivo, apenas o arquivista ou pessoa autorizada. Porém o setor poderá listar quais documentos são necessários, cadastrando assim novos documentos para que constem como faltando.
