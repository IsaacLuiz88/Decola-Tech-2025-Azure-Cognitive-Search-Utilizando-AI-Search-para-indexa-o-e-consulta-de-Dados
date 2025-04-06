# Decola Tech 2025 - Azure Cognitive Search para Análise de Cafeterias

Projeto demonstrando a utilização do Azure AI Search para indexação e análise de reviews de cafeterias.

## Recursos Utilizados
- **Azure AI Search**: Serviço de busca cognitiva
- **Blob Storage**: Armazenamento dos documentos originais
- **Cognitive Skills**:
  - Análise de sentimentos
  - Extração de frases-chave
  - Reconhecimento de entidades

## Dados Processados
O conjunto inclui 6 reviews com diferentes perfis:
- 2 avaliações negativas (Grão Dourado, Expresso Rápido)
- 2 positivas (Aroma Premium, Padaria Café com Tudo)
- 2 neutras/mistas (Pausa Café, Sabor & Arte)

## Fluxo de Trabalho
1. **Armazenamento**: Upload do documento DOCX com reviews para o Blob Storage
2. **Indexação**: Configuração do indexador para processar o documento
3. **Enriquecimento**: Aplicação de:
   - Análise de sentimentos
   - Extração de entidades (nomes de cafeterias)
   - Detecção de idioma
4. **Busca**: Consulta aos dados indexados via Search Explorer

## Insights Obtidos
1. **Padrões de Avaliação**:
   - Identificação de termos mais comuns em reviews positivos
   - Palavras-chave associadas a experiências negativas

2. **Desempenho**:
   - Tempo médio de indexação para documentos DOCX
   - Eficiência na identificação de entidades (nomes de estabelecimentos)

3. **Aplicações Práticas**:
   - Sistema de monitoramento de reputação para redes de cafeterias
   - Identificação de pontos de melhoria com base nas críticas
   - Análise comparativa entre diferentes unidades