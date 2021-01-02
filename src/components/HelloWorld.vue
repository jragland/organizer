<template>
  <div class="organizer">
    <h1>{{ msg }}</h1>
    <p>
      Welcome to Orgnaizer!
    </p>
    <p> 
      <a href="https://github.com/jragland/organizer" target="_blank" rel="noopener">organizer Github</a>.
    </p>
    <p>
      Daily Routine
        0530
            Wake Up
                Stretch (10 mins)
                Workout (Bike 3miles or Walk 2miles) (60 mins)
                Brush Teeth (5 mins)
                Mouth Wash
                Shower (30 mins)
                Eat Small Breakfast (30 mins)
        0800
            Work
                8am to 5pm
                Eat Small Lunch (45 mins at ~ 1200)
        1700
            After Work
                Chores (60 mins)
                Cook/Eat Dinner (60 mins)
                Read (30+ mins)
    </p>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
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
