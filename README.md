Ce dépôt regroupe plusieurs exercices d'analyse de données que j'ai réalisés lors de mon Master 2, il contient uniquement le code brut avec des commentaires, sans aucun graphique. 
<ul>
  <li> Méthodes statistiques afin de réduire l'information contenue dans les grandes bases de données :
    <ul>
      <br><li> Analyses factorielles multivariées >> ACP (nature des variables : quantitative) & ACM (nature des variables : qualitative) réalisées via des scripts SAS <code>ACM_appli_chiens_res</code> <code>ACP_appli_hotel_macro-insee</code> 		 
      <code>ACP_appli_hotel_res</code> <code>ACP_appli_temperature</code> <code>ACP_appli_temperature_macro-insee</code>.</li>
    </ul>
    <ul>
       <br><li> Classification (CAH) >> Classification ascendante hiérarchique (variables quantitatives & qualitatives) réalisée via des scripts SAS <code>CAH_appli_chiens</code> <code>CAH_appli_hotels</code> <code>CAH_appli_temperature</code>.
      <br><em> Les bases de données sont situées dans le dossier <code>database</code>: <code>chiens</code> <code>hotels</code> <code>temperature</code>.</em></li>
    </ul>
  </li>
</ul>
<ul>
  <li> Méthodes statistiques prédictives :
    <ul>  
       <br><li> Régression linéaire multiple >> Evaluation : "Analyser l’écart de salaire mensuel net (facteur à expliquer : variable quantitative) entre la population immigrée et la population née en 
      France" - Les données à mobiliser sont issues des enquêtes Emploi réalisées par l’Insee en 2015 et 2016 via un script R <code>RLM_appli_examen</code> et la synthèse de l'analyse <code>RLM_synthese_examen</code>.
      <br><em> L'énoncé se situe dans le dossier <code>annexe</code><code>RLM_devoir_examen</code>.</em>
      <br><em> La base de données est située dans le dossier <code>database</code> : <code>enq_emploi_salarie_2016</code> <code>enq_emploi_salarie_2015</code>.</em></li>
    </ul>
  </li>
</ul>
