
# Yvette-Ondachi-Profile
This explains what I do and why I do it. It is based on my personal gifting or talents, experience, areas I am passionate about and life's calling. My aspiration is that it will be inspirational and lead to doors of collaboration
<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Yvette Atieno Ondachi | Commercial Growth Architect & Systems Builder</title>
  
  <!-- Tailwind CSS CDN -->
  <script src="https://cdn.tailwindcss.com"></script>
  
  <!-- Google Fonts: Cormorant Garamond & Plus Jakarta Sans -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,400;0,600;0,700;1,400;1,600&family=Plus+Jakarta+Sans:wght@300;400;500;600;700&display=swap" rel="stylesheet">
  
  <!-- Phosphor Icons -->
  <script src="https://unpkg.com/@phosphor-icons/web"></script>

  <script>
    tailwind.config = {
      theme: {
        extend: {
          colors: {
            obsidian: '#090A0C',
            surface: '#111317',
            surfaceLight: '#181B22',
            gold: {
              300: '#F5DEB3',
              400: '#E5C17C',
              500: '#D4AF37',
              600: '#AA8825'
            }
          },
          fontFamily: {
            serif: ['"Cormorant Garamond"', 'serif'],
            sans: ['"Plus Jakarta Sans"', 'sans-serif']
          }
        }
      }
    }
  </script>

  <style>
    body {
      background-color: #090A0C;
      color: #E2E8F0;
      font-family: 'Plus Jakarta Sans', sans-serif;
    }
    .gold-gradient-text {
      background: linear-gradient(135deg, #FFF3D6 0%, #D4AF37 50%, #AA8825 100%);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
    }
    .card-border {
      border: 1px solid rgba(212, 175, 55, 0.15);
      backdrop-filter: blur(12px);
    }
    .card-border:hover {
      border-color: rgba(212, 175, 55, 0.4);
    }
  </style>
</head>
<body class="selection:bg-gold-500/20 selection:text-gold-300">

  <!-- Image Uploader / Sync Notice Bar -->
  <div class="bg-surfaceLight/90 border-b border-gold-500/20 px-4 py-2.5 text-xs text-slate-300 flex flex-wrap items-center justify-between gap-3 sticky top-0 z-50 backdrop-blur-md">
    <div class="flex items-center gap-2">
      <span class="inline-block w-2 h-2 rounded-full bg-gold-400 animate-pulse"></span>
      <span><strong>Flagship Image Live Preview:</strong> Click any photo placeholder below or upload your photos here to see them appear live immediately.</span>
    </div>
    <div class="flex items-center gap-2">
      <label class="cursor-pointer bg-gold-500/10 hover:bg-gold-500/20 text-gold-400 border border-gold-500/30 px-3 py-1 rounded-full text-xs font-semibold transition">
        <i class="ph ph-upload-simple mr-1"></i> Choose Files to Preview
        <input type="file" id="batchUploader" multiple accept="image/*" class="hidden" onchange="handleBatchUpload(this)">
      </label>
    </div>
  </div>

  <!-- Navigation -->
  <nav class="border-b border-white/5 bg-obsidian/80 backdrop-blur-md sticky top-9 z-40">
    <div class="max-w-7xl mx-auto px-6 py-4 flex items-center justify-between">
      <div>
        <a href="#hero" class="text-xl font-serif tracking-widest text-white uppercase font-bold">
          Yvette <span class="text-gold-400">Ondachi</span>
        </a>
        <p class="text-[10px] tracking-widest text-slate-400 uppercase">Commercial Growth Architect &middot; Sub-Saharan Africa</p>
      </div>

      <div class="hidden md:flex items-center space-x-8 text-xs font-medium tracking-wider uppercase text-slate-300">
        <a href="#thesis" class="hover:text-gold-400 transition">The Thesis</a>
        <a href="#systems" class="hover:text-gold-400 transition">Systems Built</a>
        <a href="#gallery" class="hover:text-gold-400 transition">In Motion</a>
        <a href="#impact" class="hover:text-gold-400 transition">Impact</a>
        <a href="#contact" class="px-4 py-2 rounded-full border border-gold-400/40 text-gold-300 hover:bg-gold-500/10 transition">Engage</a>
      </div>
    </div>
  </nav>

  <!-- Hero Section -->
  <section id="hero" class="relative pt-16 pb-24 md:py-28 overflow-hidden">
    <div class="max-w-7xl mx-auto px-6 grid grid-cols-1 lg:grid-cols-12 gap-12 items-center">
      
      <!-- Hero Copy -->
      <div class="lg:col-span-7 space-y-6">
        <div class="inline-flex items-center gap-2 px-3 py-1 rounded-full bg-gold-500/10 border border-gold-500/20 text-gold-400 text-xs tracking-wider uppercase font-medium">
          <i class="ph ph-globe-hemisphere-east text-sm"></i> Pan-African Catalyst &middot; 25+ Years Leadership[cite: 1]
        </div>

        <h1 class="text-4xl sm:text-6xl font-serif font-bold leading-tight text-white">
          Architecting systems where <span class="gold-gradient-text italic">African Potential</span> meets catalytic capital.
        </h1>

        <p class="text-base sm:text-lg text-slate-300 font-light leading-relaxed max-w-2xl">
          Africa is not lacking in ingenuity, resilience, or market potential. The continent's frontier lies in bridging the divide between high-capacity execution and sovereign, scalable capital. I design, deploy, and scale commercial operating systems across <strong>Food</strong>, <strong>Healthcare</strong>, and <strong>Entrepreneurship</strong>[cite: 1].
        </p>

        <div class="flex flex-wrap gap-4 pt-4">
          <a href="#systems" class="px-6 py-3.5 bg-gradient-to-r from-gold-500 to-gold-600 text-obsidian font-semibold rounded-lg shadow-lg shadow-gold-500/10 hover:brightness-110 transition flex items-center gap-2 text-sm">
            <span>Explore the 3 Core Systems</span>
            <i class="ph ph-arrow-right"></i>
          </a>
          <a href="#contact" class="px-6 py-3.5 bg-surfaceLight border border-white/10 text-white rounded-lg hover:border-gold-400/40 transition text-sm flex items-center gap-2">
            <span>Advisory & Board Appointments</span>
          </a>
        </div>

        <!-- Verified Quick Metrics -->
        <div class="pt-8 border-t border-white/10 grid grid-cols-3 gap-6">
          <div>
            <div class="text-2xl sm:text-3xl font-serif font-bold text-gold-400">20x</div>
            <div class="text-[11px] text-slate-400 uppercase tracking-wider mt-1">YoY Sales Growth[cite: 1]</div>
          </div>
          <div>
            <div class="text-2xl sm:text-3xl font-serif font-bold text-gold-400">47K+</div>
            <div class="text-[11px] text-slate-400 uppercase tracking-wider mt-1">SME Stakeholders Impacted[cite: 1]</div>
          </div>
          <div>
            <div class="text-2xl sm:text-3xl font-serif font-bold text-gold-400">9+</div>
            <div class="text-[11px] text-slate-400 uppercase tracking-wider mt-1">Sub-Saharan Markets[cite: 1]</div>
          </div>
        </div>
      </div>

      <!-- Hero Visual (Mimi yv.jpg) -->
      <div class="lg:col-span-5 relative flex justify-center">
        <div class="relative w-full max-w-md aspect-[4/5] rounded-2xl overflow-hidden card-border bg-surface group shadow-2xl">
          <!-- Live/Drop Target Image -->
          <img 
            id="hero-img"
            src="Mimi yv.jpg" 
            alt="Yvette Atieno Ondachi" 
            class="w-full h-full object-cover object-top transition duration-500 group-hover:scale-105"
            onerror="renderFallback(this, 'Mimi yv.jpg', 'Flagship Portrait');"
          />
          <div class="absolute inset-0 bg-gradient-to-t from-obsidian via-transparent to-transparent opacity-80"></div>
          
          <div class="absolute bottom-6 left-6 right-6">
            <span class="text-xs uppercase tracking-widest text-gold-400 font-semibold">Executive Profile</span>
            <h3 class="text-xl font-serif font-bold text-white">Yvette Atieno Ondachi</h3>
            <p class="text-xs text-slate-300 mt-1">East Africa Regional Director, Sinapis Group &middot; Agribusiness & Healthcare Innovator[cite: 1]</p>
          </div>

          <label class="absolute top-4 right-4 bg-obsidian/70 backdrop-blur-md p-2 rounded-full cursor-pointer hover:bg-gold-500/20 text-gold-400 border border-gold-400/30 transition text-xs flex items-center gap-1.5" title="Swap this photo">
            <i class="ph ph-camera"></i>
            <span class="text-[10px] font-sans pr-1">Swap</span>
            <input type="file" accept="image/*" class="hidden" onchange="previewIndividual(this, 'hero-img')">
          </label>
        </div>
      </div>

    </div>
  </section>

  <!-- The Thesis Section -->
  <section id="thesis" class="py-20 bg-surface border-y border-white/5">
    <div class="max-w-4xl mx-auto px-6 text-center space-y-6">
      <div class="text-gold-400 text-xs font-semibold uppercase tracking-widest">The Core Conviction</div>
      <blockquote class="text-2xl sm:text-3xl font-serif italic text-white leading-relaxed">
        &ldquo;The continent of Africa possesses unmatched human vitality and entrepreneurial depth. Yet potential without robust operating systems remains undercapitalized. My life's work is designing the commercial plumbing and delivery mechanisms that make African enterprises globally bankable, resilient, and transformative.&rdquo;
      </blockquote>
      <div class="text-xs uppercase tracking-widest text-slate-400">&mdash; Yvette Ondachi, Commercial Growth Architect[cite: 1]</div>
    </div>
  </section>

  <!-- The 3 Core Systems -->
  <section id="systems" class="py-24 max-w-7xl mx-auto px-6">
    <div class="text-center max-w-2xl mx-auto mb-16 space-y-3">
      <div class="text-gold-400 text-xs font-semibold uppercase tracking-widest">Architectural Pillars</div>
      <h2 class="text-3xl sm:text-4xl font-serif font-bold text-white">The Three Systems Built for Scale</h2>
      <p class="text-slate-400 text-sm">Deploying scalable frameworks across the continent's most vital sectors.</p>
    </div>

    <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
      
      <!-- System 1: Food -->
      <div class="bg-surface p-8 rounded-2xl card-border space-y-5 flex flex-col justify-between">
        <div class="space-y-4">
          <div class="w-12 h-12 rounded-xl bg-gold-500/10 border border-gold-500/30 flex items-center justify-center text-gold-400 text-2xl">
            <i class="ph ph-plant"></i>
          </div>
          <h3 class="text-2xl font-serif font-bold text-white">Food & Agribusiness Systems</h3>
          <p class="text-slate-300 text-sm leading-relaxed">
            Pioneered traceable, climate-resilient production pipelines connecting smallholder producers directly to institutional off-takers. Designed and deployed <strong>UstawiHub&copy;</strong>, a proprietary digital platform impacting 47,000+ agricultural stakeholders[cite: 1].
          </p>
        </div>
        <div class="pt-4 border-t border-white/10 text-xs text-gold-300 font-medium">
          Ojay Greene &middot; UstawiHub&copy; &middot; GIZ & USAID Partnerships[cite: 1]
        </div>
      </div>

      <!-- System 2: Healthcare -->
      <div class="bg-surface p-8 rounded-2xl card-border space-y-5 flex flex-col justify-between">
        <div class="space-y-4">
          <div class="w-12 h-12 rounded-xl bg-gold-500/10 border border-gold-500/30 flex items-center justify-center text-gold-400 text-2xl">
            <i class="ph ph-first-aid"></i>
          </div>
          <h3 class="text-2xl font-serif font-bold text-white">Healthcare & Life Sciences Systems</h3>
          <p class="text-slate-300 text-sm leading-relaxed">
            Over 16 years scaling multinational pharmaceutical delivery across GlaxoSmithKline and AstraZeneca[cite: 1]. Accelerated an <strong>11-fold increase in chronic medication access</strong> for underserved populations across 8 East African countries and pioneered B2B procurement with MedSource[cite: 1].
          </p>
        </div>
        <div class="pt-4 border-t border-white/10 text-xs text-gold-300 font-medium">
          GSK &middot; AstraZeneca &middot; MedSource Group[cite: 1]
        </div>
      </div>

      <!-- System 3: Entrepreneur OS -->
      <div class="bg-surface p-8 rounded-2xl card-border space-y-5 flex flex-col justify-between">
        <div class="space-y-4">
          <div class="w-12 h-12 rounded-xl bg-gold-500/10 border border-gold-500/30 flex items-center justify-center text-gold-400 text-2xl">
            <i class="ph ph-trend-up"></i>
          </div>
          <h3 class="text-2xl font-serif font-bold text-white">Entrepreneur Operating Systems</h3>
          <p class="text-slate-300 text-sm leading-relaxed">
            Leading regional expansion for <strong>Sinapis Group</strong> across Kenya, Uganda, and Rwanda[cite: 1]. Structuring capital readiness, institutional debt/equity alignment, and operational rigor for high-growth African founders to bridge the frontier capital deficit[cite: 1].
          </p>
        </div>
        <div class="pt-4 border-t border-white/10 text-xs text-gold-300 font-medium">
          Sinapis Group &middot; Multi-Country Ecosystem Pipeline[cite: 1]
        </div>
      </div>

    </div>
  </section>

  <!-- Photographic Leadership Gallery -->
  <section id="gallery" class="py-20 bg-surface border-y border-white/5">
    <div class="max-w-7xl mx-auto px-6">
      
      <div class="flex flex-col md:flex-row md:items-end justify-between mb-12">
        <div class="space-y-2">
          <div class="text-gold-400 text-xs font-semibold uppercase tracking-widest">Leadership In Motion</div>
          <h2 class="text-3xl sm:text-4xl font-serif font-bold text-white">Mobilizing People, Capital & Coalitions</h2>
        </div>
        <p class="text-slate-400 text-xs max-w-md mt-4 md:mt-0">
          From regional policy dialogues and cross-border accelerators to convening corporate boards and founder networks.
        </p>
      </div>

      <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
        
        <!-- Image Card 1: Sinapis Regional Leadership (IMG_3199.jpg) -->
        <div class="group relative rounded-2xl overflow-hidden card-border bg-surfaceLight aspect-[3/4]">
          <img 
            id="gal-img-1"
            src="IMG_3199.jpg" 
            alt="Yvette Ondachi - Sinapis Regional Leadership" 
            class="w-full h-full object-cover object-top transition duration-500 group-hover:scale-105"
            onerror="renderFallback(this, 'IMG_3199.jpg', 'Sinapis Leadership & Keynotes');"
          />
          <div class="absolute inset-0 bg-gradient-to-t from-obsidian via-obsidian/20 to-transparent"></div>
          <div class="absolute bottom-5 left-5 right-5">
            <span class="text-[10px] uppercase font-bold tracking-widest text-gold-400">Regional Leadership</span>
            <h4 class="text-base font-serif font-bold text-white mt-0.5">Scaling Ecosystems Across East Africa</h4>
            <p class="text-xs text-slate-300 mt-1">Driving multi-country entrepreneurship acceleration and capital access[cite: 1].</p>
          </div>
          <label class="absolute top-3 right-3 bg-obsidian/70 backdrop-blur-md p-1.5 rounded-full cursor-pointer hover:bg-gold-500/20 text-gold-400 border border-gold-400/30 transition text-xs" title="Swap this photo">
            <i class="ph ph-camera"></i>
            <input type="file" accept="image/*" class="hidden" onchange="previewIndividual(this, 'gal-img-1')">
          </label>
        </div>

        <!-- Image Card 2: Public Convening & Partnerships (Eldohub Partnership.jpg) -->
        <div class="group relative rounded-2xl overflow-hidden card-border bg-surfaceLight aspect-[3/4]">
          <img 
            id="gal-img-2"
            src="Eldohub Partnership.jpg" 
            alt="Yvette Ondachi - Convening Power & Strategic Partnerships" 
            class="w-full h-full object-cover object-top transition duration-500 group-hover:scale-105"
            onerror="renderFallback(this, 'Eldohub Partnership.jpg', 'Convening Strategic Partnerships');"
          />
          <div class="absolute inset-0 bg-gradient-to-t from-obsidian via-obsidian/20 to-transparent"></div>
          <div class="absolute bottom-5 left-5 right-5">
            <span class="text-[10px] uppercase font-bold tracking-widest text-gold-400">Strategic Convening</span>
            <h4 class="text-base font-serif font-bold text-white mt-0.5">Forging Impactful Coalitions</h4>
            <p class="text-xs text-slate-300 mt-1">Uniting ecosystem builders, commercial banks, and international partners[cite: 1].</p>
          </div>
          <label class="absolute top-3 right-3 bg-obsidian/70 backdrop-blur-md p-1.5 rounded-full cursor-pointer hover:bg-gold-500/20 text-gold-400 border border-gold-400/30 transition text-xs" title="Swap this photo">
            <i class="ph ph-camera"></i>
            <input type="file" accept="image/*" class="hidden" onchange="previewIndividual(this, 'gal-img-2')">
          </label>
        </div>

        <!-- Image Card 3: Accelerating Founders (IMG_3198.jpg) -->
        <div class="group relative rounded-2xl overflow-hidden card-border bg-surfaceLight aspect-[3/4]">
          <img 
            id="gal-img-3"
            src="IMG_3198.jpg" 
            alt="Yvette Ondachi - Accelerating High Growth Entrepreneurs" 
            class="w-full h-full object-cover object-top transition duration-500 group-hover:scale-105"
            onerror="renderFallback(this, 'IMG_3198.jpg', 'Accelerating Founders');"
          />
          <div class="absolute inset-0 bg-gradient-to-t from-obsidian via-obsidian/20 to-transparent"></div>
          <div class="absolute bottom-5 left-5 right-5">
            <span class="text-[10px] uppercase font-bold tracking-widest text-gold-400">Founder Mentorship</span>
            <h4 class="text-base font-serif font-bold text-white mt-0.5">Equipping Africa's Growth Leaders</h4>
            <p class="text-xs text-slate-300 mt-1">Transforming high-potential visionaries into disciplined commercial operators[cite: 1].</p>
          </div>
          <label class="absolute top-3 right-3 bg-obsidian/70 backdrop-blur-md p-1.5 rounded-full cursor-pointer hover:bg-gold-500/20 text-gold-400 border border-gold-400/30 transition text-xs" title="Swap this photo">
            <i class="ph ph-camera"></i>
            <input type="file" accept="image/*" class="hidden" onchange="previewIndividual(this, 'gal-img-3')">
          </label>
        </div>

      </div>
    </div>
  </section>

  <!-- Global Recognition & Speaking -->
  <section id="impact" class="py-24 max-w-7xl mx-auto px-6">
    <div class="grid grid-cols-1 lg:grid-cols-12 gap-12 items-center">
      <div class="lg:col-span-5 space-y-4">
        <div class="text-gold-400 text-xs font-semibold uppercase tracking-widest">Global Platform</div>
        <h2 class="text-3xl sm:text-4xl font-serif font-bold text-white">Thought Leadership & Global Convening</h2>
        <p class="text-slate-300 text-sm leading-relaxed">
          Sharing battle-tested playbooks on market access, agritech supply chain architecture, and commercial viability across the world's most prestigious stages[cite: 1].
        </p>
        <div class="space-y-3 pt-4">
          <div class="flex items-start gap-3 text-sm text-slate-200">
            <i class="ph ph-check-circle text-gold-400 text-lg mt-0.5"></i>
            <span><strong>Yale School of Management</strong> &mdash; African Business Practicum & Yale Women Innovators Keynote[cite: 1]</span>
          </div>
          <div class="flex items-start gap-3 text-sm text-slate-200">
            <i class="ph ph-check-circle text-gold-400 text-lg mt-0.5"></i>
            <span><strong>CNN African Start-Up</strong> &mdash; Featured Innovation Business Leader[cite: 1]</span>
          </div>
          <div class="flex items-start gap-3 text-sm text-slate-200">
            <i class="ph ph-check-circle text-gold-400 text-lg mt-0.5"></i>
            <span><strong>UN FAO / World Food Day (Stockholm)</strong> &mdash; Climate-Smart Food Systems Keynote[cite: 1]</span>
          </div>
          <div class="flex items-start gap-3 text-sm text-slate-200">
            <i class="ph ph-check-circle text-gold-400 text-lg mt-0.5"></i>
            <span><strong>SOCAP & Opportunity Collaboration</strong> &mdash; Frontier Capital Mechanics[cite: 1]</span>
          </div>
        </div>
      </div>

      <div class="lg:col-span-7 bg-surface p-8 sm:p-10 rounded-2xl card-border space-y-6">
        <h3 class="text-xl font-serif font-bold text-white border-b border-white/10 pb-4">Executive Endorsements</h3>
        <div class="grid grid-cols-1 md:grid-cols-2 gap-6 text-sm">
          <div class="space-y-2">
            <div class="text-gold-400 font-serif font-bold text-lg">Dr. Ademola Braimoh[cite: 1]</div>
            <div class="text-xs uppercase tracking-wider text-slate-400">Head of Climate Smart Agriculture &ndash; Africa[cite: 1]</div>
            <div class="text-xs text-slate-300 font-semibold">World Bank Group &middot; Washington, DC[cite: 1]</div>
          </div>
          <div class="space-y-2">
            <div class="text-gold-400 font-serif font-bold text-lg">Jacqueline Wambua[cite: 1]</div>
            <div class="text-xs uppercase tracking-wider text-slate-400">East Africa General Manager[cite: 1]</div>
            <div class="text-xs text-slate-300 font-semibold">Roche East Africa[cite: 1]</div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Contact & Advisory -->
  <section id="contact" class="py-20 bg-surface border-t border-white/5">
    <div class="max-w-4xl mx-auto px-6 text-center space-y-6">
      <div class="text-gold-400 text-xs font-semibold uppercase tracking-widest">Connect & Architect</div>
      <h2 class="text-3xl sm:text-5xl font-serif font-bold text-white">Let's Build Resilient Systems Together</h2>
      <p class="text-slate-300 text-sm max-w-lg mx-auto">
        Available for Non-Executive Board Appointments, Growth Strategy Advisory, and International Keynote Engagements.
      </p>

      <div class="flex flex-wrap justify-center gap-6 pt-4 text-sm">
        <a href="mailto:yaondachi@gmail.com" class="px-6 py-3 rounded-xl bg-gold-500 text-obsidian font-bold hover:brightness-110 transition flex items-center gap-2">
          <i class="ph ph-envelope-simple text-base"></i>
          <span>yaondachi@gmail.com</span>[cite: 1]
        </a>
        <a href="tel:+254721383595" class="px-6 py-3 rounded-xl bg-surfaceLight border border-white/10 text-white hover:border-gold-400/40 transition flex items-center gap-2">
          <i class="ph ph-phone text-base"></i>
          <span>+254 721 383 595</span>[cite: 1]
        </a>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer class="py-8 bg-obsidian text-center text-xs text-slate-500 border-t border-white/5">
    &copy; 2026 Yvette Atieno Ondachi. All rights reserved. Commercial Growth Architect &middot; Nairobi, Kenya.[cite: 1]
  </footer>

  <!-- Dynamic Image Mapping Engine -->
  <script>
    // Fallback UI generator if the image file isn't in the same folder yet
    function renderFallback(imgElement, filename, label) {
      const parent = imgElement.parentElement;
      imgElement.style.display = 'none';

      // Check if fallback already injected
      if (parent.querySelector('.fallback-box')) return;

      const fallbackDiv = document.createElement('div');
      fallbackDiv.className = 'fallback-box absolute inset-0 flex flex-col items-center justify-center p-6 text-center bg-surfaceLight border border-dashed border-gold-500/30 rounded-2xl cursor-pointer hover:bg-gold-500/5 transition';
      fallbackDiv.innerHTML = `
        <div class="w-12 h-12 rounded-full bg-gold-500/10 flex items-center justify-center text-gold-400 mb-3 text-xl">
          <i class="ph ph-image"></i>
        </div>
        <p class="text-xs font-semibold text-white">${label}</p>
        <p class="text-[11px] text-gold-400 font-mono mt-1">${filename}</p>
        <span class="mt-4 px-3 py-1 bg-gold-500/20 text-gold-300 text-[10px] rounded-full font-sans">Click to pick photo</span>
      `;

      fallbackDiv.onclick = () => {
        const tempInput = document.createElement('input');
        tempInput.type = 'file';
        tempInput.accept = 'image/*';
        tempInput.onchange = (e) => previewIndividual(e.target, imgElement.id);
        tempInput.click();
      };

      parent.appendChild(fallbackDiv);
    }

    // Individual file reader
    function previewIndividual(input, imgId) {
      if (input.files && input.files[0]) {
        const reader = new FileReader();
        reader.onload = function(e) {
          const targetImg = document.getElementById(imgId);
          targetImg.src = e.target.result;
          targetImg.style.display = 'block';
          
          // Remove any fallback box
          const fallback = targetImg.parentElement.querySelector('.fallback-box');
          if (fallback) fallback.remove();
        };
        reader.readAsDataURL(input.files[0]);
      }
    }

    // Batch uploader by file name
    function handleBatchUpload(input) {
      const files = Array.from(input.files);
      files.forEach(file => {
        const reader = new FileReader();
        reader.onload = (e) => {
          const dataUri = e.target.result;
          const name = file.name.toLowerCase();

          if (name.includes('mimi') || name.includes('yv')) {
            updateImage('hero-img', dataUri);
          } else if (name.includes('3199')) {
            updateImage('gal-img-1', dataUri);
          } else if (name.includes('eldohub') || name.includes('partnership')) {
            updateImage('gal-img-2', dataUri);
          } else if (name.includes('3198')) {
            updateImage('gal-img-3', dataUri);
          }
        };
        reader.readAsDataURL(file);
      });
    }

    function updateImage(id, dataUri) {
      const el = document.getElementById(id);
      if (el) {
        el.src = dataUri;
        el.style.display = 'block';
        const fallback = el.parentElement.querySelector('.fallback-box');
        if (fallback) fallback.remove();
      }
    }
  </script>
</body>
</html>
