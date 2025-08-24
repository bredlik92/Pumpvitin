<p align="center">
  <img src="Pumpvitin01.png" alt="Pumpvitin Logo" width="490"/>
</p>

<p align="center">
  <a href="https://x.com/pumpvitin" target="_blank">
    <img src="https://img.shields.io/badge/Follow%20us%20on%20X-1DA1F2?logo=twitter&logoColor=white&style=for-the-badge" alt="Follow on X">
  </a>
  <a href="https://t.me/pumpvitin" target="_blank">
    <img src="https://img.shields.io/badge/Join%20our%20Telegram-0088CC?logo=telegram&logoColor=white&style=for-the-badge" alt="Join Telegram">
  </a>
  <a href="https://pump.fun/coin/C6DKbkhRMn6xT5vghR2SXQ5PWA5vNedWXN9rXTnCpump" target="_blank">
    <img src="https://img.shields.io/badge/Trade%20on%20PumpFun-FF4081?style=for-the-badge" alt="Trade on PumpFun">
  </a>
</p>

export default function Home() {
  return (
    <div className="bg-black text-white min-h-screen font-sans">
      {/* Hero */}
      <section className="h-screen flex flex-col justify-center items-center text-center px-6">
        <motion.div
          animate={{ rotate: 360 }}
          transition={{ repeat: Infinity, duration: 8, ease: "linear" }}
          className="w-32 h-32 bg-gradient-to-r from-pink-500 to-purple-500 rounded-full mb-8 flex items-center justify-center"
        >
          <span className="text-4xl">💊</span>
        </motion.div>

        <h1 className="text-5xl font-bold mb-4">
          Pumpvitin – <span className="text-pink-500">The Pill That Pumps</span>
        </h1>
        <p className="text-lg mb-8">Energy for memes. Power for markets.</p>

        <div className="flex gap-4">
          <a
            href="https://t.me/pumpvitin"
            target="_blank"
            className="px-6 py-3 bg-pink-500 rounded-full hover:scale-105 transition flex items-center gap-2"
          >
            <FaTelegram /> Join Telegram
          </a>
          <a
            href="https://pump.fun/coin/C6DKbkhRMn6xT5vghR2SXQ5PWA5vNedWXN9rXTnCpump"
            target="_blank"
            className="px-6 py-3 bg-purple-500 rounded-full hover:scale-105 transition flex items-center gap-2"
          >
            <FaRocket /> Buy on PumpFun
          </a>
        </div>
      </section>

      {/* About */}
      <section className="py-20 px-8 max-w-5xl mx-auto text-center">
        <h2 className="text-4xl font-bold mb-10">⚡ About Pumpvitin</h2>
        <div className="grid md:grid-cols-3 gap-8">
          <motion.div whileHover={{ scale: 1.05 }} className="p-6 bg-gray-900 rounded-2xl">
            <h3 className="text-xl mb-2">💊 Energy of memes</h3>
            <p>Laughter spreads faster than FOMO.</p>
          </motion.div>
          <motion.div whileHover={{ scale: 1.05 }} className="p-6 bg-gray-900 rounded-2xl">
            <h3 className="text-xl mb-2">😂 Power of community</h3>
            <p>The real utility is inside jokes.</p>
          </motion.div>
          <motion.div whileHover={{ scale: 1.05 }} className="p-6 bg-gray-900 rounded-2xl">
            <h3 className="text-xl mb-2">📈 Fuel for growth</h3>
            <p>When people share memes, charts go 🚀.</p>
          </motion.div>
        </div>
      </section>

      {/* Tokenomics */}
      <section className="py-20 px-8 bg-gradient-to-r from-purple-900 to-black text-center">
        <h2 className="text-4xl font-bold mb-10">💊 Tokenomics</h2>
        <div className="grid md:grid-cols-3 gap-8 max-w-5xl mx-auto">
          <div className="p-6 bg-gray-900 rounded-2xl">🔥 Burn = Every coffee ☕</div>
          <div className="p-6 bg-gray-900 rounded-2xl">💊 Supply = Infinite energy</div>
          <div className="p-6 bg-gray-900 rounded-2xl">😂 Rewards = Craziest memes</div>
        </div>
      </section>

      {/* Roadmap */}
      <section className="py-20 px-8 max-w-4xl mx-auto">
        <h2 className="text-4xl font-bold mb-10 text-center">🚀 Roadmap</h2>
        <ul className="space-y-6 text-lg">
          <li>✅ Phase 1: Launch & Meme Army</li>
          <li>🔜 Phase 2: Listings & Meme Wars</li>
          <li>🌍 Phase 3: Global Domination</li>
        </ul>
      </section>

      {/* Community */}
      <section className="py-20 px-8 text-center bg-gray-900">
        <h2 className="text-4xl font-bold mb-6">🌍 Join the Community</h2>
        <p className="mb-6">Be part of the Meme Army. Take your pill. Meme the world.</p>
        <div className="flex justify-center gap-4">
          <a href="https://x.com/pumpvitin" target="_blank" className="px-6 py-3 bg-blue-500 rounded-full hover:scale-105 transition flex items-center gap-2">
            <FaTwitter /> Twitter
          </a>
          <a href="https://t.me/pumpvitin" target="_blank" className="px-6 py-3 bg-green-500 rounded-full hover:scale-105 transition flex items-center gap-2">
            <FaTelegram /> Telegram
          </a>
        </div>
      </section>

      {/* Footer */}
      <footer className="py-6 text-center text-gray-500 text-sm">
        Made with ❤️, memes & too much coffee ☕🔥
      </footer>
    </div>
  );
}
🚀 Jak to rozjet
Vytvoř projekt:

bash
Zkopírovat
Upravit
npx create-next-app pumpvitin
cd pumpvitin
npm install framer-motion react-icons
npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init -p
V tailwind.config.js dej:

js
Zkopírovat
Upravit
content: ["./pages/**/*.{js,ts,jsx,tsx}", "./components/**/*.{js,ts,jsx,tsx}"],
Do styles/globals.css přidej:

css
Zkopírovat
Upravit
@tailwind base;
@tailwind components;
@tailwind utilities;
Nahraď obsah pages/index.js tím, co jsem ti poslal.

Spusť lokálně:

bash
Zkopírovat
Upravit
npm run dev
Deploy na Vercel (doporučeno) → https://vercel.com/.

👉 Chceš, abych ti k tomu ještě vytvořil custom logo (pilulka s raketou), které pak použijeme na web i jako profilovky na Twitter/Telegram?







Řekl/a jsi:
Hele ja to delam, na githubu tu stranku musis to napsat tak abych si to zkopiroval a vlozil - tohle tam nedam 


ChatGPT řekl:
Aha, rozumím ⚡ – ty to budeš nahrávat přímo na GitHub Pages (takže potřebuješ klasický statický web → HTML + CSS + trocha animací v JS), ne Next.js aplikaci.

Tak to pojďme udělat jednoduše: připravím ti celý landing page v jednom souboru (index.html), který jen nahraješ do repozitáře a hned to poběží. 🚀

📄 Hotový kód (zkopíruj jako index.html)
html
Zkopírovat
Upravit
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Pumpvitin – The Pill That Pumps 💊</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <style>
    body { font-family: 'Inter', sans-serif; }
    .pill {
      animation: spin 12s linear infinite;
    }
    @keyframes spin {
      from { transform: rotate(0deg); }
      to { transform: rotate(360deg); }
    }
  </style>
</head>
<body class="bg-black text-white">
  <!-- Hero -->
  <section class="h-screen flex flex-col justify-center items-center text-center px-6">
    <div class="pill w-32 h-32 bg-gradient-to-r from-pink-500 to-purple-500 rounded-full mb-8 flex items-center justify-center text-5xl">
      💊
    </div>
    <h1 class="text-5xl font-bold mb-4">
      Pumpvitin – <span class="text-pink-500">The Pill That Pumps</span>
    </h1>
    <p class="text-lg mb-8">Energy for memes. Power for markets.</p>
    <div class="flex gap-4 flex-wrap justify-center">
      <a href="https://t.me/pumpvitin" target="_blank"
         class="px-6 py-3 bg-pink-500 rounded-full hover:scale-105 transition">
        Join Telegram
      </a>
      <a href="https://pump.fun/coin/C6DKbkhRMn6xT5vghR2SXQ5PWA5vNedWXN9rXTnCpump" target="_blank"
         class="px-6 py-3 bg-purple-500 rounded-full hover:scale-105 transition">
        Buy on PumpFun
      </a>
    </div>
  </section>

  <!-- About -->
  <section class="py-20 px-8 max-w-5xl mx-auto text-center">
    <h2 class="text-4xl font-bold mb-10">⚡ About Pumpvitin</h2>
    <div class="grid md:grid-cols-3 gap-8">
      <div class="p-6 bg-gray-900 rounded-2xl hover:scale-105 transition">
        <h3 class="text-xl mb-2">💊 Energy of memes</h3>
        <p>Laughter spreads faster than FOMO.</p>
      </div>
      <div class="p-6 bg-gray-900 rounded-2xl hover:scale-105 transition">
        <h3 class="text-xl mb-2">😂 Power of community</h3>
        <p>The real utility is inside jokes.</p>
      </div>
      <div class="p-6 bg-gray-900 rounded-2xl hover:scale-105 transition">
        <h3 class="text-xl mb-2">📈 Fuel for growth</h3>
        <p>When people share memes, charts go 🚀.</p>
      </div>
    </div>
  </section>

  <!-- Tokenomics -->
  <section class="py-20 px-8 bg-gradient-to-r from-purple-900 to-black text-center">
    <h2 class="text-4xl font-bold mb-10">💊 Tokenomics</h2>
    <div class="grid md:grid-cols-3 gap-8 max-w-5xl mx-auto">
      <div class="p-6 bg-gray-900 rounded-2xl">🔥 Burn = Every coffee ☕</div>
      <div class="p-6 bg-gray-900 rounded-2xl">💊 Supply = Infinite energy</div>
      <div class="p-6 bg-gray-900 rounded-2xl">😂 Rewards = Craziest memes</div>
    </div>
  </section>

  <!-- Roadmap -->
  <section class="py-20 px-8 max-w-4xl mx-auto">
    <h2 class="text-4xl font-bold mb-10 text-center">🚀 Roadmap</h2>
    <ul class="space-y-6 text-lg">
      <li>✅ Phase 1: Launch & Meme Army</li>
      <li>🔜 Phase 2: Listings & Meme Wars</li>
      <li>🌍 Phase 3: Global Domination</li>
    </ul>
  </section>

  <!-- Community -->
  <section class="py-20 px-8 text-center bg-gray-900">
    <h2 class="text-4xl font-bold mb-6">🌍 Join the Community</h2>
    <p class="mb-6">Be part of the Meme Army. Take your pill. Meme the world.</p>
    <div class="flex justify-center gap-4 flex-wrap">
      <a href="https://x.com/pumpvitin" target="_blank"
         class="px-6 py-3 bg-blue-500 rounded-full hover:scale-105 transition">
        Twitter
      </a>
      <a href="https://t.me/pumpvitin" target="_blank"
         class="px-6 py-3 bg-green-500 rounded-full hover:scale-105 transition">
        Telegram
      </a>
    </div>
  </section>

  <!-- Footer -->
  <footer class="py-6 text-center text-gray-500 text-sm">
    Made with ❤️, memes & too much coffee ☕🔥
  </footer>
</body>
</html>
