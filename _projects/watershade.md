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
    .ws section{margin:clamp(.55rem,1.2vw,.9rem) 0;}
    .ws h2{
      font-family:var(--display);font-weight:500;font-optical-sizing:auto;
      font-size:clamp(1.7rem,4vw,2.2rem);line-height:1.12;letter-spacing:-.01em;
      margin:0 0 .5rem;color:var(--ink);
    }
    .ws p{margin:0 0 .4rem;}
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
    .ws-document-links{display:flex;flex-wrap:wrap;gap:.65rem;margin-top:.25rem;}
    .ws-document-link{display:inline-block;padding:.6rem .85rem;background:var(--teal);color:#fff;text-decoration:none;font-weight:500;border-radius:3px;}
    .ws-document-link:hover{background:var(--river);}
    .ws-document-link--secondary{background:var(--river);}
    .ws-partner-links{display:flex;flex-wrap:wrap;gap:.55rem;margin:.85rem 0 0;}
    .ws-partner-links a{color:var(--teal);font-weight:500;text-decoration-thickness:1px;text-underline-offset:3px;}

    /* ---- Emplacements image (a remplacer) ---- */
    .ws-fig{margin:clamp(.55rem,1.2vw,.9rem) auto;max-width:880px;padding:0 24px;}
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

  <div data-lang="fr">
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
      <p>Les changements climatiques et l’utilisation du territoire influencent ensemble l’hétérogénéité de la température de l’eau. La revue de littérature WaterShade souligne notamment le rôle de la foresterie, du couvert riverain, des routes, du drainage et des apports d’eau souterraine dans la qualité thermique des cours d’eau.</p>
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
      <p>D’autres documents du projet, dont la revue de littérature, se trouvent dans la section Documentation WaterShade pour référence.</p>
      <div class="ws-document-links">
        <a class="ws-document-link" href="{{ '/resources/research/' | relative_url }}">Voir la documentation WaterShade</a>
      </div>
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
      <h2>Quatre années pour faire progresser WaterShade</h2>
      <p>De 2023 à 2026, les projets financés par la Fondation pour la conservation du saumon atlantique ont fait évoluer WaterShade d’un cadre de gestion à des plans de conservation adaptés aux sous-bassins versants. Il s’agit d’un projet de longue haleine : la stratégie de gestion et le plan d’implantation offrent une base commune appelée à évoluer avec les nouvelles données, les résultats de terrain, les connaissances des partenaires et les conditions changeantes du bassin versant.</p>
      <ol class="ws-steps">
        <li><span class="n">2023</span><div><h3>Établir une base commune</h3><p>Élaboration de la stratégie de gestion des refuges thermiques et du plan d’implantation qui oriente la protection, la mise en valeur et la recherche appliquée.</p></div></li>
        <li><span class="n">2024</span><div><h3>Cartographier et caractériser</h3><p>Recensement géomatique par type, présélection des refuges, analyse des bandes riveraines et des aires de drainage, validation terrain, imagerie par drone et suivi de température.</p></div></li>
        <li><span class="n">2025</span><div><h3>Cibler les actifs prioritaires</h3><p>Élaboration de plans de conservation pour les sous-bassins sélectionnés, caractérisation des régimes thermiques et acquisition continue de données pour orienter les interventions.</p></div></li>
        <li><span class="n">2026</span><div><h3>Optimiser les plans de conservation</h3><p>Mise à jour des plans, ajout des données de débit, poursuite des suivis thermiques et collaboration avec le ministère afin d’arrimer les actions de gestion.</p></div></li>
      </ol>
    </div>
  </section>

  <!-- ===================== PARTENARIATS ===================== -->
  <section class="ws-reveal">
    <div class="ws-in">
      <h2>Une démarche portée par des partenariats</h2>
      <p>WaterShade est conçu spécifiquement pour le Nouveau-Brunswick par le Conseil de gestion du bassin versant de la rivière Restigouche et le Gespe’gewa’gi Institute of Natural Understanding (GINU). LeBlanc MultiRessources agit comme collaborateur et fait partie de l’équipe de travail, en permettant l’articulation sur le terrain lors des campagnes d’acquisition de données.</p>
      <p>Au Québec, le projet Garde-la frette!, chapeauté par l’Organisme de bassin versant Matapédia-Restigouche (OBVMR), complète l’approche de protection des refuges thermiques en mobilisant les connaissances et les acteurs du territoire. Ensemble, ces initiatives soutiennent une protection cohérente des eaux froides à l’échelle du bassin versant de la Restigouche.</p>
      <p class="ws-partner-links"><a href="https://www.matapediarestigouche.org/garde-la-frette" target="_blank" rel="noopener">Découvrir Garde-la frette! de l’OBVMR</a><a href="https://ginu.co/?p=2902" target="_blank" rel="noopener">Découvrir le projet Thermal Refuge de GINU</a></p>
    </div>
  </section>


  </div>

  <div data-lang="en">
  <header class="ws-hero ws-reveal"><svg class="ws-mark" viewBox="0 0 80 40" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" aria-hidden="true"><path d="M2 12c10-8 18 8 28 0s18 8 28 0 18 8 20 6"/><path d="M2 24c10-8 18 8 28 0s18 8 28 0 18 8 20 6"/></svg><p class="ws-eyebrow">Strategic project</p><h1>WaterShade</h1><p class="ws-lead">Protecting cold-water refuges in the Restigouche River watershed.</p><p class="intro">When the river warms in summer, Atlantic salmon seek naturally cooler areas to reduce thermal stress. WaterShade is a watershed-scale strategy that brings together protection, refuge enhancement, stewardship and research to sustain these essential habitats over time.</p></header>
  <section class="ws-reveal"><div class="ws-in"><h2>Warmer summers, a river under pressure</h2><p>Summer temperatures in the Restigouche have risen, especially over the last decade. During hot, low-flow periods, some parts of the river become difficult for Atlantic salmon, a cold-water fish, to tolerate.</p><p>The clearest signal is the number of thermal-stress days for adult salmon. Between 2003 and 2017, there were always <span class="num">fewer than 15</span> per summer. In 2018, 2020 and 2021, that number <span class="heat">exceeded 30</span>.</p><p>Climate change and land use together influence water-temperature heterogeneity. The WaterShade literature review highlights the roles of forestry, riparian cover, roads, drainage and groundwater inputs in the thermal quality of watercourses.</p></div></section>
  <figure class="ws-fig ws-reveal"><img src="{{ '/assets/img/watershade/watershade1.webp' | relative_url }}" alt="Shaded reach of the Restigouche River"><figcaption>A healthy river and wooded banks: the first line of defence for cold-water refuges.</figcaption></figure>
  <section class="ws-reveal"><div class="ws-in"><h2>Understanding cold-water refuges</h2><p>The WaterShade placemat gives an at-a-glance overview of cold-water refuges, water-warming pressures and the actions that help protect them.</p><p>Other project documents, including the literature review, are available in the WaterShade documentation section for reference.</p><div class="ws-document-links"><a class="ws-document-link" href="{{ '/resources/research/' | relative_url }}">View WaterShade documentation</a></div></div></section>
  <section class="ws-reveal"><div class="ws-in"><h2>Four pillars for watershed-scale action</h2><p>The WaterShade management strategy and implementation plan organize work around four complementary pillars.</p><ol class="ws-steps">
    <li><div class="ws-step-media"><span class="n">01</span><img class="ws-step-photo" src="{{ '/assets/img/watershade/watershade-pillar-protection.jpg' | relative_url }}" alt="Confluence pre-selection map for cold-water refuge protection" loading="lazy"></div><div><h3>Protect refuges and their drainage areas</h3><p>Map, characterize and prioritize cold-water refuges, then guide protection of upstream watercourses, riparian areas and land uses that support their function.</p></div></li>
    <li><div class="ws-step-media"><span class="n">02</span><img class="ws-step-photo" src="{{ '/assets/img/watershade/watershade-pillar-enhancement.jpg' | relative_url }}" alt="Field test to enhance a cold-water refuge" loading="lazy"></div><div><h3>Enhance and restore targeted habitats</h3><p>Where conditions are suitable, design site-specific measures to strengthen cold-water inputs, riparian areas and habitat quality, with the necessary approvals.</p></div></li>
    <li><div class="ws-step-media"><span class="n">03</span><img class="ws-step-photo" src="{{ '/assets/img/watershade/watershade-pillar-stewardship.jpg' | relative_url }}" alt="Cold-water refuge research supporting stewardship" loading="lazy"></div><div><h3>Advance stewardship and knowledge sharing</h3><p>Work with communities, landowners, land users and governments to encourage practices that protect refuges over the long term.</p></div></li>
    <li><div class="ws-step-media"><span class="n">04</span><img class="ws-step-photo" src="{{ '/assets/img/watershade/watershade-pillar-research.png' | relative_url }}" alt="LiDAR data used for applied research" loading="lazy"></div><div><h3>Advance applied research</h3><p>Combine thermal imagery, LiDAR, temperature monitoring, drones and field validation to better understand thermal regimes and guide future decisions.</p></div></li>
  </ol></div></section>
  <section class="ws-reveal"><div class="ws-in"><h2>Four years of advancing WaterShade</h2><p>From 2023 to 2026, projects funded by the Atlantic Salmon Conservation Foundation have advanced WaterShade from a management framework to sub-watershed-specific conservation plans. This is long-term work: the management strategy and implementation plan provide a shared foundation that will evolve with new data, field results, partner knowledge and changing conditions across the watershed.</p><ol class="ws-steps">
    <li><span class="n">2023</span><div><h3>Establishing a shared foundation</h3><p>Development of the thermal-refuge management strategy and implementation plan guiding protection, enhancement and applied research.</p></div></li>
    <li><span class="n">2024</span><div><h3>Mapping and characterizing</h3><p>Geospatial inventory by type, refuge pre-selection, riparian-area and drainage-area analysis, field validation, drone imagery and temperature monitoring.</p></div></li>
    <li><span class="n">2025</span><div><h3>Focusing on priority assets</h3><p>Development of conservation plans for selected sub-watersheds, thermal-regime characterization and ongoing data collection to guide interventions.</p></div></li>
    <li><span class="n">2026</span><div><h3>Optimizing conservation plans</h3><p>Plan updates, addition of flow data, continued thermal monitoring and collaboration with the department to align management actions.</p></div></li>
  </ol></div></section>
  <section class="ws-reveal"><div class="ws-in"><h2>A partnership-driven approach</h2><p>WaterShade is designed specifically for New Brunswick by the Restigouche River Watershed Management Council and the Gespe’gewa’gi Institute of Natural Understanding (GINU). LeBlanc MultiRessources is a collaborator and part of the working team, helping coordinate field operations during data-acquisition campaigns.</p><p>In Quebec, Garde-la frette!, led by the Organisme de bassin versant Matapédia-Restigouche (OBVMR), complements the thermal-refuge protection approach by bringing together knowledge and people from across the territory. Together, these initiatives support coherent protection of cold water across the Restigouche watershed.</p><p class="ws-partner-links"><a href="https://www.matapediarestigouche.org/garde-la-frette" target="_blank" rel="noopener">Explore OBVMR’s Garde-la frette! page</a><a href="https://ginu.co/?p=2902" target="_blank" rel="noopener">Explore GINU’s Thermal Refuge project</a></p></div></section>

  </div>
</article>
