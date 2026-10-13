---
layout: project
title: modele-predictif-temperature-protocole-eau-chaude
status: published
featured: true
order: 7
title_fr: Modèle prédictif de température pour le protocole d’eau chaude
title_en: Water temperature forecasting model for the Warm Water Protocol
subtitle_fr: Anticiper les épisodes de chaleur pour mieux protéger le saumon atlantique et soutenir les décisions de gestion de la pêche.
subtitle_en: Anticipating warm-water events to better protect Atlantic salmon and support angling-management decisions.
hero_image: /assets/img/warm-water-protocol/saumon.jpg
hero_alt_fr: Saumon atlantique dans son habitat naturel
hero_alt_en: Atlantic salmon in its natural habitat
hero_caption_fr: Protéger le saumon pendant les épisodes d’eau chaude.
hero_caption_en: Protecting salmon during warm-water events.
card_image: /assets/img/warm-water-protocol/saumon.jpg
card_alt_fr: Saumon atlantique dans son habitat naturel
card_alt_en: Atlantic salmon in its natural habitat

sections:
  - type: text
    kicker_fr: Contexte du projet
    kicker_en: Project context
    title_fr: Le protocole d’eau chaude au Nouveau-Brunswick
    title_en: The Warm Water Protocol in New Brunswick
    body_fr: |
      Le protocole d’eau chaude s’applique uniquement aux secteurs néo-brunswickois des rivières Restigouche et Upsalquitch. Il encadre la pêche récréative lorsque la température de l’eau atteint des niveaux qui augmentent le stress physiologique du saumon atlantique. Une température minimale quotidienne supérieure à 20 °C pendant deux périodes de 24 heures mène à une restriction de pêche après 11 h. Au-delà de 23 °C pendant deux périodes de 24 heures, la pêche est fermée.

      Des sondes de température en temps réel, actuellement utilisées dans les secteurs visés, transmettent les données qui appuient le protocole. Les niveaux d’eau, les prévisions météorologiques et les observations de comportement des poissons complètent ce portrait.

      <div class="project-button-row"><a class="project-button" href="/assets/documents/restigouche-warm-water-protocol-2026.pdf" target="_blank" rel="noopener">Consulter le protocole d’eau chaude 2026</a></div>
    body_en: |
      The Warm Water Protocol applies only to the New Brunswick reaches of the Restigouche and Upsalquitch rivers. It guides recreational angling when water temperatures reach levels that increase physiological stress in Atlantic salmon. A daily minimum temperature above 20 °C for two consecutive 24-hour periods leads to an after-11 a.m. angling restriction. Above 23 °C for two consecutive 24-hour periods, angling closes.

      Real-time temperature probes currently used in the monitored reaches provide the data that support the protocol. Water levels, weather forecasts and observations of fish behaviour complete this picture.

      <div class="project-button-row"><a class="project-button" href="/assets/documents/restigouche-warm-water-protocol-2026.pdf" target="_blank" rel="noopener">Read the 2026 Warm Water Protocol</a></div>
    image_show: true
    image: /assets/img/warm-water-protocol/protocol-stations-map.png
    image_alt_fr: Localisation des sondes de température utilisées pour le protocole d’eau chaude
    image_alt_en: Locations of temperature probes used for the Warm Water Protocol
    image_caption_fr: Les sondes en temps réel soutiennent le suivi des secteurs visés.
    image_caption_en: Real-time probes support monitoring of the targeted reaches.
    below_image_show: true
    below_image: /assets/img/warm-water-protocol/protocol-thresholds.png
    below_image_alt_fr: Schéma de prise de décision du protocole d’eau chaude
    below_image_alt_en: Warm Water Protocol decision-making diagram
    below_image_caption_fr: Les seuils de température guident les restrictions et les fermetures.
    below_image_caption_en: Temperature thresholds guide restrictions and closures.

  - type: text
    kicker_fr: Modèle prédictif
    kicker_en: Predictive model
    title_fr: Développement d’un modèle prédictif
    title_en: Developing a predictive model
    body_fr: |
      Les données en temps réel indiquent ce qui s’est déjà produit. Avant de mettre une restriction en place, les partenaires doivent analyser les conditions, se concerter, prendre une décision et la communiquer aux pêcheurs. Cette séquence peut créer un délai d’un à deux jours entre le dépassement d’un seuil et la mesure appliquée.

      Par exemple, en juin 2024, la température a atteint 27 °C les 19 et 20 juin, alors que la fermeture partielle a commencé le 21 juin. Le graphique illustre cette limite de l’opérationnalisation actuelle : une mesure peut commencer après le pic de température qu’elle vise à éviter.

      Le projet développe et évalue un modèle CEQUEAU semi-distribué qui simule le débit et la température de l’eau dans le bassin versant. Il combine les observations de la rivière avec les prévisions météorologiques d’ensemble d’Environnement et Changement climatique Canada, puis utilise l’assimilation des données et un post-traitement statistique pour corriger les biais et estimer la probabilité de dépasser les seuils du protocole.

      L’objectif est de fournir, avec une faible erreur de simulation, des prévisions à un horizon d’un à deux jours afin d’amorcer la concertation plus tôt. La routine peut simuler jusqu’à huit jours, mais l’incertitude augmente à mesure que l’horizon s’allonge : les résultats préliminaires montrent généralement un écart inférieur à ±0,75 °C à 24 heures, pouvant atteindre environ ±5 °C à huit jours. L’outil demeure en évaluation avant toute utilisation opérationnelle.

      <div class="project-button-row"><a class="project-button" href="/assets/documents/warm-water-protocol-literature-review-2025.pdf" target="_blank" rel="noopener">Consulter la revue de littérature</a></div>
    body_en: |
      Real-time data show what has already happened. Before a restriction can be put in place, partners must analyze conditions, consult one another, make a decision and communicate it to anglers. This sequence can create a one- to two-day delay between a threshold being exceeded and a management measure being applied.

      For example, in June 2024, water temperature reached 27 °C on June 19 and 20, while the partial closure began on June 21. The graph illustrates a limitation of the current process: a measure can start after the temperature peak it seeks to avoid.

      The project is developing and evaluating a semi-distributed CEQUEAU model that simulates flow and water temperature across the watershed. It combines river observations with Environment and Climate Change Canada ensemble weather forecasts, then uses data assimilation and statistical post-processing to correct bias and estimate the probability of exceeding protocol thresholds.

      The goal is to provide one- to two-day forecasts with low simulation error so discussion can begin earlier. The routine can simulate up to eight days ahead, but uncertainty rises with the forecast horizon: preliminary results generally show an error below ±0.75 °C at 24 hours, potentially increasing to approximately ±5 °C at eight days. The tool remains under evaluation before any operational use.

      <div class="project-button-row"><a class="project-button" href="/assets/documents/warm-water-protocol-literature-review-2025.pdf" target="_blank" rel="noopener">Read the literature review</a></div>
    image_show: true
    image: /assets/img/warm-water-protocol/decision-delay-june-2024.png
    image_alt_fr: Température de l’eau et période de fermeture partielle en juin 2024
    image_alt_en: Water temperature and partial-closure period in June 2024
    image_caption_fr: En juin 2024, la fermeture partielle a commencé après deux jours où la température avait atteint 27 °C.
    image_caption_en: In June 2024, the partial closure began after two days when water temperature reached 27 °C.
    below_image_show: true
    below_image: /assets/img/warm-water-protocol/forecast-uncertainty-over-time.png
    below_image_alt_fr: Prévision de la température de l’eau avec intervalle de confiance qui s’élargit dans le temps
    below_image_alt_en: Water-temperature forecast with a confidence interval that widens over time
    below_image_caption_fr: L’intervalle de confiance s’élargit avec l’horizon de prévision.
    below_image_caption_en: The confidence interval widens as the forecast horizon increases.
---
