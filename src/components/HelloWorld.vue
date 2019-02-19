 /* eslint-disable */
<template>
 <v-app light>
    <v-toolbar class="white">
      <v-toolbar-title><img src="../assets/logo.png" alt="Vuetify.js" height="50"></v-toolbar-title>
    </v-toolbar>
    <v-content>
      <section>
        <v-parallax  :src="require('@/assets/pioneerSet.png')" height="600">
          <v-layout
            column
            align-center
            justify-center
            class="white--text"
          >
            <img src="../assets/logo.png" alt="Vuetify.js" height="50">
            <h1 class="white--text mb-2 display-1 text-xs-center">Voor al uw feest en partijen</h1>
            <div class="subheading mb-3 text-xs-center">Hebben wij de perfecte match in geluid en licht!</div>
            <v-btn
              class="blue lighten-2 mt-5"
              dark
              large
              href="/pre-made-themes"
            >
             klik hier voor ons aanbod
            </v-btn>
          </v-layout>
        </v-parallax>
      </section>

      <section>
        <v-layout
          column
          wrap
          class="my-5"
          align-center
        >
          <v-flex xs12 sm4 class="my-3">
            <div class="text-xs-center">
              <h2 class="headline">Voor iedereen hebben wij de licht en geluid oplossing</h2>
            </div>
          </v-flex>
          <v-flex xs12>
            <v-container grid-list-xl>
              <v-layout row wrap align-center>
                <v-flex xs12 md4>
                  <v-card class="elevation-0 transparent">
                    <v-card-text class="text-xs-center">
                      <v-icon x-large class="blue--text text--lighten-2">headset</v-icon>
                    </v-card-text>
                    <v-card-title primary-title class="layout justify-center">
                      <div class="headline text-xs-center">Voor Dj's</div>
                    </v-card-title>
                    <v-card-text>
Als dj een dj set nodig op locatie? met zonder of djbooth, speakers noem maar op en wij bouwen het op! voor de dj’s maken wij gebruik van een van de toon aangevende dj sets die er zijn van het merk Pioneer. Hier hebben wij verschillende modellen cd spelers, mengpanelen en effecten.
                    </v-card-text>
                  </v-card>
                </v-flex>
                <v-flex xs12 md4>
                  <v-card class="elevation-0 transparent">
                    <v-card-text class="text-xs-center">
                      <v-icon x-large class="blue--text text--lighten-2">domain</v-icon>
                    </v-card-text>
                    <v-card-title primary-title class="layout justify-center">
                      <div class="headline">Voor bedrijven en feesten</div>
                    </v-card-title>
                    <v-card-text>
   Organiseert u een bedrijfsfeest, festival of verjaardagsfeest? Wij denken met plezier met u mee zodat uw evenement perfect verloopt!
U kunt al het werk bij ons in handen schuiven en dan kijkt onze eventplanner met u mee.
Ook spreken wij van te voren een prijs af zodat u niet achteraf onverwachte kosten krijgt! 
  </v-card-text>
                  </v-card>
                </v-flex>
                <v-flex xs12 md4>
                  <v-card class="elevation-0 transparent">
                    <v-card-text class="text-xs-center">
                      <v-icon x-large class="blue--text text--lighten-2">music_note</v-icon>
                    </v-card-text>
                    <v-card-title primary-title class="layout justify-center">
                      <div class="headline text-xs-center">Voor bands</div>
                    </v-card-title>
                    <v-card-text>
Wilt u een band of een singer songwriter op uw evenement? Dat is bij ons ook mogelijk! Wij werken samen met een kleine band en een aantal singer songwriters! Of wilt u ondersteuning bij uw band met licht en geluid bij uw optreden, of een podia? Dan bent u bij ons bij het juiste adres!
                    </v-card-text>
                  </v-card>
                </v-flex>
              </v-layout>
            </v-container>
          </v-flex>
        </v-layout>
      </section>

      <section>
        <v-parallax :src="require('@/assets/party.jpg')" height="380">
          <v-layout column align-center justify-center>
            <div class="headline white--text mb-3 text-xs-center">Op zoek naar wat van onze sfeer impressies?</div>
            <em>kijk op onze facebook pagina</em>
            <v-btn
              class="blue lighten-2 mt-5"
              dark
              large
              href="https://www.facebook.com/audiohuur/"
              target="_blank"
            >
              klik hier
            </v-btn>
          </v-layout>
        </v-parallax>
      </section>

      <section>
        <v-container grid-list-xl>
          <v-layout row wrap justify-center class="my-5">
            <v-flex xs12 sm4>
              <v-card class="elevation-0 transparent">
                <v-card-title primary-title class="layout justify-center">
                  <div class="headline">Over Mij</div>
                </v-card-title>
                <v-card-text>
Hallo allemaal!

Ik ben Kjeld van Straalen, 26 jaar oud en oprichter van dit bedrijf. Drie jaar geleden ben ik begonnen met Audio Huur met de gedachten om geluids-, verlichtings- en dj-apparatuur te verhuren. Dit gehele concept is ontstaan doordat ik vroeger met mijn oudere broer mee op pad ging met zijn drive-in shows. Mijn broer was dan de dj en ik hielp hem om zijn apparatuur zo goed mogelijk te plaatsen op de locatie. Allerlei vragen kwamen er dan in mij op tijdens het opbouwen. Wat is de beste plek voor de dj om te draaien? Waar moet de verlichting komen te staan voor een geweldig effect? Waar moeten de speakers komen te staan zodat het geluid uitstekend is? Ik heb altijd plezier gehad met het regelen van deze drive-in shows dat ik uiteindelijk heb besloten om dit zelf voort te zetten. Ik verhuur dus niet alleen, maar organiseer ook evenementen waarbij ik ook dj’s tot mijn beschikking heb. Dit doe ik met veel passie en plezier!
                </v-card-text>
              </v-card>
            </v-flex>
            <v-flex xs12 sm4 offset-sm1>
              <v-card class="elevation-0 transparent">
                <v-card-title primary-title class="layout justify-center">
                  <div class="headline">neem contact op</div>
                </v-card-title>
                <v-card-text>
                  Dit zijn onze contact gegevens
                </v-card-text>
                <v-list class="transparent">
                  <v-list-tile>
                    <v-list-tile-action>
                      <v-icon class="blue--text text--lighten-2">phone</v-icon>
                    </v-list-tile-action>
                    <v-list-tile-content>
                      <v-list-tile-title>+316 234 381 79</v-list-tile-title>
                    </v-list-tile-content>
                  </v-list-tile>
                  <v-list-tile>
                    <v-list-tile-action>
                      <v-icon class="blue--text text--lighten-2">place</v-icon>
                    </v-list-tile-action>
                    <v-list-tile-content>
                      <v-list-tile-title>Utrecht, NL</v-list-tile-title>
                    </v-list-tile-content>
                  </v-list-tile>
                  <v-list-tile>
                    <v-list-tile-action>
                      <v-icon class="blue--text text--lighten-2">email</v-icon>
                    </v-list-tile-action>
                    <v-list-tile-content>
                      <v-list-tile-title>kjeldstraalen@gmail.com</v-list-tile-title>
                    </v-list-tile-content>
                  </v-list-tile>
                </v-list>
              </v-card>
            </v-flex>
          </v-layout>
        </v-container>
      </section>

      <v-footer class="blue darken-2">
        <v-layout row wrap align-center>
          <v-flex xs12>
            <div class="white--text ml-3">
              Made by Sven van Straalen
            </div>
          </v-flex>
        </v-layout>
      </v-footer>
    </v-content>
  </v-app>
</div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data() {
    return {
      msg: 'Welcome to Your Vue.js App',
    };
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
