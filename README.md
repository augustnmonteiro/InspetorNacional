# Inspetor Nacional

## Introdução

O Inspetor Nacional é um projeto de código aberto que visa oferecer uma plataforma para visualização e análise de métricas governamentais e de saúde pública no Brasil. O projeto tem como objetivo fornecer informações precisas e atualizadas sobre diversas métricas, como preços de energia, água, gasolina, alimentos, bem como dados de saúde, como casos de COVID-19, gripe, dengue, entre outros. Além disso, o sistema pretende criar um novo índice de inflação em tempo real, baseado nos valores coletados e processados.

## Metas

- **Meta 1**
  - Pegar métricas usando sites de supermercados para gerar métrica de aumento de preços
  - Pegar dados de preço de energia/água/gás de fontes seguras
  - Pegar dados de preço de gasolina/etanol
  - Gerar um índice baseado nessas métricas
  - O sistema deve mostrar gráficos com dados diários
  - Um bot vai 1 vez ao dia pegar todos os dados e atualizar o banco de dados
  - Um bot vai postar um resumo no Telegram e no Twitter

- **Meta 2**
  - Adicionar a possibilidade dos usuários adicionarem problemas como buracos nas estradas, problemas de infraestrutura
  - O sistema vai registrar quando o problema foi reportado pela primeira vez e quanto tempo demorou para corrigirem o problema

- **Meta 3**
  - Possibilidade dos usuários reportarem coisas como falta de medicamentos/vacinas/médicos
  - Métricas de saúde como nascimentos, óbitos, casos de gripe, dengue, entre outros

- **Meta 4**
  - Métricas sobre políticos de Presidente a vereador
  - As métricas precisam ser métricas objetivas

## Visão

O Inspetor Nacional tem como visão se tornar um lugar onde os cidadãos podem reportar problemas e saber quanto tempo levou para ser corrigido, tudo isso pode ser usado pelos governantes para fazer um governo mais assertivo e usar esses dados para ajudar no seu governo. Ter dados em tempo real sobre o governo e índices em tempo real o mais próximo possível da realidade. O índice inflacionário será criado utilizando os valores da: energia/aumento de produtos nos supermercados/água/gás/dólar/iene/euro.

Como podemos perceber, este é um projeto gigante, pois garantir que todos esses dados são válidos é uma missão muito difícil, mas possível.

## Como Contribuir

Contribuições para o projeto são bem-vindas e podem ser feitas de várias formas:

- Adicionando novas funcionalidades
- Corrigindo bugs e problemas de desempenho
- Melhorando a interface do usuário
- Contribuindo com dados e informações relevantes

Para contribuir, siga os passos abaixo:

1. Faça um fork do repositório
2. Crie uma branch para a sua contribuição: `git checkout -b minha-contribuicao`
3. Faça as alterações necessárias
4. Faça o commit das suas alterações: `git commit -m 'Minha contribuição'`
5. Faça o push para o seu fork: `git push origin minha-contribuicao`
6. Abra um pull request para a branch principal do projeto

## Contato

Todas as questões, sugestões e problemas devem ser registrados como issues no [repositório do GitHub](https://github.com/augustnmonteiro/InspetorNacional/issues).

## Licença

O Inspetor Nacional é licenciado sob a [Licença MIT](https://opensource.org/licenses/MIT), o que significa que você pode usar, copiar, modificar, mesclar, publicar, distribuir, sublicenciar e/ou vender cópias do software, sob certas condições.
