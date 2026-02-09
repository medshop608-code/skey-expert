<!DOCTYPE html>
<html class="dark" lang="en"><head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<title>Sky Expert - Service Marketplace</title>
<script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<script id="tailwind-config">
        tailwind.config = {
            darkMode: "class",
            theme: {
                extend: {
                    colors: {
                        "primary": "#136dec",
                        "accent-blue": "#3b82f6",
                        "light-blue": "#60a5fa",
                        "gold": "#FFD700",
                        "background-dark": "#0A0F14",
                        "card-dark": "#161D26",
                    },
                    fontFamily: {
                        "display": ["Inter"]
                    },
                    borderRadius: {
                        "DEFAULT": "0.25rem",
                        "lg": "0.5rem",
                        "xl": "1rem",
                        "2xl": "1.5rem",
                        "full": "9999px"
                    },
                },
            },
        }
    </script>
<style type="text/tailwindcss">
        @layer base {
            body { font-family: 'Inter', sans-serif; }
        }
        .hide-scrollbar::-webkit-scrollbar { display: none; }
        .hide-scrollbar { -ms-overflow-style: none; scrollbar-width: none; }
        .gradient-btn {
            background: linear-gradient(135deg, #136dec 0%, #60a5fa 100%);
        }
        .card-overlay {
            background: linear-gradient(to top, rgba(10, 15, 20, 0.95) 0%, rgba(10, 15, 20, 0.4) 50%, transparent 100%);
        }
    </style>
<style>
    body {
      min-height: max(884px, 100dvh);
    }
  </style>
  </head>
<body class="bg-background-dark font-display text-slate-100">
<div class="relative flex h-auto min-h-screen w-full flex-col bg-background-dark overflow-x-hidden pb-24">
<div class="sticky top-0 z-50 bg-background-dark/80 backdrop-blur-xl border-b border-slate-800/50">
<div class="flex items-center p-4 pb-2 justify-between">
<button class="text-slate-100 flex size-10 shrink-0 items-center justify-center">
<span class="material-symbols-outlined text-2xl">chevron_left</span>
</button>
<h2 class="text-lg font-semibold leading-tight tracking-tight flex-1 text-center">Service Marketplace</h2>
<div class="flex w-10 items-center justify-end">
<button class="flex items-center justify-center text-slate-100">
<span class="material-symbols-outlined">notifications</span>
</button>
</div>
</div>
<div class="px-4 py-3">
<div class="flex w-full items-stretch rounded-2xl h-12 bg-card-dark border border-slate-700/50 shadow-lg">
<div class="text-slate-400 flex items-center justify-center pl-4">
<span class="material-symbols-outlined text-xl">search</span>
</div>
<input class="w-full bg-transparent border-none text-white focus:ring-0 placeholder:text-slate-500 px-4 pl-2 text-base" placeholder="Search elite services..."/>
</div>
</div>
<div class="flex gap-3 px-4 pb-4 overflow-x-auto hide-scrollbar">
<button class="flex h-10 shrink-0 items-center justify-center gap-x-2 rounded-full bg-primary px-6 shadow-lg shadow-primary/20">
<p class="text-white text-sm font-bold">All</p>
</button>
<button class="flex h-10 shrink-0 items-center justify-center gap-x-2 rounded-full bg-card-dark px-5 border border-slate-700/50">
<span class="material-symbols-outlined text-lg text-slate-400">auto_towing</span>
<p class="text-slate-300 text-sm font-medium">Towing</p>
</button>
<button class="flex h-10 shrink-0 items-center justify-center gap-x-2 rounded-full bg-card-dark px-5 border border-slate-700/50">
<span class="material-symbols-outlined text-lg text-slate-400">auto_fix</span>
<p class="text-slate-300 text-sm font-medium">Detailing</p>
</button>
<button class="flex h-10 shrink-0 items-center justify-center gap-x-2 rounded-full bg-card-dark px-5 border border-slate-700/50">
<span class="material-symbols-outlined text-lg text-slate-400">build</span>
<p class="text-slate-300 text-sm font-medium">Maintenance</p>
</button>
</div>
</div>
<div class="px-4 pt-6">
<div class="flex items-center justify-between mb-4">
<h3 class="text-lg font-bold">Recommended for You</h3>
<span class="text-accent-blue text-sm font-semibold">View All</span>
</div>
<div class="grid grid-cols-2 gap-4">
<div class="group relative flex flex-col bg-card-dark rounded-2xl overflow-hidden border border-slate-800/50 shadow-2xl">
<div class="relative w-full aspect-[1/1.1] bg-center bg-no-repeat bg-cover" style='background-image: url("https://lh3.googleusercontent.com/aida-public/AB6AXuAAbhq5nBDHt02FnCGk5NqER7B_7MYNdtBQNyG7iD5HrvWKZ5l2IMbyvtixWH21OFahiy41yOWvVn_3Fx4ZZ9vq608ONAhxsx2Nx70BL3fPxOxFOIzO4hKkBrXPCHJBkRnAsbrJL3334na7uLn8Lxn_9JM_2AMIedM55ymVM-dddm9MEWonom5bBFAfbQ6PfIRTgo91xWgOGeGXNLDDagMImoHqtArUIfROkAj_4FjQs-5eRL3JqGFH89Tb2Ok_tBaxquiXgS-IjaM");'>
<div class="absolute inset-0 card-overlay"></div>
<div class="absolute top-2 right-2 bg-black/60 px-2 py-1 rounded-lg backdrop-blur-md border border-white/10">
<div class="flex items-center gap-1">
<span class="material-symbols-outlined text-gold text-xs" style="font-variation-settings: 'FILL' 1">star</span>
<span class="text-[11px] font-bold text-gold">4.9</span>
</div>
</div>
<div class="absolute bottom-0 left-0 p-3 w-full">
<h4 class="text-sm font-bold text-white line-clamp-1">Ceramic Pro Coating</h4>
<p class="text-[10px] text-slate-400 mt-0.5">Paint Protection</p>
<div class="mt-3 flex items-center justify-between gap-2">
<span class="text-white font-bold text-xs">$299</span>
<button class="gradient-btn text-white text-[10px] font-black px-3 py-2 rounded-lg uppercase tracking-wider shadow-lg shadow-primary/20">Book Now</button>
</div>
</div>
</div>
</div>
<div class="group relative flex flex-col bg-card-dark rounded-2xl overflow-hidden border border-slate-800/50 shadow-2xl">
<div class="relative w-full aspect-[1/1.1] bg-center bg-no-repeat bg-cover" style='background-image: url("https://lh3.googleusercontent.com/aida-public/AB6AXuDNU1Ve6lrxK484pIba6ltSd6Q-WTvU4-Cl6ef0vlOh1ODCBABeHnwLrbLMuVtID4adTSNMvU_EfNULC_2rYTWfrcvJxjD42yCf-ZcAu_Q8xHf6g8R48u0HNdfqdUwzUjb-UcqzXAV3B-ObnWhPTrCy4q074sWztBqxSSq4QbD099d7nGqDLEjNZIUoTppY85xrBjNKyAnQtD6v8Qth_ZwJZyjSy6erxpPABqYLIfJEfJ9QS1fRxmSnFbVmlHmktFNhi-2sTGgzadg");'>
<div class="absolute inset-0 card-overlay"></div>
<div class="absolute top-2 right-2 bg-black/60 px-2 py-1 rounded-lg backdrop-blur-md border border-white/10">
<div class="flex items-center gap-1">
<span class="material-symbols-outlined text-gold text-xs" style="font-variation-settings: 'FILL' 1">star</span>
<span class="text-[11px] font-bold text-gold">5.0</span>
</div>
</div>
<div class="absolute bottom-0 left-0 p-3 w-full">
<h4 class="text-sm font-bold text-white line-clamp-1">V8 Engine Tune-up</h4>
<p class="text-[10px] text-slate-400 mt-0.5">Performance Check</p>
<div class="mt-3 flex items-center justify-between gap-2">
<span class="text-white font-bold text-xs">$150</span>
<button class="gradient-btn text-white text-[10px] font-black px-3 py-2 rounded-lg uppercase tracking-wider shadow-lg shadow-primary/20">Book Now</button>
</div>
</div>
</div>
</div>
<div class="group relative flex flex-col bg-card-dark rounded-2xl overflow-hidden border border-slate-800/50 shadow-2xl">
<div class="relative w-full aspect-[1/1.1] bg-center bg-no-repeat bg-cover" style='background-image: url("https://lh3.googleusercontent.com/aida-public/AB6AXuASzJML86bU9Tfh17ugLFfIOh6ZGa5odj13wUzPZ8_7MebMFoeJFQNemPc87wmRRGQ4FpRWAkORsEErjHWrq6vFbwin80pHvW_-KkV6meeFeYwdhKoTkHuIdejFWujg85MIeijW8K5nidNWn0kqCgHKZWKI7JdskY_oUSU87LTlcGw1sRFJY5vW9vnGIXsx3npFn46lRvZ8EhWEkPaeyMUCumRsU9ggOjGQjc-EOU3gN1SninwHR-P9-AbaH8kIbvMhlD19Tuc4-7I");'>
<div class="absolute inset-0 card-overlay"></div>
<div class="absolute top-2 right-2 bg-black/60 px-2 py-1 rounded-lg backdrop-blur-md border border-white/10">
<div class="flex items-center gap-1">
<span class="material-symbols-outlined text-gold text-xs" style="font-variation-settings: 'FILL' 1">star</span>
<span class="text-[11px] font-bold text-gold">4.8</span>
</div>
</div>
<div class="absolute bottom-0 left-0 p-3 w-full">
<h4 class="text-sm font-bold text-white line-clamp-1">Elite Towing</h4>
<p class="text-[10px] text-slate-400 mt-0.5">Flatbed Service</p>
<div class="mt-3 flex items-center justify-between gap-2">
<span class="text-white font-bold text-xs">$85</span>
<button class="gradient-btn text-white text-[10px] font-black px-3 py-2 rounded-lg uppercase tracking-wider shadow-lg shadow-primary/20">Book Now</button>
</div>
</div>
</div>
</div>
<div class="group relative flex flex-col bg-card-dark rounded-2xl overflow-hidden border border-slate-800/50 shadow-2xl">
<div class="relative w-full aspect-[1/1.1] bg-center bg-no-repeat bg-cover" style='background-image: url("https://lh3.googleusercontent.com/aida-public/AB6AXuC--hjSo_S0AkcMhuwfIHpbRGKOxEM4hgGt9ZByT0SsVuel-SWZAAKH2KEsrqF-E7HVp4XkUNA2thZHcozRiO9hq6TRpQ7E3khn3n6EDLCBY5jsE1p-2rTn4lnZwDNTCqGRzbTYWVx2L-txNiC8v_lO9jufuWnuyxY4fFJBw6eYI_Eoi3ItbJocNj3Cf-ielIXrp2BuHmDrZ0jv6LVpy74dkr6LPd6Totqh283zD4EXeO6pc2xPWKrLOodgLGL1q2z8J5Gb9Jk5nRA");'>
<div class="absolute inset-0 card-overlay"></div>
<div class="absolute top-2 right-2 bg-black/60 px-2 py-1 rounded-lg backdrop-blur-md border border-white/10">
<div class="flex items-center gap-1">
<span class="material-symbols-outlined text-gold text-xs" style="font-variation-settings: 'FILL' 1">star</span>
<span class="text-[11px] font-bold text-gold">4.7</span>
</div>
</div>
<div class="absolute bottom-0 left-0 p-3 w-full">
<h4 class="text-sm font-bold text-white line-clamp-1">Interior Care</h4>
<p class="text-[10px] text-slate-400 mt-0.5">Leather Restoration</p>
<div class="mt-3 flex items-center justify-between gap-2">
<span class="text-white font-bold text-xs">$120</span>
<button class="gradient-btn text-white text-[10px] font-black px-3 py-2 rounded-lg uppercase tracking-wider shadow-lg shadow-primary/20">Book Now</button>
</div>
</div>
</div>
</div>
</div>
</div>
<div class="px-4 py-8">
<div class="bg-gradient-to-br from-card-dark to-slate-900 rounded-2xl p-5 flex items-center gap-4 border border-slate-700/50">
<div class="bg-primary/20 text-accent-blue p-3 rounded-2xl">
<span class="material-symbols-outlined text-3xl">verified</span>
</div>
<div>
<h5 class="text-sm font-bold text-white">Sky Expert Guarantee</h5>
<p class="text-xs text-slate-400 leading-relaxed mt-1">Insured, background-checked, and highly rated automotive specialists.</p>
</div>
</div>
</div>
<div class="px-4">
<div class="flex items-center justify-between mb-4">
<h3 class="text-lg font-bold">Popular Categories</h3>
<span class="text-accent-blue text-sm font-semibold">View All</span>
</div>
<div class="flex flex-col gap-4">
<div class="flex items-center gap-4 bg-card-dark p-3 rounded-2xl border border-slate-800/50">
<div class="size-16 rounded-xl bg-cover bg-center shrink-0 border border-slate-700/30" style='background-image: url("https://lh3.googleusercontent.com/aida-public/AB6AXuCk_kWXXFa5bwR-YbCxcZuhiH971w_jTw7RScWgGEqT1r-lmo9B9N4JHHcQujoSxoD7u8WVM3d3lE_nrBuWD8M47sXasYm54T_rTJwQ7ayqplv622APYekm4CbE8IcB3YeHDRI5s3j6xNaIIJA1_BwQO8DjLnYqvVt7WRcNuDrtI_i24XEygVAQqwosEgf4ZhDoslLL-S_p-Nwp_xt0KxApzJizDnd82nwKv_WJAV-sdnk-TNIoQX3GM8YAK5h8gKhjJBgEUX5Em-8");'></div>
<div class="flex-1">
<h4 class="text-sm font-bold">Brake Inspection</h4>
<p class="text-[11px] text-slate-500">Expert safety check</p>
<div class="flex items-center gap-1 mt-1.5">
<span class="material-symbols-outlined text-gold text-[12px]" style="font-variation-settings: 'FILL' 1">star</span>
<span class="text-[10px] font-semibold text-gold">4.9</span>
<span class="text-[10px] text-slate-500 ml-1">(1.2k)</span>
</div>
</div>
<div class="text-right">
<p class="text-sm font-bold text-white mb-2">$45</p>
<button class="gradient-btn text-white text-[9px] font-black px-3 py-1.5 rounded-lg uppercase tracking-tighter">Book</button>
</div>
</div>
<div class="flex items-center gap-4 bg-card-dark p-3 rounded-2xl border border-slate-800/50">
<div class="size-16 rounded-xl bg-cover bg-center shrink-0 border border-slate-700/30" style='background-image: url("https://lh3.googleusercontent.com/aida-public/AB6AXuBEJq_UAabdRPqpWdpgUG9cPa6CG7a4_7C2ACTVXiKeJENShaA1END83yeDZSUvz4dKUUwFmEcxUbU1AvYDXoFUuPfiogBboA-M6BpCVRaWpcmWl-ulCnmZVa_-wQb1Fic2oSAqfbf7EamNuCWQOZzMLyl6yuS5v6cIJw4ftYOB2gmUVa5uIiMBpQBwwm4iLV5Uz3dKWIn6gn1AsSpc5Hwm4yMFpqxtHI_gIVFUIGrZWyGYPXYj2BtkfsdEPnlvNrC-hQJe2Qo1fGk");'></div>
<div class="flex-1">
<h4 class="text-sm font-bold">Showroom Polishing</h4>
<p class="text-[11px] text-slate-500">Mirror finish detail</p>
<div class="flex items-center gap-1 mt-1.5">
<span class="material-symbols-outlined text-gold text-[12px]" style="font-variation-settings: 'FILL' 1">star</span>
<span class="text-[10px] font-semibold text-gold">5.0</span>
<span class="text-[10px] text-slate-500 ml-1">(850)</span>
</div>
</div>
<div class="text-right">
<p class="text-sm font-bold text-white mb-2">$180</p>
<button class="gradient-btn text-white text-[9px] font-black px-3 py-1.5 rounded-lg uppercase tracking-tighter">Book</button>
</div>
</div>
</div>
</div>
<div class="fixed bottom-0 left-0 right-0 bg-background-dark/90 backdrop-blur-2xl border-t border-slate-800/50 px-8 pt-3 pb-8 flex justify-between items-center z-[100]">
<div class="flex flex-col items-center gap-1.5">
<span class="material-symbols-outlined text-slate-500">home</span>
<span class="text-[10px] font-medium text-slate-500">Home</span>
</div>
<div class="flex flex-col items-center gap-1.5">
<div class="relative">
<span class="material-symbols-outlined text-accent-blue" style="font-variation-settings: 'FILL' 1">storefront</span>
<div class="absolute -top-1 -right-1 size-1.5 bg-accent-blue rounded-full"></div>
</div>
<span class="text-[10px] font-bold text-accent-blue">Market</span>
</div>
<div class="flex flex-col items-center gap-1.5">
<span class="material-symbols-outlined text-slate-500">event_note</span>
<span class="text-[10px] font-medium text-slate-500">Bookings</span>
</div>
<div class="flex flex-col items-center gap-1.5">
<span class="material-symbols-outlined text-slate-500">person</span>
<span class="text-[10px] font-medium text-slate-500">Profile</span>
</div>
</div>
<div class="fixed bottom-1.5 left-1/2 -translate-x-1/2 w-32 h-1 bg-white/20 rounded-full z-[101]"></div>
</div>

</body></html>
