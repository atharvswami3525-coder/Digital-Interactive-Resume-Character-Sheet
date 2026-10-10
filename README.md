<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Cozy Corner — Hot & Cold Coffee & Softea Chocklet Cafe</title>
  <meta name="description" content="Order handcrafted hot coffee, artisanal cold brews, and signature Softea Chocklet drinks online from Cozy Corner. Earn Cozy Beans with every order[cite: 5]." />
  <script src="https://cdn.tailwindcss.com"></script>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Fraunces:ital,opsz,wght@0,9..144,500;0,9..144,600;0,9..144,700;1,9..144,400&family=JetBrains+Mono:wght@400;500;600&family=Plus+Jakarta+Sans:wght@400;500;600;700&display=swap" rel="stylesheet">
  <script>
    tailwind.config = {
      theme: {
        extend: {
          colors: {
            cozy: {
              bg: '#FAF7F2',
              card: '#F3EDE2',
              dark: '#1C1613',
              accent: '#8C4A27',
              chocolate: '#4A2810',
              foam: '#FFFDF9'
            }
          },
          fontFamily: {
            serif: ['Fraunces', 'serif'],
            sans: ['Plus Jakarta Sans', 'sans-serif'],
            mono: ['JetBrains Mono', 'monospace'],
          }
        }
      }
    }
  </script>
  <style>
    @keyframes float {
      0%, 100% { transform: translateY(0px) rotate(0deg); }
      50% { transform: translateY(-10px) rotate(2deg); }
    }
    @keyframes steam {
      0% { transform: translateY(0) scaleX(1); opacity: 0; }
      50% { opacity: 0.6; }
      100% { transform: translateY(-25px) scaleX(1.5); opacity: 0; }
    }
    .float-slow { animation: float 6s ease-in-out infinite; }
    .steam-1 { animation: steam 3s ease-out infinite; }
    .steam-2 { animation: steam 3s ease-out 1.2s infinite; }
    
    .glass-card {
      background: rgba(255, 253, 249, 0.75);
      backdrop-filter: blur(12px);
      border: 1px solid rgba(140, 74, 39, 0.12);
    }
  </style>
</head>
<body class="bg-[#FAF7F2] text-[#1C1613] font-sans antialiased selection:bg-[#8C4A27] selection:text-white min-h-screen flex flex-col justify-between overflow-x-hidden">

  <!-- Ambient Background Blobs -->
  <div class="fixed top-0 left-1/4 w-96 h-96 bg-[#E8D9CD] rounded-full filter blur-3xl opacity-50 -z-10 pointer-events-none"></div>
  <div class="fixed bottom-10 right-10 w-96 h-96 bg-[#DFCCB9] rounded-full filter blur-3xl opacity-45 -z-10 pointer-events-none"></div>

  <!-- Header -->
  <header class="w-full max-w-6xl mx-auto px-6 py-6 flex items-center justify-between">
    <div class="flex items-center gap-3">
      <div class="w-10 h-10 rounded-2xl bg-[#8C4A27] flex items-center justify-center text-white shadow-lg shadow-[#8C4A27]/20 font-serif font-bold text-xl">
        C
      </div>
      <div>
        <span class="font-serif font-bold text-xl tracking-tight text-[#1C1613]">Cozy Corner</span>
        <span class="block text-[10px] uppercase font-mono tracking-widest text-[#8C4A27]">Cafe & Softea Chocklet</span>
      </div>
    </div>
    <div class="hidden md:flex items-center gap-8 text-sm font-medium text-[#1C1613]/80">
      <a href="#menu" class="hover:text-[#8C4A27] transition-colors">Menu Highlights</a>
      <a href="#rewards" class="hover:text-[#8C4A27] transition-colors">Cozy Beans</a>
      <a href="#about" class="hover:text-[#8C4A27] transition-colors">Our Story</a>
    </div>
    <a href="#order" class="bg-[#1C1613] hover:bg-[#8C4A27] text-white px-5 py-2.5 rounded-full text-sm font-medium transition-all shadow-md">
      Order Online
    </a>
  </header>

  <!-- Hero Section -->
  <main class="w-full max-w-6xl mx-auto px-6 py-12 md:py-20 grid grid-cols-1 md:grid-cols-12 gap-12 items-center">
    
    <!-- Left Copy -->
    <div class="md:col-span-7 space-y-6 text-left">
      <div class="inline-flex items-center gap-2 bg-[#F3EDE2] border border-[#8C4A27]/20 px-3.5 py-1.5 rounded-full text-xs font-mono text-[#8C4A27]">
        <span class="w-2 h-2 rounded-full bg-[#8C4A27] animate-pulse"></span>
        Shop 08, Kamla Arcade, JM Road, Pune[cite: 5]
      </div>
      
      <h1 class="font-serif text-5xl md:text-7xl font-bold tracking-tight leading-[1.08]">
        Handcrafted <span class="text-[#8C4A27] italic">warmth</span> in every sip.
      </h1>
      
      <p class="text-lg text-[#1C1613]/75 max-w-xl font-normal leading-relaxed">
        Experience artisanal hot coffee, refreshing cold brews, and our signature decadent <strong class="text-[#1C1613] font-semibold">Softea Chocklet</strong> drinks crafted to make your day cozy[cite: 5].
      </p>

      <!-- Action Buttons -->
      <div class="flex flex-wrap items-center gap-4 pt-2">
        <a href="#order" class="bg-[#8C4A27] hover:bg-[#723b1e] text-white px-8 py-4 rounded-2xl font-medium transition-all shadow-xl shadow-[#8C4A27]/25 flex items-center gap-2 group">
          Explore Menu & Order
          <svg class="w-4 h-4 group-hover:translate-x-1 transition-transform" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M14 5l7 7m0 0l-7 7m7-7H3"/></svg>
        </a>
        <div class="flex items-center gap-3 px-4 py-3 glass-card rounded-2xl">
          <div class="flex -space-x-2">
            <div class="w-8 h-8 rounded-full bg-[#8C4A27] text-white flex items-center justify-center text-xs font-bold border-2 border-white">4.5</div>
          </div>
          <div class="text-xs">
            <p class="font-bold text-[#1C1613]">1,113+ Ratings</p>
            <p class="text-[#1C1613]/60">Loved across Pune[cite: 5]</p>
          </div>
        </div>
      </div>
    </div>

    <!-- Right Creative Visual -->
    <div class="md:col-span-5 relative flex justify-center">
      <div class="relative w-72 h-80 sm:w-80 sm:h-96 float-slow">
        
        <!-- Coffee Mug Illustration Container -->
        <div class="absolute inset-0 bg-gradient-to-br from-[#E2D4C5] to-[#C9B4A0] rounded-[40px] shadow-2xl flex flex-col items-center justify-center p-6 border-4 border-white/60 relative overflow-hidden">
          
          <!-- Steam Animation -->
          <div class="absolute top-12 flex gap-4">
            <div class="w-2 h-12 bg-white/40 rounded-full blur-[2px] steam-1"></div>
            <div class="w-2 h-16 bg-white/40 rounded-full blur-[2px] steam-2"></div>
          </div>

          <!-- Cup Body -->
          <div class="w-48 h-48 bg-[#4A2810] rounded-b-[70px] rounded-t-2xl shadow-inner relative flex flex-col items-center justify-center border-t-8 border-[#341C0A]">
            <!-- Foam Heart / Art -->
            <div class="w-24 h-16 bg-[#FFFDF9] rounded-full opacity-90 shadow-inner flex items-center justify-center transform -rotate-6">
              <span class="text-[#8C4A27] font-serif text-xl font-bold">Cozy</span>
            </div>
            
            <!-- Cup Handle -->
            <div class="absolute -right-10 top-10 w-12 h-20 border-8 border-[#4A2810] rounded-r-3xl"></div>
          </div>

          <!-- Badge Overlay -->
          <div class="absolute bottom-4 bg-white/90 backdrop-blur-md px-4 py-2 rounded-xl shadow-lg border border-[#8C4A27]/15 flex items-center gap-2">
            <span class="text-xl">🍫</span>
            <div class="text-left">
              <p class="text-[10px] font-mono text-[#8C4A27] uppercase font-bold tracking-wider">Signature Special</p>
              <p class="text-xs font-bold text-[#1C1613]">Softea Chocklet Brew</p>
            </div>
          </div>

        </div>

      </div>
    </div>

  </main>

  <!-- Footer Info / Quick Banner -->
  <footer class="w-full border-t border-[#1C1613]/10 py-6 mt-12 bg-[#F3EDE2]/50 backdrop-blur-sm">
    <div class="w-full max-w-6xl mx-auto px-6 flex flex-col md:flex-row items-center justify-between text-xs text-[#1C1613]/70 gap-4">
      <p>© 2026 Cozy Corner Cafe. Handcrafted with warmth & passion[cite: 5].</p>
      <div class="flex items-center gap-6 font-mono">
        <span>📞 +91 88066 73797[cite: 5]</span>
        <span>₹120 - ₹260 avg[cite: 5]</span>
      </div>
    </div>
  </footer>

</body>
</html>
