# BeautyFlow — Sistema para Loja de Cosméticos

Protótipo web de um sistema completo para lojas de cosméticos, perfumarias, salões e negócios de beleza. A aplicação roda em um único arquivo `index.html`, sem backend, e demonstra os principais módulos necessários para operação comercial.

## Funcionalidades implementadas

- **Dashboard gerencial** com indicadores de faturamento potencial, valor em estoque, margem média, agenda do dia e alertas operacionais.
- **PDV e catálogo de produtos** com busca por nome, marca, categoria ou benefício.
- **Filtros por categoria** para Skincare, Cabelos, Maquiagem, Perfumaria e Unhas.
- **Carrinho de venda** com controle de quantidade, subtotal, desconto automático e total.
- **Finalização de venda simulada** com registro em histórico e persistência local das últimas vendas via `localStorage`.
- **Controle de estoque** com estoque mínimo, margem por produto e alerta de reposição.
- **CRM básico** com clientes, nível de fidelidade, pontos, preferência e ticket médio.
- **Agenda de serviços** para consultorias, diagnósticos, retiradas de pedido e atendimento presencial.
- **Relatórios de vendas recentes** com status de pagamento.
- **Simulação de reposição** para produtos abaixo do mínimo.

## Como executar

Abra o arquivo `index.html` diretamente em um navegador moderno ou sirva o diretório localmente:

```bash
python3 -m http.server 8000
```

Depois acesse:

```text
http://localhost:8000
```

## Estrutura atual

```text
/
├── index.html      # Aplicação web demonstrativa BeautyFlow
├── README.md       # Documentação do projeto
└── images/         # Imagens mantidas do projeto anterior
```

## Próximos passos recomendados

1. Adicionar autenticação por perfil: administrador, caixa, vendedor e estoque.
2. Criar backend com banco de dados para produtos, clientes, vendas e agenda.
3. Integrar emissão fiscal, meios de pagamento e controle de caixa.
4. Adicionar cadastro completo de produtos com lote, validade, fornecedor e código de barras.
5. Integrar WhatsApp para recuperação de carrinho, aniversário, recompra e campanhas segmentadas.
6. Criar tela mobile dedicada para vendedores consultarem produtos e clientes no salão/loja.

## Observação

Este projeto é um MVP visual e funcional para validar fluxo, layout e regras de negócio. Ele pode ser evoluído para uma aplicação de produção com API, banco de dados, autenticação e integrações externas.
