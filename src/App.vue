<template>
  <div class="font-sans text-gray-800">
    <!-- NAVBAR -->
    <header class="fixed top-0 left-0 right-0 z-50 bg-white/80 backdrop-blur shadow-soft">
      <nav class="max-w-7xl mx-auto px-6 py-3 flex items-center justify-between">
        <a href="#" class="flex items-center gap-3">
          <div class="w-10 h-10 rounded-full bg-brand flex items-center justify-center text-white font-bold">G</div>
          <span class="font-semibold">GASPRED</span>
        </a>
        <ul class="hidden md:flex items-center gap-6">
          <li><a class="hover:text-brand" href="#accueil">Accueil</a></li>
          <li><a class="hover:text-brand" href="#presentation">Présentation</a></li>
          <li><a class="hover:text-brand" href="#missions">Missions</a></li>
          <li><a class="hover:text-brand" href="#galerie">Galerie</a></li>
          <li><a class="hover:text-brand" href="#contact">Contact</a></li>
        </ul>
        <a href="#contact" class="px-4 py-2 rounded-2xl bg-brand text-white shadow-soft hover:bg-brand-dark transition">Faire un don</a>
      </nav>
    </header>

    <!-- HERO -->
    <section id="accueil" class="relative min-h-screen flex items-center justify-center">
      <img src="/images/banner.png" alt="Nature" class="absolute inset-0 h-full w-full object-cover opacity-70" />
      <div class="absolute inset-0 bg-gradient-to-b from-black/60 to-black/30"></div>
      <div class="relative z-10 text-center text-white px-6 pt-28">
        <h1 class="text-4xl md:text-6xl font-extrabold leading-tight">Protection de l'Environnement & Développement Durable</h1>
        <p class="mt-4 text-lg md:text-2xl text-white/90 max-w-3xl mx-auto">
          Nous œuvrons pour des communautés haïtiennes résilientes, prospères et en harmonie avec la nature.
        </p>
        <div class="mt-8 flex gap-4 justify-center">
          <a href="#missions" class="px-6 py-3 rounded-2xl bg-white text-brand font-semibold shadow-soft hover:bg-brand-light transition">Nos missions</a>
          <a href="#contact" class="px-6 py-3 rounded-2xl bg-brand text-white font-semibold shadow-soft hover:bg-brand-dark transition">Nous contacter</a>
        </div>
      </div>
    </section>

    <!-- PRESENTATION -->
    <section id="presentation" class="py-20 px-6 bg-brand-light">
      <div class="max-w-5xl mx-auto grid md:grid-cols-2 gap-10 items-center">
        <div>
          <h2 class="text-3xl md:text-4xl font-bold text-brand mb-4">Qui sommes-nous ?</h2>
          <p class="text-lg leading-relaxed">
            GASPRED est une organisation à but non lucrative, fondée en 2020 à Delmas 29 et dans la commune de Saint‑Marc.
            Elle a pour mission de contribuer au développement socioéconomique et environnemental des communautés haïtiennes,
            luttant contre les violences sur les enfants et les femmes, favorisant l'émancipation et l'autonomie des femmes,
            renforçant les capacités des organisations de producteurs agricoles, et conduisant des projets pour protéger
            l'environnement, notamment les écosystèmes marins.
          </p>
          <div class="mt-6 flex flex-wrap gap-3">
            <span class="px-3 py-1 rounded-full bg-white text-brand border border-brand/20">Haïti</span>
            <span class="px-3 py-1 rounded-full bg-white text-brand border border-brand/20">ONG</span>
            <span class="px-3 py-1 rounded-full bg-white text-brand border border-brand/20">Depuis 2020</span>
          </div>
        </div>
        <div class="relative">
          <img src="/images/image_2.png" class="rounded-2xl shadow-soft object-cover w-full h-full" alt="Action terrain" />
          <div class="absolute -bottom-6 -right-6 bg-white p-5 rounded-2xl shadow-soft">
            <p class="font-semibold text-brand">36 Delmas 29, Delmas, Haïti<br/>Cité Kebereau, St‑Marc</p>
          </div>
        </div>
      </div>
    </section>

    <!-- MISSIONS -->
    <section id="missions" class="py-20 px-6">
      <div class="max-w-6xl mx-auto">
        <h2 class="text-3xl md:text-4xl font-bold text-center mb-12">Nos missions clés</h2>
        <div class="grid md:grid-cols-3 gap-8">
          <div class="bg-white rounded-2xl shadow-soft p-6 text-center">
            <div class="text-5xl">🌱</div>
            <h3 class="mt-4 text-xl font-semibold">Protection de l'environnement</h3>
            <p class="mt-2 text-gray-600">Reboisement, gestion des déchets, préservation des écosystèmes marins et côtiers.</p>
          </div>
          <div class="bg-white rounded-2xl shadow-soft p-6 text-center">
            <div class="text-5xl">👩‍🌾</div>
            <h3 class="mt-4 text-xl font-semibold">Agriculture durable</h3>
            <p class="mt-2 text-gray-600">Renforcement des capacités des organisations de producteurs agricoles.</p>
          </div>
          <div class="bg-white rounded-2xl shadow-soft p-6 text-center">
            <div class="text-5xl">🛡️</div>
            <h3 class="mt-4 text-xl font-semibold">Protection des personnes</h3>
            <p class="mt-2 text-gray-600">Lutte contre les violences faites aux enfants et aux femmes, et autonomisation.</p>
          </div>
        </div>
      </div>
    </section>

    <!-- GALERIE -->
    <section id="galerie" class="py-20 bg-gray-50 px-6">
      <div class="max-w-6xl mx-auto">
        <h2 class="text-3xl md:text-4xl font-bold text-center mb-12">Galerie</h2>
        <div class="grid sm:grid-cols-2 md:grid-cols-3 gap-6">
          <img src="/images/image_6.jpg" class="rounded-2xl shadow-soft object-cover w-full h-64" alt="Projet 1">
          <img src="/images/image_3.jpg" class="rounded-2xl shadow-soft object-cover w-full h-64" alt="Projet 2">
          <img src="/images/image_5.png" class="rounded-2xl shadow-soft object-cover w-full h-64" alt="Projet 3">
        </div>
      </div>
    </section>

    <!-- CONTACT -->
    <section id="contact" class="py-20 px-6">
      <div class="max-w-4xl mx-auto text-center">
        <h2 class="text-3xl md:text-4xl font-bold mb-8">Contact</h2>
        <div class="grid md:grid-cols-2 gap-8 text-left">
          <div class="bg-white rounded-2xl shadow-soft p-6">
            <h3 class="font-semibold text-xl mb-2">Coordonnées</h3>
            <p class="text-gray-700">Adresse : 36 Delmas 29, Delmas, Haïti / 4, Cité Kebereau, St‑Marc.</p>
            <p class="text-gray-700 mt-2">
              Email :
              <a class="text-brand underline" href="mailto:gapredd2025@gmail.com">gapredd2025@gmail.com</a>
            </p>
          </div>
          <form class="bg-white rounded-2xl shadow-soft p-6 space-y-3" @submit.prevent="submit()">
            <input v-model="form.name" required type="text" placeholder="Votre nom" class="w-full border rounded-xl px-4 py-3 focus:outline-none focus:ring-2 focus:ring-brand/40">
            <input v-model="form.email" required type="email" placeholder="Votre email" class="w-full border rounded-xl px-4 py-3 focus:outline-none focus:ring-2 focus:ring-brand/40">
            <textarea v-model="form.message" required rows="4" placeholder="Votre message" class="w-full border rounded-xl px-4 py-3 focus:outline-none focus:ring-2 focus:ring-brand/40"></textarea>
            <button class="w-full px-4 py-3 rounded-2xl bg-brand text-white font-semibold hover:bg-brand-dark">Envoyer</button>
            <p v-if="sent" class="text-green-700">Merci ! Votre message a été simulé côté client.</p>
          </form>
        </div>
      </div>
    </section>

    <footer class="bg-brand text-white py-6 text-center">
      <p>&copy; 2025 GASPRED — Tous droits réservés.</p>
    </footer>
  </div>
</template>

<script setup>
import { reactive, ref } from 'vue'

const form = reactive({ name: '', email: '', message: '' })
const sent = ref(false)
function submit() {
  // Placeholder d'envoi — à connecter à un backend ou service de formulaire.
  sent.value = true
  setTimeout(() => (sent.value = false), 3000)
}
</script>

<style scoped>
</style>
