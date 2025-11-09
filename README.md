# ATH-Automotive_3
<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Performance Auto | TonSite</title>
  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
</head>
<body class="bg-black text-white font-sans">

  <!-- HEADER -->
  <header class="flex justify-between items-center p-6 bg-black fixed w-full z-50">
    <h1 class="text-2xl font-bold text-red-600">TonSite</h1>
    <nav class="space-x-6">
      <a href="#" class="hover:text-red-500">Reprogrammation</a>
      <a href="#" class="hover:text-red-500">E85</a>
      <a href="#" class="hover:text-red-500">Pièces</a>
      <a href="#" class="hover:text-red-500">Centres</a>
      <a href="#" class="bg-red-600 px-4 py-2 rounded">Contact</a>
    </nav>
  </header>

  <!-- HERO -->
  <section class="h-screen bg-cover bg-center flex items-center justify-center" style="background-image: url('car-bg.jpg');">
    <div class="text-center bg-black bg-opacity-50 p-8 rounded-xl">
      <h2 class="text-5xl font-bold mb-4">BOOSTEZ VOTRE PERFORMANCE</h2>
      <p class="text-gray-300 mb-6">Reprogrammation moteur, E85, pièces et plus encore.</p>
      <a href="#" class="bg-red-600 px-6 py-3 rounded font-semibold">Trouver mon centre</a>
    </div>
  </section>

  <!-- SECTIONS -->
  <section class="grid md:grid-cols-3 gap-8 p-16 bg-gray-900">
    <div class="bg-black p-6 rounded-xl shadow-lg hover:scale-105 transition">
      <img src="engine.jpg" alt="Optimisation" class="rounded mb-4">
      <h3 class="text-xl font-bold mb-2 text-red-500">Reprogrammation moteur</h3>
      <p class="text-gray-400">Gagnez jusqu’à +30% de puissance et -10% de conso.</p>
    </div>
    <div class="bg-black p-6 rounded-xl shadow-lg hover:scale-105 transition">
      <img src="fuel.jpg" alt="E85" class="rounded mb-4">
      <h3 class="text-xl font-bold mb-2 text-red-500">Conversion E85</h3>
      <p class="text-gray-400">Roulez à l’éthanol et faites des économies durables.</p>
    </div>
    <div class="bg-black p-6 rounded-xl shadow-lg hover:scale-105 transition">
      <img src="parts.jpg" alt="Pièces" class="rounded mb-4">
      <h3 class="text-xl font-bold mb-2 text-red-500">Pièces performance</h3>
      <p class="text-gray-400">Turbos, filtres, suspensions — tout pour vos projets.</p>
    </div>
  </section>

  <!-- FOOTER -->
  <footer class="bg-black p-8 text-center text-gray-500">
    © 2025 TonSite — Tous droits réservés
  </footer>

</body>
</html>
