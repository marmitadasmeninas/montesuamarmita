# Monte Sua Marmita

Projeto: Marmita das Meninas — Montador de marmita (300g)

Descrição
- Página estática para permitir que clientes montem uma marmita de 300g, distribuindo gramas entre proteínas, carboidratos e legumes.
- Preço: R$ 19,00 por marmita paga.
- Promoção: a cada 10 marmitas pagas ganha +1 grátis (ex.: 10 pagas → 11 recebidas; 20 pagas → 22 recebidas).
- Visual premium e feminino, responsivo.

Arquivos neste repositório
- `index.html` — interface do montador (página web).
- `README.md` — este arquivo.
- `LICENSE` — licença MIT.

Como usar / testar localmente
1. Clone ou crie o repositório `montesuamarmita`.
2. Salve `index.html` na raiz do repositório.
3. Abra `index.html` no navegador (duplo clique ou via servidor local).
4. Testes manuais recomendados:
   - Distribuir gramas entre opções até totalizar 300g e verificar validação.
   - Testar botão "Distribuir 300g equilibrado".
   - Ajustar quantidade de marmitas e verificar cálculo de bônus e preço.
   - Verificar mensagens e comportamento do botão "Finalizar pedido" (simulação).

Sugestão de estrutura inicial
- Branch de desenvolvimento: `feat/montar-marmita` (ou `feat/montar-marmita`)
- Commit inicial sugerido:
  ```
  Adicionar página de montagem de marmita

  Adiciona index.html com montador de marmita 300g, validação da soma por marmita,
  cálculo de preço (R$19 por unidade) e promoção (a cada 10 pagas ganha +1).
  Visual premium e responsivo.
  ```

Próximos passos sugeridos
- Integrar com backend / carrinho / gateway de pagamento.
- Adicionar imagens/ícones para as opções e melhorar UX.
- Persistência da montagem (localStorage) e acessibilidade refinada.
- Automatizar deploy (GitHub Pages, Vercel, Netlify).

Contato
- Mantido por: Marmita das Meninas
