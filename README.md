# Doar: Comunidade Interativa de Doações e Recolhimentos em Biguaçu

## Descrição

O Doar é uma plataforma que visa facilitar a conexão entre pessoas que desejam doar roupas, móveis, alimentos e oferecer serviços com aqueles que necessitam desses recursos na região de Biguaçu, Santa Catarina. Este projeto busca construir uma comunidade solidária e eficiente, otimizando o processo de doação e promovendo o apoio mútuo.

## Utilização da Inteligência Artificial (Gemini)

Este projeto utiliza a API do Gemini para aprimorar a experiência do usuário e a eficácia da plataforma através dos seguintes agentes inteligentes:

* **Agente de Matching de Necessidades:** Analisa as ofertas de doação e as necessidades expressas pelos usuários para encontrar as correspondências mais relevantes de forma semântica, considerando o contexto da localização.
* **Agente Redator de Conexão:** Gera mensagens curtas e diretas para facilitar o contato entre doadores e pessoas necessitadas, incentivando a ação e a concretização da doação ou da oferta de serviço.

## Demonstração (Protótipo Simplificado com Gemini)

O código presente neste repositório demonstra um dos casos de uso da IA no Doar: a funcionalidade de matching inteligente e a geração de mensagens de conexão. Ao executar o script Python (`main.py` ou similar), você verá uma simulação onde ofertas de doação são processadas para encontrar as necessidades correspondentes em uma lista predefinida, com o Gemini gerando uma breve mensagem para conectar as partes.

**Para executar a demonstração (requer a biblioteca `google-generativeai` e uma API Key do Gemini configurada):**

1.  Certifique-se de ter a biblioteca instalada: `pip install google-generativeai`
2.  Configure sua API Key do Gemini como uma variável de ambiente (`GOOGLE_API_KEY`).
3.  Execute o script Python principal.

A saída mostrará as ofertas, os matches encontrados pela IA e as sugestões de mensagens para conectar doadores e necessitados.

## Protótipo Visual (Figma)

O protótipo visual da plataforma Doar, criado no Figma, pode ser acessado através do seguinte link:

[App Doar - Projeto Imersão Alura - IA Gemini](https://www.figma.com/design/letmRKxfjrFzu2zDhJeFcB/App-Doar---Projeto-Imers%C3%A3o-Alura---IA-Gemini?node-id=8-2&t=UA70G5gVl0I6ZsW0-1)

Este protótipo ilustra a interface do usuário, o fluxo de publicação de doações e necessidades, a visualização das ofertas e a interação entre os membros da comunidade.

## Documentação (Notion)

A documentação detalhada do projeto Doar, incluindo o planejamento, os casos de uso da IA, a arquitetura proposta e outras informações relevantes, está disponível no Notion:

[Imersão ALURA IA](https://www.notion.so/Imers-o-ALURA-IA-1f5755165b558041b680d6b64032d5b2?pvs=4)

## Próximos Passos (Visão Futura)

Embora este protótipo e demonstração foquem em um aspecto da IA, a visão futura do Doar inclui:

* Implementação completa da plataforma web ou mobile.
* Integração de um sistema de notificações para alertar sobre novas doações e necessidades relevantes.
* Expansão para incluir outros tipos de apoio comunitário.
* Potencial integração com ferramentas de busca local para facilitar a descoberta de recursos adicionais.
