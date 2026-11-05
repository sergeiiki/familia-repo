---
theme: default
class: text-center text-slate-900 bg-white
highlighter: shiki
transition: slide-left
title: FAMILIA — AI-Enabled Social Resilience in Space Settlements
mdc: true
---

<div class="flex flex-col items-center justify-center h-full px-6">
  <div class="p-10 bg-slate-50 rounded-2xl border border-slate-200 shadow-xl max-w-3xl">
    <div class="inline-block px-3 py-1 bg-blue-100 text-blue-800 rounded-full text-xs font-semibold tracking-wider uppercase mb-4">
      CIDSAI Grant Proposal • NYU Abu Dhabi
    </div>
    <h1 class="text-5xl font-extrabold text-slate-900 mb-4 tracking-tight">
      FAMILIA
    </h1>
    <h3 class="text-xl font-normal text-slate-600 mb-6 leading-relaxed">
      AI-Enabled Modeling of Social Organization &amp; Resilience in Space Settlements
    </h3>
    <div class="text-xs text-slate-500 font-medium tracking-wide uppercase border-t border-slate-200 pt-4">
      Center for Astrophysics and Space Science • NYU Abu Dhabi
    </div>
  </div>
</div>

---
layout: default
class: text-slate-900 bg-white
---

# <span class="text-blue-600">01.</span> Concept &amp; Problem Definition

What is FAMILIA and why do we need quantitative social modeling now?

<div class="p-4 bg-gradient-to-r from-blue-50 to-indigo-50 rounded-xl border border-blue-100 text-center mb-6 shadow-sm">
  <h2 class="text-xl font-bold tracking-wide text-slate-900">
    <span class="text-blue-600">F</span>amily 
    <span class="text-blue-600">A</span>daptation 
    <span class="text-blue-600">M</span>odel 
    <span class="text-blue-600">I</span>ntegrating 
    <span class="text-blue-600">L</span>iving conditions, 
    <span class="text-blue-600">I</span>nstitutions and 
    <span class="text-blue-600">A</span>I
  </h2>
</div>

<div class="grid grid-cols-2 gap-5 text-sm">
  <div class="p-5 bg-slate-50 rounded-xl border border-slate-200 shadow-sm hover:shadow-md transition-all">
    <h3 class="font-bold text-base mb-3 text-blue-900 flex items-center gap-2">🚀 Paradigm Shift</h3>
    <ul class="list-disc pl-4 space-y-2 text-slate-700">
      <li><strong>Beyond Short-Term Adult Crews:</strong> Mars-500 &amp; SIRIUS study pre-selected adults over months.</li>
      <li><strong>Intergenerational Habitats:</strong> UAE Mars 2117 requires multi-family communities over decades.</li>
      <li><strong>The Core Question:</strong> <em class="text-slate-900 font-medium">How can we design governance to ensure families thrive sustainably?</em></li>
    </ul>
  </div>
  <div class="p-5 bg-slate-50 rounded-xl border border-slate-200 shadow-sm hover:shadow-md transition-all">
    <h3 class="font-bold text-base mb-3 text-blue-900 flex items-center gap-2">🔬 Core Innovation</h3>
    <ul class="list-disc pl-4 space-y-2 text-slate-700">
      <li><strong>Hybrid AI Core:</strong> Rule-based physics engine + auditable LLM agents.</li>
      <li><strong>Empirical Anchoring:</strong> Direct translation of terrestrial family survey choices into simulated agent decisions.</li>
      <li><strong>Dual Application:</strong> Space habitats &amp; extreme Earth environments.</li>
    </ul>
  </div>
</div>

---
layout: default
class: text-slate-900 bg-white
---

# <span class="text-blue-600">02.</span> Project Structure &amp; Expertise

Team composition bridging space science, behavioral psychology, and anthropology

<div class="p-3.5 bg-amber-50 border border-amber-200 rounded-xl mb-5 text-center shadow-sm">
  <span class="font-bold text-amber-900 text-sm">Principal Investigator (PI):</span> 
  <span class="italic text-amber-800 text-sm">[To Be Determined — NYU Abu Dhabi Faculty / Leadership]</span>
</div>

<div class="grid grid-cols-3 gap-4 text-xs">
  <div class="p-4 bg-slate-50 rounded-xl border border-slate-200 shadow-sm hover:shadow-md transition-all">
    <h3 class="font-bold text-sm mb-1 text-slate-900">🪐 Sergey Nikiforov</h3>
    <p class="italic text-blue-700 font-semibold mb-2 text-[11px]">Center for Astrophysics and Space Science Fellow, NYUAD</p>
    <ul class="list-disc pl-3 space-y-1.5 text-slate-600">
      <li>Planetary environment &amp; scenario constraints</li>
      <li>Habitat living-space &amp; resupply modeling</li>
      <li>Computational experiments &amp; ML output analysis</li>
      <li>FAMILIA code integration &amp; AI pipeline</li>
    </ul>
  </div>
  <div class="p-4 bg-slate-50 rounded-xl border border-slate-200 shadow-sm hover:shadow-md transition-all">
    <h3 class="font-bold text-sm mb-1 text-slate-900">🧠 Stefania V. Vacaru</h3>
    <p class="italic text-blue-700 font-semibold mb-2 text-[11px]">Behavioral Science Researcher</p>
    <ul class="list-disc pl-3 space-y-1.5 text-slate-600">
      <li>Psychological parameters (stress, attachment, caregiving)</li>
      <li>Family survey design &amp; empirical choice mapping</li>
      <li>Model calibration against human behavioral data</li>
    </ul>
  </div>
  <div class="p-4 bg-slate-50 rounded-xl border border-slate-200 shadow-sm hover:shadow-md transition-all">
    <h3 class="font-bold text-sm mb-1 text-slate-900">🏛️ Ivan Semyan</h3>
    <p class="italic text-blue-700 font-semibold mb-2 text-[11px]">Senior Fellow, NAS Armenia / NYUAD</p>
    <ul class="list-disc pl-3 space-y-1.5 text-slate-600">
      <li>Archaeological evidence on small-group labor sharing</li>
      <li>Pre-historic collective resource governance</li>
      <li>Experimental archaeology labor-time metrics</li>
    </ul>
  </div>
</div>

---
layout: default
class: text-slate-900 bg-white
---

# <span class="text-blue-600">03.</span> Quantitative Model Dynamics

Simulating balanced community parameters: Terrestrial Baseline vs. FAMILIA Habitat Strategy

<script setup>
import { ref } from 'vue'
const mode = ref('space')
</script>

<div class="flex gap-3 mb-4">
  <button @click="mode = 'earth'" :class="mode === 'earth' ? 'bg-blue-600 text-white shadow' : 'bg-slate-100 text-slate-600 border border-slate-200'" class="px-4 py-1.5 rounded-lg text-xs font-semibold transition-all">
    🌍 Terrestrial Baseline
  </button>
  <button @click="mode = 'space'" :class="mode === 'space' ? 'bg-emerald-600 text-white shadow' : 'bg-slate-100 text-slate-600 border border-slate-200'" class="px-4 py-1.5 rounded-lg text-xs font-semibold transition-all">
    🚀 Optimized Space Settlement (FAMILIA)
  </button>
</div>

<div class="grid grid-cols-3 gap-4 text-xs mb-4">
  <div class="p-4 rounded-xl border transition-all shadow-sm" :class="mode === 'space' ? 'bg-emerald-50/60 border-emerald-200' : 'bg-slate-50 border-slate-200'">
    <div class="font-semibold text-slate-600 mb-1">Community Joy &amp; Morale</div>
    <div class="text-2xl font-extrabold my-1" :class="mode === 'space' ? 'text-emerald-700' : 'text-blue-700'">
      {{ mode === 'space' ? '76% (High Wellbeing)' : '82% (Baseline)' }}
    </div>
    <div class="text-slate-500 text-[11px]">Shared family support &amp; communal events preserve emotional balance.</div>
  </div>

  <div class="p-4 rounded-xl border transition-all shadow-sm" :class="mode === 'space' ? 'bg-indigo-50/60 border-indigo-200' : 'bg-slate-50 border-slate-200'">
    <div class="font-semibold text-slate-600 mb-1">Living Space &amp; Commons</div>
    <div class="text-2xl font-extrabold my-1" :class="mode === 'space' ? 'text-indigo-700' : 'text-blue-700'">
      {{ mode === 'space' ? '35 m³ + Green Domes' : 'Over 120 m³ / family' }}
    </div>
    <div class="text-slate-500 text-[11px]">Smart architecture compensates compact quarters with social hubs.</div>
  </div>

  <div class="p-4 rounded-xl border transition-all shadow-sm" :class="mode === 'space' ? 'bg-amber-50/60 border-amber-200' : 'bg-slate-50 border-slate-200'">
    <div class="font-semibold text-slate-600 mb-1">Adaptive Resilience</div>
    <div class="text-2xl font-extrabold my-1" :class="mode === 'space' ? 'text-amber-700' : 'text-blue-700'">
      {{ mode === 'space' ? '42% (Equilibrium)' : '25% (Baseline)' }}
    </div>
    <div class="text-slate-500 text-[11px]">AI task scheduling &amp; workload balancing prevent burnout spikes.</div>
  </div>
</div>

<div class="p-3.5 bg-slate-900 text-white rounded-xl text-xs shadow-md">
  <div class="font-bold text-blue-400 mb-1.5 tracking-wider uppercase text-[10px]">FAMILIA Simulation Pipeline</div>
  <div class="grid grid-cols-4 gap-2 text-center text-[11px]">
    <div class="p-2 bg-slate-800 rounded-lg border border-slate-700">1. Family Survey Data<br><span class="text-slate-400">Empirical priorities</span></div>
    <div class="p-2 bg-slate-800 rounded-lg border border-slate-700">2. LLM Translation<br><span class="text-slate-400">Auditable agent rules</span></div>
    <div class="p-2 bg-slate-800 rounded-lg border border-slate-700">3. Physics Rule Core<br><span class="text-slate-400">Habitat energy &amp; O2</span></div>
    <div class="p-2 bg-emerald-900/80 rounded-lg border border-emerald-500/50 text-emerald-100">4. Thriving Metrics<br><span class="text-emerald-300">Wellbeing &amp; resilience</span></div>
  </div>
</div>

---
layout: default
class: text-slate-900 bg-white
---

# <span class="text-blue-600">04.</span> Deliverables &amp; UAE Strategic Impact

Key milestones and alignment with national priorities

<div class="grid grid-cols-2 gap-5 mt-4 text-sm">
  <div class="p-5 bg-slate-50 rounded-xl border border-slate-200 shadow-sm">
    <h3 class="font-bold text-base mb-3 text-blue-900">📦 Academic &amp; Technical Deliverables</h3>
    <ul class="list-disc pl-4 space-y-2 text-slate-700">
      <li><strong>Open-Source FAMILIA ABM:</strong> Fully ODD-documented model code &amp; parameter tables.</li>
      <li><strong>Methodological Benchmark:</strong> Direct comparison of rule-only vs. LLM-augmented simulation.</li>
      <li><strong>Publication:</strong> Manuscript target for <em>JASSS</em>, <em>Acta Astronautica</em>, or <em>npj Microgravity</em>.</li>
    </ul>
  </div>
  <div class="p-5 bg-slate-50 rounded-xl border border-slate-200 shadow-sm">
    <h3 class="font-bold text-base mb-3 text-blue-900">🇦🇪 Impact for CIDSAI &amp; UAE Science</h3>
    <ul class="list-disc pl-4 space-y-2 text-slate-700">
      <li><strong>Mars 2117 Decision Support:</strong> Tools for MBRSC and <strong>Mars Science City</strong> analog protocols.</li>
      <li><strong>Public Science Engagement:</strong> Interactive game-based family workshops in the UAE for space STEM.</li>
      <li><strong>Responsible AI Asset:</strong> Transparent, auditable generative AI protecting participant privacy.</li>
    </ul>
  </div>
</div>

<div class="mt-6 p-3.5 bg-blue-50 border border-blue-200 rounded-xl text-center text-xs font-semibold text-blue-900 shadow-sm">
  Follow-on Proposal Target: MBRSC Research Calls, UAE Space Agency, ESA/NASA Human Research Programs
</div>

<style>
/* Complete removal of Slidev navigation bars, headers, and floating TOC UI */
header,
.slidev-header,
.slidev-nav-header,
.slidev-v-toc,
[layout-header],
.slidev-layout header {
  display: none !important;
  visibility: hidden !important;
  height: 0 !important;
}
</style>