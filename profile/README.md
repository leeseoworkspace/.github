# Leeseo Workspace

O Leeseo é uma plataforma de coleção e troca de cards de K-pop integrada ao Discord. A comunidade pode conseguir cards, completar coleções, abrir caixas e participar de atividades tanto pelo bot quanto pelo site.

## O que você encontra

- **Bot Discord:** drops de cards, coleção e inventário, caixas, loja, trocas, presentes, missões, recompensas e jogos.
- **Website:** visualização de coleção e álbuns, marketplace, perfil, caixas, recompensas e Game Hub. Também inclui ferramentas administrativas para criar e gerenciar cards.
- **API:** serviços de autenticação, usuários, coleção, loja, pagamentos, recompensas, jogos e administração, compartilhando os dados usados pelo bot e pelo site.

## Repositórios

| Projeto | Responsabilidade |
| --- | --- |
| [Bot](https://github.com/leeseoworkspace/bot) | Bot e experiências da comunidade no Discord. |
| [Website](https://github.com/leeseoworkspace/website) | Interface web do Leeseo. |
| [API](https://github.com/leeseoworkspace/api) | API e serviços de backend. |

## Tecnologias

- **Bot:** Node.js, TypeScript e Discord.js.
- **Website:** Next.js, React, TypeScript, Tailwind CSS e HeroUI.
- **API:** Node.js, TypeScript e Fastify.
- **Dados:** PostgreSQL e Prisma.
- **Imagens e deploy web:** armazenamento compatível com S3/R2 e Cloudflare Workers.
- **Integrações:** Discord OAuth, Top.gg e Mercado Pago.

## Como as partes se conectam

O site apresenta a experiência web, a API concentra as operações e os dados do serviço, e o bot leva os recursos de coleção e comunidade ao Discord. Os três projetos trabalham com os mesmos dados de jogo para manter cards, inventário e recompensas sincronizados.

## Idiomas

O site e o bot oferecem conteúdo em português e inglês.