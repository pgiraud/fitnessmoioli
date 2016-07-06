---
layout: home
section: home

lun_2_1: STEP Inter.
mar_3_1: STEP Inter.
mar_4_2: LIA Deb.
mer_3_2: LIA Inter.
mer_4_1: STEP Deb.
jeu_3_2: LIA Inter.
ven_3_2: LIA Deb.
sam_1_1: STEP Deb.
---

<main>
  <!-- Main jumbotron for a primary marketing message or call to action -->
  {% comment %}
  <div class="jumbotron">
    <div class="container">
      <div class="row">
        <div class="col-md-8">
          <h1>Fitness Moioli</h1>
        </div>
      </div>
    </div>
  </div>
  {% endcomment %}

  <section class="intro">
    <div class="container">
      <div class="row">
        <div class="col-sm-4">
          <img src="{{ site.baseurl}}/images/logo.png" class="img-responsive"/>
        </div>
        <div class="col-sm-8">
          <h2 class="text-primary">
            Votre centre de fitness à la Motte Servolex.
          </h2>
          <br>
          Retrouvez des cours de <span class="text-primary">STEP</span> et <span class="text-primary">AÉRODANCE</span> tout au long de la semaine,
          pour un prix très abordable.
        </div>
      </div>
    </div>
  </section>

  <section id="activites" class="activities">
    <div class="container">
      <div class="row">
        <div class="col-sm-6">
          <div class="page-header">
            <h1>
              Step
            </h1>
          </div>
          <p>
          Programme d'entrainement faisant appel principalement
          aux qualités d'endurance et de coordination, basé sur des
          déplacements en pas centrés sur un marche-pied appelé STEP<sup>&reg;</sup>.
          </p>
          <p>C'est la discipline reine du fitness et de l'aérobic.</p>
          <p>À la fois cardio et amusant.</p>
          <p>Des chorégraphies pour tous les niveaux pour brûler un max de
          calories et retrouver la pêche.</p>
          <p class="text-center">
          <img src="{{site.baseurl}}/images/Step.png" class="img-responsive">
          </p>
        </div>
        <div class="col-sm-6">
          <div class="page-header">
            <h1>
              Aérodance
              <small>LIA</small>
            </h1>
          </div>
          <p>Low Impact Aérobic.</p>
          <p>Activité chorégraphiée composée de déplacement marchés,
          accompagnés de mouvements de bras, sans sauts donc sans impacts mais
          qui reste malgré tout efficace sur le plan cardio-respiratoire.</p>
          <p>Incontournable également.</p>
          <p>Une discipline idéale pour faire bouger tout son corps en musique et retrouver du tonus sans se faire mal.</p>
          <p class="text-center">
          <img src="{{site.baseurl}}/images/LIA.png" class="img-responsive">
          </p>
        </div>
      </div>
    </div>
  </section>

  <section id="planning" class="planning">
    <div class="container">
      <div class="row">
        <div class="col-sm-12">
          <div class="page-header">
            <h1>Planning</h1>
          </div>
          {% include planning.html %}
        </div>
      </div>
    </div>
  </section>

  <section id="tarifs">
    <div class="container">
      <div class="row">
        <div class="col-sm-12">
          <div class="page-header">
            <h1>
              Tarifs
            </h1>
          </div>
          <div class="row">
            <div class="col-sm-8">
              <h3>
                180 €
                <small>
                La saison
                (octobre à juin)
                </small>
              </h3>
              <p>
                Un tarif unique qui vous donne accès à tous les cours.
              </p>
            </div>
            <div class="col-sm-4 well">
              <h2>
                Offre découverte
              </h2>
              <p>
                En septembre
              </p>
              <p>
                Venez tester les cours.
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</main>
