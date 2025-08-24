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

---

// pages/index.js
import { motion } from "framer-motion";
import { FaTelegram, FaTwitter, FaRocket } from "react-icons/fa";

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
