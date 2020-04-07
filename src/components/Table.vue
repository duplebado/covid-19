<template>
  <div id="to_center">
    <b-table striped hover :items="items"></b-table>
  </div>
</template>

<script>
  export default {
    name: 'Table',
    data() {
      return {
        items: [
          { State:'Lagos', Cases: 86, Discharged: 31, Deaths: 2 },
          { State:'Abuja', Cases: 48, Discharged: 0, Deaths: 2 },
          { State:'Osun', Cases: 20, Discharged: 1, Deaths: 0 },
          { State:'Edo', Cases: 11, Discharged: 0, Deaths: 1 },
          { State:'Oyo', Cases: 8, Discharged: 0, Deaths: 0 },
          { State:'Bauchi', Cases: 3, Discharged: 0, Deaths: 0 },
          { State:'Akwa-Ibom', Cases: 5, Discharged: 0, Deaths: 0 },
          { State:'Enugu', Cases: 4, Discharged: 2, Deaths: 0 },
          { State:'Ekiti', Cases: 2, Discharged: 1, Deaths: 0 },
          { State:'Kwara', Cases: 2, Discharged: 0, Deaths: 0 },
          { State:'Rivers', Cases: 2, Discharged: 0, Deaths: 0 },
          { State:'Benue', Cases: 1, Discharged: 0, Deaths: 0 },
          { State:'Ondo', Cases: 1, Discharged: 0, Deaths: 0 },   
        ]
      }
    }
  }
</script>

<style scoped>
#to_center{
    text-align :center;
}
</style>