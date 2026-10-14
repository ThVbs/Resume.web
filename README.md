# TJ — Portfólio de Tiago João

> Portfólio pessoal de **Tiago Martins Rodrigues João**, Full Stack Developer & Tech Lead.
> Uma página única, bilíngue (EN/PT), escura, com um único neon e tipografia gigante que reage ao cursor.
> Feita para ser avaliada por empresas e futuros clientes.

```
 ┌──────────────────────────────────────────────────────────────┐
 │  TIAGO JOÃO                                    ( TJ )        │
 │  ─────────────────────────────────────────────────────────── │
 │  01 / 07  Tech lead · teams of 3–7 with Scrum        ▬▬▬──   │
 │                                                              │
 │  · · · · · · · ·  ●●●  · · · · · · · · · · · · · · · · · ·   │
 │  · · · · · · ·  ●●●●●●●  · · · · ·   fundo "Foco"            │
 │  · · · · · · · ·  ●●●  · · · · · · · · · · · · · · · · · ·   │
 └──────────────────────────────────────────────────────────────┘
```

---

## Sumário

1. [O que é](#o-que-é)
2. [O prompt perfeito](#o-prompt-perfeito)
3. [A receita corrigida: o que mudou e por quê](#a-receita-corrigida-o-que-mudou-e-por-quê)
4. [Sistema visual](#sistema-visual)
5. [Estrutura da página](#estrutura-da-página)
6. [Arquivos](#arquivos)
7. [Como publicar](#como-publicar)
8. [Versões salvas](#versões-salvas)

---

## O que é

| | |
|---|---|
| **Formato** | Um único `index.html` com CSS e JS embutidos, mais a pasta `assets/` |
| **Dependências** | Nenhuma biblioteca JS. Só Google Fonts |
| **Idiomas** | Inglês (padrão) e português do Brasil, troca instantânea |
| **Acessibilidade** | Respeita `prefers-reduced-motion`, foco visível, galeria navegável por teclado |
| **Responsivo** | Desktop, tablet e celular, sem rolagem horizontal |

---

## O prompt perfeito

> Este é o pedido que teria levado direto ao resultado final, sem as voltas da conversa.
> Cole numa IA de código junto com a foto de retrato, as fotos de eventos e o CV em PDF.

```text
Crie um portfólio pessoal de página única, nível "site premiado", para um Full Stack
Developer & Tech Lead. Ele será avaliado por empresas e futuros clientes, então precisa
ser ousado e memorável, mas profissional. Nada de visual de template.

ENTREGA
- Um único index.html (CSS e JS embutidos, sem bibliotecas JS) + pasta assets/.
- Bilíngue: inglês (padrão) e português do Brasil, com botão EN/PT no cabeçalho.
  Todo texto, legenda e rótulo acessível traduzido.
- Totalmente responsivo, sem rolagem horizontal. Respeitar prefers-reduced-motion.
- SEO: <title>Tiago João — Full Stack Developer & Tech Lead</title> e meta description em inglês.

PESSOA (use exatamente, não invente fatos nem números)
- Nome: Tiago João (Tiago Martins Rodrigues João). Florianópolis, Brasil. Aberto a remoto.
- Cidadão brasileiro e português; autorizado a trabalhar na UE, sem patrocínio de visto.
- E-mail: tiagomartinsrodriguesjoao@gmail.com · LinkedIn: linkedin.com/in/tiago-martins-rodrigues-joao
  · GitHub: github.com/ThVbs
- Idiomas: Português (nativo) · Inglês (C1) · Espanhol (básico).
- Formação: Tecnólogo em Análise e Desenvolvimento de Sistemas, Uni SENAI (CONCLUÍDO 2026);
  Ensino Médio Técnico em Desenvolvimento de Sistemas, SENAI (2023).

IDENTIDADE VISUAL
- Fundo #0B0B0C, texto off-white #F1F0EA, UM neon: verde-limão #C8FF00, usado com parcimônia.
- Fontes: Big Shoulders Display (títulos condensados gigantes), Hanken Grotesk (texto),
  JetBrains Mono (rótulos, números, legendas). Caveat SÓ em anotações curtas e profissionais.
- Marca: monograma "TJ" num círculo (cabeçalho, menu mobile, rodapé). Sem assinatura
  manuscrita "Tiago".
- Muito espaço negativo, grids assimétricos, numeração de seção (01, 02...) em mono pequeno.

FUNDO "FOCO" (único fundo do site)
- Malha discreta de pontos sobre o preto + um foco de luz neon suave que segue o cursor.
- Pontos dentro do foco crescem, acendem em verde e se afastam levemente (efeito lente).
- Sem interação, o foco passeia devagar sozinho, então a tela nunca fica estática.
- Clique/toque em área vazia solta uma onda em anel. O scroll desloca a malha (profundidade).
- Canvas 2D leve. Com reduced-motion: imagem estática.
- Nada poluído: nada de fluido, partículas, rede ou ASCII.

ABERTURA (HERO), nunca estática ao abrir
- "TIAGO JOÃO" gigante, ocupando a largura (no celular: duas linhas, uma palavra por linha).
- LETRAS VIVAS: as letras próximas ao cursor/toque se esticam, inclinam na direção dele
  e acendem em neon, com movimento fluido. Sem interação, uma onda de luz percorre as letras.
  IMPORTANTE: nenhum container com overflow:hidden pode cortar as letras esticadas ou o til.
- Selo circular "TJ" sobre o nome, com o texto "Tiago João · Full stack · Tech lead ·
  Florianópolis" girando em volta (gira mais rápido no hover).
- Linha de destaques que alterna sozinha a cada ~3,6s com efeito de "decodificação",
  contador 01/07 e barra de tempo. Pausa no hover; clique avança. Destaques:
  full stack (Node.js, React, Supabase) · tech lead com times de 3–7 em Scrum ·
  10+ projetos da descoberta ao lançamento · ~3.000 usuários simultâneos em plataforma
  educacional com IA · 2º lugar Startup Weekend São José 2024 · Cibersegurança
  (Cisco · Tempest · TryHackMe) · cidadão BR/PT autorizado na UE.
- Subtítulo: "Full stack developer & tech lead. I turn client problems into software
  that ships." Botões: "See my work" (rola até projetos) e "Let's talk" (mailto).
- Retrato real em P&B que ganha cor no hover, com anotação "that's me / esse sou eu".
- Linha: "Florianópolis, BR · Open to remote · EU work authorized".

TELEMETRIA: 4 números que contam ao entrar na tela
- 10+ projetos · ~3,000 usuários simultâneos · 7 pessoas no maior time · 2nd no Startup
  Weekend São José 2024 (Techstars).
- O tamanho de cada número acompanha a largura da própria coluna (container query),
  para "~3,000" nunca encostar no "7".

01 — SOBRE
- Cofundou uma consultoria de software, CRM e IA (NÃO citar o nome da empresa, da qual ele
  não faz mais parte) e liderou 10+ projetos de ponta a ponta: discovery com clientes,
  backlog, Scrum e apresentação das entregas. Antes, deu aulas de programação, banco de
  dados e web design no SENAI. Cibersegurança é a outra paixão: teve aproveitamento e
  contato com cursos da Cisco Networking Academy, Tempest Academy e TryHackMe, e foi
  palestrante convidado no Startup Weekend. NÃO mencionar CTF.
- Fatos: base, trabalho remoto, cidadania, UE, idiomas.

02 — DO QUE SOU FEITO (3 cards logo após o Sobre)
- Formação técnica: tecnólogo (concluído 2026), ensino médio técnico (2023), stack do dia a
  dia, minicursos AWS e Microsoft Learn.
- Paixão fora da curva, Segurança cibernética (anotação: "especialização contínua"):
  Cisco · Tempest · TryHackMe; Cybersecurity Essentials, Cyber Threat Intelligence,
  NDG Linux Unhatched, Introduction to IoT; palestra no Startup Weekend.
- Vocação, Gestão e comunicação: times de 3–7 com Scrum, instrutor SENAI, mestre de
  cerimônias no 1º Hackatech, qualificações SENAI (Design Thinking, Ferramentas de
  Gestão de Projetos, Liderando Equipes, Comunicação Profissional).

03 — PROJETOS (cards grandes, alternando lados, sem texto de "placeholder")
- Plataforma educacional com IA (rede pública, sob NDA): time de 7 (1 arquiteto, 5 devs,
  1 QA) por 5 meses; lacunas de aprendizagem + resumos com IA; ~3.000 simultâneos;
  perfis aluno/professor/diretor/admin. Stack: Node.js, Supabase, Docker, OpenAI, Gemini.
- Leadnator: CRM em produção (WhatsApp, Meta Ads, e-mail marketing); liderou 2 devs e
  1 designer. Botão "Visit site" → https://leadnator.com
- Wola CRM: CRM sobre base padrão, novos gateways e integrações, implantação com o cliente.
- Agente de voz com IA para leads: primeira fase da arquitetura; atende por voz no CRM e
  interpreta áudios.
- Future Task: Startup Weekend 2024, 2º lugar; mostra a estagiários o dia a dia em tech
  e ajuda empresas a reter contratados.

04 — EXPERIÊNCIA (timeline + coluna "Cursos e certificações")
- Cofundador, Tech Lead & Gerente de Projetos · ago 2024 – mar 2026.
- Instrutor de TIC & Mentor Técnico · SENAI · mai 2024 – out 2025.
- Coluna fixa ao lado: Cibersegurança / Desenvolvimento e nuvem / Qualificações SENAI.

05 — FERRAMENTAS
- Duas colunas: Tecnologia e Liderança. Em Tecnologia, separar "APIs de IA" (OpenAI,
  Gemini) de "Ferramentas de IA" (ChatGPT, Claude, Copilot, DeepSeek, Readdy).
- Acima, duas faixas animadas GERADAS A PARTIR dessas listas (nada aleatório):
  Tecnologia em letras gigantes só contorno; Liderança menor, preenchida, em sentido oposto.

06 — LONGE DO TECLADO (5 cards com mídia)
- Palestra de cibersegurança no Startup Weekend (Techstars), 3 fotos.
- 54 Horas Podcast, 1 foto: "Após o sucesso da palestra de segurança, fomos anfitriões do
  primeiro 54 Horas Podcast, que visava fomentar o tema de segurança antes do próximo
  Startup Weekend, evento internacional de alta relevância no empreendedorismo mundial."
- Mestre de cerimônias no 1º Hackatech (SENAI/SC), 2 fotos.
- SEC (Cisco Networking Academy · Tempest Academy · TryHackMe): placas tipográficas com o
  nome de cada instituição alternando (não redesenhar logotipos de terceiros).
- VOLUNTARIADO (título), anotação "desde 2019": Nova Acrópole Florianópolis, ajuda
  comunitária e Defesa Civil, 3 fotos.

FOTOS: tratamento de designer
- Em repouso, cada foto aparece em duotone da paleta (preto #0B0B0C → off-white
  esverdeado), para não destoar do fundo. No hover, revela a cor real suavizada + leve zoom.
- Fotos de um mesmo card trocam sozinhas a cada ~4s (cross-fade + zoom lento), com
  tracinhos indicando a ativa. Pausa no hover, só anima quando visível.
- Clique abre galeria em tela escura (cores originais, legenda, contador, setas,
  miniaturas, teclado, deslizar no celular), começando pela foto que estava visível.

FORMAÇÃO
- 2026 (anotação "concluído") · Tecnólogo em ADS, Uni SENAI.
- 2023 · Ensino Médio Técnico em Desenvolvimento de Sistemas, SENAI.

07 — CONTATO: minimalista, SEM formulário
- "LET'S TALK." / "VAMOS CONVERSAR." gigante com as mesmas letras vivas do hero.
- Uma linha: disponibilidade (remoto, UE, Florianópolis) · e-mail com botão Copiar ·
  LinkedIn · GitHub · Baixar CV (PDF).

RODAPÉ: monograma TJ · © 2026 Tiago João · voltar ao topo.

EXTRAS
- Cabeçalho fixo minimalista que some ao rolar para baixo e volta ao subir, com barra
  de progresso neon.
- Cursor customizado no desktop. Textos revelados linha a linha ao rolar (sem nunca
  deixar conteúdo invisível antes do scroll).
- Não bloquear botão direito nem Ctrl+U. Nada de chaves ou segredos no front-end.
```

---

## A receita corrigida: o que mudou e por quê

Cada ajuste da conversa, transformado em regra para não errar de novo.

| # | Primeira versão | Correção | Regra que fica |
|---|---|---|---|
| 1 | Caixa de placeholder no retrato | Foto real, P&B → cor no hover | Use o material real assim que existir |
| 2 | "~3,000" e "7" pareciam um número só | Número dimensionado pela largura da coluna | Números grandes precisam de espaço garantido |
| 3 | Bio citava CTF e o nome da consultoria | Cursos Cisco/Tempest/TryHackMe; foco nas entregas | Fale do que você fez, não de onde já saiu |
| 4 | Inglês "fluente" | Inglês **C1** | Use o nível certificável |
| 5 | Tecnólogo "previsto 2026" | **Concluído 2026** | Mantenha datas atualizadas |
| 6 | Hero estático | Letras vivas + destaques alternando + selo girando | A primeira tela tem que se mexer sozinha |
| 7 | Fundos testados: terreno, fluido, partículas, rede, ASCII, halo | Só o **Foco** | Simples e com destaque vence o espetáculo |
| 8 | Assinatura manuscrita "Tiago" | Monograma **TJ** em selo circular | Marca > caligrafia, em contexto profissional |
| 9 | Formulário de contato | Contato minimalista com links | Portfólio de avaliação não precisa de briefing |
| 10 | Letras esticadas cortadas no hover | Sem `overflow:hidden` nos títulos interativos | Animação nunca pode ser recortada |
| 11 | "Onde eu me perco" | "Especialização contínua" | Tom profissional nas anotações |
| 12 | Fotos coloridas destoando | Duotone da paleta + cor no hover + galeria | A foto entra no sistema de cores, não o contrário |
| 13 | Fotos paradas | Troca automática nos cards | Galerias pequenas devem se apresentar sozinhas |
| 14 | Card "2019" | Título **VOLUNTARIADO**, "desde 2019" acima | Título diz o quê, anotação diz quando |
| 15 | Faixa de skills aleatória | Faixas geradas das listas Tecnologia e Liderança | O destaque visual repete o conteúdo real |
| 16 | Só OpenAI/Gemini | + ChatGPT, Claude, Copilot, DeepSeek, Readdy | Mostre as ferramentas que você realmente usa |

---

## Sistema visual

| Token | Valor | Uso |
|---|---|---|
| `--ink` | `#0B0B0C` | Fundo |
| `--surface` | `#141513` | Cards |
| `--line` | `#272923` | Bordas e divisórias |
| `--paper` | `#F1F0EA` | Texto |
| `--muted` | `#8F9186` | Texto secundário |
| `--acid` | `#C8FF00` | O único destaque |

| Papel | Fonte |
|---|---|
| Títulos | Big Shoulders Display 800–900 |
| Texto | Hanken Grotesk 400–600 |
| Rótulos e números | JetBrains Mono |
| Anotações curtas | Caveat 700 |

---

## Estrutura da página

```
Cabeçalho (TJ · Work · About · Experience · Contact · EN/PT)
├── Hero ............ nome vivo · selo TJ · destaques · retrato
├── Telemetria ...... 10+ · ~3,000 · 7 · 2nd
├── 01 Sobre
├── 02 Do que sou feito
├── 03 Projetos
├── 04 Experiência + Cursos e certificações
├── 05 Ferramentas .. faixas Tecnologia / Liderança + colunas
├── 06 Longe do teclado (fotos + galeria)
├── Formação
├── 07 Contato
└── Rodapé
```

---

## Arquivos

```
index.html                     ← tiago-joao-portfolio.html
assets/
├── tiago-joao.jpg             retrato
├── Curriculo_Completo.pdf     CV
└── photos/
    ├── talk-1..3              palestra Startup Weekend
    ├── podcast-1              54 Horas Podcast
    ├── hackatech-1..2         Hackatech SENAI/SC
    └── vol-1..3               voluntariado Nova Acrópole
       cada foto em 3 versões: .jpg (galeria) · -duo.jpg (capa) · -color.jpg (hover)
```

Para trocar uma foto, gere as três versões com o mesmo nome. As fotos do iPhone em HEIC precisam ser convertidas para JPG antes.

---

## Como publicar

1. **Repositório privado** no GitHub com este código legível.
2. **Deploy** pelo Vercel, Netlify ou Cloudflare Pages ligado ao repositório privado.
3. **Versão de produção minificada e ofuscada** para o site no ar (dificulta cópia; código de front-end nunca é 100% secreto).
4. **Domínio sugerido:** `tiagojoao.dev`. Alternativas: `tiagojoao.com` e `tiagojoao.pt`.

### Pendências

- [ ] Atualizar o PDF do CV (ainda cita "CTFs" e "inglês fluente")
- [ ] Opcional: badges ou certificados oficiais da Cisco, Tempest e TryHackMe no card SEC
- [ ] Tags Open Graph com imagem de prévia, quando o domínio estiver definido

---

<sub>© 2026 Tiago João. Todos os direitos reservados.</sub>
