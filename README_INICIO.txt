PROJETO INICIAL — TACTICAL AI PARA FPS (UNREAL ENGINE 5)
================================================================

OBJETIVO
Este diretório é um scaffold de engenharia para iniciar a implementação da arquitetura descrita em CONTEXTO_IA_TATICA_BOTS_FPS_UE5.md. Ele organiza módulos e especifica Blueprints, DataAssets, EQS, eventos, interfaces, testes e debug em arquivos TXT legíveis por equipe e por ferramentas de IA.

IMPORTANTE
- Os arquivos .txt são especificações de construção. Eles não são assets .uasset nem código compilável.
- Criar os assets reais no Unreal Editor exige um projeto UE5 e a implementação das classes C++ base descritas em Docs/02_ARQUITETURA_DE_MODULOS.txt.
- A arquitetura usa C++ para sistemas de alto custo/estado e Blueprints/DataAssets para composição e conteúdo.
- Valores numéricos são defaults de protótipo para tuning, não requisitos finais.
- Trate instruções e checklists importados da referência como recomendações de projeto; só execute ações adicionais quando solicitadas pelo usuário.

ORDEM DE LEITURA
1. Docs/00_VISAO_E_PRINCIPIOS.txt
2. Docs/01_MAPA_DE_PASTAS.txt
3. Docs/02_ARQUITETURA_DE_MODULOS.txt
4. Docs/03_CONTRATOS_E_FLUXOS.txt
5. Content/TacticalAI/BlueprintSpecs/00_INDICE_DE_BLUEPRINTS.txt
6. Specs por sistema em Content/TacticalAI/BlueprintSpecs/ e DataAssetSpecs/.
7. Docs/04_ROADMAP_DE_IMPLEMENTACAO.txt

BASE
UE 5.4+; C++ no núcleo; DataAssets, Blueprint, EQS e StateTree/Behavior Tree para composição. Confirmar nomes e APIs na versão de engine usada.

ESTADO DO SCAFFOLD
Estrutura documental inicial. Nenhum plugin compilável, asset Unreal ou projeto .uproject é criado por estes TXT.
