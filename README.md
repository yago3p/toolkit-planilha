# Toolkit Planilhas

Extraia abas de uma planilha como CSVs individuais, compile múltiplos arquivos XLSX em uma base única com mapeamento de campos 100% configurável, ou segmente dados por intervalo numérico — tudo direto no navegador.

![status](https://img.shields.io/badge/status-ativo-4ADE80) ![stack](https://img.shields.io/badge/stack-HTML%20%2F%20JS-00D4FF) ![license](https://img.shields.io/badge/license-MIT-8B98A5)

<!-- 🖼️ Screenshot ou GIF do app aqui -->

**Demo ao vivo:** [toolkit-planilhas.vercel.app](https://toolkit-planilhas.vercel.app/)

## Funcionalidades

- **Extrair abas** — carregue uma planilha e baixe cada aba como um CSV individual (ou todas juntas em um ZIP)
- **Compilar planilhas** — consolide dados de múltiplos arquivos XLSX em uma única tabela, com:
  - Campos configuráveis vindos de célula fixa, coluna da tabela ou valor fixo
  - Tipos de dado (texto, número, moeda, data, latitude, longitude)
  - Detecção de campos duplicados
  - Importação/exportação da configuração de campos em JSON, para reaproveitar em outras compilações
  - Busca, ordenação por coluna e paginação nos resultados
  - Exportação para CSV ou XLSX consolidado
- **Segmentar dados** — importe uma planilha (ou monte uma tabela manualmente) e divida cada linha em segmentos por intervalo numérico, com passo configurável:
  - Colunas de início/fim e passo escolhidos livremente
  - Edição inline de colunas e linhas, com renomear/excluir coluna
  - Validação de passo (bloqueia valores zero ou negativos, evitando travamentos)
  - Exportação para CSV ou XLSX do resultado segmentado

Todas as operações rodam 100% no navegador (client-side), usando [SheetJS](https://sheetjs.com/) e [JSZip](https://stuk.github.io/jszip/) — nenhum arquivo é enviado a servidores externos.

## Como rodar localmente

Não há build nem dependências para instalar — é um arquivo único:

1. Baixe o `index.html`
2. Abra no navegador (duplo clique ou `Arquivo > Abrir`)

## Stack

HTML, CSS, JavaScript vanilla · [SheetJS (xlsx)](https://sheetjs.com/) · [JSZip](https://stuk.github.io/jszip/) · [Lucide Icons](https://lucide.dev/)

## Licença

MIT
