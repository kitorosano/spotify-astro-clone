<script lang="ts">
  const currentTime = new Date();
  const currentHour = currentTime.getHours();

  let greeting = "¡Buenos dias!";

  if(currentHour > 18) {
    greeting = "¡Buenas noches!";
  } else if(currentHour > 12) {
    greeting = "¡Buenas tardes!";
  }
</script>

<h1 class="text-3xl font-bold">{greeting}</h1>