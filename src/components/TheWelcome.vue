<script setup>
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from './icons/IconSupport.vue'
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>Sole</template>

    La radiazione solare consente la vita sulla Terra fornendo l'energia necessaria ad attivare i principali meccanismi che ne stanno alla base;inoltre l'insolazione della superficie terrestre regola il 
    <a href="https://it.wikipedia.org/wiki/Clima" target="_blank" rel="noopener">clima</a> e la maggior parte dei <a href="https://it.wikipedia.org/wiki/Meteorologia" target="_blank" rel="noopener">fenomeni meteorologici.</a>
    
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Nuvola</template>

    In meteorologia una nuvola è
    <a href="https://it.wikipedia.org/wiki/Idrometeora" target="_blank" rel="noopener">un'idrometeora</a> 
    costituita da minute particelle di vapore d'acqua condensato e/o cristalli di ghiaccio, sospesi nell'atmosfera grazie a correnti ascensionali o in stato di galleggiamento e solitamente non a contatto con il suolo.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Pioggia</template>

    La pioggia è la più comune <a href="https://it.wikipedia.org/wiki/Precipitazione_(meteorologia)" target="_blank" rel="noopener">precipitazione atmosferica</a> e si forma quando gocce separate di acqua cadono al suolo dalle nuvole.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Neve</template>

    La neve, in meteorologia, è un tipo di precipitazione atmosferica nella forma di 
    <a href="https://it.wikipedia.org/wiki/Acqua" target="_blank" rel="noopener">acqua ghiacciata cristallina</a>, 
    formata da una moltitudine di minuscoli 
    <a href="https://it.wikipedia.org/wiki/Cristalli_di_ghiaccio" target="_blank" rel="noopener"> cristalli di ghiaccio</a>, 
    tutti aventi di base una simmetria esagonale e spesso anche una geometria frattale, ma ognuno di tipo diverso e spesso aggregati tra loro in maniera casuale a formare fiocchi di neve.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Nebbia</template>

    La nebbia è il fenomeno meteorologico per il quale il vapore acqueo contenuto in una massa d'aria, 
    raggiunta la saturazione, inizia a condensare nella parte in eccesso, dando origine a minutissime 
    <a href="https://it.wikipedia.org/wiki/Goccia" target="_blank" rel="noopener">goccioline</a> di acqua liquida o cristalli di ghiaccio sospesi in aria.
  </WelcomeItem>
</template>
