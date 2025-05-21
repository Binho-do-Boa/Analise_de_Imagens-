# Analise_de_Imagens-
Projeto de Análise de Imagens (Folhas de Feijão)
Problema: Identificar automaticamente se uma folha está saudável ou apresenta sintomas de doenças específicas, como ferrugem ou manchas bacterianas em culturas como milho, soja, feijão.
Justificativa: Doenças em plantas causam perdas globais significativas $$$, a detecção precoce é crucial para mitigar danos, aumentar a produção e baixar o custo com fertilizantes e outros insumos.
Dados Usados: Fotos das plantas com e sem doenças, foram usados 2 Datasets PlantVillage do Keggle, fiz a combinação de duas bases para ter mais imagens que totalizou 6.135 assim distribuídas: com Ferrugem 2095; com Mancha angular 2099 e  Saudável 1941. Nessa base de dados já está separa três pasta (Treinamento, Validação e Teste) com suas respectivas classes
Classes: Mancha angular, Ferrugem, Saudável.
Modelo Usado: Transfer Learning Mobilenet-v2.
Usei uma API Flask em conjunto com Ngrok, para fazer os testes fazendo upload de uma imagem que pode ser coletada em campo, o modelo processa e da resposta (predict) com percentual de confiança por classe.
Fiz todos esses testes em campo e usei o GoogleColab para desenvolvimento e processamento. 
