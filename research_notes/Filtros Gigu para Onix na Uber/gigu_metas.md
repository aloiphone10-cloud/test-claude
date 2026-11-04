# GigU (ex-StopClub): como funciona e metas recomendadas (R$/km, R$/hora, nota do passageiro) para UberX/Comfort, 2025-2026

> Method note: WebFetch was blocked in this session for every relevant host (gigu.app, www.gigu.app, play.google.com, apps.apple.com, site.stopclub.com.br, reclameaqui.com.br, 55content.com.br, tribunademinas.com.br). Everything below comes from search-engine snippets and summaries of those pages, not full-page reads. Exact UI labels ("Meta de Ganho /Km", "Lucro Líquido", "Me ajude com as metas") are only partly confirmed. To verify them, open the app or allow those domains.

## 1. What GigU is, how it reads offers, its filters, Lucro Líquido, pricing

### Takeaway
GigU is the rebrand of StopClub, a Brazilian company. It is a "copiloto" that reads Uber/99/inDrive offer cards on screen (Android overlay; iOS was in beta in 2025-26). It scores each offer against your goals for R$/km and R$/hora with a green/yellow/red "Semáforo", and passenger rating also counts. A free Lucro Líquido calculator works out your custom cost per km from consumo, preço do combustível and fixed costs, and suggests goals. In Brazil the paid plan was reported at R$ 12,90/mês. GigU's own blog says pickup distance must be counted. I found no official statement on whether the Semáforo's R$/km uses trip km only or trip + pickup km, and one StopClub-era example suggests trip-only.

### Cited Findings
**Identity and legal context**
- GigU is formerly StopClub. It filters/scores rides for Uber, 99 and InDrive, and has been in legal conflict with Uber — [BNews](https://www.bnews.com.br/noticias/crime-e-justica-bahia/aplicativo-que-salva-motoristas-de-prejuizo-vira-alvo-da-uber-na-justica-veja-como-funciona-o-app.html); [Business Insider NL](https://www.businessinsider.nl/an-app-that-says-it-can-help-uber-drivers-pick-profitable-rides-has-arrived-in-the-us-uber-has-fought-against-it-before)
- The Reclame Aqui company page is still "Stopclub Tecnologia, Soluções e Serviços", with complaints about the "aplicativo Gigu" — [Reclame Aqui](https://www.reclameaqui.com.br/stopclub-tecnologia-solucoes-e-servicos/alertas-de-valor-por-km-incorretos-no-aplicativo-gigu_wLSOEjVrKeIHGs26/)
- Uber sued for unfair competition, objecting to the "cálculo de ganhos" and "recusa automática" features. TJ/SP lifted Uber's injunction, so those features could keep running until the case is decided — [Migalhas](https://www.migalhas.com.br/quentes/404804/tj-sp-valida-stopclub-app-que-calcula-ganhos-em-corridas-da-uber)
- Uber's terms forbid automation tools or bots that access Uber data. GigU says it has come out ahead in court, while Uber says the process is ongoing — [Business Insider NL](https://www.businessinsider.nl/an-app-that-says-it-can-help-uber-drivers-pick-profitable-rides-has-arrived-in-the-us-uber-has-fought-against-it-before)
- GigU filed a CADE complaint over Uber restricting drivers who use its tool. The SG closed it in 2025 for lack of evidence. GigU appealed, and reports say the case was reopened in 2026 — [Times Brasil](https://timesbrasil.com.br/empresas-e-negocios/uber-e-investigada-pelo-cade-apos-denuncia-de-startup-que-calcula-ganhos-reais-de-motoristas-por-corrida/); [NC News, jul/2026](https://ncnews.com.br/2026/07/29/cade-reabre-caso-contra-uber-brasil-e-desafia-uber-passageiro-em-2026/)
- In the US version (launched May 2025), GigU detects Uber/Lyft offer notifications through Android Accessibility Services and needs no platform password — [The Rideshare Guy review 2026](https://therideshareguy.com/gigu-app-review/); [parsers.vc](https://parsers.vc/news/250516-gigu-s-bold-leap-into-the-u-s--market--a)
- StopClub PRO "lê os cards da Uber e da 99" even while the driver uses Waze or Google Maps (a screen-reading overlay) — [StopClub help, via search](https://site.stopclub.com.br/app-ajuda/configurando-o-calculo-de-ganhoss)
- The iOS app "GigU: Seu copiloto inteligente" (App Store id6775593538) and an iOS beta page exist. The listing says it works with Uber, 99, 99 Food, inDrive, iFood and Keeta — [App Store](https://apps.apple.com/us/app/gigu-seu-copiloto-inteligente/id6775593538?l=fr-FR); [gigu.app/pt/ios](https://gigu.app/pt/ios)

**Filters / Semáforo**
- Drivers set minimum values per km, per minute and per hour. Rides show in color: green (good), yellow (borderline/"cobre custos"), red (refuse) — [Startupi/Times Brasil summary via search](https://startupi.com.br/gigu-atinge-breakeven-receita-mensal-de-2-milhoes/); [Seu Crédito Digital](https://seucreditodigital.com.br/ferramentas-motoristas-corrida/)
- Official help page "Ajustando o Semáforo Inteligente": colors are based on your Ganhos por Km and Ganhos por Hora settings, configured under **Copiloto > Cálculo de Ganhos**. Green means the ride pays well, but watch for low-demand destinations. Yellow means it may or may not be worth it. Red means less advantageous, though it may take you to a higher-demand area — [GigU help](https://www.gigu.app/help/ajustando-o-semaforo-inteligente)
- Replying on Reclame Aqui to a complaint that "alertas de valor por km [estavam] incorretos", the company said the color does not depend on R$/km alone. Users must also set the per-hour estimate and "outros indicadores importantes, como a nota do passageiro". So passenger rating is an input to the Semáforo — [Reclame Aqui](https://www.reclameaqui.com.br/stopclub-tecnologia-solucoes-e-servicos/alertas-de-valor-por-km-incorretos-no-aplicativo-gigu_wLSOEjVrKeIHGs26/)
- The App Store changelog for v1.0.2 (7 Oct, year not shown in the snippet, probably 2025) added **"Ajude a calcular metas"** / "Help me calculate my goals", which helps set per-km and per-hour goals. This is most likely the feature the brief calls "Me ajude com as metas". Google Play (US) says you can set minimum and maximum values for distance and hourly earnings — [App Store](https://apps.apple.com/us/app/gigu-seu-copiloto-inteligente/id6775593538?l=fr-FR); [Google Play](https://play.google.com/store/apps/details?id=co.gigu.app&hl=en_US)
- After calculating costs, "você pode aplicar as metas sugeridas de ganho por km e por hora diretamente no Semáforo de Valores do Cálculo de Ganhos" — [GigU blog: Lucro Líquido](https://gigu.app/br/blog/lucro-liquido-saiba-quanto-voce-realmente-ganha-em-cada-corrida)
- Automatic refusal ("recusa automática") existed in StopClub and is the most controversial feature. A 2025-26 summary says the current GigU "Cherry Picker" only suggests and does not refuse for you. Not confirmed for the current Brazilian version — [Migalhas](https://www.migalhas.com.br/quentes/404804/tj-sp-valida-stopclub-app-que-calcula-ganhos-em-corridas-da-uber); [manualdaweb](https://manualdaweb.com/motoristas/corridas-que-pagam-mais/)

**Pickup distance and time**
- GigU's own blog: "Os aplicativos mostram na tela da oferta quanto você vai andar até o embarque, e esse trecho precisa entrar na conta". So a 10 km ride with 4 km of pickup costs like 14 km — [GigU blog: Custo por km](https://gigu.app/br/blog/custo-por-km-motorista-de-aplicativo)
- Manual da Web says the GigU calculation considers distance, estimated time, ride value "e o custo do deslocamento até o passageiro" — [manualdaweb](https://manualdaweb.com/motoristas/corridas-que-pagam-mais/)
- Counter-evidence from the StopClub era: an example offer with an 11.40 km trip, 8.5 km pickup and R$ 19.59 payout was shown as R$ 1.72/km. That equals 19.59 / 11.40, i.e. trip km only. 19.59 / 19.9 would be R$ 0.98. This is my arithmetic on the reported numbers — [55content: "Copiloto inteligente" StopClub](https://55content.com.br/noticia/copiloto-inteligente-stopclub-lanca-aplicativo-para-maximizar-ganhos-dos-motoristas-de-app/)
- By contrast, Uber's own "ganhos estimados por km" pilot in Brazil divides the offer price by **total** distance (pickup + trip). Pickup distance is measured from your position when you accept — [Uber blog](https://www.uber.com/pt-BR/blog/piloting-estimated-earnings-per-kilometer-on-trip-requests)
- The Uber offer card shows the total value, the km and minutes to the pickup point, and the trip km — [Uber blog: novo modelo de ganhos](https://www.uber.com/br/pt-br/blog/novo-modelo-de-ganhos/); [Uber: novo cartão de oferta](https://www.uber.com/pt-BR/blog/novo-cartao-de-oferta)
- The general formula guides recommend is ganho ÷ (km até passageiro + km da viagem) — [Guia de Economia Pessoal 2026](https://guiadeeconomiapessoal.com.br/quanto-ganha-motorista-uber-2026/)

**Lucro Líquido section**
- It is set up in three steps. (1) Rotina: dias/semana, horas/dia, km/dia, ganhos semanais. (2) Veículo: tipo, and whether it is próprio, financiado or alugado. (3) Custos: fixed costs (financiamento, seguro, manutenção, impostos) plus fuel (consumo médio km/l and preço por litro). The app then outputs cost per km and suggested goals. The overlay card can show projected **lucro** por hora, por km or margin per ride. The Lucro Líquido calculation is free for anyone — [GigU blog: Lucro Líquido](https://gigu.app/br/blog/lucro-liquido-saiba-quanto-voce-realmente-ganha-em-cada-corrida)
- GigU recommends keeping two numbers. "Custo do veículo" is used to decide each ride; "custo da atividade" is used to see whether the month closes. Cost per km = gastos do mês ÷ km do mês. In GigU's example profile, custo do veículo ≈ R$ 1,09/km and custo da atividade ≈ R$ 1,26/km. Any ride paying less per km than the custo do veículo loses money — [GigU blog: Custo por km](https://gigu.app/br/blog/custo-por-km-motorista-de-aplicativo)
- Exame describes the tool as discounting combustível, manutenção, taxas and depreciação — [Exame](https://exame.com/negocios/essa-startup-quer-mostrar-para-os-motoristas-e-entregadores-de-aplicativo-o-lucro-real-das-corridas/)

**Pricing / company**
- Brazil: a fixed subscription of **R$ 12,90/mês**. Reported prices elsewhere: US$ 6.95 in the US and €5.90 in Portugal — [Poder360, 2026](https://www.poder360.com.br/poder-empreendedor/plataforma-para-motoristas-de-app-faturou-r-123-mi-em-2025/)
- There is a free functional version. The paid plan adds detailed ride history, performance by period and cross-platform comparisons — [manualdaweb](https://manualdaweb.com/motoristas/corridas-que-pagam-mais/)
- US/Canada: free until 4 Jan 2027 according to Google Play (US) — [Google Play](https://play.google.com/store/apps/details?id=co.gigu.app&hl=en_US); [Rideshare Guy](https://therideshareguy.com/gigu-app-review/)
- GigU billed R$ 12.3M in 2025 — [Poder360](https://www.poder360.com.br/poder-empreendedor/plataforma-para-motoristas-de-app-faturou-r-123-mi-em-2025/). It reached breakeven and is targeting R$ 2M monthly revenue — [Startupi](https://startupi.com.br/gigu-atinge-breakeven-receita-mensal-de-2-milhoes/)
- GigU data: average profit of R$ 15,57/h (43.6% net margin) in the São Paulo metro area vs R$ 10,11/h (33%) in northwest SP state — [Times Brasil](https://timesbrasil.com.br/brasil/motoristas-de-aplicativo-recebem-ate-r-669-a-menos-por-hora-trabalhada-fora-das-regioes-metropolitanas-revela-levantamento/)

### Inferences
- In GigU, "Meta de Ganho /Km" and "/Hora" are gross revenue targets (R$ recebido ÷ km or h). The Lucro Líquido module converts your costs into suggested gross goals, and can also show net profit on the card. A practical setup is to fill in Lucro Líquido first, apply the suggested goals, then adjust them.
- Whether the Semáforo divides by trip km or by trip + pickup km is unresolved. Safe practice: if the card's R$/km uses trip km only, raise the km goal, or mentally divide by total km for long pickups. Uber's native R$/km (where piloted) already uses total km, so the two numbers can differ for the same offer.
- Hourly goals likely use estimated trip + pickup time, but no source confirms this.

### Gaps
- No full-text read of gigu.app help pages, the store listings or the YouTube tutorials (domains blocked). The exact field names ("Meta de Ganho /Km", "Nota do passageiro" slider range, default values) and the algorithm for yellow vs red are unconfirmed.
- No source states GigU's default or suggested values. The "Ajude a calcular metas" output depends on user inputs.
- No official confirmation of whether pickup distance or pickup time enter the Semáforo's R$/km and R$/h.
- The current status of automatic refusal in the Brazilian app is unclear.

## 2. Comparable apps and their default thresholds

### Takeaway
Several competitors do the same overlay scoring: StopClub (now GigU), Rota Pro, Corridex (iPhone), DriveSocial, Rebu, and Uber's own R$/km pilot. None publishes a universal default R$/km. All push the driver to derive thresholds from their own cost per km. Rota Pro's passenger-rating bands are the only concrete "default" found.

### Cited Findings
- Rota Pro calculates rides and earnings on Uber/99 and recommends judging both R$/km (pays for the car) and R$/hora (pays for your time). "O que paga mais por km nem sempre paga mais por hora" — [Rota Pro](https://rotapro.app/); [Rota Pro: melhor horário](https://rotapro.app/guia/melhor-horario-para-rodar-uber/)
- Rota Pro passenger-rating bands: below 4.30 is "ruim", 4.90 and above is "aceitar" (Android) — [Rota Pro: motorista 5 estrelas](https://rotapro.app/guia/motorista-5-estrelas-uber/)
- Corridex (iPhone only) monitors Uber/99 offers and lets you set a minimum R$/km and a minimum R$/hora — [Corridex](https://corridex.app/)
- DriveSocial (Android) reads Uber/99 cards and shows R$/km, R$/hora and R$/min. The page is old, about 1,300 days — [DriveSocial](https://drivesocial.io/ferramenta-de-calculos-de-ganho/)
- Rebu also lets you set minimum values to accept rides — [Seu Crédito Digital](https://seucreditodigital.com.br/apps-corridas-lucrativas-uber-99/)
- Uber is piloting an estimated R$/km on the offer card (total distance incl. pickup) — [Uber blog](https://www.uber.com/pt-BR/blog/piloting-estimated-earnings-per-kilometer-on-trip-requests)
- Uber has offered a "Preferência de Nota" / "Rider Ratings Preference" so drivers can set a minimum passenger rating. Uber warns it reduces the number of offers. It was tested in Brazil in 2021, and a later rollout was reported — [Uber blog: preferência de nota](https://www.uber.com/pt-BR/blog/preferencia-de-nota/); [55content](https://55content.com.br/noticia/uber-lanca-funcao-que-permite-motoristas-definirem-nota-minima-de-avaliacao-para-aceitar-corridas/)
- Uber lets drivers block future matches with a rider they rated 2 or 3 stars — [Uber newsroom](https://www.uber.com/pt-BR/newsroom/uber-lanca-recurso-para-motoristas-bloquearem-conexao-com-usuarios)

### Inferences
- Because the tools ship without fixed defaults, the beginner thresholds in section 3 come from driver and specialist commentary plus cost math, not from the apps.

### Gaps
- "Ganho Certo" was not found in any search result. No information.
- No StopClub/GigU or Rota Pro default R$/km or R$/h values were found.

## 3. Recommended R$/km and R$/hora (UberX, Comfort), beginner vs experienced, pickup, peaks

### Takeaway
The figure that recurs in 2025-26 Brazilian commentary is about **R$ 2/km** as a floor for UberX. Some influencers argue R$ 3/km "should" be the minimum, but that is advocacy, not what the market pays. Practical floors drivers report are R$ 1,60/km off-peak and R$ 2,00/km at peak. For Comfort, drivers cite R$ 1,60-2,00 off-peak up to R$ 2,50/km. Hourly targets of R$ 30-40/h gross (some SP drivers aim for R$ 60/h) appear. The method everyone endorses: cost per km (often R$ 0,60-1,35 depending on car and fuel) × a margin, with pickup km counted.

### Cited Findings
**R$/km**
- Influencer interview: value should be calculated per km because depreciation and wear are per km. "Mínimo justo" is R$ 2/km, with the opinion that R$ 3/km should be today's floor. This is advocacy — [55content entrevista](https://55content.com.br/entrevista/a-uber-nao-quer-que-o-motorista-escolha-corridas-ela-quer-que-ele-aceite-tudo-sem-questionar-quer-que-ele-seja-refem-do-sistema-diz-influenciador/)
- Driver reports: accepts from **R$ 1,60/km** off-peak and **R$ 2/km** at peak. Another driver calculates a cost of R$ 1,35/km and says the ideal is to accept only rides **above R$ 2,50/km**. These quotes appear in Comfort-focused 2025 articles; the snippets were mixed, so the exact article is uncertain — [55content: Quanto ganha um Uber](https://55content.com.br/reportagem/quanto-ganha-um-uber/); [MotorAgora: Comfort 2025](https://www.motoragora.com.br/ganhos-e-dicas-para-uber-comfort/); [ClubMotor: Comfort 2025](https://www.clubmotor.com.br/uber-comfort-em-2025-quanto-ganha-um-motorista-em-8-horas-e-dicas-essenciais-para-trabalhar/)
- Comfort per-km generally runs R$ 1,50-2,00 according to a tips site (generic) — [MotorAgora](https://www.motoragora.com.br/ganhos-e-dicas-para-uber-comfort/)
- Salvador, early 2025 (opinion piece): a Comfort ride that paid R$ 60 now pays R$ 49,95, and per-km fell from R$ 1,80 to R$ 1,43-1,45. Treat as an anecdote — [55content opinião](https://55content.com.br/opiniao/uma-viagem-no-uber-comfort-que-antes-pagava-r-60-agora-e-oferecida-por-r-4995-o-valor-do-km-que-era-r-180-hoje-fica-entre-r143-ou-r145/)
- Comfort cars consume more fuel and cost more to maintain, so Comfort needs a higher floor — [ClubMotor](https://www.clubmotor.com.br/uber-comfort-em-2025-quanto-ganha-um-motorista-em-8-horas-e-dicas-essenciais-para-trabalhar/)
- Comfort eligibility changed in 2025 (car year; minimum driver rating of 4.80 or 4.85 depending on city). Uber published further Black/Comfort changes from January 2026 — [MixVale, nov/2024](https://www.mixvale.com.br/2024/11/12/uber-implementa-mudancas-significativas-nas-categorias-black-e-comfort-para-2025/amp/); [Uber blog jan/2026](https://www.uber.com/pt-BR/blog/mudancas%20-nas-categorias-black-e-comfort-a-partir-de%20-janeiro-2026)
- Cost per km varies widely. GigU example: R$ 1,09 (vehicle) and R$ 1,26 (activity) — [GigU blog](https://gigu.app/br/blog/custo-por-km-motorista-de-aplicativo). An economy car on ethanol computed by a driver: ≈ R$ 0,58/km (fuel-centric), per search summary — [55content: Quanto a Uber cobra por km](https://55content.com.br/motorista/quanto-a-uber-cobra-por-km/)
- Uber per-km pay "triplica dependendo da cidade" — [55content](https://55content.com.br/motorista/quanto-a-uber-cobra-por-km/)
- Uber minimum fare is about R$ 6-8 in many cities, and the commission is commonly 25-40% (third-party, 2024-25) — [Carona BR](https://caronabrasil.com.br/quanto-a-uber-cobra-por-km/)

**R$/hora**
- A São Paulo driver only accepts rides above R$ 20 per 20 minutes, to keep at least **R$ 60/h** — [55content: Quanto ganha um Uber](https://55content.com.br/reportagem/quanto-ganha-um-uber/)
- Uber's own SP estimate (checked 1 Sep 2026): R$ 1.750/week for about 50 h, roughly **R$ 35/h gross** — [Vida de Motorista 2026](https://www.vidademotorista.com.br/posts/ganhos-medios-motorista/)
- Blog ranges: R$ 18-38/h per hour actually worked. SP/RJ peak: R$ 30-40/h net (2025 guide, marketing-grade) — [Vida de Motorista](https://vidademotorista.com.br/ganhos-medios-motorista/); [ProntoPaguei 2025](https://online.prontopaguei.com/posts/quanto-ganha-um-motorista-de-aplicativo-em-2025)
- IBGE (released 2025): app drivers average **R$ 14,40/h** declared income over about 45.9 h/week. This is realized income including idle time, not a per-offer target — [SpaceMoney/IBGE](https://www.spacemoney.com.br/carreiras/renda-motorista-de-aplicativo-ibge)
- GigU: average profit of R$ 15,57/h in metro SP vs R$ 10,11/h inland — [Times Brasil](https://timesbrasil.com.br/brasil/motoristas-de-aplicativo-recebem-ate-r-669-a-menos-por-hora-trabalhada-fora-das-regioes-metropolitanas-revela-levantamento/)

**Pickup, peaks, strategy**
- Pickup km must be added: 10 km trip + 4 km pickup = 14 km of cost — [GigU blog](https://gigu.app/br/blog/custo-por-km-motorista-de-aplicativo); [Guia de Economia Pessoal](https://guiadeeconomiapessoal.com.br/quanto-ganha-motorista-uber-2026/)
- Red rides may lead to higher-demand areas, and green rides may strand you in low-demand areas, so destination matters — [GigU help](https://www.gigu.app/help/ajustando-o-semaforo-inteligente)
- The best hours pay well on both R$/km and R$/h. Peaks are early morning, late afternoon, rain, weekends and events, when surge raises fares — [Rota Pro](https://rotapro.app/guia/melhor-horario-para-rodar-uber/); [Renda Massiva 2026](https://rendamassiva.com.br/2026/08/31/como-ganhar-dinheiro-motorista-de-aplicativo-2026/)
- The common practice is to raise the per-km floor at peak (R$ 1,60 off-peak → R$ 2,00 at peak) — [55content](https://55content.com.br/reportagem/quanto-ganha-um-uber/)
- Uber has changed long-trip pricing in some cities (older posts; check them) — [Uber blog: mudança valor longas viagens](https://www.uber.com/pt-BR/blog/mudanca-valor-longas-viagens)

### Inferences
- **Suggested starting point for a beginner with an economy car (e.g. Onix 1.0) on UberX, synthesized from the sources above.** Run GigU's Lucro Líquido to get your custo do veículo (likely R$ 0,60-1,10/km on gasoline at current prices). Then set:
  - **UberX:** green at ≥ R$ 2,00/km and yellow from about R$ 1,60/km. Hourly goal: green ≥ R$ 40/h, yellow from about R$ 30/h.
  - **Comfort:** green at ≥ R$ 2,30-2,50/km and yellow from about R$ 1,80-2,00/km. Hourly goal: green ≥ R$ 45-50/h.
  - Count pickup km whenever possible.
- Beginners have no history and may need volume, both to learn the city and for acceptance-related perks. So start at the lower end (yellow ≈ cost × 1.5) and tighten to cost × 2 or more once you know demand patterns. Experienced drivers in big capitals cherry-pick harder (R$ 2,50/km+, R$ 60/h).
- Short rides inflate R$/km (because of the minimum fare) but often have poor R$/h once pickup is included. Long rides do the opposite and carry the risk of a dead return. Use both goals together, which is what the Semáforo does.
- Thresholds vary by city. Inland cities pay roughly 35% less per hour (GigU data), so a fixed "R$ 2/km" may reject most offers outside capitals.

### Gaps
- No Reddit r/motoristasdeapp or Facebook-group threads surfaced in search. No YouTube transcripts could be read. Forum consensus is therefore represented only via press quotes.
- No 2026-dated systematic survey of thresholds. Most numeric quotes are from 2025.
- The "R$ 2/km rule" is widely referenced but has no single authoritative source.

## 4. Passenger rating cut-off

### Takeaway
The Brazilian average passenger rating is about 4.88-4.90, so most riders sit around 4.8-5.0. Common driver heuristics: below 4.7 is "problemático", 4.9 and above is "excelente". Rota Pro uses a 4.30 "ruim" and 4.90 "aceitar" scheme. A brand-new 5.0 account is viewed with suspicion. Uber warns that a minimum-rating filter cuts offer volume. A cut-off around 4.7-4.75 (UberX) and 4.8 (Comfort, at night or for beginners worried about safety) is a reasonable synthesis.

### Cited Findings
- Uber stated the average passenger rating in Brazil was **4.88** (older press, around 2019-2022) — [Uber newsroom](https://www.uber.com/br/pt-br/newsroom/381369/); [Folha PE](https://www.folhape.com.br/colunistas/tecnologia-e-games/uber-permitira-que-passageiros-vejam-as-classificacoes-dadas-por-motoristas-media-nacional-e-de-488/29669/)
- A 2025 article cites a Brazilian average of 4.90 — [Olhar Digital, jun/2025](https://olhardigital.com.br/2025/06/18/dicas-e-tutoriais/10-motivos-que-levam-motoristas-da-uber-a-darem-nota-baixa-a-passageiros/)
- Uber says passengers who don't keep a minimum rating can be deactivated, and a 1-star rating prevents future matching between those two users — [Uber blog: critérios de qualidade usuários](https://www.uber.com/pt-BR/blog/criterios-qualidade-usuarios)
- Sources disagree on how the rating is computed: last 500 trips vs all trips. Few-trip accounts swing more — [Uber blog](https://www.uber.com/pt-BR/blog/veja-como-funciona-e-para-que-serve-a-avaliacao-da-uber); [Uber: critérios](https://www.uber.com/pt-BR/blog/criterios-qualidade-usuarios)
- Informal driver heuristic: ≥ 4.90 is "excelente", < 4.70 is "problemático". A 5.0 is "mal vista" because it is probably a new account, with some drivers citing scam risk (opinion, Threads) — [Threads post](https://www.threads.com/@adriarocais/post/DGIlIBcuBuC)
- Rota Pro: < 4.30 is "ruim", ≥ 4.90 is "aceitar". New passengers have little history — [Rota Pro](https://rotapro.app/guia/motorista-5-estrelas-uber/)
- Guides say below 4.6, or below 4.5, drivers tend to refuse. One beginner blog uses < 4.0 as its safety cut-off — [Gazeta do Povo](https://www.gazetadopovo.com.br/economia/nova-economia/motoristas-e-passageiros-precisam-ter-nota-boa-na-uber-saiba-o-motivo-8parzxdyinebbyz2m8plwie3i/); [Gringo blog](https://gringo.com.vc/blog/dicas-para-motorista-de-uber-iniciante/)
- Uber's own minimum-rating preference: "ao limitar a nota mínima, o motorista também limita o número de chamados" — [Uber blog: preferência de nota](https://www.uber.com/pt-BR/blog/preferencia-de-nota/)
- GigU's Semáforo takes "nota do passageiro" into account — [Reclame Aqui reply](https://www.reclameaqui.com.br/stopclub-tecnologia-solucoes-e-servicos/alertas-de-valor-por-km-incorretos-no-aplicativo-gigu_wLSOEjVrKeIHGs26/)
- Common reasons drivers give low ratings: delays, rudeness, mess, extra stops — [Olhar Digital](https://olhardigital.com.br/2025/06/18/dicas-e-tutoriais/10-motivos-que-levam-motoristas-da-uber-a-darem-nota-baixa-a-passageiros/)

### Inferences
- With an average around 4.88-4.90, a 4.9 cut-off would likely discard roughly half of offers. 4.85 is still restrictive. **4.7-4.75** filters the problematic tail while keeping volume, which suits UberX beginners. **4.8** for Comfort, late night, or risky areas.
- Treat 5.0 with few trips as "unknown", not "great". Do not use rating as the sole criterion; combine it with R$/km and R$/h.

### Gaps
- No public data on the distribution of passenger ratings (the share above 4.8 etc.) in Brazil.
- I couldn't find GigU's slider range or default for the passenger-rating filter.
- No 2025-26 Uber Brazil statement on the current status of the Rider Ratings Preference.
