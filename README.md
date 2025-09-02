# Visão Geral do Projeto Didático
### O projeto será dividido em 3 etapas principais, cada uma com seu próprio script:

### Treinamento do Modelo (ou Transferência de Aprendizagem): 
Iremos carregar um modelo pré-treinado (ResNet18) e adaptá-lo para nossa tarefa. O objetivo não é classificá-lo por texto, mas sim, usá-lo para gerar vetores de características (embeddings) para cada imagem.

### Geração e Armazenamento dos Embeddings: 
Vamos processar todas as imagens do dataset, gerar seus embeddings e salvá-los em um arquivo para uso futuro.

### Sistema de Recomendação: 
Com os embeddings prontos, iremos carregar a imagem de um produto de consulta e encontrar as imagens mais visualmente parecidas usando a métrica de similaridade de cosseno.
