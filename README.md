
<html lang="id" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Laela Aldellisa - Portfolio 2026</title>
    <!-- Tailwind CSS via CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        navy: {
                            700: '#1D3557',
                            800: '#1E293B',
                            900: '#0F172A',
                            accent: '#1D4ED8'
                        }
                    }
                }
            }
        }
    </script>
    <!-- Fonts & Icons -->
    <link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@400;500;600;700;800&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        body { font-family: 'Plus Jakarta Sans', sans-serif; }
    </style>
</head>
<body class="bg-white text-slate-800 antialiased selection:bg-navy-900 selection:text-white">

    <!-- Navbar -->
    <header class="fixed top-0 left-0 w-full bg-white/90 backdrop-blur-md z-50 border-b border-slate-100">
        <div class="max-w-6xl mx-auto px-6 py-4 flex justify-between items-center">
            <a href="#" class="text-xl font-extrabold tracking-wider text-navy-900 uppercase">
                LAELA<span class="text-navy-accent">.</span>
            </a>
            <nav class="hidden md:flex space-x-8 text-sm font-semibold text-slate-600">
                <a href="#about" class="hover:text-navy-900 transition-colors">Tentang Saya</a>
                <a href="#experience" class="hover:text-navy-900 transition-colors">Pengalaman</a>
                <a href="#projects" class="hover:text-navy-900 transition-colors">Projects</a>
                <a href="#skills" class="hover:text-navy-900 transition-colors">Keahlian</a>
            </nav>
            <a href="#contact" class="bg-navy-900 text-white px-6 py-2.5 rounded-lg text-sm font-bold hover:bg-navy-accent transition-colors shadow-sm">
                Hubungi Saya
            </a>
        </div>
    </header>

    <main class="pt-16">

        <!-- Hero Section (Inspired by Behance Cover Style) -->
        <section class="bg-navy-900 text-white py-24 sm:py-32 px-6 relative overflow-hidden">
            <!-- Background Accent Grid/Shadow Effect -->
            <div class="absolute inset-0 opacity-10 bg-[radial-gradient(#fff_1px,transparent_1px)] [background-size:16px_16px]"></div>
            
            <div class="max-w-5xl mx-auto text-center relative z-10">
                <div class="inline-block bg-white text-navy-900 px-4 py-1.5 rounded-sm font-black text-xs uppercase tracking-widest mb-6 shadow-md">
                    PORTOFOLIO 2026
                </div>
                <h1 class="text-4xl sm:text-7xl font-extrabold tracking-tight uppercase leading-none mb-6">
                    LAELA ALDELLISA
                </h1>
                <p class="text-xl sm:text-2xl text-slate-300 font-light max-w-2xl mx-auto mb-8 italic">
                    "Your only limit is your mind"
                </p>
                <div class="flex justify-center gap-4">
                    <a href="#projects" class="bg-white text-navy-900 px-8 py-3.5 rounded-lg font-bold hover:bg-slate-100 transition-all shadow-lg">
                        Lihat Project <i class="fa-solid fa-arrow-down ml-2 text-xs"></i>
                    </a>
                    <a href="#contact" class="border-2 border-white text-white px-8 py-3.5 rounded-lg font-bold hover:bg-white hover:text-navy-900 transition-all">
                        Kontak
                    </a>
                </div>
            </div>

            <!-- Ticker Banner (Visual Accent from Behance Reference) -->
            <div class="w-full bg-white text-navy-900 py-3 mt-16 -rotate-1 shadow-lg overflow-hidden whitespace-nowrap">
                <div class="inline-block animate-pulse font-extrabold text-sm sm:text-base uppercase tracking-wider space-x-8">
                    <span>HUMAN RESOURCES</span> • <span>TALENT ACQUISITION</span> • <span>PSYCHOLOGY GRADUATE</span> • <span>PEOPLE DEVELOPMENT</span> • <span>RECRUITMENT SPECIALIST</span>
                </div>
            </div>
        </section>

        <!-- About Me Section -->
        <section id="about" class="py-20 bg-white">
            <div class="max-w-5xl mx-auto px-6">
                <div class="grid grid-cols-1 md:grid-cols-12 gap-10 items-center">
                    
                    <!-- Profile Card Box -->
                    <div class="md:col-span-5">
                        <div class="bg-slate-50 border border-slate-200 p-6 rounded-2xl shadow-sm text-center">
                            <div class="w-32 h-32 mx-auto mb-4 bg-navy-900 text-white rounded-full flex items-center justify-center text-4xl font-bold">
                                LA
                            </div>
                            <h3 class="text-xl font-bold text-navy-900">Laela Aldellisa</h3>
                            <p class="text-sm text-slate-500 mb-4">S1 Psikologi • UIN Walisongo</p>
                            <div class="inline-block px-3 py-1 bg-navy-900 text-white text-xs font-semibold rounded-full mb-2">
                                IPK 3.73 / 4.00
                            </div>
                            <p class="text-xs text-slate-400">Lulusan 2025</p>
                        </div>
                    </div>

                    <!-- Description -->
                    <div class="md:col-span-7">
                        <span class="text-xs font-extrabold uppercase tracking-widest text-navy-accent">Tentang Saya</span>
                        <h2 class="text-3xl font-extrabold text-navy-900 mt-1 mb-6">Hi! Saya Laela</h2>
                        <p class="text-slate-600 leading-relaxed mb-4">
                            Saya merupakan Fresh Graduate Psikologi yang memiliki minat berkarir di bidang **Human Resources**. Berpengalaman mendukung proses rekrutmen selama program magang di Balai Latihan Kerja serta terlibat dalam proses seleksi calon peserta pelatihan[cite: 1].
                        </p>
                        <p class="text-slate-600 leading-relaxed mb-6">
                            Terbiasa mendampingi rekruter dalam tahapan rekrutmen, menyusun instrumen tes untuk mendukung proses seleksi yang objektif, serta memiliki pemahaman mendalam terkait penggunaan alat tes psikologi untuk asesmen kandidat[cite: 1].
                        </p>
                        <div class="p-4 bg-slate-50 border-l-4 border-navy-900 rounded-r-lg text-xs text-slate-600">
                            <strong>Judul Skripsi:</strong> Pengaruh Job Insecurity dan Organizational Citizenship Behavior terhadap Turnover Intention pada Gen Z di Kota Semarang[cite: 1].
                        </div>
                    </div>

                </div>
            </div>
        </section>

        <!-- Experience Section -->
        <section id="experience" class="py-20 bg-slate-50 border-y border-slate-100">
            <div class="max-w-5xl mx-auto px-6">
                <div class="mb-12">
                    <span class="text-xs font-extrabold uppercase tracking-widest text-navy-accent">Track Record</span>
                    <h2 class="text-3xl font-extrabold text-navy-900 mt-1">Pengalaman Kerja & Organisasi</h2>
                </div>

                <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
                    <!-- Magang BLK -->
                    <div class="bg-white p-6 rounded-xl border border-slate-200 shadow-sm">
                        <span class="text-xs font-bold text-navy-accent bg-blue-50 px-2.5 py-1 rounded">Feb - Apr 2024</span>
                        <h3 class="text-lg font-bold text-navy-900 mt-3">Human Resources Intern</h3>
                        <p class="text-xs text-slate-500 mb-4">Balai Latihan Kerja - Semarang</p>
                        <ul class="text-xs text-slate-600 space-y-2 list-disc list-inside">
                            <li>Menyusun pertanyaan seleksi tes tertulis calon peserta pelatihan kerja[cite: 1].</li>
                            <li>Membersamai proses seleksi wawancara calon peserta pelatihan kerja[cite: 1].</li>
                            <li>Merekap data absensi harian & mendampingi peserta berkebutuhan khusus[cite: 1].</li>
                        </ul>
                    </div>

                    <!-- Magang PKBI -->
                    <div class="bg-white p-6 rounded-xl border border-slate-200 shadow-sm">
                        <span class="text-xs font-bold text-navy-accent bg-blue-50 px-2.5 py-1 rounded">Apr - Jun 2024</span>
                        <h3 class="text-lg font-bold text-navy-900 mt-3">People Development & Education Intern</h3>
                        <p class="text-xs text-slate-500 mb-4">PKBI Jawa Tengah - Semarang</p>
                        <ul class="text-xs text-slate-600 space-y-2 list-disc list-inside">
                            <li>Mengembangkan keterampilan melalui pembelajaran kepada anak-anak jalanan[cite: 1].</li>
                            <li>Membuat konten edukasi sosial media & mendampingi sesi edukasi remaja[cite: 1].</li>
                            <li>Pencatatan dan pengelolaan dokumentasi rekam konseling sesuai prosedur[cite: 1].</li>
                        </ul>
                    </div>

                    <!-- Organisasi Sekretaris -->
                    <div class="bg-white p-6 rounded-xl border border-slate-200 shadow-sm">
                        <span class="text-xs font-bold text-slate-600 bg-slate-100 px-2.5 py-1 rounded">2023 - 2024</span>
                        <h3 class="text-lg font-bold text-navy-900 mt-3">Sekretaris Umum</h3>
                        <p class="text-xs text-slate-500 mb-4">UKM Taekwondo UIN Walisongo</p>
                        <ul class="text-xs text-slate-600 space-y-2 list-disc list-inside">
                            <li>Menyusun catatan rapat dengan ketelitian 90% & mengarsip surat masuk/keluar[cite: 1].</li>
                            <li>Mengelola administrasi & komunikasi antar-anggota/unit kegiatan[cite: 1].</li>
                        </ul>
                    </div>

                    <!-- Organisasi Pubdekdok -->
                    <div class="bg-white p-6 rounded-xl border border-slate-200 shadow-sm">
                        <span class="text-xs font-bold text-slate-600 bg-slate-100 px-2.5 py-1 rounded">2022 - 2023</span>
                        <h3 class="text-lg font-bold text-navy-900 mt-3">Publikasi, Dekor, & Dokumentasi</h3>
                        <p class="text-xs text-slate-500 mb-4">UKM Taekwondo UIN Walisongo</p>
                        <ul class="text-xs text-slate-600 space-y-2 list-disc list-inside">
                            <li>Membuat poster, pamflet, dan banner acara[cite: 2].</li>
                            <li>Mendokumentasikan seluruh kegiatan latihan rutin, seminar, dan kejuaraan[cite: 2].</li>
                        </ul>
                    </div>
                </div>
            </div>
        </section>

        <!-- Projects Section (Grid Card - Placeholder for Manual Edit) -->
        <section id="projects" class="py-20 bg-white">
            <div class="max-w-5xl mx-auto px-6">
                <div class="mb-12">
                    <span class="text-xs font-extrabold uppercase tracking-widest text-navy-accent">Showcase</span>
                    <h2 class="text-3xl font-extrabold text-navy-900 mt-1">My Projects</h2>
                    <p class="text-xs text-slate-400 mt-1">*Bagian ini disiapkan untuk Anda isi dengan karya/proyek manual di kemudian hari.</p>
                </div>

                <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
                    <!-- Project Card 1 (Placeholder) -->
                    <div class="border border-slate-200 rounded-xl overflow-hidden shadow-sm group hover:border-navy-900 transition-all">
                        <div class="h-44 bg-slate-100 flex items-center justify-center text-slate-400">
                            <i class="fa-regular fa-image text-3xl"></i>
                        </div>
                        <div class="p-5">
                            <span class="text-[10px] font-extrabold uppercase tracking-wider text-navy-accent bg-blue-50 px-2 py-0.5 rounded">Category Name</span>
                            <h3 class="text-base font-bold text-navy-900 mt-2">Judul Project 1</h3>
                            <p class="text-xs text-slate-500 mt-1 mb-4">Deskripsi singkat mengenai proyek yang pernah Anda kerjakan atau modul pelatihan yang Anda buat.</p>
                            <a href="#" class="text-xs font-bold text-navy-900 hover:text-navy-accent inline-flex items-center">
                                Detail Project <i class="fa-solid fa-arrow-right ml-1 text-[10px]"></i>
                            </a>
                        </div>
                    </div>

                    <!-- Project Card 2 (Placeholder) -->
                    <div class="border border-slate-200 rounded-xl overflow-hidden shadow-sm group hover:border-navy-900 transition-all">
                        <div class="h-44 bg-slate-100 flex items-center justify-center text-slate-400">
                            <i class="fa-regular fa-image text-3xl"></i>
                        </div>
                        <div class="p-5">
                            <span class="text-[10px] font-extrabold uppercase tracking-wider text-navy-accent bg-blue-50 px-2 py-0.5 rounded">Category Name</span>
                            <h3 class="text-base font-bold text-navy-900 mt-2">Judul Project 2</h3>
                            <p class="text-xs text-slate-500 mt-1 mb-4">Deskripsi singkat mengenai proyek yang pernah Anda kerjakan atau modul pelatihan yang Anda buat.</p>
                            <a href="#" class="text-xs font-bold text-navy-900 hover:text-navy-accent inline-flex items-center">
                                Detail Project <i class="fa-solid fa-arrow-right ml-1 text-[10px]"></i>
                            </a>
                        </div>
                    </div>

                    <!-- Project Card 3 (Placeholder) -->
                    <div class="border border-slate-200 rounded-xl overflow-hidden shadow-sm group hover:border-navy-900 transition-all">
                        <div class="h-44 bg-slate-100 flex items-center justify-center text-slate-400">
                            <i class="fa-regular fa-image text-3xl"></i>
                        </div>
                        <div class="p-5">
                            <span class="text-[10px] font-extrabold uppercase tracking-wider text-navy-accent bg-blue-50 px-2 py-0.5 rounded">Category Name</span>
                            <h3 class="text-base font-bold text-navy-900 mt-2">Judul Project 3</h3>
                            <p class="text-xs text-slate-500 mt-1 mb-4">Deskripsi singkat mengenai proyek yang pernah Anda kerjakan atau modul pelatihan yang Anda buat.</p>
                            <a href="#" class="text-xs font-bold text-navy-900 hover:text-navy-accent inline-flex items-center">
                                Detail Project <i class="fa-solid fa-arrow-right ml-1 text-[10px]"></i>
                            </a>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Skills & Badges Section -->
        <section id="skills" class="py-20 bg-slate-50 border-t border-slate-100">
            <div class="max-w-5xl mx-auto px-6">
                <div class="mb-12">
                    <span class="text-xs font-extrabold uppercase tracking-widest text-navy-accent">Capabilities</span>
                    <h2 class="text-3xl font-extrabold text-navy-900 mt-1">My Skills & Certifications</h2>
                </div>

                <div class="space-y-8">
                    <!-- Administrasi Alat Tes Psikologi -->
                    <div>
                        <h3 class="text-sm font-bold uppercase tracking-wider text-slate-400 mb-3">Administrasi Alat Tes Psikologi</h3>
                        <div class="flex flex-wrap gap-2">
                            <span class="px-4 py-2 bg-navy-900 text-white rounded-lg text-xs font-bold">Kraeplin</span>
                            <span class="px-4 py-2 bg-navy-900 text-white rounded-lg text-xs font-bold">Pauli</span>
                            <span class="px-4 py-2 bg-navy-900 text-white rounded-lg text-xs font-bold">BAUM</span>
                            <span class="px-4 py-2 bg-navy-900 text-white rounded-lg text-xs font-bold">DAP</span>
                            <span class="px-4 py-2 bg-navy-900 text-white rounded-lg text-xs font-bold">HTP</span>
                            <span class="px-4 py-2 bg-navy-900 text-white rounded-lg text-xs font-bold">WARTEGG</span>
                        </div>
                    </div>

                    <!-- Hard & Soft Skills -->
                    <div>
                        <h3 class="text-sm font-bold uppercase tracking-wider text-slate-400 mb-3">Hard & Soft Skills</h3>
                        <div class="flex flex-wrap gap-2">
                            <span class="px-4 py-2 bg-white text-navy-900 border border-slate-200 rounded-lg text-xs font-semibold">Microsoft Word</span>
                            <span class="px-4 py-2 bg-white text-navy-900 border border-slate-200 rounded-lg text-xs font-semibold">Microsoft Excel</span>
                            <span class="px-4 py-2 bg-white text-navy-900 border border-slate-200 rounded-lg text-xs font-semibold">PowerPoint</span>
                            <span class="px-4 py-2 bg-white text-navy-900 border border-slate-200 rounded-lg text-xs font-semibold">Canva</span>
                            <span class="px-4 py-2 bg-blue-50 text-navy-accent border border-blue-100 rounded-lg text-xs font-semibold">Komunikasi Efektif</span>
                            <span class="px-4 py-2 bg-blue-50 text-navy-accent border border-blue-100 rounded-lg text-xs font-semibold">Berpikir Kritis</span>
                            <span class="px-4 py-2 bg-blue-50 text-navy-accent border border-blue-100 rounded-lg text-xs font-semibold">Public Speaking</span>
                            <span class="px-4 py-2 bg-blue-50 text-navy-accent border border-blue-100 rounded-lg text-xs font-semibold">Kerjasama Tim</span>
                        </div>
                    </div>

                    <!-- Sertifikasi -->
                    <div>
                        <h3 class="text-sm font-bold uppercase tracking-wider text-slate-400 mb-3">Sertifikasi</h3>
                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-3 text-xs">
                            <div class="p-3 bg-white border border-slate-200 rounded-lg">
                                <span class="font-bold text-navy-900 block">HR Specialist: Rekrutmen Karyawan dan Payroll</span>
                                <span class="text-slate-500">IODA Academy (Sep 2026)</span>
                            </div>
                            <div class="p-3 bg-white border border-slate-200 rounded-lg">
                                <span class="font-bold text-navy-900 block">Talent Acquisition E-Learning</span>
                                <span class="text-slate-500">MySkill (Sep 2026)</span>
                            </div>
                            <div class="p-3 bg-white border border-slate-200 rounded-lg">
                                <span class="font-bold text-navy-900 block">TOEFL ITP Certification</span>
                                <span class="text-slate-500">UIN Wali
