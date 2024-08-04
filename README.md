# PLN_2024_Silva_Any

1) Escolha um conjunto de dados disponível nos links a seguir que contenha no mínimo 10.000 registros. Consulte
a lista de conjuntos de dados já escolhidos pela turma para certificar-se de que o conjunto por você selecionado ainda não foi escolhido. Inclua o nome do conjunto de dados e a url de acesso na thread disponibilizada no Google Classroom da disciplina
para esta finalidade.

https://dadosabertos.bcb.gov.br/dataset

https://www.tesourotransparente.gov.br/ckan/dataset

2) Escolha um dos modelos disponíveis no Hugging Face utilizando os filtros “sentence-tranformers” e “portuguese” para
que este modelo seja utilizado para a criação dos embeddings.

3) Utilize o modelo selecionado para converter o conjunto selecionado para embeddings.

4) Instale um banco de dados vetorial (por exemplo, Milvus ou Chroma) e armazene os embeddings criados neste banco.

Consulte uma lista de bancos de dados vetoriais na url abaixo:

https://medium.com/google-cloud/vector-databases-are-all-the-rage-872c888fa348

5) Utilize uma estrutura de índice no banco de dados vetorial para fazer consultas aos registros armazenados no banco usando recursos de similaridade semântica. Crie um cenário da necessidade de busca por registros para atender alguma necessidade específica e que exemplifique o uso da similaridade semântica como uma alternativa mais efetiva que uma consulta em um banco de dados tradicional.

Passo a passo:
1. Escolher o dataset e o modelo
2. Criar repositório com a máquina virtual e a lista de bibliotecas necessárias no requirements.txt.
3. Configurar o ambiente para usar a máquina virtual como kernel
3. Instalar as bibliotecas com pip install -r requirements.txt
4. Resolver problema com o sentence_transformers na instalação do Visua Studio https://visualstudio.microsoft.com/pt-br/vs/features/cplusplus/
5. Buscar formas de concatenar o texto como uma única sentença
