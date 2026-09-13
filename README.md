<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Card of Pokemon - Boutique JCC Pokémon 30 ans</title>
    <!-- Intégration de Tailwind CSS pour un design moderne -->
    <script src="https://tailwindcss.com"></script>
    <style>
        .pokemon-bg {
            background: linear-gradient(135deg, #1a202c 0%, #2d3748 100%);
        }
        .gold-glow {
            box-shadow: 0 0 20px rgba(217, 119, 6, 0.6);
        }
    </style>
</head>
<body class="pokemon-bg text-white font-sans menu-smooth">

    <!-- 1. BANNIÈRE DE BIENVENUE -->
    <header class="bg-red-600 text-white text-center py-8 px-4 shadow-lg border-b-4 border-yellow-400">
        <h1 class="text-4xl md:text-6xl font-extrabold tracking-wide uppercase drop-shadow-md">
            Bienvenue dans Card of Pokemon
        </h1>
        <p class="mt-2 text-yellow-300 text-lg md:text-xl font-medium tracking-wider">
            Votre univers cartes et boosters Pokémon officiels
        </p>
    </header>

    <!-- 2. BARRE DE NAVIGATION -->
    <nav class="bg-gray-900 sticky top-0 z-50 py-4 px-6 flex justify-between items-center border-b border-gray-800">
        <div class="text-2xl font-bold text-yellow-400 tracking-wider">CARD OF POKÉMON</div>
        <div class="space-x-6 text-sm md:text-base font-semibold">
            <a href="#30ans" class="text-yellow-400 hover:text-yellow-300 transition">✨ 30 Ans</a>
            <a href="#boosters" class="hover:text-red-400 transition">Boosters</a>
            <a href="#unite" class="hover:text-red-400 transition">Cartes à l'unité</a>
        </div>
    </nav>

    <main class="max-w-7xl mx-auto px-4 py-12 space-y-20">

        <!-- 3. EN AVANT : EXCLUSIVITÉ 30 ANS (SORTIE LE 16 SEPTEMBRE) -->
        <section id="30ans" class="bg-gradient-to-r from-amber-900/40 via-yellow-900/20 to-amber-900/40 rounded-3xl p-8 md:p-12 border-2 border-yellow-500 gold-glow relative overflow-hidden">
            <div class="absolute top-4 right-4 bg-yellow-500 text-gray-900 font-black px-4 py-2 rounded-full text-xs uppercase tracking-widest animate-pulse">
                Événement
            </div>
            
            <div class="text-center max-w-3xl mx-auto space-y-6">
                <h2 class="text-3xl md:text-5xl font-black text-transparent bg-clip-text bg-gradient-to-r from-yellow-300 via-amber-400 to-yellow-500 uppercase">
                    Packs Anniversaire 30 Ans
                </h2>
                <p class="text-xl md:text-2xl text-gray-200 font-semibold">
                    ⚡ Sortie officielle et expédition le <span class="text-yellow-400 underline decoration-wavy">16 Septembre</span> ⚡
                </p>
                <p class="text-gray-400 max-w-xl mx-auto text-sm md:text-base">
                    Célébrez trois décennies d'histoire Pokémon avec ces coffrets exclusifs en édition ultra-limitée. Sécurisez votre pack dès maintenant !
                </p>
                
                <!-- Liste des produits 30 ans -->
                <div class="grid grid-cols-1 md:grid-cols-2 gap-6 pt-6 text-left">
                    <!-- Produit 1 -->
                    <div class="bg-gray-900/90 p-6 rounded-xl border border-yellow-600/50 flex flex-col justify-between">
                        <div>
                            <div class="h-48 bg-gray-800 rounded-lg flex items-center justify-center text-gray-500 mb-4 border border-dashed border-gray-700">
                                🖼️ [Image Pack Premium 30 Ans]
                            </div>
                            <h3 class="text-xl font-bold text-yellow-400">Coffret Premium Anniversaire 30 Ans</h3>
                            <p class="text-sm text-gray-400 mt-1">Inclus : 10 Boosters spéciaux, 1 carte promo dorée et des accessoires exclusifs.</p>
                        </div>
                        <div class="mt-6 flex justify-between items-center">
                            <span class="text-2xl font-black text-white">Préparez vos précommandes</span>
                            <button class="bg-gradient-to-r from-yellow-500 to-amber-600 text-gray-900 font-bold px-4 py-2 rounded-lg hover:from-yellow-400 hover:to-amber-500 transition shadow-md text-sm">
                                Bientôt disponible
                            </button>
                        </div>
                    </div>

                    <!-- Produit 2 -->
                    <div class="bg-gray-900/90 p-6 rounded-xl border border-yellow-600/50 flex flex-col justify-between">
                        <div>
                            <div class="h-48 bg-gray-800 rounded-lg flex items-center justify-center text-gray-500 mb-4 border border-dashed border-gray-700">
                                🖼️ [Image Pack Duo Booster 30 Ans]
                            </div>
                            <h3 class="text-xl font-bold text-yellow-400">Pack Duo de Boosters Célébration</h3>
                            <p class="text-sm text-gray-400 mt-1">Contient 2 boosters exclusifs de l'extension des 30 ans du JCC.</p>
                        </div>
                        <div class="mt-6 flex justify-between items-center">
                            <span class="text-2xl font-black text-white">Édition Limitée</span>
                            <button class="bg-gradient-to-r from-yellow-500 to-amber-600 text-gray-900 font-bold px-4 py-2 rounded-lg hover:from-yellow-400 hover:to-amber-500 transition shadow-md text-sm">
                                Bientôt disponible
                            </button>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- 4. SECTION BOOSTERS -->
        <section id="boosters" class="space-y-6">
            <div class="border-l-4 border-red-500 pl-4">
                <h2 class="text-3xl font-extrabold uppercase tracking-wide">Nos Boosters Scellés</h2>
                <p class="text-gray-400 text-sm">Agrandissez votre collection avec nos boosters récents et vintage.</p>
            </div>
            
            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-6">
                <!-- Carte Booster 1 -->
                <div class="bg-gray-800 rounded-xl p-5 border border-gray-700 hover:border-red-500 transition flex flex-col justify-between">
                    <div>
                        <div class="h-52 bg-gray-700 rounded-lg flex items-center justify-center text-gray-500 mb-4">🖼️ [Image Booster]</div>
                        <h3 class="text-lg font-bold">Booster Épée et Bouclier</h3>
                        <p class="text-xs text-gray-400 mt-1">Extension officielle en français.</p>
                    </div>
                    <div class="mt-4 flex justify-between items-center">
                        <span class="text-xl font-bold text-red-400">Prix Attractif</span>
                        <button class="bg-red-600 hover:bg-red-500 px-3 py-1.5 rounded-lg text-sm font-semibold transition">Ajouter au panier</button>
                    </div>
                </div>
                <!-- Carte Booster 2 -->
                <div class="bg-gray-800 rounded-xl p-5 border border-gray-700 hover:border-red-500 transition flex flex-col justify-between">
                    <div>
                        <div class="h-52 bg-gray-700 rounded-lg flex items-center justify-center text-gray-500 mb-4">🖼️ [Image Booster]</div>
                        <h3 class="text-lg font-bold">Booster Écarlate et Violet</h3>
                        <p class="text-xs text-gray-400 mt-1">Dernières nouveautés du JCC.</p>
                    </div>
                    <div class="mt-4 flex justify-between items-center">
                        <span class="text-xl font-bold text-red-400">En stock</span>
                        <button class="bg-red-600 hover:bg-red-500 px-3 py-1.5 rounded-lg text-sm font-semibold transition">Ajouter au panier</button>
                    </div>
                </div>
            </div>
        </section>

        <!-- 5. SECTION CARTES À L'UNITÉ -->
        <section id="unite" class="space-y-6">
            <div class="border-l-4 border-blue-500 pl-4">
                <h2 class="text-3xl font-extrabold uppercase tracking-wide">Cartes à l'Unité</h2>
                <p class="text-gray-400 text-sm">Trouvez la perle rare manquante pour compléter vos decks ou collections.</p>
            </div>

            <div class="grid grid-cols-2 md:grid-cols-4 gap-4">
                <!-- Carte Unité 1 -->
                <div class="bg-gray-800 p-4 rounded-xl border border-gray-700 hover:border-blue-500 transition text-center">
                    <div class="h-40 bg-gray-700 rounded-lg flex items-center justify-center text-gray-500 mb-3">🃏 [Image Carte]</div>
                    <h3 class="font-bold text-sm truncate">Dracaufeu Ex</h3>
                    <p class="text-xs text-gray-400">État Neuf (Mint)</p>
                    <button class="w-full mt-3 bg-blue-600 hover:bg-blue-500 py-1 rounded-lg text-xs font-semibold transition">Voir la carte</button>
                </div>
                <!-- Carte Unité 2 -->
                <div class="bg-gray-800 p-4 rounded-xl border border-gray-700 hover:border-blue-500 transition text-center">
                    <div class="h-40 bg-gray-700 rounded-lg flex items-center justify-center text-gray-500 mb-3">🃏 [Image Carte]</div>
                    <h3 class="font-bold text-sm truncate">Pikachu Illustration Rare</h3>
                    <p class="text-xs text-gray-400">État Neuf (Mint)</p>
                    <button class="w-full mt-3 bg-blue-600 hover:bg-blue-500 py-1 rounded-lg text-xs font-semibold transition">Voir la carte</button>
                </div>
            </div>
        </section>

    </main>

    <!-- FOOTER -->
