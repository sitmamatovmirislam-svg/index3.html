<!DOCTYPE html>

<html class="dark" lang="ru"><head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<title>ИИ-Город 2050 | Исследования Будущего</title>
<script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&amp;family=Space+Grotesk:wght@300;400;500;600;700&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<script id="tailwind-config">
      tailwind.config = {
        darkMode: "class",
        theme: {
          extend: {
            "colors": {
                    "on-secondary": "#290067",
                    "on-error": "#490006",
                    "error-dim": "#d7383b",
                    "on-tertiary-container": "#ffffff",
                    "surface-container": "#19191f",
                    "secondary": "#ac89ff",
                    "tertiary-container": "#aa19f9",
                    "on-primary": "#005d63",
                    "surface": "#0e0e13",
                    "tertiary-fixed-dim": "#cf82ff",
                    "tertiary-fixed": "#d896ff",
                    "outline-variant": "#48474d",
                    "surface-container-high": "#1f1f26",
                    "on-primary-container": "#005359",
                    "background": "#0e0e13",
                    "surface-container-low": "#131319",
                    "surface-container-highest": "#25252d",
                    "inverse-surface": "#fcf8ff",
                    "on-tertiary-fixed-variant": "#5c008b",
                    "on-error-container": "#ffa8a3",
                    "error": "#ff716c",
                    "secondary-fixed": "#dac9ff",
                    "secondary-fixed-dim": "#ceb9ff",
                    "primary-container": "#00eefc",
                    "inverse-on-surface": "#55545b",
                    "on-secondary-fixed-variant": "#6300e2",
                    "on-secondary-container": "#f8f1ff",
                    "surface-container-lowest": "#000000",
                    "on-secondary-fixed": "#41009a",
                    "surface-dim": "#0e0e13",
                    "secondary-container": "#7000ff",
                    "on-tertiary-fixed": "#2a0043",
                    "surface-tint": "#8ff5ff",
                    "on-primary-fixed-variant": "#005e64",
                    "on-background": "#f9f5fd",
                    "on-surface": "#f9f5fd",
                    "error-container": "#9f0519",
                    "on-tertiary": "#360055",
                    "secondary-dim": "#874cff",
                    "primary-fixed": "#00eefc",
                    "tertiary-dim": "#af25fe",
                    "outline": "#76747b",
                    "on-primary-fixed": "#003f43",
                    "tertiary": "#cc7aff",
                    "inverse-primary": "#006a71",
                    "on-surface-variant": "#acaab1",
                    "primary-dim": "#00deec",
                    "surface-variant": "#25252d",
                    "primary-fixed-dim": "#00deec",
                    "surface-bright": "#2c2b33",
                    "primary": "#8ff5ff"
            },
            "borderRadius": {
                    "DEFAULT": "0.25rem",
                    "lg": "0.5rem",
                    "xl": "0.75rem",
                    "full": "9999px"
            },
            "fontFamily": {
                    "headline": ["Space Grotesk"],
                    "body": ["Inter"],
                    "label": ["Inter"]
            }
          },
        },
      }
    </script>
<style>
        .material-symbols-outlined {
            font-variation-settings: 'FILL' 0, 'wght' 400, 'GRAD' 0, 'opsz' 24;
        }
        body {
            background-color: #0e0e13;
            color: #f9f5fd;
            font-family: 'Inter', sans-serif;
        }
        .glass-panel {
            background: rgba(25, 25, 31, 0.6);
            backdrop-filter: blur(12px);
            border: 1px solid rgba(143, 245, 255, 0.1);
        }
        .shimmer {
            background: linear-gradient(90deg, transparent, rgba(143, 245, 255, 0.05), transparent);
            background-size: 200% 100%;
        }
    </style>
<style>
    body {
      min-height: max(884px, 100dvh);
    }
  </style>
  </head>
<body class="selection:bg-primary/30">
<!-- TopAppBar -->
<header class="bg-[#0e0e13]/80 backdrop-blur-xl text-[#8ff5ff] font-['Space_Grotesk'] tracking-tight fixed top-0 w-full z-50 border-b border-[#8ff5ff]/10 shadow-[0_0_20px_rgba(143,245,255,0.05)]">
<div class="flex items-center justify-between px-6 h-16 w-full max-w-none">
<div class="flex items-center gap-3 active:scale-95 transition-transform cursor-pointer">
<span class="material-symbols-outlined text-2xl">explore</span>
<span class="text-xl font-bold bg-gradient-to-r from-[#8ff5ff] to-[#ac89ff] bg-clip-text text-transparent">Исследования Будущего</span>
</div>
<div class="hidden md:flex items-center gap-8 font-medium">
<a class="text-[#8ff5ff] transition-colors duration-300" href="#">Портал</a>
<a class="text-[#f9f5fd]/60 hover:text-[#8ff5ff] transition-colors duration-300" href="#">Темы</a>
<a class="text-[#f9f5fd]/60 hover:text-[#8ff5ff] transition-colors duration-300" href="#">Избранное</a>
</div>
<div class="flex items-center gap-4">
<button class="material-symbols-outlined text-[#f9f5fd]/60 hover:text-[#8ff5ff] transition-colors">notifications</button>
<div class="w-10 h-10 rounded-full border border-primary/20 p-0.5">
<img class="w-full h-full rounded-full object-cover" data-alt="Modern minimalist portrait of a digital analyst in cool blue neon lighting, high-tech aesthetic" src="https://lh3.googleusercontent.com/aida-public/AB6AXuCnH7m4wWy0jBvcwT0cDd0y7kYdScQQ_tbVljc5vx32Co3Zb6Y-tVyw8gUFG3QFu7eYbDABhzwqIsXV2XGRl1ApzDNBM5RJKWW99eIEbQc73LvhdxnovAk6kBz_c4UxMMW2reGTeQrO88vxQhnOBkpGHnKsXfuuK7xABsfvSLfP67ROSDNbDT-Z0Rdoq_4Dki5MXRn0FCRaETjPvNO6mabUN8mGFQYM-At8siXdRjznJBytDaU19UG0XTE3trfZedZWwfgxOxCTyc0"/>
</div>
</div>
</div>
</header>
<!-- NavigationDrawer (Desktop) -->
<aside class="hidden lg:flex flex-col bg-[#0e0e13] text-[#8ff5ff] font-['Inter'] text-sm uppercase tracking-widest rounded-r-lg border-r border-[#8ff5ff]/10 fixed left-0 top-0 h-full w-72 z-[60] py-8">
<div class="px-8 mb-12">
<h2 class="text-[#8ff5ff] font-['Space_Grotesk'] text-lg font-bold tracking-normal capitalize">Навигатор Будущего</h2>
</div>
<nav class="flex-1 space-y-1">
<!-- Active Item -->
<a class="flex items-center gap-4 px-8 py-4 bg-gradient-to-r from-[#8ff5ff]/10 to-transparent border-l-2 border-[#8ff5ff] text-[#8ff5ff] font-bold duration-200 ease-in-out" href="#">
<span class="material-symbols-outlined">apartment</span>
<span>ИИ-Города</span>
</a>
<a class="flex items-center gap-4 px-8 py-4 text-[#f9f5fd]/40 hover:bg-[#8ff5ff]/5 hover:text-[#8ff5ff] duration-200 ease-in-out" href="#">
<span class="material-symbols-outlined">memory</span>
<span>Цифровые Двойники</span>
</a>
<a class="flex items-center gap-4 px-8 py-4 text-[#f9f5fd]/40 hover:bg-[#8ff5ff]/5 hover:text-[#8ff5ff] duration-200 ease-in-out" href="#">
<span class="material-symbols-outlined">school</span>
<span>Школы Будущего</span>
</a>
<a class="flex items-center gap-4 px-8 py-4 text-[#f9f5fd]/40 hover:bg-[#8ff5ff]/5 hover:text-[#8ff5ff] duration-200 ease-in-out" href="#">
<span class="material-symbols-outlined">share_reviews</span>
<span>Спец. Соцсети</span>
</a>
<a class="flex items-center gap-4 px-8 py-4 text-[#f9f5fd]/40 hover:bg-[#8ff5ff]/5 hover:text-[#8ff5ff] duration-200 ease-in-out" href="#">
<span class="material-symbols-outlined">location_city</span>
<span>Города 2050</span>
</a>
<a class="flex items-center gap-4 px-8 py-4 text-[#f9f5fd]/40 hover:bg-[#8ff5ff]/5 hover:text-[#8ff5ff] duration-200 ease-in-out" href="#">
<span class="material-symbols-outlined">public</span>
<span>Мировое През.</span>
</a>
</nav>
<div class="px-8 pt-8 border-t border-[#8ff5ff]/5">
<div class="bg-surface-container-low p-4 rounded-lg flex items-center gap-3">
<div class="w-2 h-2 rounded-full bg-primary animate-pulse"></div>
<span class="text-[10px] text-on-surface-variant tracking-wider">СИСТЕМА: ONLINE</span>
</div>
</div>
</aside>
<!-- Main Content Canvas -->
<main class="pt-24 pb-32 lg:pl-80 px-6 max-w-7xl mx-auto min-h-screen">
<!-- Hero Section: City Status -->
<section class="mb-12">
<div class="flex flex-col md:flex-row md:items-end justify-between gap-6 mb-8">
<div>
<div class="flex items-center gap-2 text-primary mb-2">
<span class="material-symbols-outlined text-sm">settings_input_antenna</span>
<span class="text-xs font-label uppercase tracking-[0.2em]">Live Data Stream</span>
</div>
<h1 class="text-5xl md:text-6xl font-headline font-bold text-on-surface leading-tight">ИИ-Город 2050</h1>
<p class="text-on-surface-variant mt-2 max-w-xl text-lg">Единый центр управления мета-полисом. Синхронизация жизненных систем в реальном времени.</p>
</div>
<div class="flex gap-4">
<button class="bg-primary text-on-primary px-6 py-3 rounded-lg font-bold flex items-center gap-2 hover:shadow-[0_0_15px_rgba(143,245,255,0.4)] transition-all">
<span class="material-symbols-outlined">rocket_launch</span>
                        Оптимизировать
                    </button>
<button class="glass-panel text-primary px-6 py-3 rounded-lg font-bold hover:bg-primary/10 transition-all">
                        Отчеты
                    </button>
</div>
</div>
<!-- Bento Grid Dashboard -->
<div class="grid grid-cols-1 md:grid-cols-4 lg:grid-cols-12 gap-6">
<!-- Traffic Monitor (Large) -->
<div class="md:col-span-4 lg:col-span-8 glass-panel p-6 rounded-xl relative overflow-hidden group">
<div class="absolute top-0 left-0 w-full h-1 bg-gradient-to-r from-primary to-secondary"></div>
<div class="flex justify-between items-start mb-6">
<div>
<h3 class="text-xl font-headline font-bold text-on-surface">Транспортная Сеть</h3>
<p class="text-xs text-on-surface-variant">Автономные потоки: 98.4% эффективность</p>
</div>
<span class="material-symbols-outlined text-primary text-3xl">directions_transit</span>
</div>
<div class="h-64 w-full relative rounded-lg overflow-hidden border border-outline-variant/30">
<img class="w-full h-full object-cover opacity-60" data-alt="Futuristic neon city map with glowing blue and purple light trails representing autonomous traffic flow and data connections" src="https://lh3.googleusercontent.com/aida-public/AB6AXuCHFePmhJ1n3aGWoq1T4tPOkxctkYfDaDBlk9cIhgu56LCFL2DioRPXV55qKMFKOFjG8bZoaaeiBVG1qsB1XTbth5fD6DQOV6byf2cryUU_aHH_XFfRLvfZ9LVFrRnvFf_idwrtJpH_Ui-elTxfwWtW_eBeE436SYWJJ0SDuGnomME2-TBHLogDKkREEudbVhV5R4vWxOWDRIbfeNmQPDPpxpHXjPTjymz-n6D3ctJYd6ZK8v08GKVgTqywnPo69ZidObTyeMBttus"/>
<div class="absolute inset-0 bg-gradient-to-t from-background via-transparent to-transparent"></div>
<!-- UI Overlays for "Interactive" look -->
<div class="absolute top-4 right-4 flex flex-col gap-2">
<div class="bg-black/60 backdrop-blur-md px-3 py-1.5 rounded border border-primary/20 text-[10px]">СЕКТОР A-12: <span class="text-primary">НОРМА</span></div>
<div class="bg-black/60 backdrop-blur-md px-3 py-1.5 rounded border border-error/20 text-[10px]">СЕКТОР B-04: <span class="text-error">ЗАГРУЗКА 15%</span></div>
</div>
</div>
</div>
<!-- Climate Control (Small) -->
<div class="md:col-span-2 lg:col-span-4 glass-panel p-6 rounded-xl flex flex-col justify-between">
<div>
<div class="flex items-center justify-between mb-4">
<span class="material-symbols-outlined text-secondary">cloud_done</span>
<span class="text-[10px] font-bold text-secondary bg-secondary/10 px-2 py-0.5 rounded">ECO-MODE</span>
</div>
<h3 class="text-lg font-headline font-bold text-on-surface mb-1">Климат</h3>
<p class="text-sm text-on-surface-variant">CO2: 280 ppm (Оптим.)</p>
</div>
<div class="mt-8">
<div class="text-4xl font-headline text-primary mb-2">22.4°C</div>
<div class="w-full h-2 bg-surface-container-highest rounded-full overflow-hidden">
<div class="h-full bg-gradient-to-r from-primary to-secondary w-[72%]"></div>
</div>
<div class="flex justify-between mt-2 text-[10px] text-on-surface-variant">
<span>ВЛАЖНОСТЬ: 45%</span>
<span>AQI: 12</span>
</div>
</div>
</div>
<!-- Citizen Wellbeing (Medium) -->
<div class="md:col-span-2 lg:col-span-4 glass-panel p-6 rounded-xl border-l-4 border-tertiary">
<h3 class="text-lg font-headline font-bold mb-4">Благополучие</h3>
<div class="space-y-4">
<div class="flex items-center justify-between">
<span class="text-sm text-on-surface-variant">Индекс счастья</span>
<span class="text-tertiary font-bold">8.9/10</span>
</div>
<div class="flex items-center justify-between">
<span class="text-sm text-on-surface-variant">Доступность сервисов</span>
<span class="text-tertiary font-bold">100%</span>
</div>
<div class="flex items-center justify-between">
<span class="text-sm text-on-surface-variant">Уровень шума</span>
<span class="text-tertiary font-bold">32 dB</span>
</div>
</div>
<div class="mt-6 p-3 bg-tertiary/5 rounded border border-tertiary/10">
<p class="text-[11px] leading-relaxed text-on-surface-variant">ИИ рекомендует увеличить площадь озеленения в южном секторе для повышения социального комфорта.</p>
</div>
</div>
<!-- Resource Monitoring (Medium) -->
<div class="md:col-span-2 lg:col-span-4 glass-panel p-6 rounded-xl">
<h3 class="text-lg font-headline font-bold mb-6">Ресурсы</h3>
<div class="grid grid-cols-2 gap-4">
<div class="text-center">
<div class="text-primary text-xl font-bold">92%</div>
<div class="text-[10px] text-on-surface-variant uppercase">Энергия (Fusion)</div>
</div>
<div class="text-center">
<div class="text-secondary text-xl font-bold">88%</div>
<div class="text-[10px] text-on-surface-variant uppercase">Вода (Recycle)</div>
</div>
<div class="text-center">
<div class="text-tertiary text-xl font-bold">96%</div>
<div class="text-[10px] text-on-surface-variant uppercase">Переработка</div>
</div>
<div class="text-center">
<div class="text-primary-container text-xl font-bold">1.2ms</div>
<div class="text-[10px] text-on-surface-variant uppercase">Задержка сети</div>
</div>
</div>
</div>
<!-- AI Decision Log (Medium) -->
<div class="md:col-span-2 lg:col-span-4 glass-panel p-6 rounded-xl overflow-hidden relative">
<div class="shimmer absolute inset-0 pointer-events-none opacity-20"></div>
<h3 class="text-lg font-headline font-bold mb-4 flex items-center gap-2">
<span class="material-symbols-outlined text-primary">auto_awesome</span>
                        Лог решений ИИ
                    </h3>
<div class="space-y-3 font-mono text-[10px]">
<div class="flex gap-2 border-b border-outline-variant/10 pb-2">
<span class="text-primary">[12:45]</span>
<span class="text-on-surface-variant">Оптимизация освещения в парке "Заря-2" завершена.</span>
</div>
<div class="flex gap-2 border-b border-outline-variant/10 pb-2">
<span class="text-primary">[12:42]</span>
<span class="text-on-surface-variant">Перераспределение 500 МВт на медицинский кластер.</span>
</div>
<div class="flex gap-2 border-b border-outline-variant/10 pb-2">
<span class="text-secondary">[12:38]</span>
<span class="text-on-surface-variant">Запуск дронов-садовников в секторе О-5.</span>
</div>
<div class="flex gap-2">
<span class="text-primary">[12:30]</span>
<span class="text-on-surface-variant">Обновление протоколов безопасности ИИ.</span>
</div>
</div>
</div>
</div>
</section>
<!-- Dynamic Insights Section -->
<section class="grid grid-cols-1 md:grid-cols-2 gap-8 mb-12">
<div class="space-y-6">
<h2 class="text-3xl font-headline font-bold text-on-surface">Стратегические цели</h2>
<div class="space-y-4">
<div class="p-5 surface-container-highest rounded-lg flex items-center gap-4 border-l-2 border-primary">
<div class="w-12 h-12 bg-primary/10 rounded flex items-center justify-center">
<span class="material-symbols-outlined text-primary">eco</span>
</div>
<div class="flex-1">
<div class="flex justify-between mb-1">
<span class="text-sm font-bold">Нулевой выброс углерода</span>
<span class="text-sm text-primary">94%</span>
</div>
<div class="w-full h-1 bg-background rounded-full">
<div class="h-full bg-primary w-[94%]"></div>
</div>
</div>
</div>
<div class="p-5 surface-container-highest rounded-lg flex items-center gap-4 border-l-2 border-secondary">
<div class="w-12 h-12 bg-secondary/10 rounded flex items-center justify-center">
<span class="material-symbols-outlined text-secondary">groups</span>
</div>
<div class="flex-1">
<div class="flex justify-between mb-1">
<span class="text-sm font-bold">Инклюзивность среды</span>
<span class="text-sm text-secondary">87%</span>
</div>
<div class="w-full h-1 bg-background rounded-full">
<div class="h-full bg-secondary w-[87%]"></div>
</div>
</div>
</div>
</div>
</div>
<div class="glass-panel p-8 rounded-2xl flex items-center gap-8 border-none bg-gradient-to-br from-primary-container/20 to-transparent">
<div class="flex-1">
<h3 class="text-2xl font-headline font-bold mb-3 text-primary">ИИ-Прогноз 24ч</h3>
<p class="text-on-surface-variant text-sm leading-relaxed">
                        Ожидается повышение солнечной активности на 15%. Система автоматически переключает накопители в режим "Max-Capture". Рекомендуется снижение нагрузки на стационарные охладители.
                    </p>
<button class="mt-6 text-primary text-xs font-bold flex items-center gap-1 group">
                        ПОЛНЫЙ АНАЛИЗ
                        <span class="material-symbols-outlined text-sm group-hover:translate-x-1 transition-transform">arrow_forward</span>
</button>
</div>
<div class="hidden sm:block w-32 h-32 relative">
<div class="absolute inset-0 bg-primary/20 rounded-full blur-2xl animate-pulse"></div>
<span class="material-symbols-outlined text-primary text-8xl relative z-10" style="font-variation-settings: 'FILL' 1;">bubble_chart</span>
</div>
</div>
</section>
</main>
<!-- BottomNavBar (Mobile) -->
<nav class="md:hidden fixed bottom-0 left-0 w-full h-20 bg-[#0e0e13]/90 backdrop-blur-lg flex justify-around items-center px-4 pb-safe z-50 rounded-t-xl border-t border-[#8ff5ff]/10 shadow-[0_-4px_24px_rgba(0,240,255,0.1)]">
<a class="flex flex-col items-center justify-center bg-[#8ff5ff]/10 text-[#8ff5ff] rounded-xl px-4 py-1 active:scale-90 transition-all duration-300" href="#">
<span class="material-symbols-outlined" style="font-variation-settings: 'FILL' 1;">hub</span>
<span class="font-['Inter'] text-[10px] font-medium mt-1">Портал</span>
</a>
<a class="flex flex-col items-center justify-center text-[#f9f5fd]/50 hover:text-[#ac89ff] active:scale-90 transition-all duration-300" href="#">
<span class="material-symbols-outlined">grid_view</span>
<span class="font-['Inter'] text-[10px] font-medium mt-1">Темы</span>
</a>
<a class="flex flex-col items-center justify-center text-[#f9f5fd]/50 hover:text-[#ac89ff] active:scale-90 transition-all duration-300" href="#">
<span class="material-symbols-outlined">auto_awesome</span>
<span class="font-['Inter'] text-[10px] font-medium mt-1">Избранное</span>
</a>
<a class="flex flex-col items-center justify-center text-[#f9f5fd]/50 hover:text-[#ac89ff] active:scale-90 transition-all duration-300" href="#">
<span class="material-symbols-outlined">account_circle</span>
<span class="font-['Inter'] text-[10px] font-medium mt-1">Профиль</span>
</a>
</nav>
<!-- Contextual FAB (Only for specific primary action) -->
<button class="fixed right-6 bottom-24 md:bottom-10 bg-primary text-on-primary w-14 h-14 rounded-full shadow-2xl flex items-center justify-center hover:scale-110 active:scale-95 transition-all z-[70] shadow-primary/30">
<span class="material-symbols-outlined text-3xl">add_chart</span>
</button>
</body></html>
<!DOCTYPE html>

<html class="dark" lang="ru"><head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<title>Исследования Будущего | Портал Сингулярности</title>
<script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&amp;family=Space+Grotesk:wght@300;500;700&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<script id="tailwind-config">
      tailwind.config = {
        darkMode: "class",
        theme: {
          extend: {
            "colors": {
                    "on-secondary": "#290067",
                    "on-error": "#490006",
                    "error-dim": "#d7383b",
                    "on-tertiary-container": "#ffffff",
                    "surface-container": "#19191f",
                    "secondary": "#ac89ff",
                    "tertiary-container": "#aa19f9",
                    "on-primary": "#005d63",
                    "surface": "#0e0e13",
                    "tertiary-fixed-dim": "#cf82ff",
                    "tertiary-fixed": "#d896ff",
                    "outline-variant": "#48474d",
                    "surface-container-high": "#1f1f26",
                    "on-primary-container": "#005359",
                    "background": "#0e0e13",
                    "surface-container-low": "#131319",
                    "surface-container-highest": "#25252d",
                    "inverse-surface": "#fcf8ff",
                    "on-tertiary-fixed-variant": "#5c008b",
                    "on-error-container": "#ffa8a3",
                    "error": "#ff716c",
                    "secondary-fixed": "#dac9ff",
                    "secondary-fixed-dim": "#ceb9ff",
                    "primary-container": "#00eefc",
                    "inverse-on-surface": "#55545b",
                    "on-secondary-fixed-variant": "#6300e2",
                    "on-secondary-container": "#f8f1ff",
                    "surface-container-lowest": "#000000",
                    "on-secondary-fixed": "#41009a",
                    "surface-dim": "#0e0e13",
                    "secondary-container": "#7000ff",
                    "on-tertiary-fixed": "#2a0043",
                    "surface-tint": "#8ff5ff",
                    "on-primary-fixed-variant": "#005e64",
                    "on-background": "#f9f5fd",
                    "on-surface": "#f9f5fd",
                    "error-container": "#9f0519",
                    "on-tertiary": "#360055",
                    "secondary-dim": "#874cff",
                    "primary-fixed": "#00eefc",
                    "tertiary-dim": "#af25fe",
                    "outline": "#76747b",
                    "on-primary-fixed": "#003f43",
                    "tertiary": "#cc7aff",
                    "inverse-primary": "#006a71",
                    "on-surface-variant": "#acaab1",
                    "primary-dim": "#00deec",
                    "surface-variant": "#25252d",
                    "primary-fixed-dim": "#00deec",
                    "surface-bright": "#2c2b33",
                    "primary": "#8ff5ff"
            },
            "borderRadius": {
                    "DEFAULT": "0.125rem",
                    "lg": "0.25rem",
                    "xl": "0.5rem",
                    "full": "0.75rem"
            },
            "fontFamily": {
                    "headline": ["Space Grotesk"],
                    "body": ["Inter"],
                    "label": ["Inter"]
            }
          },
        },
      }
    </script>
<style>
        .material-symbols-outlined {
            font-variation-settings: 'FILL' 0, 'wght' 400, 'GRAD' 0, 'opsz' 24;
        }
        .glass-card {
            background: rgba(37, 37, 45, 0.4);
            backdrop-filter: blur(12px);
            border: 1px solid rgba(143, 245, 255, 0.1);
        }
        .text-gradient {
            background: linear-gradient(to right, #8ff5ff, #ac89ff);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
        body {
            background-color: #0e0e13;
            color: #f9f5fd;
            overflow-x: hidden;
        }
    </style>
<style>
    body {
      min-height: max(884px, 100dvh);
    }
  </style>
  </head>
<body class="font-body selection:bg-primary/30">
<!-- TopAppBar -->
<header class="fixed top-0 w-full z-50 bg-[#0e0e13]/80 backdrop-blur-xl border-b border-[#8ff5ff]/10 shadow-[0_0_20px_rgba(143,245,255,0.05)]">
<div class="flex items-center justify-between px-6 h-16 w-full max-w-none">
<div class="flex items-center gap-4">
<span class="material-symbols-outlined text-[#8ff5ff] active:scale-95 transition-transform cursor-pointer" data-icon="explore">explore</span>
<h1 class="text-xl font-bold bg-gradient-to-r from-[#8ff5ff] to-[#ac89ff] bg-clip-text text-transparent font-['Space_Grotesk'] tracking-tight">Исследования Будущего</h1>
</div>
<nav class="hidden md:flex gap-8">
<a class="text-[#8ff5ff] font-medium transition-colors duration-300" href="#">Портал</a>
<a class="text-[#f9f5fd]/60 hover:text-[#8ff5ff] transition-colors duration-300" href="#">Темы</a>
<a class="text-[#f9f5fd]/60 hover:text-[#8ff5ff] transition-colors duration-300" href="#">Избранное</a>
</nav>
<div class="w-10 h-10 rounded-full border border-[#8ff5ff]/20 bg-surface-container overflow-hidden flex items-center justify-center cursor-pointer active:scale-95 transition-transform">
<img class="w-full h-full object-cover" data-alt="close-up portrait of a digital human avatar with subtle glowing cybernetic markings on skin and bioluminescent eyes" src="https://lh3.googleusercontent.com/aida-public/AB6AXuAXSybGoWycSQ4y-X9VdsnUmt2ZMU0vHEIudGETrlAYYwhJwOKkrravHtN6kUo7MZMfCjz2_cjJ7Cj_9CFkXDHIkjsbWcSHsd2f73bFPSxNDGF6OMgITZoV1CDeDTN7S28G-k1Hl__nETP23RzXJb23EdZSxfzlbi6ED9i_Lb19PI6EmvgNVvmKHVjqpLCwU6JLmKQstAiRoHnU0yOwUy807Hlvi5GQtwoxudGkQu4XIeyLAiQ6ixlZDah4Owp7S7c8Wi0XD4KFO8g"/>
</div>
</div>
</header>
<!-- NavigationDrawer (Sidebar) -->
<aside class="fixed left-0 top-0 h-full w-72 z-[60] py-8 bg-[#0e0e13] rounded-r-lg border-r border-[#8ff5ff]/10 shadow-2xl shadow-cyan-900/20 hidden lg:block transform -translate-x-full lg:translate-x-0 transition-transform duration-300">
<div class="px-6 mb-10">
<span class="text-[#8ff5ff] font-['Space_Grotesk'] text-sm uppercase tracking-widest font-bold">Навигатор Будущего</span>
</div>
<nav class="flex flex-col gap-1">
<a class="flex items-center gap-4 px-6 py-3 bg-gradient-to-r from-[#8ff5ff]/10 to-transparent border-l-2 border-[#8ff5ff] text-[#8ff5ff] font-bold duration-200 ease-in-out" href="#">
<span class="material-symbols-outlined" data-icon="apartment">apartment</span>
<span class="font-['Inter'] text-sm uppercase tracking-widest">ИИ-Города</span>
</a>
<a class="flex items-center gap-4 px-6 py-3 text-[#f9f5fd]/40 hover:bg-[#8ff5ff]/5 hover:text-[#8ff5ff] duration-200 ease-in-out" href="#">
<span class="material-symbols-outlined" data-icon="memory">memory</span>
<span class="font-['Inter'] text-sm uppercase tracking-widest">Цифровые Двойники</span>
</a>
<a class="flex items-center gap-4 px-6 py-3 text-[#f9f5fd]/40 hover:bg-[#8ff5ff]/5 hover:text-[#8ff5ff] duration-200 ease-in-out" href="#">
<span class="material-symbols-outlined" data-icon="school">school</span>
<span class="font-['Inter'] text-sm uppercase tracking-widest">Школы Будущего</span>
</a>
<a class="flex items-center gap-4 px-6 py-3 text-[#f9f5fd]/40 hover:bg-[#8ff5ff]/5 hover:text-[#8ff5ff] duration-200 ease-in-out" href="#">
<span class="material-symbols-outlined" data-icon="location_city">location_city</span>
<span class="font-['Inter'] text-sm uppercase tracking-widest">Города 2050</span>
</a>
<a class="flex items-center gap-4 px-6 py-3 text-[#f9f5fd]/40 hover:bg-[#8ff5ff]/5 hover:text-[#8ff5ff] duration-200 ease-in-out" href="#">
<span class="material-symbols-outlined" data-icon="public">public</span>
<span class="font-['Inter'] text-sm uppercase tracking-widest">Мировое Президентство</span>
</a>
<div class="mt-8 px-6">
<div class="h-[1px] bg-[#8ff5ff]/10 w-full mb-6"></div>
<a class="flex items-center gap-4 py-2 text-[#f9f5fd]/40 hover:text-[#ac89ff] transition-colors" href="#">
<span class="material-symbols-outlined" data-icon="bolt">bolt</span>
<span class="font-['Inter'] text-xs uppercase tracking-widest">Сверхспособности</span>
</a>
</div>
</nav>
</aside>
<!-- Main Content Canvas -->
<main class="lg:pl-72 pt-24 pb-32 px-6 md:px-12 min-h-screen">
<!-- Hero Section -->
<section class="max-w-7xl mx-auto mb-20 relative">
<div class="absolute -top-24 -left-24 w-96 h-96 bg-primary/10 rounded-full blur-[120px]"></div>
<div class="absolute top-0 right-0 w-64 h-64 bg-secondary/10 rounded-full blur-[100px]"></div>
<div class="relative z-10">
<span class="text-secondary font-medium tracking-[0.3em] uppercase text-xs mb-4 block">Экспедиция в завтра</span>
<h2 class="font-headline text-5xl md:text-7xl font-bold mb-8 max-w-4xl leading-[1.1] tracking-tight">
                    Архитектура <span class="text-gradient">Цивилизации</span> следующего поколения
                </h2>
<p class="text-on-surface-variant text-lg md:text-xl max-w-2xl leading-relaxed mb-10 font-light">
                    Исследуйте конвергенцию человеческого разума и синтетического интеллекта в крупнейшем архиве футурологических прогнозов.
                </p>
<div class="flex gap-4">
<button class="bg-primary text-on-primary px-8 py-4 rounded font-bold hover:shadow-[0_0_30px_rgba(143,245,255,0.3)] transition-all active:scale-95">
                        Начать погружение
                    </button>
<button class="border border-outline-variant hover:border-primary/50 px-8 py-4 rounded font-medium backdrop-blur-sm transition-all active:scale-95">
                        Смотреть демо
                    </button>
</div>
</div>
</section>
<!-- Bento Grid Section -->
<section class="max-w-7xl mx-auto">
<div class="grid grid-cols-1 md:grid-cols-12 gap-6 auto-rows-[280px]">
<!-- AI Cities (Large Hero Card) -->
<div class="md:col-span-8 md:row-span-2 glass-card rounded-xl overflow-hidden group relative p-8 flex flex-col justify-end">
<div class="absolute inset-0 z-0">
<img class="w-full h-full object-cover opacity-40 group-hover:scale-105 transition-transform duration-700" data-alt="futuristic cityscape with glowing neon architecture and floating transport pods at night with cinematic blue and purple lighting" src="https://lh3.googleusercontent.com/aida-public/AB6AXuCGn1HSdrnQ_ch4HTFeV-gZgJR-Qr-GEyO0naBtvnARepogWn-3M_AZDEw-cALd4dnoiUiOmCL9obCTzCyjqAD5EZ-yypsyW-td7MbhmBhkglAqUFmazzrhPEvTDunJ_2EpL8CX2ebSi7z3gfOBPDguImSBunxQfyYmo1BWz2Fw4wAakfXTw5u_Lhk2cAug00VDL63ov7-BODgJw2r50XJ_U3P1VCbyEJvEtTz6G21rrt7SSuHboJ4VvfueWAyw4asmc2Ma0KP977k"/>
<div class="absolute inset-0 bg-gradient-to-t from-background via-background/40 to-transparent"></div>
</div>
<div class="relative z-10">
<div class="flex items-center gap-3 mb-4">
<span class="material-symbols-outlined text-primary text-3xl" data-icon="apartment">apartment</span>
<span class="px-3 py-1 bg-primary/10 border border-primary/20 rounded-full text-primary text-[10px] uppercase tracking-widest font-bold">Активно</span>
</div>
<h3 class="font-headline text-3xl font-bold mb-3 tracking-tight text-[#8ff5ff]">ИИ-Города</h3>
<p class="text-on-surface/70 max-w-md leading-relaxed mb-6">Автономные мегаполисы, управляемые нейронными сетями в режиме реального времени. Оптимизация ресурсов 100%.</p>
<a class="inline-flex items-center gap-2 text-primary hover:gap-4 transition-all font-medium" href="#">
                            Исследовать концепт <span class="material-symbols-outlined">arrow_forward</span>
</a>
</div>
</div>
<!-- Digital Twins -->
<div class="md:col-span-4 md:row-span-1 glass-card rounded-xl p-8 flex flex-col justify-between border-l-4 border-secondary/40">
<div class="flex justify-between items-start">
<span class="material-symbols-outlined text-secondary text-4xl" data-icon="memory">memory</span>
<span class="text-on-surface-variant text-[10px] font-mono">CODE: DT_01</span>
</div>
<div>
<h3 class="font-headline text-xl font-bold mb-2 tracking-tight">Цифровые Двойники</h3>
<p class="text-on-surface/60 text-sm">Виртуальные копии организмов для симуляции будущего.</p>
</div>
</div>
<!-- Schools of Future -->
<div class="md:col-span-4 md:row-span-1 glass-card rounded-xl p-8 flex flex-col justify-between hover:bg-surface-container-highest transition-colors">
<div class="flex justify-between items-start">
<span class="material-symbols-outlined text-tertiary text-4xl" data-icon="school">school</span>
</div>
<div>
<h3 class="font-headline text-xl font-bold mb-2 tracking-tight">Школы Будущего</h3>
<p class="text-on-surface/60 text-sm">Нейроинтерфейсное обучение и передача знаний по запросу.</p>
</div>
</div>
<!-- World Presidency -->
<div class="md:col-span-4 md:row-span-2 glass-card rounded-xl overflow-hidden relative group">
<div class="absolute inset-0 z-0">
<img class="w-full h-full object-cover opacity-30 group-hover:scale-110 transition-transform duration-1000" data-alt="holographic projection of planet earth glowing in deep blue with digital data streams and network lines orbiting it in space" src="https://lh3.googleusercontent.com/aida-public/AB6AXuClLw4UpIP5p3qhm7ApJAtpJgt7a9CVRNQX7Ul38As430ZfhyUfQAhoqwsMhv8K3htuOtuLaDdlCuaDuPFkSo-ZYcUe7AkQaoyfSAC5LCPw8V5gOpN4b6DR0t6nwIZVgYZ4PvTC5CGPVlljeBr6sx3ssBJ7J9LvnjFjY60Xc-ooEH4lx0qlh69P-OhGqDuc04UcUyqIoh0jFGnkMG_Xcb-ztsQRymid26OFOoqYNPnk0Yw4E2I6lc11kywIPKlRPddqOLKZgq5bkds"/>
</div>
<div class="relative z-10 p-8 h-full flex flex-col justify-between">
<span class="material-symbols-outlined text-primary text-5xl" data-icon="public">public</span>
<div>
<h3 class="font-headline text-2xl font-bold mb-3 tracking-tight">Мировое Президентство</h3>
<p class="text-on-surface/70 text-sm leading-relaxed mb-6">Единая глобальная система управления на базе квантового консенсуса.</p>
<div class="flex -space-x-3">
<div class="w-8 h-8 rounded-full border border-background bg-surface-container-highest"></div>
<div class="w-8 h-8 rounded-full border border-background bg-secondary"></div>
<div class="w-8 h-8 rounded-full border border-background bg-primary"></div>
<div class="w-8 h-8 rounded-full border border-background bg-surface-container-low flex items-center justify-center text-[10px]">+12</div>
</div>
</div>
</div>
</div>
<!-- City 2050 -->
<div class="md:col-span-8 md:row-span-1 glass-card rounded-xl p-8 flex items-center gap-8 group">
<div class="w-1/3 h-full rounded bg-surface-container-highest overflow-hidden relative">
<img class="w-full h-full object-cover opacity-60 group-hover:scale-110 transition-transform duration-500" data-alt="extreme close-up of a high-tech processor chip with glowing neon circuits and light trails pulsing through it" src="https://lh3.googleusercontent.com/aida-public/AB6AXuBBZX982nexkteGtZkKPGhobSFUfXc7tL_MOVzjAPiVdYeRmm_T4H-5AhI2UIsCyw9uwcUNtGeQ5ANczAa8rTJqD-j6aDiVC2fcfsfmQjGkWbhLZUqk6FUN1HqTM-xeIZzlLN0-MUKjDdfgBoLaXvQNCcgt3ZRSa84GTGTOzHxLojK_lrR4Et7bM47OX6qHEnmCm7Ek3dFuPgk_4dvpGnpHowJ-IAV1NAKCHyE-oac7I7m8eIWllWEnnoUwiNi9CaScoewAYI04AnM"/>
<div class="absolute inset-0 flex items-center justify-center">
<span class="material-symbols-outlined text-primary text-4xl" data-icon="location_city">location_city</span>
</div>
</div>
<div class="w-2/3">
<div class="flex items-center gap-2 mb-2">
<span class="w-2 h-2 rounded-full bg-error animate-pulse"></span>
<span class="text-error text-[10px] uppercase font-bold tracking-tighter">Лимит времени: 26 лет</span>
</div>
<h3 class="font-headline text-2xl font-bold mb-2 tracking-tight">Город 2050</h3>
<p class="text-on-surface/60 text-sm">Проектирование инфраструктуры для первой марсианской колонии на Земле.</p>
</div>
</div>
</div>
</section>
<!-- Stats Section -->
<section class="max-w-7xl mx-auto mt-32 py-20 border-t border-outline-variant/10">
<div class="grid grid-cols-2 md:grid-cols-4 gap-12">
<div class="text-center">
<div class="text-4xl font-headline font-bold text-primary mb-2">14.2 ПБ</div>
<div class="text-on-surface-variant text-xs uppercase tracking-widest">Данных синтезировано</div>
</div>
<div class="text-center">
<div class="text-4xl font-headline font-bold text-secondary mb-2">856</div>
<div class="text-on-surface-variant text-xs uppercase tracking-widest">ИИ-Архитекторов</div>
</div>
<div class="text-center">
<div class="text-4xl font-headline font-bold text-tertiary mb-2">99.9%</div>
<div class="text-on-surface-variant text-xs uppercase tracking-widest">Точность прогнозов</div>
</div>
<div class="text-center">
<div class="text-4xl font-headline font-bold text-primary mb-2">2050</div>
<div class="text-on-surface-variant text-xs uppercase tracking-widest">Горизонт планирования</div>
</div>
</div>
</section>
</main>
<!-- BottomNavBar (Mobile) -->
<nav class="md:hidden fixed bottom-0 left-0 w-full h-20 bg-[#0e0e13]/90 backdrop-blur-lg border-t border-[#8ff5ff]/10 flex justify-around items-center px-4 pb-safe z-50 shadow-[0_-4px_24px_rgba(0,240,255,0.1)] rounded-t-xl">
<a class="flex flex-col items-center justify-center bg-[#8ff5ff]/10 text-[#8ff5ff] rounded-xl px-4 py-1 active:scale-90 transition-all duration-300" href="#">
<span class="material-symbols-outlined" data-icon="hub">hub</span>
<span class="font-['Inter'] text-[10px] font-medium">Портал</span>
</a>
<a class="flex flex-col items-center justify-center text-[#f9f5fd]/50 hover:text-[#ac89ff] active:scale-90 transition-all duration-300" href="#">
<span class="material-symbols-outlined" data-icon="grid_view">grid_view</span>
<span class="font-['Inter'] text-[10px] font-medium">Темы</span>
</a>
<a class="flex flex-col items-center justify-center text-[#f9f5fd]/50 hover:text-[#ac89ff] active:scale-90 transition-all duration-300" href="#">
<span class="material-symbols-outlined" data-icon="auto_awesome">auto_awesome</span>
<span class="font-['Inter'] text-[10px] font-medium">Избранное</span>
</a>
<a class="flex flex-col items-center justify-center text-[#f9f5fd]/50 hover:text-[#ac89ff] active:scale-90 transition-all duration-300" href="#">
<span class="material-symbols-outlined" data-icon="account_circle">account_circle</span>
<span class="font-['Inter'] text-[10px] font-medium">Профиль</span>
</a>
</nav>
<!-- Floating Action Button -->
<button class="fixed bottom-24 right-8 lg:bottom-12 lg:right-12 w-16 h-16 bg-primary text-on-primary rounded-full shadow-[0_0_40px_rgba(143,245,255,0.4)] flex items-center justify-center z-40 active:scale-90 transition-transform">
<span class="material-symbols-outlined text-3xl" data-icon="bolt" data-weight="fill" style="font-variation-settings: 'FILL' 1;">bolt</span>
</button>
</body></html>
<!DOCTYPE html>

<html class="dark" lang="ru"><head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<title>Школа Будущего | ИИ-Навигатор</title>
<script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&amp;family=Space+Grotesk:wght@300;400;500;600;700&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<script id="tailwind-config">
        tailwind.config = {
            darkMode: "class",
            theme: {
                extend: {
                    "colors": {
                        "on-secondary": "#290067",
                        "on-error": "#490006",
                        "error-dim": "#d7383b",
                        "on-tertiary-container": "#ffffff",
                        "surface-container": "#19191f",
                        "secondary": "#ac89ff",
                        "tertiary-container": "#aa19f9",
                        "on-primary": "#005d63",
                        "surface": "#0e0e13",
                        "tertiary-fixed-dim": "#cf82ff",
                        "tertiary-fixed": "#d896ff",
                        "outline-variant": "#48474d",
                        "surface-container-high": "#1f1f26",
                        "on-primary-container": "#005359",
                        "background": "#0e0e13",
                        "surface-container-low": "#131319",
                        "surface-container-highest": "#25252d",
                        "inverse-surface": "#fcf8ff",
                        "on-tertiary-fixed-variant": "#5c008b",
                        "on-error-container": "#ffa8a3",
                        "error": "#ff716c",
                        "secondary-fixed": "#dac9ff",
                        "secondary-fixed-dim": "#ceb9ff",
                        "primary-container": "#00eefc",
                        "inverse-on-surface": "#55545b",
                        "on-secondary-fixed-variant": "#6300e2",
                        "on-secondary-container": "#f8f1ff",
                        "surface-container-lowest": "#000000",
                        "on-secondary-fixed": "#41009a",
                        "surface-dim": "#0e0e13",
                        "secondary-container": "#7000ff",
                        "on-tertiary-fixed": "#2a0043",
                        "surface-tint": "#8ff5ff",
                        "on-primary-fixed-variant": "#005e64",
                        "on-background": "#f9f5fd",
                        "on-surface": "#f9f5fd",
                        "error-container": "#9f0519",
                        "on-tertiary": "#360055",
                        "secondary-dim": "#874cff",
                        "primary-fixed": "#00eefc",
                        "tertiary-dim": "#af25fe",
                        "outline": "#76747b",
                        "on-primary-fixed": "#003f43",
                        "tertiary": "#cc7aff",
                        "inverse-primary": "#006a71",
                        "on-surface-variant": "#acaab1",
                        "primary-dim": "#00deec",
                        "surface-variant": "#25252d",
                        "primary-fixed-dim": "#00deec",
                        "surface-bright": "#2c2b33",
                        "primary": "#8ff5ff"
                    },
                    "borderRadius": {
                        "DEFAULT": "0.25rem",
                        "lg": "0.5rem",
                        "xl": "0.75rem",
                        "full": "9999px"
                    },
                    "fontFamily": {
                        "headline": ["Space Grotesk"],
                        "body": ["Inter"],
                        "label": ["Inter"]
                    }
                },
            },
        }
    </script>
<style>
        body { background-color: #0e0e13; color: #f9f5fd; font-family: 'Inter', sans-serif; }
        .material-symbols-outlined { font-variation-settings: 'FILL' 0, 'wght' 400, 'GRAD' 0, 'opsz' 24; }
        .glass-panel { background: rgba(25, 25, 31, 0.6); backdrop-filter: blur(12px); border: 1px solid rgba(143, 245, 255, 0.05); }
        .neon-glow { text-shadow: 0 0 10px rgba(143, 245, 255, 0.5); }
    </style>
<style>
    body {
      min-height: max(884px, 100dvh);
    }
  </style>
  </head>
<body class="overflow-x-hidden">
<!-- TopAppBar -->
<header class="fixed top-0 w-full z-50 bg-[#0e0e13]/80 backdrop-blur-xl border-b border-[#8ff5ff]/10 shadow-[0_0_20px_rgba(143,245,255,0.05)]">
<div class="flex items-center justify-between px-6 h-16 w-full max-w-none">
<div class="flex items-center gap-4">
<span class="material-symbols-outlined text-[#8ff5ff]" data-icon="explore">explore</span>
<span class="font-['Space_Grotesk'] tracking-tight text-xl font-bold bg-gradient-to-r from-[#8ff5ff] to-[#ac89ff] bg-clip-text text-transparent">Исследования Будущего</span>
</div>
<div class="flex items-center gap-6">
<nav class="hidden md:flex gap-8 text-sm font-medium">
<a class="text-[#8ff5ff] hover:text-[#8ff5ff] transition-colors duration-300" href="#">Портал</a>
<a class="text-[#f9f5fd]/60 hover:text-[#8ff5ff] transition-colors duration-300" href="#">Темы</a>
<a class="text-[#f9f5fd]/60 hover:text-[#8ff5ff] transition-colors duration-300" href="#">Избранное</a>
</nav>
<div class="h-10 w-10 rounded-full border border-[#8ff5ff]/30 p-0.5 overflow-hidden active:scale-95 transition-transform">
<img class="w-full h-full object-cover rounded-full" data-alt="Portrait of a young male student with a neutral expression and high-tech glasses, cinematic lighting with blue rim light" src="https://lh3.googleusercontent.com/aida-public/AB6AXuDbcObdFoySeK5DoR6hdKkTAWcMyPcpEr2EhEZf0UN2N0GnuzXf76q_Y_gePCwHUAzk8aazM4zNCYhbEr4O-5HH7srSYja13muk5WE7ouCXmiRwq-UgFhZug33xCTrjuDGypEadla-WqJad3wMKAYSpCEb0_DcWMYB_BIZHLBgbaVYle0eF55PQ5nsZBXi-8D5VcUlywug1_R-Wnwe-AQo6VJ6AdY6cSLNi6vAWuhxfb-m3bnuM9ssD5eHwaeFTk0NT9OG0Lhk80YI"/>
</div>
</div>
</div>
</header>
<!-- NavigationDrawer -->
<aside class="fixed left-0 top-0 h-full w-72 z-[60] py-8 bg-[#0e0e13] rounded-r-lg border-r border-[#8ff5ff]/10 shadow-2xl shadow-cyan-900/20 hidden lg:block">
<div class="px-8 mb-10">
<h2 class="text-[#8ff5ff] font-['Space_Grotesk'] text-lg font-bold">Навигатор Будущего</h2>
</div>
<nav class="flex flex-col gap-1">
<div class="px-6 py-3 text-[#f9f5fd]/40 font-['Inter'] text-xs uppercase tracking-widest mb-2">Направления</div>
<a class="flex items-center gap-4 px-8 py-3 text-[#f9f5fd]/40 hover:bg-[#8ff5ff]/5 hover:text-[#8ff5ff] duration-200 ease-in-out" href="#">
<span class="material-symbols-outlined text-lg" data-icon="apartment">apartment</span>
<span class="font-['Inter'] text-sm uppercase tracking-widest">ИИ-Города</span>
</a>
<a class="flex items-center gap-4 px-8 py-3 text-[#f9f5fd]/40 hover:bg-[#8ff5ff]/5 hover:text-[#8ff5ff] duration-200 ease-in-out" href="#">
<span class="material-symbols-outlined text-lg" data-icon="memory">memory</span>
<span class="font-['Inter'] text-sm uppercase tracking-widest">Цифровые Двойники</span>
</a>
<a class="flex items-center gap-4 px-8 py-3 bg-gradient-to-r from-[#8ff5ff]/10 to-transparent border-l-2 border-[#8ff5ff] text-[#8ff5ff] font-bold duration-200 ease-in-out" href="#">
<span class="material-symbols-outlined text-lg" data-icon="school">school</span>
<span class="font-['Inter'] text-sm uppercase tracking-widest">Школы Будущего</span>
</a>
<a class="flex items-center gap-4 px-8 py-3 text-[#f9f5fd]/40 hover:bg-[#8ff5ff]/5 hover:text-[#8ff5ff] duration-200 ease-in-out" href="#">
<span class="material-symbols-outlined text-lg" data-icon="biotech">biotech</span>
<span class="font-['Inter'] text-sm uppercase tracking-widest">Юные Изобретатели</span>
</a>
<a class="flex items-center gap-4 px-8 py-3 text-[#f9f5fd]/40 hover:bg-[#8ff5ff]/5 hover:text-[#8ff5ff] duration-200 ease-in-out" href="#">
<span class="material-symbols-outlined text-lg" data-icon="swap_horiz">swap_horiz</span>
<span class="font-['Inter'] text-sm uppercase tracking-widest">Биржа Талантов</span>
</a>
</nav>
</aside>
<!-- Main Content Area -->
<main class="lg:pl-72 pt-16 pb-24 min-h-screen">
<div class="max-w-7xl mx-auto px-6 py-12">
<!-- Hero Section: AI Mentor -->
<section class="mb-16 grid grid-cols-1 lg:grid-cols-12 gap-8 items-center">
<div class="lg:col-span-7">
<div class="inline-flex items-center gap-2 px-3 py-1 rounded-full bg-primary/10 border border-primary/20 mb-6">
<span class="w-2 h-2 rounded-full bg-primary animate-pulse"></span>
<span class="text-primary text-[10px] uppercase font-bold tracking-tighter">AI Mentor Online</span>
</div>
<h1 class="font-['Space_Grotesk'] text-5xl md:text-7xl font-bold text-on-surface mb-8 leading-tight">
                        Школа без <br/><span class="text-secondary neon-glow">учителей</span>.
                    </h1>
<p class="text-on-surface-variant text-lg max-w-xl leading-relaxed mb-10">
                        Ваш индивидуальный образовательный путь формируется нейросетью в реальном времени. Нет звонков, нет границ — только чистое познание.
                    </p>
<div class="flex flex-wrap gap-4">
<button class="px-8 py-4 bg-primary text-on-primary font-bold rounded-lg shadow-[0_0_30px_rgba(143,245,255,0.3)] hover:scale-105 transition-transform">
                            Продолжить обучение
                        </button>
<button class="px-8 py-4 glass-panel text-on-surface font-bold rounded-lg hover:bg-surface-container-highest transition-colors">
                            Выбрать новый трек
                        </button>
</div>
</div>
<div class="lg:col-span-5 relative">
<div class="aspect-square rounded-full border border-primary/20 flex items-center justify-center p-8 bg-gradient-to-br from-primary/5 to-secondary/5">
<img class="w-full h-full object-cover rounded-full mix-blend-screen opacity-80" data-alt="Abstract glowing 3D particle sphere representing artificial intelligence consciousness, blue and violet neon colors on dark background" src="https://lh3.googleusercontent.com/aida-public/AB6AXuBNnV4v4uqnu1n5fu3Lh5xZmyFBR1BHzl4BctzNEHmN5QMwcIAw_3DEUbQIClyy6GMAshD66tY9oVRZ_q07epHnYRNjqeQzKqKkQNUb75_2jV-xkXgOSPdhe9rRilEMammrtieOhYCArwXDPIrX1ljPUWVx2bhP8RTlzLYficafFuZscpeyvbyVyvGopxw_vueAVU7SmCl5TbKk9MoWUf3J7HOu6yWpWbyxEnASgDDShLc20_BnZu3SGn4MAyOwlOiB7bfM1BV_8hI"/>
</div>
<!-- Stats Floating Card -->
<div class="absolute -bottom-4 -left-4 glass-panel p-6 rounded-xl shadow-2xl">
<div class="text-xs text-[#f9f5fd]/40 uppercase tracking-widest mb-1">Ваш IQ прогресс</div>
<div class="text-3xl font-bold text-primary tracking-tighter">142.8</div>
<div class="mt-2 flex gap-1 h-1 w-32 bg-surface-container rounded-full overflow-hidden">
<div class="h-full w-3/4 bg-primary"></div>
</div>
</div>
</div>
</section>
<!-- Learning Paths Grid (Bento Style) -->
<section class="grid grid-cols-1 md:grid-cols-4 md:grid-rows-2 gap-6">
<!-- Large Feature: Virtual Class -->
<div class="md:col-span-2 md:row-span-2 glass-panel rounded-xl overflow-hidden group cursor-pointer">
<div class="relative h-64 overflow-hidden">
<img class="w-full h-full object-cover group-hover:scale-110 transition-transform duration-700" data-alt="Futuristic server room with glowing fiber optic cables and digital holographic interfaces, high-tech laboratory aesthetic" src="https://lh3.googleusercontent.com/aida-public/AB6AXuARJWEpI_gk5sp7B88JjZ1pRZt0FC0gcopEmbJZlifEfLSJ4myRezG4Z0FDnBVSyNn6BDCyK_mb5PBttMHNsAaTXh-28OEVXS9SEj3uCzd4-MvytuQF-B2tkK68r7Z5nKzuhKtCrtyaQQ0Yps5Y23cfsiAiWW4ovCcGSYrntvegL3u1AzgcrJRyZcTu1NKUXMKSJeGCh_dLFFIoiVb1cmBpJ0qHnxyHCQ0c4ZswxwoW375bLyz34_LvcAP4Lqr_px2iyHTVIiyqbh0"/>
<div class="absolute inset-0 bg-gradient-to-t from-surface to-transparent"></div>
</div>
<div class="p-8">
<div class="flex items-center gap-2 mb-4">
<span class="material-symbols-outlined text-secondary" data-icon="visibility">visibility</span>
<span class="text-secondary font-bold text-xs uppercase tracking-widest">Виртуальный класс</span>
</div>
<h3 class="font-['Space_Grotesk'] text-2xl font-bold mb-4">Симуляция Квантовых Систем</h3>
<p class="text-on-surface-variant text-sm leading-relaxed mb-6">
                            Погрузитесь в микромир. Управляйте атомами и наблюдайте за квантовой запутанностью в безопасной VR-среде.
                        </p>
<div class="flex items-center justify-between">
<span class="text-xs font-mono text-primary/60">SESSION_ID: QN-092</span>
<span class="material-symbols-outlined text-primary" data-icon="arrow_forward">arrow_forward</span>
</div>
</div>
</div>
<!-- Skill Card 1 -->
<div class="md:col-span-2 glass-panel rounded-xl p-8 flex flex-col justify-between hover:border-primary/30 transition-colors">
<div>
<div class="flex justify-between items-start mb-6">
<div class="p-3 bg-tertiary/10 rounded-lg">
<span class="material-symbols-outlined text-tertiary" data-icon="neurology">neurology</span>
</div>
<span class="text-[10px] bg-surface-container-highest px-2 py-1 rounded">HARD SKILL</span>
</div>
<h4 class="font-bold text-lg mb-2">Нейро-архитектура</h4>
<p class="text-on-surface-variant text-xs">Проектирование нейронных связей для адаптивных ИИ-систем.</p>
</div>
<div class="mt-8">
<div class="flex justify-between text-[10px] mb-2 uppercase opacity-50">
<span>Прогресс</span>
<span>68%</span>
</div>
<div class="h-1.5 w-full bg-surface-container-highest rounded-full overflow-hidden">
<div class="h-full w-[68%] bg-gradient-to-r from-primary to-secondary"></div>
</div>
</div>
</div>
<!-- Small Card: Mentor -->
<div class="glass-panel rounded-xl p-6 hover:bg-surface-container transition-colors cursor-pointer border-l-4 border-secondary/40">
<span class="material-symbols-outlined text-secondary mb-4" data-icon="psychology">psychology</span>
<h5 class="font-bold text-sm mb-1">ИИ-Наставник</h5>
<p class="text-[11px] text-on-surface-variant">Чат доступен 24/7</p>
</div>
<!-- Small Card: Achievements -->
<div class="glass-panel rounded-xl p-6 hover:bg-surface-container transition-colors cursor-pointer border-l-4 border-primary/40">
<span class="material-symbols-outlined text-primary mb-4" data-icon="workspace_premium">workspace_premium</span>
<h5 class="font-bold text-sm mb-1">Достижения</h5>
<p class="text-[11px] text-on-surface-variant">3 новых токена</p>
</div>
</section>
<!-- Bottom Data Stream Component -->
<section class="mt-16 glass-panel rounded-xl p-8 overflow-hidden relative">
<div class="absolute top-0 left-0 w-full h-1 bg-gradient-to-r from-primary via-secondary to-tertiary opacity-50"></div>
<div class="flex flex-col md:flex-row items-center justify-between gap-8">
<div class="flex gap-4 items-center">
<div class="w-12 h-12 rounded-full border-2 border-primary/20 flex items-center justify-center">
<span class="material-symbols-outlined text-primary" data-icon="history_edu">history_edu</span>
</div>
<div>
<h4 class="font-bold">Дневник Развития</h4>
<p class="text-xs text-on-surface-variant">Последнее обновление: 2 минуты назад</p>
</div>
</div>
<div class="flex items-center gap-8">
<div class="text-center">
<div class="text-xl font-bold text-primary">1,240</div>
<div class="text-[10px] uppercase tracking-tighter opacity-50">Часов практики</div>
</div>
<div class="text-center">
<div class="text-xl font-bold text-secondary">84%</div>
<div class="text-[10px] uppercase tracking-tighter opacity-50">Концентрация</div>
</div>
<div class="text-center">
<div class="text-xl font-bold text-tertiary">9/10</div>
<div class="text-[10px] uppercase tracking-tighter opacity-50">Рейтинг ИИ</div>
</div>
</div>
<button class="px-6 py-3 bg-surface-container-highest text-primary font-bold rounded-lg border border-primary/20 hover:bg-primary hover:text-on-primary transition-all">
                        Экспортировать отчет
                    </button>
</div>
</section>
</div>
</main>
<!-- BottomNavBar (Mobile Only) -->
<nav class="md:hidden fixed bottom-0 left-0 w-full h-20 bg-[#0e0e13]/90 backdrop-blur-lg flex justify-around items-center px-4 pb-safe z-50 border-t border-[#8ff5ff]/10 shadow-[0_-4px_24px_rgba(0,240,255,0.1)] rounded-t-xl">
<a class="flex flex-col items-center justify-center text-[#f9f5fd]/50 hover:text-[#ac89ff] active:scale-90 transition-all duration-300" href="#">
<span class="material-symbols-outlined" data-icon="hub">hub</span>
<span class="font-['Inter'] text-[10px] font-medium">Портал</span>
</a>
<a class="flex flex-col items-center justify-center text-[#f9f5fd]/50 hover:text-[#ac89ff] active:scale-90 transition-all duration-300" href="#">
<span class="material-symbols-outlined" data-icon="grid_view">grid_view</span>
<span class="font-['Inter'] text-[10px] font-medium">Темы</span>
</a>
<a class="flex flex-col items-center justify-center bg-[#8ff5ff]/10 text-[#8ff5ff] rounded-xl px-4 py-1 active:scale-90 transition-all duration-300" href="#">
<span class="material-symbols-outlined" data-icon="auto_awesome">auto_awesome</span>
<span class="font-['Inter'] text-[10px] font-medium">Избранное</span>
</a>
<a class="flex flex-col items-center justify-center text-[#f9f5fd]/50 hover:text-[#ac89ff] active:scale-90 transition-all duration-300" href="#">
<span class="material-symbols-outlined" data-icon="account_circle">account_circle</span>
<span class="font-['Inter'] text-[10px] font-medium">Профиль</span>
</a>
</nav>
<!-- Decorative Glow Elements -->
<div class="fixed top-0 right-0 w-[500px] h-[500px] bg-primary/5 blur-[150px] -z-10 rounded-full"></div>
<div class="fixed bottom-0 left-0 w-[500px] h-[500px] bg-secondary/5 blur-[150px] -z-10 rounded-full"></div>
</body></html>
<!DOCTYPE html>

<html class="dark" lang="ru"><head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<link href="https://fonts.googleapis.com" rel="preconnect"/>
<link crossorigin="" href="https://fonts.gstatic.com" rel="preconnect"/>
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&amp;family=Space+Grotesk:wght@300;400;500;600;700&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
<script id="tailwind-config">
      tailwind.config = {
        darkMode: "class",
        theme: {
          extend: {
            "colors": {
                    "on-secondary": "#290067",
                    "on-error": "#490006",
                    "error-dim": "#d7383b",
                    "on-tertiary-container": "#ffffff",
                    "surface-container": "#19191f",
                    "secondary": "#ac89ff",
                    "tertiary-container": "#aa19f9",
                    "on-primary": "#005d63",
                    "surface": "#0e0e13",
                    "tertiary-fixed-dim": "#cf82ff",
                    "tertiary-fixed": "#d896ff",
                    "outline-variant": "#48474d",
                    "surface-container-high": "#1f1f26",
                    "on-primary-container": "#005359",
                    "background": "#0e0e13",
                    "surface-container-low": "#131319",
                    "surface-container-highest": "#25252d",
                    "inverse-surface": "#fcf8ff",
                    "on-tertiary-fixed-variant": "#5c008b",
                    "on-error-container": "#ffa8a3",
                    "error": "#ff716c",
                    "secondary-fixed": "#dac9ff",
                    "secondary-fixed-dim": "#ceb9ff",
                    "primary-container": "#00eefc",
                    "inverse-on-surface": "#55545b",
                    "on-secondary-fixed-variant": "#6300e2",
                    "on-secondary-container": "#f8f1ff",
                    "surface-container-lowest": "#000000",
                    "on-secondary-fixed": "#41009a",
                    "surface-dim": "#0e0e13",
                    "secondary-container": "#7000ff",
                    "on-tertiary-fixed": "#2a0043",
                    "surface-tint": "#8ff5ff",
                    "on-primary-fixed-variant": "#005e64",
                    "on-background": "#f9f5fd",
                    "on-surface": "#f9f5fd",
                    "error-container": "#9f0519",
                    "on-tertiary": "#360055",
                    "secondary-dim": "#874cff",
                    "primary-fixed": "#00eefc",
                    "tertiary-dim": "#af25fe",
                    "outline": "#76747b",
                    "on-primary-fixed": "#003f43",
                    "tertiary": "#cc7aff",
                    "inverse-primary": "#006a71",
                    "on-surface-variant": "#acaab1",
                    "primary-dim": "#00deec",
                    "surface-variant": "#25252d",
                    "primary-fixed-dim": "#00deec",
                    "surface-bright": "#2c2b33",
                    "primary": "#8ff5ff"
            },
            "borderRadius": {
                    "DEFAULT": "0.25rem",
                    "lg": "0.5rem",
                    "xl": "0.75rem",
                    "full": "9999px"
            },
            "fontFamily": {
                    "headline": ["Space Grotesk"],
                    "body": ["Inter"],
                    "label": ["Inter"]
            }
          },
        },
      }
    </script>
<style>
        .material-symbols-outlined {
            font-variation-settings: 'FILL' 0, 'wght' 400, 'GRAD' 0, 'opsz' 24;
        }
        .glass-panel {
            background: rgba(14, 14, 19, 0.7);
            backdrop-filter: blur(12px);
        }
        .data-stream {
            background: linear-gradient(90deg, #8ff5ff 0%, #ac89ff 100%);
        }
    </style>
<style>
    body {
      min-height: max(884px, 100dvh);
    }
  </style>
  </head>
<body class="bg-background text-on-background font-body selection:bg-primary/30">
<!-- TopAppBar -->
<header class="fixed top-0 w-full z-50 bg-[#0e0e13]/80 backdrop-blur-xl border-b border-[#8ff5ff]/10 shadow-[0_0_20px_rgba(143,245,255,0.05)]">
<div class="flex items-center justify-between px-6 h-16 w-full max-w-none">
<div class="flex items-center gap-3">
<span class="material-symbols-outlined text-[#8ff5ff]">explore</span>
<span class="text-xl font-bold bg-gradient-to-r from-[#8ff5ff] to-[#ac89ff] bg-clip-text text-transparent font-['Space_Grotesk'] tracking-tight">Исследования Будущего</span>
</div>
<div class="flex items-center gap-6">
<nav class="hidden md:flex gap-8 font-['Space_Grotesk'] tracking-tight">
<a class="text-[#f9f5fd]/60 hover:text-[#8ff5ff] transition-colors duration-300" href="#">ПОРТАЛ</a>
<a class="text-[#f9f5fd]/60 hover:text-[#8ff5ff] transition-colors duration-300" href="#">ТЕМЫ</a>
<a class="text-[#f9f5fd]/60 hover:text-[#8ff5ff] transition-colors duration-300" href="#">ИЗБРАННОЕ</a>
<a class="text-[#8ff5ff]" href="#">ПРОФИЛЬ</a>
</nav>
<div class="w-10 h-10 rounded-full border border-primary/30 p-0.5 overflow-hidden active:scale-95 transition-transform">
<img alt="User Profile" class="w-full h-full object-cover rounded-full" data-alt="Stylized neon avatar of a futuristic digital user profile with cyan glow and geometric patterns" src="https://lh3.googleusercontent.com/aida-public/AB6AXuAywekipwfdz9sHxVE0qeVCpGHtTlr8PvyqDCaQvJ0Qlr9oPh3Qaq3nzjM-uU8QqcG0QU3lyqfGmowuZGooz1XQI1V2PFwEcEGBYJzuBNVZ6fWWdQEK_VGuaIggIlCEKKdoKnLh1FJXfoCyn_lM2GNpTES7yVE6vip_blmAkY0VkEzLwLZfXvQAGmq_ED_1XWQ1CnRY2id_AzUESvq_C3n78HGzqd5HW8DEVsPbTePapJu6Ks0ut4nhTV0S3I8SCt8r9vj7Fcwc8rc"/>
</div>
</div>
</div>
</header>
<!-- Sidebar (Hidden on mobile) -->
<aside class="hidden lg:flex fixed left-0 top-0 h-full w-72 z-[60] py-8 flex-col bg-[#0e0e13] rounded-r-lg border-r border-[#8ff5ff]/10 shadow-2xl shadow-cyan-900/20">
<div class="px-6 mb-10">
<h2 class="text-[#8ff5ff] font-['Space_Grotesk'] font-bold text-lg">Навигатор Будущего</h2>
<p class="text-[10px] text-on-surface-variant tracking-widest mt-1 opacity-60">СИСТЕМА v4.0.2</p>
</div>
<nav class="flex-1 px-4 space-y-1">
<a class="flex items-center gap-4 px-4 py-3 text-[#f9f5fd]/40 hover:bg-[#8ff5ff]/5 hover:text-[#8ff5ff] duration-200 ease-in-out group" href="#">
<span class="material-symbols-outlined">apartment</span>
<span class="font-['Inter'] text-sm uppercase tracking-widest">ИИ-Города</span>
</a>
<a class="flex items-center gap-4 px-4 py-3 bg-gradient-to-r from-[#8ff5ff]/10 to-transparent border-l-2 border-[#8ff5ff] text-[#8ff5ff] font-bold duration-200 ease-in-out" href="#">
<span class="material-symbols-outlined">memory</span>
<span class="font-['Inter'] text-sm uppercase tracking-widest">Цифровые Двойники</span>
</a>
<a class="flex items-center gap-4 px-4 py-3 text-[#f9f5fd]/40 hover:bg-[#8ff5ff]/5 hover:text-[#8ff5ff] duration-200 ease-in-out group" href="#">
<span class="material-symbols-outlined">school</span>
<span class="font-['Inter'] text-sm uppercase tracking-widest">Школы Будущего</span>
</a>
<a class="flex items-center gap-4 px-4 py-3 text-[#f9f5fd]/40 hover:bg-[#8ff5ff]/5 hover:text-[#8ff5ff] duration-200 ease-in-out group" href="#">
<span class="material-symbols-outlined">share_reviews</span>
<span class="font-['Inter'] text-sm uppercase tracking-widest">Спец. Соцсети</span>
</a>
<a class="flex items-center gap-4 px-4 py-3 text-[#f9f5fd]/40 hover:bg-[#8ff5ff]/5 hover:text-[#8ff5ff] duration-200 ease-in-out group" href="#">
<span class="material-symbols-outlined">bolt</span>
<span class="font-['Inter'] text-sm uppercase tracking-widest">Сверхспособности</span>
</a>
</nav>
<div class="px-8 mt-auto pt-8 border-t border-outline-variant/10">
<div class="flex items-center gap-3">
<div class="w-2 h-2 rounded-full bg-primary animate-pulse"></div>
<span class="text-[10px] uppercase tracking-tighter text-on-surface-variant">Синхронизация: 99.8%</span>
</div>
</div>
</aside>
<!-- Main Content -->
<main class="lg:ml-72 pt-24 pb-32 px-6 md:px-12 max-w-7xl mx-auto">
<!-- Hero Section: Digital Twin Visualization -->
<section class="grid grid-cols-1 lg:grid-cols-12 gap-8 mb-16">
<div class="lg:col-span-7 flex flex-col justify-center">
<div class="mb-4">
<span class="text-secondary font-headline text-sm tracking-[0.2em] uppercase">Протокол: Теневой Резонанс</span>
<h1 class="text-4xl md:text-6xl font-headline font-bold text-on-surface mt-2 leading-tight">Цифровой Двойник: <br/><span class="text-primary">Александр В.</span></h1>
</div>
<p class="text-body-lg text-on-surface-variant max-w-lg mb-8">Виртуальная репрезентация вашего когнитивного профиля. Синхронизация данных в реальном времени на основе биометрии, нейронной активности и цифрового следа.</p>
<div class="flex flex-wrap gap-4">
<button class="bg-primary text-on-primary px-8 py-3 font-headline font-bold rounded hover:shadow-[0_0_20px_rgba(143,245,255,0.4)] transition-all">СИНХРОНИЗИРОВАТЬ</button>
<button class="border border-outline-variant text-on-surface px-8 py-3 font-headline font-bold rounded hover:bg-surface-container transition-all">АНАЛИЗ ДАННЫХ</button>
</div>
</div>
<div class="lg:col-span-5 relative aspect-square">
<div class="absolute inset-0 bg-gradient-to-br from-primary/20 to-secondary/20 rounded-full blur-[80px]"></div>
<div class="relative w-full h-full glass-panel rounded-xl border border-primary/20 flex items-center justify-center overflow-hidden">
<!-- Twin Visualization Placeholder -->
<img class="w-full h-full object-cover mix-blend-screen opacity-80" data-alt="Holographic human bust composed of glowing cyan particles and interconnected data nodes on a dark background" src="https://lh3.googleusercontent.com/aida-public/AB6AXuB1LRLQ7wJlQldBqXNcYiULavopAmfTBqkMeRCUJXLbRlLyf3x4Zoqa2D79bQN1X8AM4m3hbyNhJcFiWHkQnqqyWCK7FjyuFGwGMtUCw4rQFB1SHjSYPY9S6G0NWs7JMrgfUA6gUgBSMRVAeb4p5svFwkUe-3YIYhs02V3s-J42VevKuN883pdmnOZQjPOnntDcSDoPrUMk1onTQ4EMl_mcPBZuaQtG48u7mDDvibnc3AAHGgVkAQ-03SLqmLvOou9EHPSV1ZhgcGI"/>
<div class="absolute bottom-6 left-6 right-6 p-4 bg-surface-container-highest/60 backdrop-blur-md rounded border border-white/5">
<div class="flex justify-between items-center mb-2">
<span class="text-[10px] font-headline text-on-surface-variant">ЦЕЛОСТНОСТЬ ДАННЫХ</span>
<span class="text-[10px] font-headline text-primary">94%</span>
</div>
<div class="h-1 w-full bg-surface-container rounded-full overflow-hidden">
<div class="h-full data-stream w-[94%]"></div>
</div>
</div>
</div>
</div>
</section>
<!-- Bento Grid: Parameters & Stats -->
<section class="grid grid-cols-1 md:grid-cols-3 lg:grid-cols-4 gap-4 mb-16">
<!-- Large Stats Card -->
<div class="md:col-span-2 md:row-span-2 bg-surface-container-low p-8 border border-outline-variant/10 flex flex-col justify-between">
<div>
<h3 class="text-xl font-headline font-bold text-on-surface mb-6">Когнитивная Карта</h3>
<div class="space-y-6">
<div class="space-y-2">
<div class="flex justify-between text-xs tracking-widest text-on-surface-variant">
<span>АНАЛИТИКА</span>
<span>88%</span>
</div>
<div class="h-0.5 w-full bg-surface-container-highest">
<div class="h-full bg-primary w-[88%]"></div>
</div>
</div>
<div class="space-y-2">
<div class="flex justify-between text-xs tracking-widest text-on-surface-variant">
<span>КРЕАТИВНОСТЬ</span>
<span>72%</span>
</div>
<div class="h-0.5 w-full bg-surface-container-highest">
<div class="h-full bg-secondary w-[72%]"></div>
</div>
</div>
<div class="space-y-2">
<div class="flex justify-between text-xs tracking-widest text-on-surface-variant">
<span>ЭМПАТИЯ</span>
<span>64%</span>
</div>
<div class="h-0.5 w-full bg-surface-container-highest">
<div class="h-full bg-tertiary w-[64%]"></div>
</div>
</div>
</div>
</div>
<div class="mt-12 flex gap-4">
<div class="flex-1 p-4 bg-surface-container-highest/30 border border-white/5">
<p class="text-[10px] text-on-surface-variant uppercase">IQ Эквивалент</p>
<p class="text-2xl font-headline font-bold text-primary">142</p>
</div>
<div class="flex-1 p-4 bg-surface-container-highest/30 border border-white/5">
<p class="text-[10px] text-on-surface-variant uppercase">Обучаемость</p>
<p class="text-2xl font-headline font-bold text-secondary">A+</p>
</div>
</div>
</div>
<!-- Knowledge Base -->
<div class="bg-surface-container-highest p-6 border border-primary/10">
<span class="material-symbols-outlined text-primary mb-4" data-icon="hub">hub</span>
<h4 class="font-headline font-bold mb-2">База знаний</h4>
<p class="text-xs text-on-surface-variant mb-4">Накоплено 1.4 TB данных из 12 сфер интересов.</p>
<div class="flex flex-wrap gap-2">
<span class="px-2 py-1 bg-surface-container text-[10px] rounded text-primary">Quantum</span>
<span class="px-2 py-1 bg-surface-container text-[10px] rounded text-secondary">Art</span>
<span class="px-2 py-1 bg-surface-container text-[10px] rounded text-on-surface-variant">+9</span>
</div>
</div>
<!-- Real-world Sync -->
<div class="bg-surface-container-low p-6 border border-outline-variant/10 flex flex-col justify-between">
<div>
<h4 class="font-headline font-bold mb-2">Мировая связь</h4>
<p class="text-xs text-on-surface-variant">Активных подключений: 4</p>
</div>
<div class="flex -space-x-2 mt-4">
<div class="w-8 h-8 rounded-full bg-surface-container-highest border border-background flex items-center justify-center">
<span class="material-symbols-outlined text-[16px]">watch</span>
</div>
<div class="w-8 h-8 rounded-full bg-surface-container-highest border border-background flex items-center justify-center">
<span class="material-symbols-outlined text-[16px]">home</span>
</div>
<div class="w-8 h-8 rounded-full bg-surface-container-highest border border-background flex items-center justify-center">
<span class="material-symbols-outlined text-[16px]">directions_car</span>
</div>
</div>
</div>
<!-- Health Status -->
<div class="md:col-span-2 bg-gradient-to-r from-surface-container-low to-surface-container-highest p-6 border border-outline-variant/10 flex items-center justify-between gap-8">
<div class="flex-1">
<h4 class="font-headline font-bold mb-1">Биометрический статус</h4>
<p class="text-xs text-on-surface-variant">Оптимальное состояние. Рекомендация: Повысить уровень гидратации.</p>
</div>
<div class="flex items-center gap-4">
<div class="text-right">
<p class="text-[10px] text-on-surface-variant">PULSE</p>
<p class="text-xl font-headline font-bold text-error">72 BPM</p>
</div>
<div class="w-12 h-12 rounded-full border-2 border-error/20 flex items-center justify-center">
<span class="material-symbols-outlined text-error" data-weight="fill">favorite</span>
</div>
</div>
</div>
</section>
<!-- Asymmetric Section: Experience Timeline -->
<section class="mb-16">
<h2 class="text-2xl font-headline font-bold mb-8 flex items-center gap-4">
<span class="material-symbols-outlined text-secondary">history</span>
                Лог трансформации данных
            </h2>
<div class="relative border-l border-outline-variant/20 ml-4 pl-8 space-y-12">
<div class="relative">
<div class="absolute -left-[41px] top-0 w-4 h-4 rounded-full bg-primary border-4 border-background"></div>
<span class="text-[10px] font-headline text-primary tracking-widest uppercase">Сегодня, 14:20</span>
<h3 class="text-lg font-headline font-bold text-on-surface mt-1">Интеграция новой языковой модели</h3>
<p class="text-sm text-on-surface-variant mt-2 max-w-2xl leading-relaxed">Двойник успешно ассимилировал корпус текстов по квантовой физике. Когнитивный индекс аналитики вырос на 1.2%.</p>
</div>
<div class="relative">
<div class="absolute -left-[41px] top-0 w-4 h-4 rounded-full bg-secondary border-4 border-background"></div>
<span class="text-[10px] font-headline text-secondary tracking-widest uppercase">Вчера, 22:05</span>
<h3 class="text-lg font-headline font-bold text-on-surface mt-1">Синхронизация эмоционального отклика</h3>
<p class="text-sm text-on-surface-variant mt-2 max-w-2xl leading-relaxed">Обновлены паттерны реакции на визуальный контент в категории "Футуристический дизайн".</p>
</div>
<div class="relative">
<div class="absolute -left-[41px] top-0 w-4 h-4 rounded-full bg-outline border-4 border-background"></div>
<span class="text-[10px] font-headline text-on-surface-variant tracking-widest uppercase">12 Октября</span>
<h3 class="text-lg font-headline font-bold text-on-surface mt-1">Первичная инициализация</h3>
<p class="text-sm text-on-surface-variant mt-2 max-w-2xl leading-relaxed">Создание базового слепка личности на основе социальных сетей и личных архивов.</p>
</div>
</div>
</section>
</main>
<!-- BottomNavBar (Mobile only) -->
<nav class="md:hidden fixed bottom-0 left-0 w-full h-20 bg-[#0e0e13]/90 backdrop-blur-lg flex justify-around items-center px-4 pb-safe z-50 border-t border-[#8ff5ff]/10 shadow-[0_-4px_24px_rgba(0,240,255,0.1)] rounded-t-xl">
<a class="flex flex-col items-center justify-center text-[#f9f5fd]/50 hover:text-[#ac89ff] transition-all duration-300 active:scale-90" href="#">
<span class="material-symbols-outlined">hub</span>
<span class="font-['Inter'] text-[10px] font-medium mt-1">Портал</span>
</a>
<a class="flex flex-col items-center justify-center text-[#f9f5fd]/50 hover:text-[#ac89ff] transition-all duration-300 active:scale-90" href="#">
<span class="material-symbols-outlined">grid_view</span>
<span class="font-['Inter'] text-[10px] font-medium mt-1">Темы</span>
</a>
<a class="flex flex-col items-center justify-center text-[#f9f5fd]/50 hover:text-[#ac89ff] transition-all duration-300 active:scale-90" href="#">
<span class="material-symbols-outlined">auto_awesome</span>
<span class="font-['Inter'] text-[10px] font-medium mt-1">Избранное</span>
</a>
<a class="flex flex-col items-center justify-center bg-[#8ff5ff]/10 text-[#8ff5ff] rounded-xl px-4 py-1 transition-all duration-300 active:scale-90" href="#">
<span class="material-symbols-outlined">account_circle</span>
<span class="font-['Inter'] text-[10px] font-medium mt-1">Профиль</span>
</a>
</nav>
</body></html>
