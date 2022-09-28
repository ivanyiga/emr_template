<template>
  <div class="container mt-8 pb-8 px-8">
    <h3 class="text-lg font-bold leading-6 text-gray-900 mt-8">DISPLAYING STATS</h3>
    <p class="text-[#626890] mb-8">Display Stats with comparison of the previous periods</p>
    <StatsComponent />
    <hr/>
    <h3 class="text-lg font-bold leading-6 text-gray-900 mt-8">BUTTONS</h3>
    <p class="text-[#626890] mb-8">Primary Buttons, Secondary Buttons, Action Buttons, Silent Buttons</p>

    <PrimaryButton />
    <SecondaryButton />
    <SuccessButton />

    <hr/>
    <h3 class="text-lg font-bold leading-6 text-gray-900 mt-8">CARDS</h3>
    <p class="text-[#626890] mb-8">White raised cards</p>

    <div class="col columns-4">
      <RaisedCard />
      <NotRaisedCard />
      <CardWithHeader />
      <CardWithFooter />
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import StatsComponent from '@/components/StatsComponent.vue'
import PrimaryButton from '@/components/PrimaryButtons.vue'
import SecondaryButton from '@/components/SecondaryButtons.vue'
import SuccessButton from '@/components/SuccessButtons.vue'
import RaisedCard from '@/components/RaisedCard.vue'
import NotRaisedCard from '@/components/NotraisedCard.vue'
import CardWithHeader from '@/components/CardWithHeader.vue'
import CardWithFooter from '@/components/CardWithFooter.vue'


export default {
  name: 'HomeView',
  components: {
    StatsComponent,
    PrimaryButton,
    SecondaryButton,
    SuccessButton,
    RaisedCard,
    NotRaisedCard,
    CardWithHeader,
    CardWithFooter
  },
};

</script>
