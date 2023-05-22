<script setup lang="ts">
</script>

<template>
  <main>
    <div class="container px-20 py-8">
      <h1 class="text-center text-2xl pb-8">Qohesion - Réservation salle commune</h1>
      <form>
        <div class="sm:col-span-3">
          <label for="PrenomNom">Prénom / PrenomNom
            <input id="PrenomNom" type="text" placeholder="Votre prénom et nom" class="w-full border-2 rounded" />
          </label>
        </div>

        <div class="sm:col-span-3 pt-4">
          <label for="Email">E-mail
            <input id="Email" type="email" placeholder="Votre e-mail" class="w-full border-2 rounded" />
          </label>
        </div>

        <div class="sm:col-span-3 pt-4">
          <label for="Date">Date
            <input id="Date" type="date" class="w-full border-2 rounded" />
          </label>
        </div>

        <div class="sm:col-span-3 pt-4">
          <label for="HeureDebut">Heure de début
            <input id="HeureDebut" type="time" class="w-full border-2 rounded" />
          </label>
        </div>

        <div class="sm:col-span-3 pt-4">
          <label for="HeureFin">Heure de fin
            <input id="HeureFin" type="time" class="w-full border-2 rounded" />
          </label>
        </div>

      </form>

      <div class="sm:col-span-3 pt-8">
        <button id="HeureFin" class="w-full rounded bg-sky-600 p-1">Réserver</button>
      </div>
    </div>
  </main>
</template>
