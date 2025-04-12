import React from "react";

export default function LandingPage() {
  return (
    <div className="min-h-screen bg-gradient-to-br from-slate-900 to-gray-800 text-white px-6 py-10">
      {/* Hero Section */}
      <section className="text-center max-w-4xl mx-auto py-20">
        <h1 className="text-5xl font-bold mb-4">DHIBOTAi</h1>
        <p className="text-xl mb-6">Empowering Bharat with Intelligent AI Agents</p>
        <a
          href="#early-access"
          className="bg-indigo-600 hover:bg-indigo-700 text-white px-6 py-3 rounded-2xl shadow-xl text-lg"
        >
          Join Early Access
        </a>
      </section>

      {/* Features Section */}
      <section className="max-w-5xl mx-auto py-16 grid md:grid-cols-3 gap-8 text-center">
        <div>
          <h3 className="text-2xl font-semibold mb-2">Multilingual Support</h3>
          <p>Speak to AI in Hindi, Gujarati, Tamil, and more.</p>
        </div>
        <div>
          <h3 className="text-2xl font-semibold mb-2">AI Agents for Every Domain</h3>
          <p>From healthcare to education, personalized AI for all sectors.</p>
        </div>
        <div>
          <h3 className="text-2xl font-semibold mb-2">Secure & On-Device</h3>
          <p>Edge AI for real-time and private conversations.</p>
        </div>
      </section>

      {/* About Section */}
      <section className="max-w-3xl mx-auto py-20 text-center">
        <h2 className="text-3xl font-bold mb-4">Why DHIBOTAi?</h2>
        <p className="text-lg text-gray-300">
          DHIBOTAi is building India's first Bharat-centric AI ecosystem focused on real-world needs of local
          industries, education, and healthcare with modular, multilingual, and ethical AI agents.
        </p>
      </section>

      {/* Call to Action */}
      <section
        id="early-access"
        className="max-w-3xl mx-auto bg-indigo-700 text-white rounded-2xl p-10 text-center shadow-2xl"
      >
        <h2 className="text-2xl font-bold mb-4">Be a Part of the AI Revolution</h2>
        <p className="mb-6">Join the early access list and get exclusive updates & beta access.</p>
        <input
          type="email"
          placeholder="Your Email"
          className="p-3 w-full rounded-xl text-black mb-4"
        />
        <button className="bg-black hover:bg-gray-900 px-6 py-3 rounded-xl">Notify Me</button>
      </section>

      {/* Footer */}
      <footer className="mt-20 text-center text-sm text-gray-400">
        Made with love in Ahmedabad, Gujarat by Aryas Ashish
      </footer>
    </div>
  );
}
"dependencies": {
  "next": "^13.0.0",     
  "react": "^18.0.0",
  "react-dom": "^18.0.0"
}
