# Plataforma de Entregas: GPN

Trabalho em grupo da disciplina **Gerência de Processos de Negócio**, do curso de Bacharelado em Sistemas de Informação do Ifes.
O tema escolhido é o **7: Plataforma de entregas (pedidos, restaurantes, entregadores e clientes)**.
A entrega é em **30/11/2026**.

## Integrantes

- Luan Oliveira
- Gabriele Modesto
- Danilo Pimenta
- Guilherme Costa

## Artefatos

| Artefato | Onde está |
|---|---|
| Relatório (em edição) | [Google Docs](https://docs.google.com/document/d/1aXC5tmnIrDs0h0d7FG10hV_hwDVPUg8ga8NAoBA5cxM/edit) |
| Relatório final | `relatorio/relatorio.pdf` |
| Modelos BPMN editáveis (BPMN 2.0 XML) | `processos/bpmn/` |
| Exportações dos diagramas (PNG/SVG/PDF) | `processos/imagens/` |
| Slides da apresentação (PDF e editável) | `apresentacao/` |
| Protótipos de interface | `prototipos/` (o link do Figma vai aqui quando existir) |

## Processos

| ID | Processo | Responsável |
|---|---|---|
| P1 | Credenciamento de restaurante | a definir |
| P2 | Cadastro e aprovação de entregador | a definir |
| P3 | Gestão de cardápio e disponibilidade | a definir |
| P4 | Realização do pedido e pagamento | a definir |
| P5 | Aceite e preparo do pedido | a definir |
| P6 | Despacho e execução da entrega | a definir |
| P7 | Cancelamento, ocorrência e reembolso | a definir |
| P8 | Repasse financeiro | a definir |
| C1 | Colaboração (Cliente, Plataforma, Restaurante, Entregador, Gateway) | a definir |

## Como contribuir

- Os diagramas são feitos no [bpmn.io](https://demo.bpmn.io) ou no Camunda Modeler. Cada processo é salvo como `processos/bpmn/P<N>-<nome>.bpmn`, com a exportação em `processos/imagens/P<N>-<nome>.png`.
- Cada integrante faz commit dos próprios arquivos, porque o histórico de contribuições entra na avaliação.
- O texto do relatório é escrito no Google Docs. Na entrega, ele é exportado para `relatorio/relatorio.pdf`.

## Estrutura do ZIP de entrega

```
relatorio.pdf
processos/      # .bpmn + imagens
apresentacao/   # slides PDF + editável
README.md       # este arquivo
```
