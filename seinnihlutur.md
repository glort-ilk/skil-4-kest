# Gitsvör

## Hvað gera eftirfarandi Linux skipanir?

**cd -** Skipunin fer aftur í fyrra skráarsafn sem notandinn var í.

**ls -** Sýnir lista af skrám og möppum í núverandi skráarsafni.

**pwd -** Sýnir slóðina á núverandi skráarsafni.

**mkdir -** Býr til nýja möppu.


## Hvað gera eftirfarandi Git skipanir?

**git clone** Afritar Git geymslu af netinu yfir í staðvært kerfi.

**git status** Sýnir stöðu skráa í geymslunni, hvort þær hafi breyst eða séu óskráðar.

**git diff** Sýnir muninn á skráarsafni í mismunandi áföngum (t.d. á milli commit-a).


## Hvað gera eftirfarandi Git skipanir saman? Hvaða gagn er að þeirri aðgerð?

**git log** Sýnir lista yfir allar fyrri færslur (commit) í Git geymslunni.

**git checkout** Leyfir notandanum að skipta á milli útgáfa (branches) eða fyrri commit-a.

**git branch** Sýnir lista yfir útibú (branches) í verkefninu og leyfir notandanum að búa til ný.

Þessar skipanir saman hjálpa til við að skoða sögu verkefnisins, skipta um útibú og vinna með mismunandi útgáfur af verkefninu.


## Hvað er útgáfustýring (Version Control)?

Útgáfustýring er kerfi sem heldur utan um breytingar á skrám með tímanum, sem gerir notendum kleift að endurheimta fyrri útgáfur, vinna saman í teymi og halda utan um breytingar í verkefnum.


## Hverjir eru helstu kostir við að nota GIT?

- Heldur utan um allar breytingar á verkefnum.
- Leyfir mörgum að vinna saman á skilvirkan hátt.
- Stuðningur við útibú (branches) til að skipta upp vinnu.
- Öryggi, þar sem engar upplýsingar tapast auðveldlega.
- Einfalt að deila og geyma verkefni á GitHub.


## Hversu oft telur þú að eigi að gera færslur (commit) í verkefni?

Það er best að gera commit eftir hverja merkingarbæra breytingu, svo sem þegar:
- Ný virkni er bætt við.
- Villuleiðréttingar eru gerðar.
- Umbætur á kóða eru gerðar.
- Stórir hlutar verkefnisins eru kláraðir.


## Hvað er átt við með “Working Directory” og “Staging Area” í GIT?

**Working Directory** er staðurinn þar sem notandinn vinnur með skrárnar áður en þær eru settar í Git.

**Staging Area** er svæðið þar sem breytingar eru undirbúnar fyrir næsta commit með `git add` skipuninni.
