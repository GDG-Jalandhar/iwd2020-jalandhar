<template>
  <v-content class="pa-0">
    <v-container fluid class="mb-4 d-none d-sm-block">
      <v-layout wrap align-center justify-center row fill-height class="my-0">
        <v-flex xs12 md10 class="my-0 pa-5">
            <p class="google-font mb-0" style="font-size:200%;color:#0097a7">Our lineup of big thinkers and even bigger doers</p>
            <p class="google-font mt-0 mb-0" style="font-size:110%">Google is known all around the world. Everyone is 'googling', checking on 'maps' and communicating in 'gmail'. For simple users, they are services that just works, but not for us. Developers see much more: APIs, scalability issues, complex technology stacks. And that is what GDG is about. </p>

            <p class="google-font mt-3 mb-0" style="font-size:110%">Our goal is to organize space to connect the best industry experts with Indian audience to boost development of IT. And Our Team is: </p>

        </v-flex>
      </v-layout>
    </v-container>

    <v-container fluid class="ma-0 pa-0 hidden-sm-and-up">
      <v-layout wrap row fill-height>
        <v-flex xs12 md10>
          <mobileTeam/>
        </v-flex>
      </v-layout>
    </v-container>

    <v-container fluid class="d-none d-sm-block" >
      <v-layout wrap align-center justify-center row fill-height>
        <v-flex xs12 md10>
          <organizingTeam/>
        </v-flex>
      </v-layout>
    </v-container>

    <v-container fluid class="d-none d-sm-block">
      <v-layout wrap align-center justify-center row fill-height>
        <v-flex xs12 md10>
          <coreTeam/>
        </v-flex>
      </v-layout>
    </v-container>

    <v-container fluid class="d-none d-sm-block">
      <v-layout wrap align-center justify-center row fill-height>
        <v-flex xs12 md10>
          <volunteerDetails/>
        </v-flex>
      </v-layout>
    </v-container>

  </v-content>
  
</template>

<script>
import coreTeam from '@/components/team/coreTeam'
import volunteerDetails from '@/components/team/volunteerTeam'
import organizingTeam from '@/components/team/organizingTeam'
import mobileTeam from '@/components/team/mobileTeam'
  export default {
    components: {
      coreTeam,
      organizingTeam,
      volunteerDetails,
      mobileTeam
    },
    data() {
      return {
      }
    },
  }
</script>
