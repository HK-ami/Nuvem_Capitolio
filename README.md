# Nuvem_Capit-lio
Nuvem de Palavras sobre "US Capitol" no Twitter usando Knime  
Usando a API do Twitter, foi feita uma busca por "US Capitol" nos 100 tweets mais relevantes, usando um critério misto de mais recentes e mais populares, seus textos foram analisados com os seguintes passos:
  Informações dos tweets foram convertidos para documento de texto
  Foram removidos campos nulos
  Foi filtrada a coluna de "tweet", indexada por "user_name"
  Foram atribuídas classes gramaticais e identificados nomes de entidades (pessoas) para as palavras dos textos
  Às palavras caetgorizadas, foram associados sentimentos Negativos e Positivos de acordo com o dicionário de termos utilizado (MPQA Corpus)
  Stopwords foram removidas
  Caracteres foram convertidos para minúsculo
  Raízes das palavras forame extraídas
  Documento foi quebrado em palavras
  A frequencia com que as palavras aparecem foi computada
