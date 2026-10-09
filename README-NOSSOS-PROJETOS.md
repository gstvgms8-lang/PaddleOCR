# PaddleOCR: aplicações nos nossos sistemas

Documentação complementar de gstvgms8-lang, preparada em 09/10/2026 para estudo. As aplicações abaixo são propostas de avaliação, não funcionalidades já integradas aos nossos sistemas.

[Repositório original](https://github.com/PaddlePaddle/PaddleOCR) · [Nosso fork](https://github.com/gstvgms8-lang/PaddleOCR) · [README oficial](https://github.com/PaddlePaddle/PaddleOCR/blob/main/README.md) · [Documentação](https://www.paddleocr.com) · [Biblioteca](https://github.com/gstvgms8-lang/referencias-projetos)

## Finalidade

**Área:** Extração de texto.

Toolkit de OCR e análise de documentos para extrair texto e estruturas de imagens e PDFs.

## Possíveis aplicações

- Pesquisar captura de textos de etiquetas, comprovantes e documentos recebidos.
- Avaliar extração assistida de campos para preencher formulários, mantendo conferência humana.
- Comparar resultados em português e em tabelas com um conjunto representativo de documentos.

## O que avaliar antes de integrar

- Escolher o modelo e a configuração adequados; não extrapolar métricas publicadas para nossos documentos.
- Avaliar requisitos de CPU/GPU, tamanho dos modelos, tempo de processamento e licenças dos modelos e dependências.
- Usar amostras anonimizadas e definir privacidade, retenção e revisão de erros antes de enviar documentos a qualquer serviço.

## Estado e próximos passos

O fork é uma referência para estudo e documentação. Nenhum pacote, skill, serviço ou integração foi instalado em nossos aplicativos nesta organização. A próxima etapa exige escolher o projeto-alvo, registrar requisitos e critérios de aceitação e avaliar uma prova de conceito isolada. Mudanças futuras devem preservar funcionalidades atuais e passar por revisão e testes de regressão.

## Preservação, créditos e manutenção

O código, os READMEs oficiais, avisos, licenças e históricos pertencem aos autores e colaboradores do [projeto original](https://github.com/PaddlePaddle/PaddleOCR). Esta documentação própria não representa afiliação ou endosso. Consulte o [arquivo de licença original](https://github.com/PaddlePaddle/PaddleOCR/blob/main/LICENSE); dependências e componentes adicionais podem ter condições próprias.

Manter este guia separado como `README-NOSSOS-PROJETOS.md`, sem substituir documentação ou licença original. Para atualizar o fork, conferir mudanças do upstream e resolver conflitos sem apagar customizações ou reescrever o histórico. Atualizar o fork não atualiza automaticamente os aplicativos.
