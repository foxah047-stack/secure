---
layout: default
title: WaterShade
lang: fr
permalink: /projects/watershade/
status: published
featured: true
order: 1
title_en: WaterShade
title_fr: WaterShade
subtitle_en: A watershed-scale strategy to protect cold-water refuges for Atlantic salmon in the Restigouche River watershed.
subtitle_fr: Une stratégie à l’échelle du bassin versant pour protéger les refuges d’eau froide du saumon atlantique.
card_image: /assets/img/watershade/watershade1.webp
card_alt_fr: Rivière Restigouche bordée d'une végétation riveraine
card_alt_en: Restigouche River bordered by riparian vegetation
---

<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Fraunces:opsz,wght@9..144,400;9..144,500;9..144,600&family=Spectral:ital,wght@0,300;0,400;0,500;1,400&display=swap" rel="stylesheet">

<article class="ws">
  <style>
    .ws{
      /* ---- Reglages rapides : couleurs et polices ---- */
      --paper:#FAF6EE;        /* fond papier chaud */
      --panel:#F0E9DC;        /* panneaux / emplacements image */
      --ink:#1C2A2A;          /* texte principal (presque noir, teinte ardoise) */
      --muted:#5B6A68;        /* texte secondaire */
      --teal:#2B6660;         /* eau froide — accent principal */
      --river:#4E8A93;        /* bleu-vert rivière */
      --ember:#B0562C;        /* note de chaleur — usage rare, signal seulement */
      --rule:rgba(28,42,42,.16);
      --display:"Fraunces",Georgia,"Times New Roman",serif;
      --body:"Spectral",Georgia,"Times New Roman",serif;

      background:var(--paper);
      color:var(--ink);
      font-family:var(--body);
      font-weight:400;
      font-size:1.075rem;
      line-height:1.62;
      letter-spacing:.002em;
      padding:clamp(1.4rem,3vw,2.2rem) 0 clamp(1.6rem,3.5vw,2.6rem);
      -webkit-font-smoothing:antialiased;
    }
    .ws *{box-sizing:border-box;}
    .ws-in{max-width:680px;margin:0 auto;padding:0 24px;}

    /* ---- Hero ---- */
    .ws-hero{max-width:760px;margin:0 auto clamp(1.1rem,2.4vw,1.7rem);padding:0 24px;}
    .ws-mark{width:54px;height:auto;color:var(--river);opacity:.85;margin-bottom:.65rem;}
    .ws-eyebrow{
      font-family:var(--body);font-weight:500;font-size:.78rem;
      letter-spacing:.18em;text-transform:uppercase;color:var(--teal);
      margin:0 0 .5rem;
    }
    .ws h1{
      font-family:var(--display);font-weight:500;font-optical-sizing:auto;
      font-size:clamp(2.9rem,8vw,4.6rem);line-height:.98;letter-spacing:-.015em;
      margin:0 0 .55rem;color:var(--ink);
    }
    .ws-lead{
      font-family:var(--display);font-weight:400;
      font-size:clamp(1.3rem,3.2vw,1.65rem);line-height:1.32;
      color:var(--teal);margin:0 0 .75rem;max-width:34ch;
    }
    .ws-hero p.intro{font-size:1.15rem;color:var(--ink);margin:0;max-width:60ch;}

    /* ---- Rythme general ---- */
    .ws section{margin:clamp(1.1rem,2.5vw,1.8rem) 0;}
    .ws h2{
      font-family:var(--display);font-weight:500;font-optical-sizing:auto;
      font-size:clamp(1.7rem,4vw,2.2rem);line-height:1.12;letter-spacing:-.01em;
      margin:0 0 .5rem;color:var(--ink);
    }
    .ws p{margin:0 0 .55rem;}
    .ws p:last-child{margin-bottom:0;}
    .ws strong{font-weight:500;color:var(--ink);}
    .ws .num{font-weight:500;color:var(--teal);white-space:nowrap;}
    .ws .heat{color:var(--ember);font-weight:500;}

    /* ---- Demarche en 4 temps (sans boites) ---- */
    .ws-steps{list-style:none;margin:.75rem 0 0;padding:0;}
    .ws-steps li{
      display:grid;grid-template-columns:auto 1fr;gap:.75rem;
      align-items:baseline;padding:.7rem 0;border-top:1px solid var(--rule);
    }
    .ws-steps li:last-child{border-bottom:1px solid var(--rule);}
    .ws-steps .n{
      font-family:var(--display);font-weight:400;font-size:2.1rem;
      line-height:1;color:var(--river);opacity:.65;font-variant-numeric:lining-nums;
    }
    .ws-steps h3{
      font-family:var(--display);font-weight:500;font-size:1.22rem;
      margin:0 0 .15rem;color:var(--ink);
    }
    .ws-steps p{margin:0;color:var(--muted);font-size:1rem;}
    .ws-step-media{display:grid;gap:.45rem;align-content:start;}
    .ws-step-photo{display:block;width:120px;height:86px;object-fit:cover;border:1px solid var(--rule);border-radius:3px;}
    .ws-document-link{display:inline-block;margin-top:.25rem;padding:.6rem .85rem;background:var(--teal);color:#fff;text-decoration:none;font-weight:500;border-radius:3px;}
    .ws-document-link:hover{background:var(--river);}

    /* ---- Emplacements image (a remplacer) ---- */
    .ws-fig{margin:clamp(1rem,2.5vw,1.7rem) auto;max-width:880px;padding:0 24px;}
    .ws-ph{
      position:relative;aspect-ratio:16/10;background:var(--panel);
      border:1px solid var(--rule);border-radius:3px;
      display:flex;flex-direction:column;align-items:center;justify-content:center;
      text-align:center;padding:.9rem;gap:.35rem;overflow:hidden;
    }
    .ws-ph svg{width:46px;height:auto;color:var(--river);opacity:.5;}
    .ws-ph .tag{
      font-family:var(--body);font-weight:500;font-size:.72rem;
      letter-spacing:.16em;text-transform:uppercase;color:var(--teal);opacity:.8;
    }
    .ws-ph .desc{font-size:.95rem;color:var(--muted);max-width:34ch;margin:0;}
    .ws figcaption{
      font-size:.88rem;font-style:italic;color:var(--muted);
      margin-top:.35rem;text-align:center;
    }
    /* Pour publier une vraie photo : retirer .ws-ph et activer l'<img> dans le HTML. */
    .ws-fig img{width:100%;height:auto;display:block;border-radius:3px;}

    /* ---- Sites associes (seul endroit avec des panneaux) ---- */
    .ws-sites{display:grid;grid-template-columns:1fr 1fr;gap:.75rem;margin-top:.75rem;}
    .ws-site{
      background:var(--paper);border:1px solid var(--rule);border-top:3px solid var(--teal);
      border-radius:3px;padding:.9rem 1rem;
    }
    .ws-site h3{font-family:var(--display);font-weight:500;font-size:1.3rem;margin:0 0 .3rem;}
    .ws-site p{font-size:1rem;color:var(--muted);margin:0 0 .45rem;}
    .ws-site .soon{
      font-family:var(--body);font-weight:500;font-size:.74rem;
      letter-spacing:.13em;text-transform:uppercase;color:var(--teal);
    }

    /* ---- Note sensibilite ---- */
    .ws-note{
      border-left:3px solid var(--river);background:rgba(78,138,147,.07);
      padding:.65rem .85rem;border-radius:0 3px 3px 0;
      font-size:.98rem;color:var(--muted);max-width:60ch;
    }
    .ws-note p{margin:0;}

    /* ---- Cloture ---- */
    .ws-close{border-top:1px solid var(--rule);padding-top:clamp(.8rem,2vw,1.2rem);}

    @media (max-width:620px){
      .ws-sites{grid-template-columns:1fr;}
      .ws-steps li{grid-template-columns:1fr;gap:.35rem;}
      .ws-steps .n{font-size:1.6rem;}
      .ws-step-photo{width:100%;height:160px;}
    }

    /* ---- Apparition douce au chargement ---- */
    @media (prefers-reduced-motion:no-preference){
      .ws-reveal{opacity:0;transform:translateY(14px);animation:wsUp .7s ease forwards;}
      .ws-reveal:nth-of-type(1){animation-delay:.05s;}
      .ws-reveal:nth-of-type(2){animation-delay:.13s;}
      .ws-reveal:nth-of-type(3){animation-delay:.21s;}
      .ws-reveal:nth-of-type(n+4){animation-delay:.28s;}
      @keyframes wsUp{to{opacity:1;transform:none;}}
    }
  </style>

  <!-- ===================== HERO ===================== -->
  <header class="ws-hero ws-reveal">
    <svg class="ws-mark" viewBox="0 0 80 40" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" aria-hidden="true">
      <path d="M2 12c10-8 18 8 28 0s18 8 28 0 18 8 20 6"/>
      <path d="M2 24c10-8 18 8 28 0s18 8 28 0 18 8 20 6"/>
    </svg>
    <p class="ws-eyebrow">Projet stratégique</p>
    <h1>WaterShade</h1>
    <p class="ws-lead">Protéger les refuges d’eau froide du bassin versant de la Restigouche.</p>
    <p class="intro">Quand la rivière se réchauffe l’été, le saumon atlantique cherche des zones naturellement plus fraîches pour réduire son stress thermique. WaterShade est une stratégie de bassin versant qui réunit la protection, l’amélioration des refuges, l’intendance et la recherche pour préserver ces habitats essentiels dans la durée.</p>
  </header>

  <!-- ===================== LE PROBLEME ===================== -->
  <section class="ws-reveal">
    <div class="ws-in">
      <h2>Des étés plus chauds, une rivière sous pression</h2>
      <p>Les températures estivales de la Restigouche augmentent, surtout depuis une dizaine d’années. Pendant les périodes de chaleur et de faible débit, certaines sections de la rivière deviennent difficiles à supporter pour le saumon atlantique, un poisson d’eau froide.</p>
      <p>Le signe le plus parlant est le nombre de journées de stress thermique pour le saumon adulte. Entre 2003 et 2017, on en comptait toujours <span class="num">moins de 15</span> par été. En 2018, 2020 et 2021, ce nombre a <span class="heat">dépassé 30</span>.</p>
    </div>
  </section>

  <!-- ===================== IMAGE 1 ===================== -->
  <figure class="ws-fig ws-reveal">
    <img src="{{ '/assets/img/watershade/watershade1.webp' | relative_url }}" alt="Section ombragée de la rivière Restigouche">
    <figcaption>Une rivière en santé et des berges boisées : la première ligne de défense des refuges d’eau froide.</figcaption>
  </figure>

  <!-- ===================== NAPPERON ===================== -->
  <section class="ws-reveal">
    <div class="ws-in">
      <h2>Comprendre les refuges d’eau froide</h2>
      <p>Le napperon WaterShade présente, en un coup d’œil, les refuges d’eau froide, les enjeux liés au réchauffement de l’eau et les gestes qui contribuent à les protéger.</p>
      <a class="ws-document-link" href="{{ '/assets/docs/watershade-napperon-2025.pdf' | relative_url }}" target="_blank" rel="noopener">Consulter le napperon WaterShade (PDF)</a>
    </div>
  </section>

  <!-- ===================== LES QUATRE PILIERS ===================== -->
  <section class="ws-reveal">
    <div class="ws-in">
      <h2>Quatre piliers pour agir à l’échelle du bassin versant</h2>
      <p>La stratégie de gestion WaterShade et son plan d’implantation organisent les interventions autour de quatre piliers complémentaires.</p>
      <ol class="ws-steps">
        <li>
          <div class="ws-step-media">
            <span class="n">01</span>
            <img class="ws-step-photo" src="{{ '/assets/img/watershade/watershade-pillar-protection.jpg' | relative_url }}" alt="Carte de présélection de confluences pour la protection des refuges d’eau froide" loading="lazy">
          </div>
          <div>
            <h3>Protéger les refuges et leurs bassins de drainage</h3>
            <p>Cartographier, caractériser et prioriser les refuges d’eau froide, puis orienter la protection des cours d’eau d’amont, des bandes riveraines et des usages du territoire qui soutiennent leur fonction.</p>
          </div>
        </li>
        <li>
          <div class="ws-step-media">
            <span class="n">02</span>
            <img class="ws-step-photo" src="{{ '/assets/img/watershade/watershade-pillar-enhancement.jpg' | relative_url }}" alt="Essai terrain pour améliorer un refuge d’eau froide" loading="lazy">
          </div>
          <div>
            <h3>Améliorer et restaurer les habitats ciblés</h3>
            <p>Lorsque les conditions s’y prêtent, concevoir des mesures adaptées au site pour renforcer les apports d’eau froide, les zones riveraines et la qualité de l’habitat, avec les autorisations nécessaires.</p>
          </div>
        </li>
        <li>
          <div class="ws-step-media">
            <span class="n">03</span>
            <img class="ws-step-photo" src="{{ '/assets/img/watershade/watershade-pillar-stewardship.jpg' | relative_url }}" alt="Recherche sur les refuges d’eau froide au soutien de l’intendance" loading="lazy">
          </div>
          <div>
            <h3>Favoriser l’intendance et le partage des connaissances</h3>
            <p>Travailler avec les collectivités, les propriétaires, les utilisateurs du territoire et les gouvernements afin d’encourager des pratiques qui protègent les refuges à long terme.</p>
          </div>
        </li>
        <li>
          <div class="ws-step-media">
            <span class="n">04</span>
            <img class="ws-step-photo" src="{{ '/assets/img/watershade/watershade-pillar-research.png' | relative_url }}" alt="Données LiDAR utilisées pour la recherche appliquée" loading="lazy">
          </div>
          <div>
            <h3>Faire progresser la recherche appliquée</h3>
            <p>Combiner imagerie thermique, LiDAR, suivis de température, drones et validation terrain pour mieux comprendre les régimes thermiques et guider les décisions futures.</p>
          </div>
        </li>
      </ol>
    </div>
  </section>


  <!-- ===================== L'ECHELLE ===================== -->
  <section class="ws-reveal">
    <div class="ws-in">
      <h2>Une stratégie à l’échelle du bassin versant</h2>
      <p>Le bassin versant de la Restigouche couvre environ <span class="num">12 800 km²</span>, partagés entre le Nouveau-Brunswick et le Québec. WaterShade se concentre sur la portion néo-brunswickoise, en grande partie forestière.</p>
      <p>Le travail s’appuie sur un inventaire de grande ampleur : près de <span class="num">862 km</span> de rivière ont été survolés en imagerie optique et thermique, ce qui a permis de classer <span class="num">1 825 anomalies thermiques</span> dans l’ensemble du bassin. À partir de là, la démarche vise à cibler une <strong>trentaine de bassins de drainage</strong> à protéger ou à restaurer, dont <strong>cinq sites prioritaires</strong>.</p>
    </div>
  </section>

  <!-- ===================== PARTENARIATS ===================== -->
  <section class="ws-reveal">
    <div class="ws-in">
      <h2>Une démarche portée par des partenariats</h2>
      <p>WaterShade est élaboré par le Conseil de gestion du bassin versant de la rivière Restigouche, le Gespe’gewa’gi Institute of Natural Understanding (GINU) et LeBlanc MultiRessources. Cette équipe de travail réunit la connaissance du territoire, l’expertise scientifique et l’expérience de mise en œuvre.</p>
      <div class="ws-sites">
        <div class="ws-site">
          <h3>Science, données et coordination</h3>
          <p>Le projet bénéficie de l’appui scientifique de l’Université du Nouveau-Brunswick et de l’INRS – Centre Eau Terre Environnement, ainsi que d’une collaboration avec l’Organisme de bassin versant Matapédia-Restigouche.</p>
          <span class="soon">Une approche à l’échelle du bassin</span>
        </div>
        <div class="ws-site">
          <h3>Application sur le territoire</h3>
          <p>La collaboration avec le ministère des Ressources naturelles et du Développement de l’énergie du Nouveau-Brunswick aide à relier les données, les pratiques de gestion et la protection des refuges d’eau froide.</p>
          <span class="soon">Des décisions informées par le terrain</span>
        </div>
      </div>
    </div>
  </section>


  <!-- ===================== NOTE SENSIBILITE ===================== -->
  <section class="ws-reveal">
    <div class="ws-in">
      <div class="ws-note">
        <p>Par souci de conservation, l’emplacement précis de certains refuges n’est pas diffusé publiquement. Les cartes et images présentées ici restent volontairement générales.</p>
      </div>
    </div>
  </section>

  <!-- ===================== CLOTURE ===================== -->
  <section class="ws-reveal">
    <div class="ws-in ws-close">
      <h2>Une stratégie qui s’adapte et se construit dans le temps</h2>
      <p>La stratégie de gestion et le plan d’implantation constituent une première base commune. WaterShade évolue avec les nouvelles données, les résultats de terrain, les connaissances des partenaires et les conditions changeantes du bassin versant. Les emplacements précis de certains refuges demeurent confidentiels afin de protéger les poissons qui y trouvent refuge.</p>
    </div>
  </section>

</article>
