Projeto: E-Commerce API (Checkout Service)

ID: DEVOPS-421

Prioridade: Alta 🔴

Relator: Tech Lead (Backend)

Título: Falha crítica no pipeline de deploy para Staging

Descrição: Após a migração das credenciais para o cofre de segurança e a atualização das versões de bibliotecas node, nosso pipeline de CI/CD parou de funcionar. O time de desenvolvimento não consegue visualizar o status dos testes e o deploy para o ambiente de Staging (simulado via GitHub Pages) está quebrado.

Critérios de Aceite:

    O pipeline deve rodar automaticamente em cada push para a branch main ou develop.

    A etapa de Testes deve rodar em paralelo para ganhar tempo.

    A etapa de Build só deve ocorrer se os testes passarem.

    O Deploy deve ser disparado apenas na branch main.

    O pipeline deve ser capaz de lidar com as variáveis de ambiente sem expor segredos.