<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Alok Dubey -- Video Creator & Content Writer</title>
  <meta name="description" content="Official portfolio of Alok Dubey -- Video Creator & Content Writer. Engineering student (2nd year) at KIIT, Ghaziabad. Showreel, projects, writing, services, and contact." />
  <meta name="author" content="Alok Dubey" />
  <meta property="og:title" content="Alok Dubey -- Video Creator & Content Writer" />
  <meta property="og:description" content="Showreel, portfolio, writing samples, and services by Alok Dubey (B.Tech 2nd year, KIIT Ghaziabad)." />
  <meta property="og:type" content="website" />
  <meta property="og:image" content="https://images.unsplash.com/photo-1524253482453-3fed8d2fe12b?w=1200" />
  <meta property="og:url" content="https://example.com" />
  <link rel="icon" href="https://fav.farm/🎬" />

  <!-- Tailwind CSS -->
  <script src="https://cdn.tailwindcss.com"></script>
  <script>
    tailwind.config = {
      theme: {
        extend: {
          colors: {
            primary: { DEFAULT: '#6366f1' },   /* indigo-500 */
            accent: { DEFAULT: '#a855f7' },    /* purple-500 */
            ink: { DEFAULT: '#0b1020' }
          },
          boxShadow: {
            soft: '0 10px 30px rgba(2,6,23,.10)',
            softxl: '0 20px 60px rgba(2,6,23,.12)'
          }
        }
      }
    }
  </script>

  <!-- Icons -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css" crossorigin="anonymous" referrerpolicy="no-referrer" />

  <!-- AOS (Animate on Scroll) -->
  <link rel="stylesheet" href="https://unpkg.com/aos@2.3.4/dist/aos.css" />
  <style>
    .card { transition: transform .25s ease, box-shadow .25s ease; }
    .card:hover { transform: translateY(-3px); box-shadow: 0 18px 50px rgba(2,6,23,.12); }
    .no-scrollbar::-webkit-scrollbar { display: none; }
    .no-scrollbar { -ms-overflow-style: none; scrollbar-width: none; }
    .glow {
      background-image: radial-gradient(1200px 600px at 10% -10%, rgba(99,102,241,.15), transparent 60%),
                        radial-gradient(1000px 600px at 110% 10%, rgba(168,85,247,.12), transparent 60%);
    }
  </style>
</head>

<body class="bg-white text-gray-800 dark:bg-ink dark:text-gray-100">
  <!-- ===== NAVBAR ===== -->
  <header class="sticky top-0 z-50 border-b border-gray-200/70 dark:border-gray-800/70 backdrop-blur bg-white/70 dark:bg-ink/60">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <div class="flex items-center justify-between h-16">
        <a href="#home" class="flex items-center gap-2 font-bold text-lg tracking-tight">
          <span class="inline-flex h-9 w-9 items-center justify-center rounded-xl bg-gradient-to-tr from-primary to-accent text-white">AD</span>
          <span>Alok Dubey</span>
        </a>
        <nav class="hidden md:flex items-center gap-6 font-medium">
          <a class="hover:text-primary" href="#about">About</a>
          <a class="hover:text-primary" href="#services">Services</a>
          <a class="hover:text-primary" href="#portfolio">Portfolio</a>
          <a class="hover:text-primary" href="#writing">Writing</a>
          <a class="hover:text-primary" href="#resume">Resume</a>
          <a class="hover:text-primary" href="#contact">Contact</a>
        </nav>
        <div class="flex items-center gap-2">
          <button id="themeToggle" class="p-2 rounded-xl hover:bg-gray-100 dark:hover:bg-gray-900" aria-label="Toggle dark mode">
            <i class="fa-solid fa-moon"></i>
          </button>
          <a href="#contact" class="hidden sm:inline-flex items-center gap-2 px-4 py-2 rounded-xl bg-gradient-to-r from-primary to-accent text-white shadow-soft hover:shadow-softxl">
            <i class="fa-solid fa-paper-plane"></i><span>Hire Me</span>
          </a>
          <button id="menuBtn" class="md:hidden p-2 rounded-xl hover:bg-gray-100 dark:hover:bg-gray-900" aria-label="Open menu">
            <i class="fa-solid fa-bars"></i>
          </button>
        </div>
      </div>
    </div>
    <!-- Mobile Menu -->
    <div id="mobileMenu" class="md:hidden hidden border-t border-gray-200 dark:border-gray-800">
      <nav class="max-w-7xl mx-auto px-4 py-3 grid gap-3 text-base font-medium">
        <a class="hover:text-primary" href="#about">About</a>
        <a class="hover:text-primary" href="#services">Services</a>
        <a class="hover:text-primary" href="#portfolio">Portfolio</a>
        <a class="hover:text-primary" href="#writing">Writing</a>
        <a class="hover:text-primary" href="#resume">Resume</a>
        <a class="hover:text-primary" href="#faq">FAQ</a>
        <a class="hover:text-primary" href="#contact">Contact</a>
      </nav>
    </div>
  </header>

  <!-- ===== HERO ===== -->
  <section id="home" class="relative glow">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-20 sm:py-28 grid lg:grid-cols-2 gap-12 items-center">
      <div data-aos="fade-up">
        <span class="inline-flex items-center gap-2 px-3 py-1.5 rounded-full bg-primary/10 text-primary text-sm font-semibold">
          <i class="fa-solid fa-bolt"></i> Open for Projects & Internships
        </span>
        <h1 class="mt-5 text-4xl sm:text-5xl font-black leading-tight tracking-tight">
          Hi, I'm <span class="text-transparent bg-clip-text bg-gradient-to-r from-primary to-accent">Alok Dubey</span> --
          <span class="block">Video Creator & Content Writer.</span>
        </h1>
        <p class="mt-5 text-lg text-gray-600 dark:text-gray-300">
          I'm a 2nd-year Engineering student at <strong>KIIT, Ghaziabad</strong>. I craft engaging videos and write crisp, impactful content that tells stories and drives action.
        </p>
        <div class="mt-8 flex flex-wrap gap-3">
          <a href="#portfolio" class="px-5 py-3 rounded-xl text-white bg-gradient-to-r from-primary to-accent hover:opacity-95 shadow-soft"><i class="fa-solid fa-play mr-2"></i> Watch Showreel</a>
          <a href="#services" class="px-5 py-3 rounded-xl border border-gray-300 dark:border-gray-700 hover:bg-gray-50 dark:hover:bg-gray-900"><i class="fa-solid fa-briefcase mr-2"></i> Services</a>
          <a href="#contact" class="px-5 py-3 rounded-xl border border-gray-300 dark:border-gray-700 hover:bg-gray-50 dark:hover:bg-gray-900"><i class="fa-brands fa-whatsapp mr-2"></i> WhatsApp Me</a>
        </div>
        <div class="mt-8 flex items-center gap-4 text-2xl">
          <a aria-label="YouTube" class="hover:text-primary" href="https://www.youtube.com/" target="_blank" rel="noreferrer"><i class="fa-brands fa-youtube"></i></a>
          <a aria-label="Instagram" class="hover:text-primary" href="#" target="_blank" rel="noreferrer"><i class="fa-brands fa-instagram"></i></a>
          <a aria-label="LinkedIn" class="hover:text-primary" href="#" target="_blank" rel="noreferrer"><i class="fa-brands fa-linkedin"></i></a>
          <a aria-label="Medium" class="hover:text-primary" href="#" target="_blank" rel="noreferrer"><i class="fa-brands fa-medium"></i></a>
        </div>
      </div>
      <div data-aos="fade-up" data-aos-delay="80">
        <div class="relative">
          <!-- Keeping your first image as requested -->
             <img loading="lazy" class="rounded-2xl shadow-softxl                   w-full object-cover"
              src="https://i.ibb.co/GQ9JPyHf/IMG-20250824-155145-529.jpg"
               alt="Alok Dubey portrait" />
          <div class="absolute -bottom-6 -right-6 bg-white dark:bg-gray-900 rounded-2xl p-4 shadow-xl flex items-center gap-4">
            <div class="text-3xl">🎬</div>
            <div>
              <p class="text-sm text-gray-600 dark:text-gray-300">Completed</p>
              <p class="font-bold text-lg">50+ Video Edits</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- ===== ABOUT ===== -->
  <section id="about" class="py-16 sm:py-24 bg-gray-50 dark:bg-gray-900/30">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <div class="grid lg:grid-cols-3 gap-10 items-start">
        <div class="lg:col-span-2" data-aos="fade-up">
          <h2 class="text-3xl font-extrabold tracking-tight">About Me</h2>
          <p class="mt-4 text-gray-600 dark:text-gray-300 leading-relaxed">
            I'm an engineering student passionate about storytelling through visuals and words. From scripting to shooting and editing, I handle end-to-end video production. On the writing side, I create blogs, scripts, captions, and website copy that are SEO-friendly and audience-first.
          </p>
          <ul class="mt-6 grid sm:grid-cols-2 gap-4 text-sm">
            <li class="flex items-center gap-3"><i class="fa-solid fa-school text-primary"></i> B.Tech (2nd Year), KIIT, Ghaziabad</li>
            <li class="flex items-center gap-3"><i class="fa-solid fa-location-dot text-primary"></i> Based in Ghaziabad, India</li>
            <li class="flex items-center gap-3"><i class="fa-solid fa-language text-primary"></i> Languages: English, Hindi</li>
            <li class="flex items-center gap-3"><i class="fa-solid fa-envelope text-primary"></i> Email: <a class="underline" href="mailto:alokd@example.com">alokd@example.com</a></li>
          </ul>
          <div class="mt-6 flex flex-wrap gap-3">
            <a href="#contact" class="px-5 py-3 rounded-xl text-white bg-gradient-to-r from-primary to-accent shadow-soft"><i class="fa-solid fa-paper-plane mr-2"></i> Contact</a>
            <a href="#" download class="px-5 py-3 rounded-xl border border-gray-300 dark:border-gray-700 hover:bg-gray-50 dark:hover:bg-gray-900"><i class="fa-solid fa-file-arrow-down mr-2"></i> Download CV</a>
          </div>
        </div>

        <div class="bg-white dark:bg-gray-900 rounded-2xl p-6 shadow-sm" data-aos="fade-up" data-aos-delay="60">
          <h3 class="font-bold text-lg">Skills & Tools</h3>
          <div class="mt-4 grid grid-cols-2 gap-3 text-sm">
            <div class="card rounded-xl border border-gray-200 dark:border-gray-800 p-3">
              <p class="font-semibold">Video</p>
              <p class="text-gray-600 dark:text-gray-400">Premiere Pro, CapCut, DaVinci Resolve</p>
            </div>
            <div class="card rounded-xl border border-gray-200 dark:border-gray-800 p-3">
              <p class="font-semibold">Writing</p>
              <p class="text-gray-600 dark:text-gray-400">Blogs, Scripts, Copy, SEO</p>
            </div>
            <div class="card rounded-xl border border-gray-200 dark:border-gray-800 p-3">
              <p class="font-semibold">Design</p>
              <p class="text-gray-600 dark:text-gray-400">Canva, Photoshop (basic)</p>
            </div>
            <div class="card rounded-xl border border-gray-200 dark:border-gray-800 p-3">
              <p class="font-semibold">Audio</p>
              <p class="text-gray-600 dark:text-gray-400">Audition, Audacity</p>
            </div>
          </div>
          <div class="mt-6 space-y-3">
            <div>
              <div class="flex justify-between text-sm"><span>Video Editing</span><span>90%</span></div>
              <div class="h-2 rounded-full bg-gray-200 dark:bg-gray-800"><div class="h-2 rounded-full bg-gradient-to-r from-primary to-accent" style="width:90%"></div></div>
            </div>
            <div>
              <div class="flex justify-between text-sm"><span>Script Writing</span><span>85%</span></div>
              <div class="h-2 rounded-full bg-gray-200 dark:bg-gray-800"><div class="h-2 rounded-full bg-gradient-to-r from-primary to-accent" style="width:85%"></div></div>
            </div>
            <div>
              <div class="flex justify-between text-sm"><span>Camera/Lighting</span><span>70%</span></div>
              <div class="h-2 rounded-full bg-gray-200 dark:bg-gray-800"><div class="h-2 rounded-full bg-gradient-to-r from-primary to-accent" style="width:70%"></div></div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- ===== SERVICES ===== -->
  <section id="services" class="py-16 sm:py-24">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <div class="flex items-end justify-between gap-6 flex-wrap">
        <div data-aos="fade-up">
          <h2 class="text-3xl font-extrabold tracking-tight">Services</h2>
          <p class="mt-2 text-gray-600 dark:text-gray-300">End-to-end video & content solutions for creators, brands, and student clubs.</p>
        </div>
        <a href="#pricing" class="inline-flex items-center gap-2 px-4 py-2 rounded-xl border border-gray-300 dark:border-gray-700 hover:bg-gray-50 dark:hover:bg-gray-900" data-aos="fade-up" data-aos-delay="60">
          View Pricing <i class="fa-solid fa-arrow-right"></i>
        </a>
      </div>

      <div class="mt-8 grid sm:grid-cols-2 lg:grid-cols-3 gap-6">
        <article class="card rounded-2xl border border-gray-200 dark:border-gray-800 p-6" data-aos="fade-up">
          <i class="fa-solid fa-clapperboard text-3xl text-primary"></i>
          <h3 class="mt-4 font-bold text-lg">Video Production</h3>
          <p class="mt-2 text-gray-600 dark:text-gray-300">Scripting, shooting, editing; reels, YouTube videos, event after-movies.</p>
          <ul class="mt-3 text-sm list-disc list-inside text-gray-600 dark:text-gray-400">
            <li>Reels/Shorts in vertical format</li>
            <li>Color grading & motion graphics</li>
            <li>Royalty-free music & SFX</li>
          </ul>
        </article>

        <article class="card rounded-2xl border border-gray-200 dark:border-gray-800 p-6" data-aos="fade-up" data-aos-delay="60">
          <i class="fa-solid fa-pen-nib text-3xl text-primary"></i>
          <h3 class="mt-4 font-bold text-lg">Content Writing</h3>
          <p class="mt-2 text-gray-600 dark:text-gray-300">Blogs, scripts, captions & website copy tailored to your audience.</p>
          <ul class="mt-3 text-sm list-disc list-inside text-gray-600 dark:text-gray-400">
            <li>SEO-friendly structure</li>
            <li>Research & outline</li>
            <li>Proofreading & revisions</li>
          </ul>
        </article>

        <article class="card rounded-2xl border border-gray-200 dark:border-gray-800 p-6" data-aos="fade-up" data-aos-delay="120">
          <i class="fa-solid fa-bullhorn text-3xl text-primary"></i>
          <h3 class="mt-4 font-bold text-lg">Social Media Kits</h3>
          <p class="mt-2 text-gray-600 dark:text-gray-300">Content calendars, thumbnails, post designs, and analytics setup.</p>
          <ul class="mt-3 text-sm list-disc list-inside text-gray-600 dark:text-gray-400">
            <li>Brand tone & style guide</li>
            <li>Hashtag strategy</li>
            <li>Monthly reporting</li>
          </ul>
        </article>
      </div>
    </div>
  </section>

  <!-- ===== SHOWREEL / PORTFOLIO ===== -->
  <section id="portfolio" class="py-16 sm:py-24 bg-gray-50 dark:bg-gray-900/30">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <div class="flex items-end justify-between gap-6 flex-wrap">
        <div data-aos="fade-up">
          <h2 class="text-3xl font-extrabold tracking-tight">Showreel & Portfolio</h2>
          <p class="mt-2 text-gray-600 dark:text-gray-300">A mix of client work, college fests, and personal projects.</p>
        </div>
        <div class="flex gap-3" data-aos="fade-up" data-aos-delay="60">
          <button class="px-4 py-2 rounded-xl border border-gray-300 dark:border-gray-700" data-filter="all">All</button>
          <button class="px-4 py-2 rounded-xl border border-gray-300 dark:border-gray-700" data-filter="video">Video</button>
          <button class="px-4 py-2 rounded-xl border border-gray-300 dark:border-gray-700" data-filter="writing">Writing</button>
        </div>
      </div>

      <!-- Grid -->
      <div class="mt-8 grid sm:grid-cols-2 lg:grid-cols-3 gap-6" id="portfolioGrid">
        <!-- 1 -->
        <figure class="card rounded-2xl overflow-hidden border border-gray-200 dark:border-gray-800 group" data-type="video" data-aos="fade-up">
          <div class="aspect-video bg-black">
            <iframe class="w-full h-full" loading="lazy"
              src="https://www.youtube.com/embed/X-jjNzDdpks?rel=0&modestbranding=1"
              title="YouTube video 1" frameborder="0"
              allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
          </div>
          <figcaption class="p-4">
            <h3 class="font-semibold">Shorts #1</h3>
            <p class="text-sm text-gray-600 dark:text-gray-400">Edited & produced.</p>
          </figcaption>
        </figure>

        <!-- 2 -->
        <figure class="card rounded-2xl overflow-hidden border border-gray-200 dark:border-gray-800 group" data-type="video" data-aos="fade-up" data-aos-delay="40">
          <div class="aspect-video bg-black">
            <iframe class="w-full h-full" loading="lazy"
              src="https://www.youtube.com/embed/VEcD2bbrmjA?rel=0&modestbranding=1"
              title="YouTube video 2" frameborder="0"
              allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
          </div>
          <figcaption class="p-4">
            <h3 class="font-semibold">Shorts #2</h3>
            <p class="text-sm text-gray-600 dark:text-gray-400">Vertical storytelling.</p>
          </figcaption>
        </figure>

        <!-- 3 -->
        <figure class="card rounded-2xl overflow-hidden border border-gray-200 dark:border-gray-800 group" data-type="video" data-aos="fade-up" data-aos-delay="80">
          <div class="aspect-video bg-black">
            <iframe class="w-full h-full" loading="lazy"
              src="https://www.youtube.com/embed/MbHJYHht6uc?rel=0&modestbranding=1"
              title="YouTube video 3" frameborder="0"
              allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
          </div>
          <figcaption class="p-4">
            <h3 class="font-semibold">Shorts #3</h3>
            <p class="text-sm text-gray-600 dark:text-gray-400">Pacing & hooks.</p>
          </figcaption>
        </figure>

        <!-- 4 -->
        <figure class="card rounded-2xl overflow-hidden border border-gray-200 dark:border-gray-800 group" data-type="video" data-aos="fade-up" data-aos-delay="120">
          <div class="aspect-video bg-black">
            <iframe class="w-full h-full" loading="lazy"
              src="https://www.youtube.com/embed/dTLLCWluZRI?rel=0&modestbranding=1"
              title="YouTube video 4" frameborder="0"
              allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
          </div>
          <figcaption class="p-4">
            <h3 class="font-semibold">Shorts #4</h3>
            <p class="text-sm text-gray-600 dark:text-gray-400">Transitions & rhythm.</p>
          </figcaption>
        </figure>

        <!-- 5 -->
        <figure class="card rounded-2xl overflow-hidden border border-gray-200 dark:border-gray-800 group" data-type="video" data-aos="fade-up" data-aos-delay="160">
          <div class="aspect-video bg-black">
            <iframe class="w-full h-full" loading="lazy"
              src="https://www.youtube.com/embed/44KaJO3uDcI?rel=0&modestbranding=1"
              title="YouTube video 5" frameborder="0"
              allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
          </div>
          <figcaption class="p-4">
            <h3 class="font-semibold">Shorts #5</h3>
            <p class="text-sm text-gray-600 dark:text-gray-400">Motion graphics.</p>
          </figcaption>
        </figure>

        <!-- 6 -->
        <figure class="card rounded-2xl overflow-hidden border border-gray-200 dark:border-gray-800 group" data-type="video" data-aos="fade-up" data-aos-delay="200">
          <div class="aspect-video bg-black">
            <iframe class="w-full h-full" loading="lazy"
              src="https://www.youtube.com/embed/wFCa5q_0jLE?rel=0&modestbranding=1"
              title="YouTube video 6" frameborder="0"
              allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
          </div>
          <figcaption class="p-4">
            <h3 class="font-semibold">Shorts #6</h3>
            <p class="text-sm text-gray-600 dark:text-gray-400">SFX & retention.</p>
          </figcaption>
        </figure>

        <!-- 7 -->
        <figure class="card rounded-2xl overflow-hidden border border-gray-200 dark:border-gray-800 group" data-type="video" data-aos="fade-up" data-aos-delay="240">
          <div class="aspect-video bg-black">
            <iframe class="w-full h-full" loading="lazy"
              src="https://www.youtube.com/embed/NdvI105rFfs?rel=0&modestbranding=1"
              title="YouTube video 7" frameborder="0"
              allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
          </div>
          <figcaption class="p-4">
            <h3 class="font-semibold">Shorts #7</h3>
            <p class="text-sm text-gray-600 dark:text-gray-400">Editing flow.</p>
          </figcaption>
        </figure>

        <!-- Writing sample (kept) -->
        <figure class="card rounded-2xl overflow-hidden border border-gray-200 dark:border-gray-800 group" data-type="writing" data-aos="fade-up">
          <img loading="lazy" class="w-full aspect-video object-cover" src="https://images.unsplash.com/photo-1519336555923-59661f41bb40?w=1200&q=80&auto=format&fit=crop" alt="Blog cover" />
          <figcaption class="p-4">
            <h3 class="font-semibold">Blog: How to Hook in 3 Seconds</h3>
            <p class="text-sm text-gray-600 dark:text-gray-400">A practical guide for short-form storytelling.</p>
            <a class="inline-flex items-center gap-2 mt-2 text-primary hover:underline" href="#" target="_blank" rel="noreferrer">Read Article <i class="fa-solid fa-arrow-up-right-from-square"></i></a>
          </figcaption>
        </figure>
      </div>

      <div class="mt-10 flex justify-center" data-aos="fade-up" data-aos-delay="80">
        <a href="https://www.youtube.com/" target="_blank" rel="noreferrer"
           class="px-6 py-3 rounded-xl text-white bg-gradient-to-r from-primary to-accent shadow-soft hover:shadow-softxl inline-flex items-center gap-2">
          <i class="fa-brands fa-youtube text-xl"></i> View All on YouTube
        </a>
      </div>
    </div>
  </section>

  <!-- ===== WRITING ===== -->
  <section id="writing" class="py-16 sm:py-24">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <h2 class="text-3xl font-extrabold tracking-tight" data-aos="fade-up">Featured Writing</h2>
      <div class="mt-8 grid sm:grid-cols-2 lg:grid-cols-3 gap-6">
        <article class="card rounded-2xl border border-gray-200 dark:border-gray-800 p-6" data-aos="fade-up">
          <h3 class="font-semibold">How to Plan a Viral Reel</h3>
          <p class="mt-2 text-gray-600 dark:text-gray-300">Idea → Hook → Script → Shoot → Edit. A checklist I use before every reel.</p>
          <a class="mt-3 inline-flex items-center gap-2 text-primary hover:underline" href="#">Read</a>
        </article>
        <article class="card rounded-2xl border border-gray-200 dark:border-gray-800 p-6" data-aos="fade-up" data-aos-delay="60">
          <h3 class="font-semibold">Writing for Retention</h3>
          <p class="mt-2 text-gray-600 dark:text-gray-300">Layer curiosity & value to keep viewers reading/watching.</p>
          <a class="mt-3 inline-flex items-center gap-2 text-primary hover:underline" href="#">Read</a>
        </article>
        <article class="card rounded-2xl border border-gray-200 dark:border-gray-800 p-6" data-aos="fade-up" data-aos-delay="120">
          <h3 class="font-semibold">Beginner's YouTube Script Template</h3>
          <p class="mt-2 text-gray-600 dark:text-gray-300">Free template with beats + timing.</p>
          <a class="mt-3 inline-flex items-center gap-2 text-primary hover:underline" href="#">Download</a>
        </article>
      </div>
    </div>
  </section>

  <!-- ===== RESUME ===== -->
  <section id="resume" class="py-16 sm:py-24 bg-gray-50 dark:bg-gray-900/30">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <h2 class="text-3xl font-extrabold tracking-tight" data-aos="fade-up">Resume</h2>
      <div class="mt-8 grid lg:grid-cols-2 gap-8">
        <div class="space-y-6" data-aos="fade-up">
          <h3 class="font-bold text-xl">Education</h3>
          <div class="card rounded-2xl border border-gray-200 dark:border-gray-800 p-6">
            <div class="flex items-start justify-between">
              <div>
                <p class="font-semibold">KIIT, Ghaziabad</p>
                <p class="text-sm text-gray-600 dark:text-gray-400">B.Tech -- 2nd Year (2024–2026)</p>
              </div>
              <span class="px-2.5 py-1 rounded-full text-xs bg-primary/10 text-primary">Current</span>
            </div>
            <p class="mt-3 text-sm text-gray-600 dark:text-gray-300">Core interests: media tech, human-computer interaction, and creative production.</p>
          </div>
        </div>

        <div class="space-y-6" data-aos="fade-up" data-aos-delay="60">
          <h3 class="font-bold text-xl">Experience</h3>
          <div class="card rounded-2xl border border-gray-200 dark:border-gray-800 p-6">
            <p class="font-semibold">Freelance Video & Content Projects</p>
            <p class="text-sm text-gray-600 dark:text-gray-400">2023–Present</p>
            <ul class="mt-3 text-sm list-disc list-inside text-gray-700 dark:text-gray-300">
              <li>Edited 50+ reels/shorts for local brands & college clubs</li>
              <li>Wrote scripts & blogs optimized for SEO & watch-time</li>
              <li>Managed content calendars and thumbnail design</li>
            </ul>
          </div>
        </div>
      </div>

      <div class="mt-10 grid sm:grid-cols-3 gap-6" data-aos="fade-up" data-aos-delay="120">
        <div class="rounded-2xl p-6 border border-gray-200 dark:border-gray-800 text-center">
          <p class="text-3xl font-extrabold">50+ </p>
          <p class="text-sm text-gray-600 dark:text-gray-400">Video Edits</p>
        </div>
        <div class="rounded-2xl p-6 border border-gray-200 dark:border-gray-800 text-center">
          <p class="text-3xl font-extrabold">30+ </p>
          <p class="text-sm text-gray-600 dark:text-gray-400">Scripts & Blogs</p>
        </div>
        <div class="rounded-2xl p-6 border border-gray-200 dark:border-gray-800 text-center">
          <p class="text-3xl font-extrabold">10+ </p>
          <p class="text-sm text-gray-600 dark:text-gray-400">Happy Clients</p>
        </div>
      </div>
    </div>
  </section>

  <!-- ===== PRICING ===== -->
  <section id="pricing" class="py-16 sm:py-24">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <h2 class="text-3xl font-extrabold tracking-tight" data-aos="fade-up">Pricing</h2>
      <p class="mt-2 text-gray-600 dark:text-gray-300" data-aos="fade-up" data-aos-delay="40">Transparent packages. Custom quotes available.</p>
      <div class="mt-8 grid sm:grid-cols-2 lg:grid-cols-3 gap-6">
        <div class="card rounded-2xl border border-gray-200 dark:border-gray-800 p-6" data-aos="fade-up">
          <h3 class="font-bold text-lg">Starter</h3>
          <p class="mt-2 text-3xl font-extrabold">₹999</p>
          <ul class="mt-3 text-sm list-disc list-inside text-gray-700 dark:text-gray-300">
            <li>1 Reel/Short (up to 30s)</li>
            <li>Basic edit + captions</li>
            <li>1 round of revisions</li>
          </ul>
          <a href="#contact" class="mt-4 inline-flex px-4 py-2 rounded-xl text-white bg-gradient-to-r from-primary to-accent">Choose</a>
        </div>
        <div class="card rounded-2xl border-2 border-primary p-6" data-aos="fade-up" data-aos-delay="60">
          <h3 class="font-bold text-lg">Creator</h3>
          <p class="mt-2 text-3xl font-extrabold">₹2,999</p>
          <ul class="mt-3 text-sm list-disc list-inside text-gray-700 dark:text-gray-300">
            <li>4 Reels/Shorts / month</li>
            <li>Kinetic text + color grade</li>
            <li>2 rounds of revisions</li>
          </ul>
          <a href="#contact" class="mt-4 inline-flex px-4 py-2 rounded-xl text-white bg-gradient-to-r from-primary to-accent">Choose</a>
        </div>
        <div class="card rounded-2xl border border-gray-200 dark:border-gray-800 p-6" data-aos="fade-up" data-aos-delay="120">
          <h3 class="font-bold text-lg">Pro</h3>
          <p class="mt-2 text-3xl font-extrabold">₹6,999</p>
          <ul class="mt-3 text-sm list-disc list-inside text-gray-700 dark:text-gray-300">
            <li>8 Reels + 1 YouTube video</li>
            <li>Scriptwriting & thumbnail</li>
            <li>Priority delivery</li>
          </ul>
          <a href="#contact" class="mt-4 inline-flex px-4 py-2 rounded-xl text-white bg-gradient-to-r from-primary to-accent">Choose</a>
        </div>
      </div>
    </div>
  </section>

  <!-- ===== FAQ ===== -->
  <section id="faq" class="py-16 sm:py-24 bg-gray-50 dark:bg-gray-900/30">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <h2 class="text-3xl font-extrabold tracking-tight" data-aos="fade-up">FAQ</h2>
      <div class="mt-6 grid gap-4">
        <details class="rounded-2xl border border-gray-200 dark:border-gray-800 p-4" data-aos="fade-up">
          <summary class="font-semibold cursor-pointer">How do we start a project?</summary>
          <p class="mt-2 text-gray-600 dark:text-gray-300">Fill the contact form with your goals. I'll reply with a concept, timeline and quote.</p>
        </details>
        <details class="rounded-2xl border border-gray-200 dark:border-gray-800 p-4" data-aos="fade-up" data-aos-delay="60">
          <summary class="font-semibold cursor-pointer">Do you shoot or only edit?</summary>
          <p class="mt-2 text-gray-600 dark:text-gray-300">Both. For local shoots in NCR, I can film. For remote, send footage and a brief.</p>
        </details>
        <details class="rounded-2xl border border-gray-200 dark:border-gray-800 p-4" data-aos="fade-up" data-aos-delay="120">
          <summary class="font-semibold cursor-pointer">What about revisions?</summary>
          <p class="mt-2 text-gray-600 dark:text-gray-300">Each package includes revisions. I aim for satisfaction while respecting scope.</p>
        </details>
      </div>
    </div>
  </section>

  <!-- ===== CONTACT ===== -->
  <section id="contact" class="py-16 sm:py-24">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <div class="grid lg:grid-cols-2 gap-10 items-start">
        <div data-aos="fade-up">
          <h2 class="text-3xl font-extrabold tracking-tight">Let's Work Together</h2>
          <p class="mt-2 text-gray-600 dark:text-gray-300">Tell me about your project. I'll reply with ideas and a quick estimate.</p>
          <div class="mt-6 space-y-4">
            <p><i class="fa-solid fa-envelope text-primary mr-2"></i> <a class="underline" href="mailto:alokd@example.com">alokd@example.com</a></p>
            <p><i class="fa-brands fa-whatsapp text-primary mr-2"></i> <a class="underline" href="https://wa.me/919999999999" target="_blank" rel="noreferrer">+91 99999 99999</a></p>
            <p><i class="fa-solid fa-location-dot text-primary mr-2"></i> Ghaziabad, NCR</p>
          </div>
        </div>

        <form id="contactForm" class="bg-white dark:bg-gray-900 rounded-2xl p-6 border border-gray-200 dark:border-gray-800" data-aos="fade-up" data-aos-delay="60">
          <div class="grid sm:grid-cols-2 gap-4">
            <div>
              <label class="text-sm font-medium" for="name">Name</label>
              <input class="mt-1 w-full rounded-xl border border-gray-300 dark:border-gray-700 bg-transparent px-3 py-2" id="name" name="name" placeholder="Your name" required />
            </div>
            <div>
              <label class="text-sm font-medium" for="email">Email</label>
              <input type="email" class="mt-1 w-full rounded-xl border border-gray-300 dark:border-gray-700 bg-transparent px-3 py-2" id="email" name="email" placeholder="you@example.com" required />
            </div>
            <div class="sm:col-span-2">
              <label class="text-sm font-medium" for="service">Service</label>
              <select class="mt-1 w-full rounded-xl border border-gray-300 dark:border-gray-700 bg-transparent px-3 py-2" id="service" name="service">
                <option>Video Production</option>
                <option>Content Writing</option>
                <option>Social Media Kit</option>
                <option>Custom</option>
              </select>
            </div>
            <div class="sm:col-span-2">
              <label class="text-sm font-medium" for="message">Message</label>
              <textarea class="mt-1 w-full rounded-xl border border-gray-300 dark:border-gray-700 bg-transparent px-3 py-2" id="message" name="message" rows="4" placeholder="Briefly describe your project" required></textarea>
            </div>
          </div>
          <button type="submit" class="mt-4 w-full px-4 py-3 rounded-xl text-white bg-gradient-to-r from-primary to-accent shadow-soft hover:shadow-softxl">Send Message</button>
          <p id="formMsg" class="mt-3 text-sm"></p>
        </form>
      </div>
    </div>
  </section>

  <!-- ===== FOOTER ===== -->
  <footer class="py-10 border-t border-gray-200 dark:border-gray-800">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 flex flex-col sm:flex-row items-center justify-between gap-4">
      <p class="text-sm text-gray-600 dark:text-gray-400">© <span id="year"></span> Alok Dubey. All rights reserved.</p>
      <div class="flex items-center gap-4 text-lg">
        <a class="hover:text-primary" href="#about">About</a>
        <a class="hover:text-primary" href="#services">Services</a>
        <a class="hover:text-primary" href="#portfolio">Portfolio</a>
        <a class="hover:text-primary" href="#contact">Contact</a>
      </div>
    </div>
  </footer>

  <!-- ===== SCRIPTS ===== -->
  <script src="https://unpkg.com/aos@2.3.4/dist/aos.js"></script>
  <script>
    // AOS init
    AOS.init({ once: true, duration: 600, easing: 'ease-out-cubic' });

    // Theme toggle + persist
    const themeToggle = document.getElementById('themeToggle');
    const root = document.documentElement;
    const storedTheme = localStorage.getItem('theme');
    if (storedTheme === 'dark' || (!storedTheme && window.matchMedia('(prefers-color-scheme: dark)').matches)) {
      root.classList.add('dark');
    }
    themeToggle?.addEventListener('click', () => {
      root.classList.toggle('dark');
      localStorage.setItem('theme', root.classList.contains('dark') ? 'dark' : 'light');
    });

    // Mobile menu
    const menuBtn = document.getElementById('menuBtn');
    const mobileMenu = document.getElementById('mobileMenu');
    menuBtn?.addEventListener('click', () => mobileMenu.classList.toggle('hidden'));

    // Portfolio filter
    const filterButtons = document.querySelectorAll('[data-filter]');
    const items = document.querySelectorAll('#portfolioGrid [data-type]');
    filterButtons.forEach(btn => btn.addEventListener('click', () => {
      const type = btn.getAttribute('data-filter');
      items.forEach(card => {
        card.style.display = (type === 'all' || card.getAttribute('data-type') === type) ? '' : 'none';
      });
    }));

    // Simple modal handler (if you add modals later)
    document.querySelectorAll('[id$="Modal"]').forEach(modal => {
      modal.addEventListener('click', (e) => { if (e.target === modal) { modal.classList.add('hidden'); modal.classList.remove('flex'); } });
    });

    // Contact form (mailto fallback)
    const form = document.getElementById('contactForm');
    const formMsg = document.getElementById('formMsg');
    form?.addEventListener('submit', (e) => {
      e.preventDefault();
      const data = Object.fromEntries(new FormData(form).entries());
      if (!data.name || !data.email || !data.message) {
        formMsg.textContent = 'Please fill all required fields.';
        formMsg.className = 'mt-3 text-sm text-red-600';
        return;
      }
      const subject = encodeURIComponent(`[Portfolio] ${data.service} inquiry from ${data.name}`);
      const body = encodeURIComponent(`${data.message}\n\n-- ${data.name}\n${data.email}`);
      window.location.href = `mailto:alokd@example.com?subject=${subject}&body=${body}`;
      formMsg.textContent = 'Opening your email app… If nothing happens, email me at alokd@example.com';
      formMsg.className = 'mt-3 text-sm text-green-600';
      form.reset();
    });

    // Footer year
    document.getElementById('year').textContent = new Date().getFullYear();
  </script>
</body>
</html>
