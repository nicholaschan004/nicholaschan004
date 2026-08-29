## Hi, I'm Nicholas 👋

I graduated from UC Davis with a B.S. in Computer Science.

Most of what I make starts with someone I know needing something that does not exist yet,
so the projects below are less portfolio pieces than things people actually use.

When I am not building, I am playing basketball or volleyball, or in the gym somewhere in
between.

### Things I've built

**[Tsuru Sushi](https://github.com/nicholaschan004/TsuruSushi)** &nbsp;·&nbsp; restaurant site
&nbsp;→&nbsp; [tsurusushi.com](https://tsurusushi.com)

Menu, hours and daily specials for a Japanese sushi kitchen. The owner edits a Google
Sheet and the site rebuilds itself, so there is no CMS to log into and no developer in the
loop for a price change.

`React` `Vite` `Radix UI` `Google Sheets` `Cloudflare Pages`

**[Ray Chan Tattoo](https://github.com/nicholaschan004/RayChanTattoo)** &nbsp;·&nbsp; portfolio and booking site
&nbsp;→&nbsp; [raychantattoo.com](https://www.raychantattoo.com)

Gallery and booking flow for a tattoo artist. The build downloads the artist's photos from
a Google Sheet and resizes them into local WebP, so the live site serves its own optimised
images instead of waiting on full resolution files from Google Drive.

`React` `Vite` `Tailwind` `sharp` `Google Sheets` `Vercel`

**[Consensus](https://github.com/nicholaschan004/Consensus)** &nbsp;·&nbsp; anonymous live voting for group decisions
&nbsp;→&nbsp; [consensus-vote.vercel.app](https://consensus-vote.vercel.app)

A host opens a session, the room joins from their phones with a six digit code, and votes
are tallied live without anyone being able to tell who voted what. One member one vote is
enforced atomically in Redis rather than in application code, and the running tally is
withheld from members until the host closes the round, because watching the count climb is
exactly what a secret ballot prevents.

`React` `TypeScript` `Vite` `Vercel Functions` `Upstash Redis`

### Currently building

A collectibles marketplace with a double entry ledger, live payments and a server
authoritative economy &nbsp;→&nbsp; [swaggystadium.com](https://swaggystadium.com)

The repository is private while the site is in closed beta.

Thanks for stopping by. Have a look around.
