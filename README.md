Projeto: E-Commerce "FastShop" – Microserviço de Inventário ID: DEVOPS-442 Relator: Squad de Backend Prioridade: Alta

Título: Automatização do Pipeline de CI e Deploy em Staging (Falhando)

Descrição: Olá, time de DevOps. Migramos o repositório do serviço de inventário para o GitHub e tentamos configurar uma Action para automatizar os testes e o build da imagem Docker. No entanto, a pipeline está quebrando e não conseguimos identificar o motivo.

Além disso, o PO solicitou que a imagem Docker só seja gerada se os testes passarem, e precisamos que o artefato final seja tagueado com o hash do commit para rastreabilidade.

Critérios de Aceite:

    A pipeline deve rodar em todo push para a branch main.

    Deve executar testes unitários (Node.js).

    Deve realizar o build da imagem Docker.

    Desafio: Corrigir os erros de sintaxe e lógica que impedem a execução.

    Melhoria: Garantir que o build do Docker dependa do sucesso dos testes.