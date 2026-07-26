# theuser.game
<!doctype html>
<html lang="id"><head><script>window["__codeletBootstrap__"]=JSON.parse('{"A":"A","B":"20260723-05-e9a76f4"}');</script><script src="/_sdk/e358eac22bd01364.telemetry_sdk.js" integrity="sha512-KPxp3rw4K8Nu9ceWJc3gyM7srgaZxiFWOVbyu260EYzzAqdz10mfo5xyXrCx+wEKtGo77JbtmwXvFLbwrGzwvw=="></script>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Kewirausahaan TKJ XII</title>
  <script src="https://cdn.tailwindcss.com/3.4.17"></script>
  <script src="https://cdn.jsdelivr.net/npm/lucide@0.263.0/dist/umd/lucide.min.js"></script>
  <link href="https://fonts.googleapis.com/css2?family=DM+Sans:wght@400;500;700&amp;display=swap" rel="stylesheet">
  <style>
        body { font-family: 'DM Sans', sans-serif; margin: 0; overflow: hidden; }
        .page { display: none; flex-direction: column; height: calc(100 * min(var(--vh, 1vh), 1vh)); width: 100%; }
        .page.active { display: flex; }
        .sakura-float { animation: float 6s ease-in-out infinite; }
        @keyframes float { 0%,100%{ transform: translateY(0) rotate(0deg); } 50%{ transform: translateY(-15px) rotate(10deg); } }
        .bottom-nav { box-shadow: 0 -2px 10px rgba(0,0,0,0.05); }
        .nav-btn.active .nav-icon { color: #ec4899; }
        .nav-btn.active .nav-label { color: #ec4899; font-weight: 600; }
        .menu-card { transition: transform 0.2s; }
        .menu-card:active { transform: scale(0.95); }
        .quiz-option { transition: all 0.2s; }
        .quiz-option:hover { background: #fce7f3; }
    </style>
  <script src="/_sdk/6030e540d4419216.resizing_sdk.js" type="text/javascript" integrity="sha512-b5KWzyoXsbWP4smq4sftIi6Kts4YVBpBsz0BwCViwbBJkK64a3/Z6ZMdWA+qnplNcXw4mhZeqvQi3mOosiRJdA=="></script>
 </head>
 <body data-template-id="__page-root" class="w-full" style="background: rgb(255, 240, 245);"><!-- SPLASH SCREEN -->
  <div id="page-splash" class="page active relative overflow-hidden items-center justify-center"><img data-template-id="splash-bg" class="canva-image absolute inset-0 w-full h-full object-cover opacity-40" loading="lazy" src="https://images.pexels.com/photos/2099737/pexels-photo-2099737.jpeg?auto=compress&amp;cs=tinysrgb&amp;w=1280" alt="Captivating cherry blossoms in full bloom, creating a breathtaking springtime scene.">
   <div class="relative z-10 text-center px-6">
    <div class="text-5xl mb-4">
     🌸
    </div>
    <h1 data-template-id="splash-title" class="canva-text text-2xl font-bold" style="color: rgb(190, 24, 93); font-weight: 700; font-style: normal; font-size: 24px;">Kewirausahaan TKJ XII</h1>
    <p data-template-id="splash-subtitle" class="canva-text mt-2 text-sm" style="color: rgb(107, 114, 128); font-weight: 400; font-style: normal; font-size: 16px;">Belajar Kewirausahaan dengan Mudah 🌸</p>
    <div class="mt-8 flex justify-center gap-1"><span class="w-2 h-2 rounded-full bg-pink-400 sakura-float" style="animation-delay:0s"></span> <span class="w-2 h-2 rounded-full bg-pink-300 sakura-float" style="animation-delay:0.3s"></span> <span class="w-2 h-2 rounded-full bg-pink-200 sakura-float" style="animation-delay:0.6s"></span>
    </div>
   </div>
  </div><!-- BERANDA -->
  <div id="page-beranda" class="page">
   <header class="bg-gradient-to-r from-pink-500 to-blue-500 text-white px-5 pt-6 pb-8 rounded-b-3xl">
    <p data-template-id="beranda-greeting" class="canva-text text-sm opacity-90" style="color: rgb(255, 255, 255); font-weight: 400; font-style: normal; font-size: 16px;">Selamat Datang, Siswa TKJ! 👋</p>
    <h2 data-template-id="beranda-title" class="canva-text font-bold mt-1" style="color: rgb(255, 255, 255); font-weight: 700; font-style: normal; font-size: 24px;">Kewirausahaan Kelas XII</h2>
   </header>
   <main class="flex-1 overflow-auto px-5 -mt-4">
    <div class="bg-white rounded-2xl shadow-md p-4 mb-4"><img data-template-id="beranda-banner" class="canva-image w-full h-32 object-cover rounded-xl" loading="lazy" src="https://images.pexels.com/photos/5905709/pexels-photo-5905709.jpeg?auto=compress&amp;cs=tinysrgb&amp;w=1280" alt="Students learning with technology in classroom">
    </div>
    <h3 data-template-id="beranda-menu-label" class="canva-text font-semibold mb-3" style="color: rgb(30, 41, 59); font-weight: 600; font-style: normal; font-size: 19px;">Menu Utama</h3>
    <div class="grid grid-cols-3 gap-3 pb-4"><button type="button" class="menu-card bg-pink-50 rounded-xl p-4 flex flex-col items-center gap-2" onclick="goTo('materi')"> <i data-lucide="book-open" style="width:28px;height:28px;color:#ec4899"></i> <span data-template-id="menu-materi" class="canva-text text-xs font-medium" style="color: rgb(55, 65, 81); font-weight: 400; font-style: normal; font-size: 16px;">Materi</span> </button> <button type="button" class="menu-card bg-blue-50 rounded-xl p-4 flex flex-col items-center gap-2" onclick="goTo('latihan')"> <i data-lucide="edit-3" style="width:28px;height:28px;color:#3b82f6"></i> <span data-template-id="menu-latihan" class="canva-text text-xs font-medium" style="color: rgb(55, 65, 81); font-weight: 400; font-style: normal; font-size: 16px;">Latihan</span> </button> <button type="button" class="menu-card bg-purple-50 rounded-xl p-4 flex flex-col items-center gap-2" onclick="goTo('nilai')"> <i data-lucide="award" style="width:28px;height:28px;color:#8b5cf6"></i> <span data-template-id="menu-nilai" class="canva-text text-xs font-medium" style="color: rgb(55, 65, 81); font-weight: 400; font-style: normal; font-size: 16px;">Nilai</span> </button> <button type="button" class="menu-card bg-green-50 rounded-xl p-4 flex flex-col items-center gap-2" onclick="goTo('profil')"> <i data-lucide="user" style="width:28px;height:28px;color:#10b981"></i> <span data-template-id="menu-profil" class="canva-text text-xs font-medium" style="color: rgb(55, 65, 81); font-weight: 400; font-style: normal; font-size: 16px;">Profil</span> </button> <button type="button" class="menu-card bg-orange-50 rounded-xl p-4 flex flex-col items-center gap-2" onclick="goTo('tentang')"> <i data-lucide="info" style="width:28px;height:28px;color:#f97316"></i> <span data-template-id="menu-tentang" class="canva-text text-xs font-medium" style="color: rgb(55, 65, 81); font-weight: 400; font-style: normal; font-size: 16px;">Tentang</span> </button> <button type="button" class="menu-card bg-cyan-50 rounded-xl p-4 flex flex-col items-center gap-2" onclick="goTo('materi')"> <i data-lucide="monitor" style="width:28px;height:28px;color:#06b6d4"></i> <span data-template-id="menu-komputer" class="canva-text text-xs font-medium" style="color: rgb(55, 65, 81); font-weight: 400; font-style: normal; font-size: 16px;">Jaringan</span> </button>
    </div>
   </main>
   <nav class="bottom-nav bg-white flex justify-around py-3 border-t"><button type="button" class="nav-btn active flex flex-col items-center gap-1" onclick="goTo('beranda')"><i data-lucide="home" class="nav-icon" style="width:20px;height:20px"></i><span class="nav-label text-[10px]">Beranda</span></button> <button type="button" class="nav-btn flex flex-col items-center gap-1" onclick="goTo('materi')"><i data-lucide="book" class="nav-icon" style="width:20px;height:20px"></i><span class="nav-label text-[10px]">Materi</span></button> <button type="button" class="nav-btn flex flex-col items-center gap-1" onclick="goTo('latihan')"><i data-lucide="pen-tool" class="nav-icon" style="width:20px;height:20px"></i><span class="nav-label text-[10px]">Latihan</span></button> <button type="button" class="nav-btn flex flex-col items-center gap-1" onclick="goTo('profil')"><i data-lucide="user" class="nav-icon" style="width:20px;height:20px"></i><span class="nav-label text-[10px]">Profil</span></button>
   </nav>
  </div><!-- MATERI -->
  <div id="page-materi" class="page">
   <header class="bg-gradient-to-r from-pink-500 to-blue-500 text-white px-5 py-4 flex items-center gap-3"><button type="button" onclick="goTo('beranda')"><i data-lucide="arrow-left" style="width:20px;height:20px;color:white"></i></button>
    <h2 data-template-id="materi-title" class="canva-text font-bold" style="color: rgb(255, 255, 255); font-weight: 700; font-style: normal; font-size: 24px;">Materi Kewirausahaan</h2>
   </header>
   <main class="flex-1 overflow-auto px-5 py-4 space-y-3">
    <div data-template-id="materi-1" class="canva-card bg-white rounded-xl p-4 shadow-sm border-l-4 border-pink-400" style="background: rgb(255, 255, 255);">
     <h3 data-template-id="materi-1-title" class="canva-text font-semibold" style="color: rgb(30, 41, 59); font-weight: 600; font-style: normal; font-size: 19px;">Konsep Dasar Kewirausahaan</h3>
     <p data-template-id="materi-1-desc" class="canva-text text-sm mt-1" style="color: rgb(100, 116, 139); font-weight: 400; font-style: normal; font-size: 16px;">Pengertian, karakteristik, dan sikap wirausahawan yang sukses dalam bidang TKJ.</p>
    </div>
    <div data-template-id="materi-2" class="canva-card bg-white rounded-xl p-4 shadow-sm border-l-4 border-blue-400" style="background: rgb(255, 255, 255);">
     <h3 data-template-id="materi-2-title" class="canva-text font-semibold" style="color: rgb(30, 41, 59); font-weight: 600; font-style: normal; font-size: 19px;">Peluang Usaha di Bidang TKJ</h3>
     <p data-template-id="materi-2-desc" class="canva-text text-sm mt-1" style="color: rgb(100, 116, 139); font-weight: 400; font-style: normal; font-size: 16px;">Identifikasi peluang usaha jasa komputer, jaringan, dan layanan IT.</p>
    </div>
    <div data-template-id="materi-3" class="canva-card bg-white rounded-xl p-4 shadow-sm border-l-4 border-pink-400" style="background: rgb(255, 255, 255);">
     <h3 data-template-id="materi-3-title" class="canva-text font-semibold" style="color: rgb(30, 41, 59); font-weight: 600; font-style: normal; font-size: 19px;">Analisis SWOT</h3>
     <p data-template-id="materi-3-desc" class="canva-text text-sm mt-1" style="color: rgb(100, 116, 139); font-weight: 400; font-style: normal; font-size: 16px;">Cara menganalisis kekuatan, kelemahan, peluang, dan ancaman usaha.</p>
    </div>
    <div data-template-id="materi-4" class="canva-card bg-white rounded-xl p-4 shadow-sm border-l-4 border-blue-400" style="background: rgb(255, 255, 255);">
     <h3 data-template-id="materi-4-title" class="canva-text font-semibold" style="color: rgb(30, 41, 59); font-weight: 600; font-style: normal; font-size: 19px;">Menyusun Business Plan</h3>
     <p data-template-id="materi-4-desc" class="canva-text text-sm mt-1" style="color: rgb(100, 116, 139); font-weight: 400; font-style: normal; font-size: 16px;">Langkah-langkah membuat rencana bisnis untuk usaha di bidang teknologi.</p>
    </div>
    <div data-template-id="materi-5" class="canva-card bg-white rounded-xl p-4 shadow-sm border-l-4 border-pink-400" style="background: rgb(255, 255, 255);">
     <h3 data-template-id="materi-5-title" class="canva-text font-semibold" style="color: rgb(30, 41, 59); font-weight: 600; font-style: normal; font-size: 19px;">Pemasaran Digital</h3>
     <p data-template-id="materi-5-desc" class="canva-text text-sm mt-1" style="color: rgb(100, 116, 139); font-weight: 400; font-style: normal; font-size: 16px;">Strategi pemasaran online: SEO, media sosial, dan marketplace.</p>
    </div>
   </main>
  </div><!-- LATIHAN SOAL -->
  <div id="page-latihan" class="page">
   <header class="bg-gradient-to-r from-pink-500 to-blue-500 text-white px-5 py-4 flex items-center gap-3"><button type="button" onclick="goTo('beranda')"><i data-lucide="arrow-left" style="width:20px;height:20px;color:white"></i></button>
    <h2 data-template-id="latihan-title" class="canva-text font-bold" style="color: rgb(255, 255, 255); font-weight: 700; font-style: normal; font-size: 24px;">Latihan Soal</h2>
   </header>
   <main class="flex-1 overflow-auto px-5 py-4">
    <div id="quiz-intro" class="text-center py-10">
     <div class="text-4xl mb-3">
      📝
     </div>
     <p data-template-id="quiz-intro-text" class="canva-text mb-4" style="color: rgb(100, 116, 139); font-weight: 400; font-style: normal; font-size: 16px;">Uji pemahamanmu tentang Kewirausahaan TKJ. 5 soal pilihan ganda menanti!</p><button type="button" id="btn-mulai-quiz" data-template-id="btn-mulai-quiz" class="canva-button px-6 py-3 rounded-full font-semibold shadow-md" style="background: rgb(236, 72, 153); color: rgb(255, 255, 255); font-weight: 600; font-style: normal; font-size: 16px;">Mulai Latihan</button>
    </div>
    <div id="quiz-area" class="hidden">
     <div class="flex justify-between items-center mb-4"><span class="text-sm text-slate-500" id="q-num"></span> <span class="text-sm font-bold text-pink-500" id="q-score-display"></span>
     </div>
     <div class="bg-white rounded-2xl p-5 shadow-sm border">
      <p class="font-semibold text-slate-800 mb-4" id="q-question"></p>
      <div id="q-opts" class="space-y-2"></div>
     </div>
    </div>
    <div id="quiz-done" class="hidden text-center py-10">
     <div class="text-5xl mb-3">
      🌸
     </div>
     <p class="font-bold text-xl text-slate-800" id="quiz-final-score"></p>
     <p class="text-sm text-slate-500 mt-2" id="quiz-final-msg"></p><button type="button" onclick="startQuiz()" class="mt-4 px-5 py-2 bg-pink-500 text-white rounded-full font-medium">Ulangi</button>
    </div>
   </main>
  </div><!-- HASIL NILAI -->
  <div id="page-nilai" class="page">
   <header class="bg-gradient-to-r from-pink-500 to-blue-500 text-white px-5 py-4 flex items-center gap-3"><button type="button" onclick="goTo('beranda')"><i data-lucide="arrow-left" style="width:20px;height:20px;color:white"></i></button>
    <h2 data-template-id="nilai-title" class="canva-text font-bold" style="color: rgb(255, 255, 255); font-weight: 700; font-style: normal; font-size: 24px;">Hasil Nilai</h2>
   </header>
   <main class="flex-1 overflow-auto px-5 py-4">
    <div id="nilai-empty" class="text-center py-16">
     <p data-template-id="nilai-empty-text" class="canva-text" style="color: rgb(148, 163, 184); font-weight: 400; font-style: italic; font-size: 16px;">Belum ada hasil. Kerjakan latihan soal dulu ya! 📝</p>
    </div>
    <div id="nilai-list" class="space-y-3"></div>
   </main>
  </div><!-- PROFIL -->
  <div id="page-profil" class="page">
   <header class="bg-gradient-to-r from-pink-500 to-blue-500 text-white px-5 py-4 flex items-center gap-3"><button type="button" onclick="goTo('beranda')"><i data-lucide="arrow-left" style="width:20px;height:20px;color:white"></i></button>
    <h2 data-template-id="profil-title" class="canva-text font-bold" style="color: rgb(255, 255, 255); font-weight: 700; font-style: normal; font-size: 24px;">Profil Siswa</h2>
   </header>
   <main class="flex-1 overflow-auto px-5 py-6 flex flex-col items-center"><img data-template-id="profil-avatar" class="canva-image w-24 h-24 rounded-full object-cover shadow-lg" loading="lazy" src="https://images.pexels.com/photos/5435044/pexels-photo-5435044.jpeg?auto=compress&amp;cs=tinysrgb&amp;w=400" alt="Asian woman in school uniform smiling indoors">
    <h3 data-template-id="profil-nama" class="canva-text font-bold mt-4" style="color: rgb(30, 41, 59); font-weight: 700; font-style: normal; font-size: 19px;">Siswa TKJ</h3>
    <p data-template-id="profil-kelas" class="canva-text text-sm mt-1" style="color: rgb(100, 116, 139); font-weight: 400; font-style: normal; font-size: 16px;">Kelas XII TKJ - Tahun Ajaran 2025/2026</p>
    <div class="w-full mt-6 bg-white rounded-2xl p-5 shadow-sm border space-y-3">
     <div class="flex items-center gap-3">
      <i data-lucide="monitor" style="width:18px;height:18px;color:#ec4899"></i><span data-template-id="profil-jurusan" class="canva-text text-sm" style="color: rgb(55, 65, 81); font-weight: 400; font-style: normal; font-size: 16px;">Teknik Komputer &amp; Jaringan</span>
     </div>
     <div class="flex items-center gap-3">
      <i data-lucide="wifi" style="width:18px;height:18px;color:#3b82f6"></i><span data-template-id="profil-konsentrasi" class="canva-text text-sm" style="color: rgb(55, 65, 81); font-weight: 400; font-style: normal; font-size: 16px;">Konsentrasi: Jaringan Komputer</span>
     </div>
     <div class="flex items-center gap-3">
      <i data-lucide="graduation-cap" style="width:18px;height:18px;color:#8b5cf6"></i><span data-template-id="profil-sekolah" class="canva-text text-sm" style="color: rgb(55, 65, 81); font-weight: 400; font-style: normal; font-size: 16px;">SMK Negeri 1</span>
     </div>
    </div>
   </main>
  </div><!-- TENTANG -->
  <div id="page-tentang" class="page">
   <header class="bg-gradient-to-r from-pink-500 to-blue-500 text-white px-5 py-4 flex items-center gap-3"><button type="button" onclick="goTo('beranda')"><i data-lucide="arrow-left" style="width:20px;height:20px;color:white"></i></button>
    <h2 data-template-id="tentang-title" class="canva-text font-bold" style="color: rgb(255, 255, 255); font-weight: 700; font-style: normal; font-size: 24px;">Tentang Aplikasi</h2>
   </header>
   <main class="flex-1 overflow-auto px-5 py-6 text-center">
    <div class="text-4xl mb-3">
     🌸
    </div>
    <h3 data-template-id="tentang-app-name" class="canva-text font-bold" style="color: rgb(190, 24, 93); font-weight: 700; font-style: normal; font-size: 19px;">Kewirausahaan TKJ XII</h3>
    <p data-template-id="tentang-version" class="canva-text text-sm mt-1" style="color: rgb(148, 163, 184); font-weight: 400; font-style: normal; font-size: 16px;">Versi 1.0 - 2025</p>
    <div class="mt-6 bg-white rounded-2xl p-5 shadow-sm border text-left space-y-3">
     <p data-template-id="tentang-desc" class="canva-text text-sm" style="color: rgb(71, 85, 105); font-weight: 400; font-style: normal; font-size: 16px;">Aplikasi pembelajaran Kewirausahaan untuk siswa SMK jurusan TKJ Kelas XII. Dilengkapi materi, latihan soal, dan penilaian otomatis.</p>
     <p data-template-id="tentang-dev" class="canva-text text-sm" style="color: rgb(71, 85, 105); font-weight: 400; font-style: normal; font-size: 16px;">Dikembangkan sebagai media belajar interaktif bertema Sakura. 🌸</p>
    </div>
   </main>
  </div>
  <script src="/_sdk/c939c145c3c74230.editing_sdk.js" integrity="sha512-jh2pv/gl9Gzzn5dxfzwQO4wkqtnAQIim+LIUDYfVu2cdqPkQV2MqbjsDUW5IYbrSZFjRlOBrIWzlvWDXQYxOjg=="></script>
  <script src="/_sdk/935a53bc2e11fb8d.data_sdk.js" integrity="sha512-qr2oyPnEys1WebcOABaRh6hG77r5PWpqeWW6JTKbRJqly/INsfBi31CVNlTmHqjgeLpkVmmHZJUdxSx/32tOFQ=="></script>
  <script>
        // Navigation
        function goTo(page) {
            document.querySelectorAll('.page').forEach(p => p.classList.remove('active'));
            document.getElementById('page-' + page).classList.add('active');
            lucide.createIcons();
        }

        // Splash auto-advance
        setTimeout(() => goTo('beranda'), 3000);

        // Quiz data
        const quizData = [
            { q: "Apa yang dimaksud dengan kewirausahaan?", opts: ["Kemampuan menciptakan sesuatu yang baru dan bernilai", "Bekerja di perusahaan besar", "Menjual barang bekas", "Menabung di bank"], ans: 0 },
            { q: "Berikut yang merupakan ciri-ciri wirausahawan adalah...", opts: ["Malas dan pesimis", "Kreatif, inovatif, dan berani mengambil risiko", "Takut gagal", "Bergantung pada orang lain"], ans: 1 },
            { q: "Analisis SWOT terdiri dari...", opts: ["Strengths, Weaknesses, Opportunities, Threats", "Sales, Wages, Orders, Taxes", "System, Work, Output, Target", "Strategy, Wisdom, Operation, Timing"], ans: 0 },
            { q: "Apa tujuan utama membuat business plan?", opts: ["Untuk tugas sekolah saja", "Sebagai panduan menjalankan usaha", "Untuk dipamerkan", "Tidak ada tujuan"], ans: 1 },
            { q: "Dalam pemasaran digital, SEO adalah singkatan dari...", opts: ["Social Enterprise Organization", "Search Engine Optimization", "System Electronic Output", "Sales and Export Operation"], ans: 1 }
        ];

        let currentQ = 0, score = 0, attempts = [];

        document.getElementById('btn-mulai-quiz').addEventListener('click', startQuiz);

        function startQuiz() {
            currentQ = 0; score = 0; attempts = [];
            document.getElementById('quiz-intro').classList.add('hidden');
            document.getElementById('quiz-done').classList.add('hidden');
            document.getElementById('quiz-area').classList.remove('hidden');
            showQ();
        }

        function showQ() {
            const q = quizData[currentQ];
            document.getElementById('q-num').textContent = `Soal ${currentQ + 1}/${quizData.length}`;
            document.getElementById('q-score-display').textContent = `Skor: ${score}`;
            document.getElementById('q-question').textContent = q.q;
            const optsEl = document.getElementById('q-opts');
            optsEl.innerHTML = '';
            q.opts.forEach((o, i) => {
                const btn = document.createElement('button');
                btn.type = 'button';
                btn.className = 'quiz-option w-full text-left px-4 py-3 rounded-xl border border-slate-200 text-sm font-medium';
                btn.textContent = o;
                btn.addEventListener('click', () => pickAnswer(i));
                optsEl.appendChild(btn);
            });
        }

        function pickAnswer(idx) {
            const q = quizData[currentQ];
            const correct = idx === q.ans;
            if (correct) score++;
            attempts.push({ question: q.q, answer: q.opts[q.ans], user_answer: q.opts[idx], is_correct: correct, score: correct ? 1 : 0, completed_at: new Date().toISOString() });

            const btns = document.getElementById('q-opts').querySelectorAll('button');
            btns.forEach((b, i) => {
                b.disabled = true;
                if (i === q.ans) b.classList.add('bg-green-100', 'border-green-400');
                else if (i === idx && !correct) b.classList.add('bg-red-100', 'border-red-400');
            });

            setTimeout(() => {
                currentQ++;
                if (currentQ < quizData.length) showQ();
                else finishQuiz();
            }, 1000);
        }

        async function finishQuiz() {
            document.getElementById('quiz-area').classList.add('hidden');
            document.getElementById('quiz-done').classList.remove('hidden');
            document.getElementById('quiz-final-score').textContent = `${score} / ${quizData.length} Benar`;
            const pct = (score / quizData.length) * 100;
            document.getElementById('quiz-final-msg').textContent = pct >= 80 ? 'Luar biasa! Kamu hebat! 🎉' : pct >= 60 ? 'Bagus! Terus belajar ya!' : 'Jangan menyerah, coba lagi!';

            // Save each attempt
            for (const a of attempts) {
                if (allRecords.length >= 999) break;
                await window.dataSdk.create(a);
            }
        }

        // Nilai page
        let allRecords = [];
        function renderNilai() {
            const list = document.getElementById('nilai-list');
            const empty = document.getElementById('nilai-empty');
            if (allRecords.length === 0) { empty.classList.remove('hidden'); list.innerHTML = ''; return; }
            empty.classList.add('hidden');
            // Group by completed_at (batch of 5)
            const batches = [];
            let batch = []; let batchTime = '';
            const sorted = [...allRecords].sort((a, b) => (b.completed_at || '').localeCompare(a.completed_at || ''));
            sorted.forEach((r, i) => {
                batch.push(r);
                if (batch.length === 5 || i === sorted.length - 1) {
                    batches.push({ time: batch[0].completed_at, items: batch, score: batch.filter(x => x.is_correct).length });
                    batch = [];
                }
            });
            list.innerHTML = batches.map((b, i) => {
                const d = b.time ? new Date(b.time).toLocaleDateString('id-ID', { day: 'numeric', month: 'short', year: 'numeric', hour: '2-digit', minute: '2-digit' }) : '-';
                return `<div class="bg-white rounded-xl p-4 shadow-sm border flex justify-between items-center"><div><p class="font-semibold text-sm text-slate-800">Percobaan ${batches.length - i}</p><p class="text-xs text-slate-400">${d}</p></div><span class="text-lg font-bold text-pink-500">${b.score}/5</span></div>`;
            }).join('');
        }

        // Data SDK
        const handler = {
            onDataChanged(data) {
                allRecords = data;
                renderNilai();
            }
        };
        (async () => { await window.dataSdk.init(handler); })();

        lucide.createIcons();
    </script>
 
</body></html>
