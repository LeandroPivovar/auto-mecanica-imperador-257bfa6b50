# Auto Mecânica Imperador

Site estático HTML/CSS/JS com única saída pública em `dist/`. Pronto para importar na Vercel com framework Other, sem dependências, instalação ou build, conforme `vercel.json`. Commit e push autorizados pelo usuário em 27/10/2026.

## Dados fornecidos

- Nome e apresentação: Auto Mecânica Imperador.
- WhatsApp: +55 16 99747-2305, exatamente como fornecido no print. Telefone e links wa.me usam 5516997472305.
- Perfil informa aberta 24 horas. Página orienta confirmar disponibilidade e modalidade de atendimento; não promete socorro, guincho, deslocamento ou resposta imediata.
- Catálogo visível com conjunto de embreagem, sem marca, aplicação, estoque ou preço confirmados. Seção permite consultar peças e embreagem, sem anunciar um produto específico ou preço fictício.
- Endereço e serviços detalhados não legíveis no print: o usuário autorizou deixá-los de fora por enquanto. Não inferir região pelo DDD. Mapa e endereço dependem de confirmação; FAQ oferece consulta por WhatsApp antes da visita.
- Sem avaliações, certificações, histórico, equipe ou fotografias próprias confirmadas. Galeria de banco identificada como ilustrativa, sem apresentar trabalhos fictícios.

## Design e interação

Referência explícita: segundo print OnEarth enviado pelo usuário. Mantém quatro fotografias escalonadas sobre faixa fotográfica, navegação arredondada, mosaico e galeria, FAQ e faixa de encerramento. Preto, branco e dourado adaptam a marca. Essa instrução prevalece sobre a hero padrão Aroe. Taste: One motif, seed 707064188, sem redraw; coroa simples como assinatura, geometria da referência prevalecendo sobre composição sorteada quando conflitante. Sem estatísticas inventadas para reproduzir o print. Fotos e licenças em [credits.md](credits.md), com créditos também no rodapé.

Contato interativo prepara texto conforme assunto e veículo opcional. Links dos serviços selecionam o assunto correspondente. O visitante revisa e envia no WhatsApp: sem envio automático, backend ou armazenamento. Sem JavaScript, contato padrão e telefone funcionam. FAQ nativa e menu com Escape; movimentos com fallback de `prefers-reduced-motion` e conteúdo sempre visível.

## Hospedagem

Importar a raiz deste repositório na Vercel, framework Other, saída dist. Não publicar CRM, QA, credenciais ou servidor local. `.gitignore` e `.vercelignore` preservam separação. Envio ao GitHub não equivale a deploy verificado na Vercel.

## Verificação da entrega

Conferência visual em 1440, 768 e 390 px: títulos com até duas linhas, sem overflow detectado e sem imagens quebradas no inspetor. Taste: 0 falhas; avisos de navegação arredondada e agrupamentos justificáveis pelo print, ausência de filmagem própria e escala responsiva com variações adicionais. Crítica visual: design 7,5, usabilidade 8, criatividade 6 e conteúdo 6, média ponderada 7,2/10; os principais limites são fotografias genéricas e oferta ainda incompleta. Nenhum redraw. Contato e FAQ testados no navegador; menu, Escape, resize, mensagem, assets e âncoras conferidos por script adicional. Sem build para executar: saída estática pronta em dist.
