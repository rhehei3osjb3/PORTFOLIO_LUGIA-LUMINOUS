import React, { useEffect, useState } from "react";
import { motion, AnimatePresence } from "framer-motion";
import { Play, Github } from "lucide-react";

// Advanced single-file React component (Tailwind + Framer Motion)
// Drop this file into a React project that has TailwindCSS configured.
// Recommended deps: framer-motion, lucide-react

const videos = [
  {
    id: 1,
    title: "Chat system scripting",
    subtitle: "First video",
    features: [
      "Private & group chat scaffolding",
      "Message history + local caching (placeholder store)",
      "Typing indicator & read receipts (UI stubs)",
      "Command-hooks for moderation & AI-integration",
    ],
  },
  {
    id: 2,
    title: "Commands scripting work",
    subtitle: "Second video",
    features: [
      "Prefix and slash-like parser",
      "Role/permission checks & cooldowns",
      "Help system & argument parsing stubs",
      "Command auto-complete UI and confirmations",
    ],
  },
  {
    id: 3,
    title: "NPC scripting",
    subtitle: "Third video",
    features: [
      "Finite-state AI (patrol / chase / idle)",
      "Dialog systems & choice branches",
      "Pathfinding stubs and interaction triggers",
      "Animation and VFX hooks for behaviours",
    ],
  },
  {
    id: 4,
    title: "Hatching system",
    subtitle: "Fourth video",
    features: [
      "Egg rarity & probability table",
      "Timed hatch with progress UI",
      "Auto-hatch + accelerate options",
      "Particle & sound trigger hooks",
    ],
  },
  {
    id: 5,
    title: "Inventory system",
    subtitle: "Fifth video",
    features: [
      "Grid-based inventory layout (slot system)",
      "Stackable items & simple drag-n-drop stubs",
      "Equip / unequip + quick-use buttons",
      "Persistence-ready data model (save/load)",
    ],
  },
  {
    id: 6,
    title: "GUI scripting (arena game)",
    subtitle: "Sixth video",
    features: [
      "Responsive HUD (health / mana / stamina)",
      "Skill buttons with cooldown visuals",
      "Round timer, scoreboard & spectator panel",
      "Adaptive layouts for mobile & desktop",
    ],
  },
];

export default function ShowcaseVideos() {
  const [active, setActive] = useState(videos[0].id);
  const [showSecondTitle, setShowSecondTitle] = useState(false);
  const [sliceAnimDone, setSliceAnimDone] = useState(false);

  useEffect(() => {
    // orchestrate the slice animation -> then slide in second title
    const t1 = setTimeout(() => setSliceAnimDone(true), 1200); // slice line crosses
    const t2 = setTimeout(() => setShowSecondTitle(true), 1600); // slide-in second
    return () => {
      clearTimeout(t1);
      clearTimeout(t2);
    };
  }, []);

  const activeData = videos.find((v) => v.id === active);

  return (
    <div className="min-h-screen bg-gradient-to-br from-slate-900 via-black to-slate-800 text-white p-8">
      <div className="max-w-6xl mx-auto">
        {/* HERO */}
        <section className="relative overflow-hidden rounded-2xl p-8 mb-8 bg-gradient-to-b from-black/40 to-white/2 backdrop-blur-md border border-white/6">
          <div className="absolute inset-0 -z-10 opacity-30" aria-hidden>
            {/* soft animated nebula background */}
            <div className="h-full w-full bg-[radial-gradient(ellipse_at_top_right,_var(--tw-gradient-stops))] from-indigo-700/30 via-fuchsia-700/10 to-transparent" />
          </div>

          <div className="flex flex-col md:flex-row items-center gap-6">
            <div className="flex-1">
              <div className="relative h-40 flex items-center">
                {/* First big title (neon) */}
                <motion.h1
                  initial={{ opacity: 1, y: 0, scale: 1 }}
                  animate={{ opacity: sliceAnimDone ? 0.08 : 1, y: sliceAnimDone ? -6 : 0 }}
                  transition={{ duration: 0.8 }}
                  className="text-5xl md:text-6xl font-extrabold leading-tight tracking-tight neon-text"
                  style={{ WebkitTextStroke: '0.3px rgba(255,255,255,0.04)' }}
                >
                  A ordinary scripter
                </motion.h1>

                {/* cutting line */}
                <motion.div
                  initial={{ x: '-100%', rotate: -6 }}
                  animate={{ x: sliceAnimDone ? '120%' : '100%', rotate: -6 }}
                  transition={{ duration: 1.2, ease: 'easeInOut' }}
                  onAnimationComplete={() => setSliceAnimDone(true)}
                  className="pointer-events-none absolute left-0 right-0 mx-auto top-1/2 h-0.5 bg-gradient-to-r from-transparent via-white/80 to-transparent transform-gpu"
                  style={{ width: '140%' }}
                />

                {/* second title slides in */}
                <AnimatePresence>
                  {showSecondTitle && (
                    <motion.h2
                      initial={{ x: 80, opacity: 0 }}
                      animate={{ x: 0, opacity: 1 }}
                      exit={{ x: 30, opacity: 0 }}
                      transition={{ duration: 0.6 }}
                      className="absolute left-0 ml-2 mt-12 text-3xl md:text-4xl font-bold text-emerald-300 drop-shadow-lg"
                    >
                      A trustworthy Scripter
                    </motion.h2>
                  )}
                </AnimatePresence>
              </div>

              <p className="mt-4 max-w-xl text-sm text-white/70">
                Professional showcase UI for your videos and systems. Click any card to reveal a modern demo panel with descriptions, features, and a visual mock video. Built with Tailwind + Framer Motion — drop into your React/Tailwind project and push to GitHub.
              </p>

              <div className="mt-6 flex gap-3 items-center">
                <a
                  href="#"
                  className="group inline-flex items-center gap-2 px-4 py-2 rounded-full bg-gradient-to-r from-emerald-500/20 to-emerald-500/8 border border-emerald-500/20 backdrop-blur text-emerald-200 hover:scale-[1.02] transition-transform"
                >
                  <Github className="w-4 h-4 opacity-90" />
                  <span className="text-sm">Use in GitHub repo</span>
                </a>

                <button
                  className="group inline-flex items-center gap-2 px-4 py-2 rounded-full bg-white/6 hover:bg-white/8 transition-all"
                  onClick={() => alert('Copy the component file into your src/ folder and import it into a page.')}
                >
                  <Play className="w-4 h-4" />
                  <span className="text-sm">Preview locally</span>
                </button>
              </div>
            </div>

            {/* Controls - Buttons for each video */}
            <div className="w-full md:w-96 mt-4 md:mt-0">
              <div className="grid grid-cols-2 md:grid-cols-1 gap-3">
                {videos.map((v) => (
                  <motion.button
                    key={v.id}
                    onClick={() => setActive(v.id)}
                    whileHover={{ scale: 1.02 }}
                    whileTap={{ scale: 0.98 }}
                    className={`group relative rounded-xl p-3 text-left border border-white/6 backdrop-blur cursor-pointer transition-all shadow-lg
                      ${active === v.id ? 'bg-gradient-to-r from-indigo-700/30 to-fuchsia-700/20 ring-1 ring-white/10' : 'bg-black/30'}`}
                  >
                    <div className="flex items-center justify-between">
                      <div>
                        <div className="flex items-baseline gap-2">
                          <span className="text-sm text-white/80">{`0${v.id}`}</span>
                          <h3 className="font-semibold text-sm md:text-base">{v.title}</h3>
                        </div>
                        <p className="text-xs text-white/60 mt-1">{v.subtitle}</p>
                      </div>

                      <div className="flex items-center gap-2">
                        <span className="text-xs px-2 py-1 rounded-full bg-white/6 text-white/80">View</span>
                        <div className="w-8 h-8 rounded-full bg-gradient-to-br from-white/6 to-white/3 flex items-center justify-center">
                          <Play className="w-4 h-4" />
                        </div>
                      </div>
                    </div>

                    {/* sliding underline & micro neon */}
                    <motion.div
                      className="absolute left-0 bottom-0 h-0.5 bg-gradient-to-r from-emerald-400 via-indigo-400 to-fuchsia-400 rounded-t-full"
                      layout
                      transition={{ type: 'spring', stiffness: 400, damping: 30 }}
                      style={{ width: active === v.id ? '100%' : '0%' }}
                    />
                  </motion.button>
                ))}
              </div>
            </div>
          </div>
        </section>

        {/* CONTENT PANEL */}
        <main className="grid md:grid-cols-2 gap-6">
          <AnimatePresence mode="wait">
            <motion.section
              key={active}
              initial={{ opacity: 0, x: 30 }}
              animate={{ opacity: 1, x: 0 }}
              exit={{ opacity: 0, x: -30 }}
              transition={{ duration: 0.45 }}
              className="rounded-2xl p-6 bg-gradient-to-b from-black/50 to-white/2 border border-white/6 shadow-2xl"
            >
              <div className="flex items-start gap-6">
                <div className="w-2/5 md:w-1/2">
                  {/* mock video / thumbnail */}
                  <div className="aspect-video rounded-xl overflow-hidden border border-white/6 relative">
                    <div className="absolute inset-0 bg-gradient-to-br from-indigo-800 via-fuchsia-700 to-emerald-600 animate-tilt" />
                    <div className="absolute inset-0 flex items-center justify-center">
                      <div className="w-16 h-16 rounded-full bg-white/6 flex items-center justify-center">
                        <Play className="w-8 h-8" />
                      </div>
                    </div>
                    <div className="absolute left-3 top-3 text-xs px-2 py-1 rounded-md bg-black/40 backdrop-blur border border-white/6">Demo</div>
                  </div>
                </div>

                <div className="flex-1">
                  <h4 className="font-bold text-xl">{activeData.title}</h4>
                  <p className="text-sm text-white/70 mt-2">Professional breakdown of what is covered in this video and what I can implement for you.</p>

                  <ul className="mt-4 space-y-2">
                    {activeData.features.map((f, i) => (
                      <li key={i} className="text-sm flex items-start gap-3">
                        <span className="mt-1 w-2 h-2 rounded-full bg-emerald-400/80 shrink-0" />
                        <span className="text-white/80">{f}</span>
                      </li>
                    ))}
                  </ul>

                  <div className="mt-6 flex gap-3">
                    <button
                      className="px-4 py-2 rounded-md bg-gradient-to-r from-emerald-400/10 to-emerald-400/6 border border-emerald-400/20 hover:scale-[1.02] transition-transform"
                      onClick={() => alert(`Open the ${activeData.title} dev folder (example)`) }
                    >
                      Open demo folder
                    </button>

                    <button
                      className="px-4 py-2 rounded-md bg-white/6 hover:bg-white/8 transition"
                      onClick={() => alert('Copy snippet to clipboard (you can implement further features).')}
                    >
                      Copy snippet
                    </button>
                  </div>
                </div>
              </div>

              <div className="mt-6 text-xs text-white/60">
                <strong>Notes:</strong> This is a visual showcase component with production-grade motion and styling. Replace the mock thumbnail with your real video thumbnails or embed players. The feature lists are starter checklists you can expand when you implement the systems.
              </div>
            </motion.section>
          </AnimatePresence>

          {/* Right side: extras, cards, micro interactions */}
          <section className="rounded-2xl p-6 bg-gradient-to-b from-black/40 to-white/2 border border-white/6 shadow-lg">
            <h5 className="font-semibold">Pro UI Extras</h5>

            <div className="mt-4 grid grid-cols-1 gap-4">
              <div className="rounded-lg p-3 bg-black/20 border border-white/6">
                <div className="flex items-center justify-between">
                  <div>
                    <p className="text-sm">Polish / Effects</p>
                    <p className="text-xs text-white/60">Neon glows, slice animation, sliding buttons, hover micro-interactions.</p>
                  </div>
                  <div className="text-xs text-white/70">Design</div>
                </div>
              </div>

              <div className="rounded-lg p-3 bg-black/20 border border-white/6">
                <div className="flex items-center justify-between">
                  <div>
                    <p className="text-sm">Integration</p>
                    <p className="text-xs text-white/60">Drop-in for React app (Tailwind). Hook real systems to the UI components.</p>
                  </div>
                  <div className="text-xs text-white/70">Hookups</div>
                </div>
              </div>

              <div className="rounded-lg p-3 bg-black/20 border border-white/6">
                <div className="flex items-center justify-between">
                  <div>
                    <p className="text-sm">Mobile Ready</p>
                    <p className="text-xs text-white/60">Layouts adapt — use the same components for mobile HUDs and overlays.</p>
                  </div>
                  <div className="text-xs text-white/70">Responsive</div>
                </div>
              </div>
            </div>

            <div className="mt-6 text-xs text-white/60">Tip: To publish this to GitHub, create a new repository and push this component along with a Tailwind-configured React app (Vite or Create-React-App). Add the actual video files or thumbnail images inside /public and update the thumbnail sources.</div>
          </section>
        </main>

        <style>{`
          .neon-text {
            color: #e9f5ff;
            text-shadow: 0 0 10px rgba(99,102,241,0.16), 0 0 30px rgba(168,85,247,0.08), 0 2px 12px rgba(99,102,241,0.08);
          }

          .animate-tilt {
            animation: tilt 10s linear infinite;
            opacity: 0.45;
            mix-blend-mode: screen;
          }

          @keyframes tilt {
            0% { transform: translateY(0px) rotate(0deg) scale(1); }
            50% { transform: translateY(-6px) rotate(1deg) scale(1.02); }
            100% { transform: translateY(0px) rotate(0deg) scale(1); }
          }

          /* small responsive tweaks */
          @media (max-width: 768px) {
            .neon-text { font-size: 2rem; }
          }
        `}</style>
      </div>
    </div>
  );
}
