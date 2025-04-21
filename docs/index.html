<!DOCTYPE html>
<html lang="sk">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Krvavý Dobšinský - Podcast</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;700&display=swap" rel="stylesheet">
    <style>
        /* Vlastné farby (Custom Colors) */
        .bg-custom-bg { background-color: #C5B38C; }
        .text-custom-header-text { color: #F5F5F5; }
        .bg-custom-nav { background-color: #A88F66; }
        .bg-custom-card { background-color: #A88F66; }
        .text-custom-gold { color: #E4C266; }
        .border-custom-gold { border-color: #E4C266; }
        .text-custom-dark { color: #1B1B1B; }
        .bg-custom-dark { background-color: #1B1B1B; }
        .text-custom-date { color: #9A7A50; }
        .fill-custom-gold { fill: #E4C266; }
        .fill-custom-dark { fill: #1B1B1B; }

        /* Základné štýly tela a kontajnera (Basic body and container styles) */
        body {
            font-family: 'Poppins', sans-serif;
            display: flex;
            flex-direction: column;
            min-height: 100vh; /* Ensure footer sticks to bottom */
        }
        .container {
            flex-grow: 1; /* Allow main content to grow */
        }

        /* Štýly pre textové elementy & Hover efekty (Styles for text elements & Hover effects) */
        .header-title {
            font-size: 2.25rem; /* 36px */
            font-weight: 700;
            transition: color 0.3s ease;
            cursor: default; /* Indicate non-clickable */
            position: relative; /* Ensure text is above decorative elements */
            z-index: 1;
        }
        .header-subtitle {
            font-size: 1.125rem; /* 18px */
            position: relative; /* Ensure text is above decorative elements */
            z-index: 1;
         }
        .nav-link { font-size: 0.875rem; /* 14px */ cursor: pointer; }

        .section-title {
            font-size: 1.5rem; /* 24px */
            font-weight: 700;
            transition: color 0.3s ease;
            cursor: pointer; /* Indicate clickable for potential future features */
        }
        .section-title:hover { color: #E4C266; /* text-custom-gold */ }

        .episode-title { /* Player episode title */
            font-size: 1.25rem; /* 20px */
            font-weight: 700;
            transition: color 0.3s ease;
            cursor: pointer; /* Indicate clickable for potential future features */
        }
        .episode-title:hover { color: #1B1B1B; /* text-custom-dark */ }

        .episode-date { font-size: 0.75rem; /* 12px */ }
        .episode-desc { font-size: 0.875rem; /* 14px */ }
        .footer-text { font-size: 0.75rem; /* 12px */ }

        .card-episode-title, .card-text-title { /* Grid titles */
            font-size: 1rem; /* 16px */
            font-weight: 700;
            transition: color 0.3s ease;
            cursor: pointer; /* Indicate clickable for potential future features */
        }
        .card-episode-title:hover, .card-text-title:hover {
             color: #1B1B1B; /* text-custom-dark */
        }

        .card-episode-desc { font-size: 0.75rem; /* 12px */ }
        .card-text-excerpt { font-size: 0.875rem; /* 14px */ }
        .subscribe-text { font-size: 0.875rem; /* 14px */ line-height: 1.625; }

        /* Indikátor sekcie (Section indicator) */
        .section-indicator::before {
            content: '';
            display: block;
            width: 4px;
            height: 2.5rem; /* 40px */
            background-color: #E4C266; /* custom-gold */
            position: absolute;
            left: 0;
            top: 0;
        }

        /* Načítavanie (Loading placeholder) */
        .loading-placeholder {
            background-color: rgba(122, 27, 26, 0.5); /* Semi-transparent dark red */
            border-radius: 6px;
            animation: pulse 2s cubic-bezier(0.4, 0, 0.6, 1) infinite;
            display: flex;
            align-items: center;
            justify-content: center;
            color: #F5F5F5; /* custom-header-text */
            text-align: center;
            font-size: 0.875rem; /* 14px */
        }
        @keyframes pulse { 0%, 100% { opacity: 1; } 50% { opacity: .5; } }

        /* Audio prehrávač (Audio player) */
        audio {
            width: 100%;
            margin-top: 10px;
            height: 35px; /* Consistent height */
        }

        /* Skrytie/zobrazenie placeholderov a views (Hide/show placeholders and views) */
        .loaded .loading-placeholder { display: none; }
        .loaded .content-placeholder { display: block; } /* Show content once loaded */
        .content-placeholder { display: none; } /* Hide content initially */

        /* Placeholder text for empty grids */
        #all-episodes-grid:empty::before,
        #texts-grid:empty::before {
            content: 'Načítavam obsah...'; /* Loading content... */
            display: block;
            text-align: center;
            padding: 2rem; /* 32px */
            color: #1B1B1B; /* custom-dark */
        }

        /* View visibility */
        .view { display: none; }
        .view.active { display: block; }


        /* Štýl pre tlačidlá (Button styles) */
        .play-button, .read-more-button, .subscribe-button, .show-more-button {
             background-color: rgba(27, 27, 27, 0.1); /* Light dark overlay */
             border-radius: 0.375rem; /* 6px */
             height: 35px; /* Consistent height */
             display: inline-flex;
             align-items: center;
             justify-content: center;
             font-size: 0.875rem; /* 14px */
             font-weight: 700;
             color: #1B1B1B; /* custom-dark */
             margin-top: 0.5rem; /* 8px */
             padding: 0 1.5rem; /* 0 24px */
             cursor: pointer;
             border: none;
             min-width: 150px; /* Ensure decent width */
             text-decoration: none; /* For anchor tags styled as buttons */
             /* Added shadows and transitions */
             box-shadow: 0 1px 2px 0 rgba(0, 0, 0, 0.05); /* shadow-sm */
             transition: background-color 0.2s ease, box-shadow 0.2s ease;
        }
        .play-button:hover, .read-more-button:hover, .subscribe-button:hover, .show-more-button:hover {
            background-color: rgba(27, 27, 27, 0.2); /* Darker overlay on hover */
            box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.1), 0 2px 4px -1px rgba(0, 0, 0, 0.06); /* shadow-md */
        }
        /* Style SVGs inside buttons */
        .play-button svg, .read-more-button svg, .subscribe-button svg, .show-more-button svg {
            width: 1em;
            height: 1em;
            margin-right: 0.5em; /* 8px */
            fill: currentColor;
        }
        /* Focus styles for accessibility */
         .play-button:focus, .read-more-button:focus, .subscribe-button:focus, .form-button:focus, .header-button:focus, .show-more-button:focus {
            outline: none;
            box-shadow: 0 0 0 3px rgba(228, 194, 102, 0.4); /* custom-gold focus ring */
         }
         /* Specific focus for header buttons due to dark background */
         .header-button:focus {
             box-shadow: 0 0 0 3px rgba(255, 255, 255, 0.5); /* white focus ring */
         }


        /* Štýly pre formulár (Form styles) */
        .form-label {
            display: block;
            margin-bottom: 0.5rem; /* 8px */
            font-size: 0.875rem; /* 14px */
            color: #1B1B1B; /* custom-dark */
        }
        .form-input, .form-textarea {
            width: 100%;
            padding: 0.75rem; /* 12px */
            border: 1px solid rgba(27, 27, 27, 0.2); /* Subtle border */
            border-radius: 0.375rem; /* 6px */
            background-color: rgba(245, 245, 245, 0.1); /* Very light background */
            color: #1B1B1B; /* custom-dark */
            margin-bottom: 1rem; /* 16px */
            font-size: 0.875rem; /* 14px */
            box-shadow: inset 0 1px 2px rgba(0,0,0,0.07); /* Subtle inner shadow */
            transition: border-color 0.2s ease, box-shadow 0.2s ease;
        }
        .form-input:focus, .form-textarea:focus {
            outline: none;
            border-color: #E4C266; /* custom-gold */
            /* Keep existing focus shadow for input border */
            box-shadow: 0 0 0 2px rgba(228, 194, 102, 0.3), inset 0 1px 2px rgba(0,0,0,0.07);
        }
        .form-textarea {
            min-height: 150px;
            resize: vertical; /* Allow vertical resize only */
        }
        .form-button {
            background-color: #7A1B1A; /* Dark red from header gradient */
            color: #F5F5F5; /* custom-header-text */
            padding: 0.75rem 1.5rem; /* 12px 24px */
            border: none;
            border-radius: 0.375rem; /* 6px */
            font-size: 0.875rem; /* 14px */
            font-weight: 700;
            cursor: pointer;
             /* Added shadows and transitions */
            box-shadow: 0 1px 3px 0 rgba(0, 0, 0, 0.1), 0 1px 2px 0 rgba(0, 0, 0, 0.06); /* shadow */
            transition: background-color 0.2s ease, box-shadow 0.2s ease;
        }
        .form-button:hover {
            background-color: #9a2b2a; /* Slightly lighter red on hover */
            box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.1), 0 2px 4px -1px rgba(0, 0, 0, 0.06); /* shadow-md */
        }
        .form-note {
            font-size: 0.75rem; /* 12px */
            color: #9A7A50; /* custom-date */
            margin-left: 0.5rem; /* 8px */
        }

        /* Štýly pre text v O podcaste (Styles for text in About section) */
        .about-text p {
             margin-bottom: 1rem; /* 16px */
             line-height: 1.625; /* More spacing for readability */
             color: #1B1B1B; /* custom-dark */
        }

        /* Card hover effect */
        .hoverable-card {
            transition: transform 0.2s ease-out, box-shadow 0.2s ease-out;
        }
        .hoverable-card:hover {
             transform: translateY(-3px); /* Slight lift effect */
             box-shadow: 0 10px 15px -3px rgba(0, 0, 0, 0.1), 0 4px 6px -2px rgba(0, 0, 0, 0.05); /* shadow-lg */
        }

        /* Twinkle animation for stars */
        @keyframes twinkle {
          0%, 100% { opacity: 0.2; } /* Start/end subtle */
          50% { opacity: 0.5; } /* Brighter mid-animation */
        }
        .animate-twinkle {
          /* Apply animation: name duration timing-function iteration-count */
          animation: twinkle 4s linear infinite;
        }
        /* Helper class for animation delay */
        .animation-delay-700 {
            animation-delay: 0.7s;
        }
         .animation-delay-1400 {
            animation-delay: 1.4s;
        }


    </style>
</head>
<body class="bg-custom-bg text-custom-dark">

    <div class="container mx-auto max-w-4xl">
        <header class="relative overflow-hidden bg-gradient-to-b from-[#7A1B1A] to-[#5A0000] text-custom-header-text text-center py-16 h-auto min-h-[300px] flex flex-col justify-center items-center shadow-lg px-4">
            <div class="absolute inset-0 z-0 pointer-events-none" aria-hidden="true">
                <svg class="absolute top-[15%] left-[10%] w-8 h-8 text-custom-header-text opacity-30 transform -rotate-12" xmlns="http://www.w3.org/2000/svg" fill="currentColor" viewBox="0 0 16 16">
                     <circle cx="8" cy="8" r="7.5"/>
                </svg>
                <svg class="absolute bottom-[10%] right-[12%] w-10 h-10 opacity-40 transform rotate-[25deg]" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16">
                    <path d="M1 8 C 4 2, 12 2, 15 8 C 12 14, 4 14, 1 8 Z" fill="#E4C266"/>
                    <rect x="7.5" y="4" width="1" height="8" fill="#1B1B1B"/>
                </svg>
                <svg class="absolute top-[20%] right-[15%] w-4 h-4 text-custom-header-text opacity-40 animate-twinkle" xmlns="http://www.w3.org/2000/svg" fill="currentColor" viewBox="0 0 16 16">
                    <path d="M3.612 15.443c-.386.198-.824-.149-.746-.592l.83-4.73L.173 6.765c-.329-.314-.158-.888.283-.95l4.898-.696L7.538.792c.197-.39.73-.39.927 0l2.184 4.327 4.898.696c.441.062.612.636.282.95l-3.522 3.356.83 4.73c.078.443-.36.79-.746.592L8 13.187l-4.389 2.256z"/>
                </svg>
                <svg class="absolute bottom-[25%] left-[20%] w-5 h-5 text-custom-header-text opacity-30 animate-twinkle animation-delay-700" xmlns="http://www.w3.org/2000/svg" fill="currentColor" viewBox="0 0 16 16">
                     <path d="M3.612 15.443c-.386.198-.824-.149-.746-.592l.83-4.73L.173 6.765c-.329-.314-.158-.888.283-.95l4.898-.696L7.538.792c.197-.39.73-.39.927 0l2.184 4.327 4.898.696c.441.062.612.636.282.95l-3.522 3.356.83 4.73c.078.443-.36.79-.746.592L8 13.187l-4.389 2.256z"/>
                </svg>
                 <svg class="absolute top-[55%] left-[5%] w-3 h-3 text-custom-header-text opacity-30 transform rotate-[-15deg]" xmlns="http://www.w3.org/2000/svg" fill="currentColor" viewBox="0 0 16 16">
                    <path d="M3.612 15.443c-.386.198-.824-.149-.746-.592l.83-4.73L.173 6.765c-.329-.314-.158-.888.283-.95l4.898-.696L7.538.792c.197-.39.73-.39.927 0l2.184 4.327 4.898.696c.441.062.612.636.282.95l-3.522 3.356.83 4.73c.078.443-.36.79-.746.592L8 13.187l-4.389 2.256z"/>
                </svg>
                 <svg class="absolute top-[65%] right-[30%] w-4 h-4 text-custom-header-text opacity-40 transform rotate-6 animate-twinkle animation-delay-1400" xmlns="http://www.w3.org/2000/svg" fill="currentColor" viewBox="0 0 16 16">
                    <path d="M3.612 15.443c-.386.198-.824-.149-.746-.592l.83-4.73L.173 6.765c-.329-.314-.158-.888.283-.95l4.898-.696L7.538.792c.197-.39.73-.39.927 0l2.184 4.327 4.898.696c.441.062.612.636.282.95l-3.522 3.356.83 4.73c.078.443-.36.79-.746.592L8 13.187l-4.389 2.256z"/>
                </svg>
            </div>

            <h1 class="header-title relative z-10">Krvavý Dobšinský</h1>
            <p class="header-subtitle mt-2 relative z-10">Mrazivé príbehy, ktoré vám nedajú spať.</p>
            <div class="mt-8 flex flex-wrap justify-center items-center gap-4 relative z-10">
                <a onclick="showView('subscribe')"
                   class="header-button inline-flex items-center justify-center bg-white bg-opacity-20 hover:bg-opacity-30 text-white font-semibold py-2 px-5 rounded-lg shadow-md transition duration-200 ease-in-out cursor-pointer"
                   aria-label="Prejsť na sekciu Odoberať">
                   Odoberať podcast
                </a>
                <a onclick="showView('contact')"
                   class="header-button inline-flex items-center justify-center bg-white bg-opacity-20 hover:bg-opacity-30 text-white font-semibold py-2 px-5 rounded-lg shadow-md transition duration-200 ease-in-out cursor-pointer"
                   aria-label="Prejsť na sekciu Kontakt">
                   Kontakt
                </a>
            </div>
        </header>

        <nav id="main-nav" class="bg-custom-nav bg-opacity-90 h-[50px] flex items-center justify-center space-x-6 md:space-x-8 lg:space-x-12 sticky top-0 z-10 text-sm shadow-md rounded-b-xl">
            <a onclick="showView('home', '#latest')" class="nav-link text-custom-header-text hover:text-custom-gold transition-colors">Najnovšia epizóda</a>
            <a onclick="showView('home', '#all')" class="nav-link text-custom-header-text hover:text-custom-gold transition-colors">Všetky Epizódy</a>
            <a onclick="showView('about')" class="nav-link text-custom-header-text hover:text-custom-gold transition-colors">O podcaste</a>
            <a onclick="showView('subscribe')" class="nav-link text-custom-header-text hover:text-custom-gold transition-colors">Odoberať</a>
            <a onclick="showView('texts')" class="nav-link text-custom-header-text hover:text-custom-gold transition-colors">Texty</a>
            <a onclick="showView('contact')" class="nav-link text-custom-header-text hover:text-custom-gold transition-colors">Kontakt</a>
        </nav>

        <main class="px-4 md:px-8 lg:px-12 py-8">

            <div id="home-view" class="view active">
                <section id="latest" class="mb-12 scroll-mt-20">
                    <div class="relative pl-5 mb-5 h-[40px] flex items-center section-indicator">
                        <h2 class="section-title">Prehrávač</h2> </div>
                    <article id="latest-episode-card" class="bg-custom-card rounded-lg p-6 flex flex-col md:flex-row items-center md:items-start space-y-4 md:space-y-0 md:space-x-6 min-h-[220px] shadow-lg">
                        <div class="w-[180px] h-[180px] rounded-md flex-shrink-0 loading-placeholder">Načítavam obrázok...</div> <img id="latest-episode-image" src="" alt="Obrázok prehrávanej epizódy" class="w-[180px] h-[180px] rounded-md flex-shrink-0 object-cover content-placeholder shadow-md" onerror="this.onerror=null; this.src='https://i.imgur.com/F9fKCIr.png';"> <div class="flex-grow">
                            <h3 id="latest-episode-title" class="episode-title text-custom-gold">Načítavam názov...</h3> <p id="latest-episode-date" class="episode-date text-custom-date mb-2">Načítavam dátum...</p> <p id="latest-episode-description" class="episode-desc text-custom-dark leading-relaxed mb-4">Načítavam popis...</p> <div class="bg-black bg-opacity-10 rounded-md p-2 flex items-center space-x-3 h-[35px] loading-placeholder">Načítavam prehrávač...</div> <audio id="latest-episode-audio" controls class="content-placeholder" src="">Váš prehliadač nepodporuje audio element.</audio> </div>
                    </article>
                    <p id="rss-error" class="text-red-700 mt-4" style="display: none;">Nepodarilo sa načítať RSS feed.</p> </section>

                <hr class="border-t border-custom-gold border-opacity-60 my-8 w-3/4 mx-auto">

                <section id="all" class="mb-12 scroll-mt-20">
                     <div class="relative pl-5 mb-5 h-[40px] flex items-center section-indicator">
                         <h2 class="section-title">Všetky Epizódy</h2> </div>
                     <div id="all-episodes-grid" class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-6">
                         <div class="loading-placeholder col-span-full h-24">Načítavam epizódy...</div> </div>
                     <div id="show-more-container" class="text-center mt-6" style="display: none;">
                         <button id="show-more-button" class="show-more-button w-full sm:w-auto">
                             Zobraziť viac
                         </button>
                     </div>
                     <p id="all-episodes-error" class="text-red-700 mt-4" style="display: none;">Nepodarilo sa načítať epizódy.</p> </section>

            </div> <div id="about-view" class="view">
                <div class="relative pl-5 mb-5 h-[40px] flex items-center section-indicator">
                    <h2 class="section-title">O podcaste</h2> </div>
                <div class="bg-custom-card rounded-lg p-6 md:p-8 overflow-hidden shadow-lg">
                    <img src="https://i.imgur.com/F9fKCIr.png"
                         alt="Logo podcastu Krvavý Dobšinský"
                         class="w-32 h-32 md:w-40 md:h-40 rounded-md flex-shrink-0 object-cover mb-4 mr-6 md:mr-8 shadow-md float-left"
                         onerror="this.style.display='none'"> <div class="about-text text-left">
                        <p>Krvavý Dobšinský je originálny slovenský podcast plný strachu, symboliky a temnej krásy rozprávania. Už niekoľko rokov píšem a nahrávam vlastné strašidelné príbehy, ktoré čerpajú z folklóru, snov, tieňov aj z toho, čo si so sebou nesieme z detstva. Každá epizóda je napísaná autorsky – od prvého slova až po posledný dozvuk.</p>
                        <p>Tento podcast vznikol ako osobný projekt. Bez plánov, bez produkčného tímu, len s túžbou rozprávať. Dnes má viac ako milión vypočutí a tisíce verných fanúšikov, ktorí sa vracajú pre atmosféru, akú inde nenájdu.</p>
                        <p>Čo robí Krvavého Dobšinského výnimočným, je profesionálny zvukový dizajn, ktorý posúva príbehy ďaleko za hranice bežného rozprávania. Namiesto klasickej narácie vytváram akustický svet, kde počuť les, dych, vietor, dvere, ticho – a niekedy aj to, čo by tam byť nemalo.</p>
                        <p>Podcast nesie meno po Pavlovi Dobšinskom, ale jeho tón je iný: temnejší, existenciálnejší, intímnejší. Ak ťa lákajú strašidelné príbehy, slovenské legendy, záhadné zmiznutia a svet, kde sa prelína realita s podvedomím – vitaj.</p>
                        <p>Toto je podcast, ktorý nepočúvaš len ušami. Cítiš ho v tele.</p>
                    </div>
                </div>
            </div> <div id="subscribe-view" class="view">
                <div class="relative pl-5 mb-5 h-[40px] flex items-center section-indicator">
                    <h2 class="section-title">Odoberať</h2> </div>
                <div class="bg-custom-card rounded-lg p-6 md:p-8 shadow-lg">
                    <p class="subscribe-text text-custom-dark mb-4">Nech ti žiadny príbeh neunikne.</p> <p class="subscribe-text text-custom-dark mb-4">Nové epizódy vychádzajú väčšinou každú stredu – no niekedy sa ozve aj niečo nečakané.</p> <p class="subscribe-text text-custom-dark mb-6">Pridaj si Krvavého Dobšinského medzi obľúbené a buď pri tom, keď sa opäť otvorí brána do tmy.</p> <div class="flex flex-wrap gap-4">
                         <a href="https://open.spotify.com/show/1jpZ723mEpLld7bZeZ2wdE?si=3d80f84aed5d4515" target="_blank" rel="noopener noreferrer" class="subscribe-button" aria-label="Odoberať na Spotify">
                             <svg xmlns="http://www.w3.org/2000/svg" width="1em" height="1em" fill="currentColor" class="bi bi-spotify" viewBox="0 0 16 16" aria-hidden="true">
                                 <path d="M8 0a8 8 0 1 0 0 16A8 8 0 0 0 8 0m3.669 11.538a.5.5 0 0 1-.686.165c-1.879-1.147-4.243-1.407-7.028-.77a.5.5 0 0 1-.222-.973c3.048-.696 5.662-.397 7.77.892a.5.5 0 0 1 .166.686m.979-2.17a.618.618 0 0 1-.858.205c-2.15-1.321-5.428-1.704-7.972-.932a.618.618 0 0 1-.28-.618c.034-.333.358-.595.681-.508 2.94.85 6.473 1.297 8.832-.078a.618.618 0 0 1 .205.858m.083-2.29a.74.74 0 0 1-1.026.271c-2.52-1.562-6.94-1.95-9.034-1.074a.739.739 0 0 1-.342-.74c.052-.43.484-.747.923-.695 2.512.94 7.473 1.412 10.088-.114a.74.74 0 0 1 .271 1.026"/>
                             </svg>
                             Spotify
                         </a>
                         <a href="https://podcasts.apple.com/sk/podcast/krvav%C3%BD-dob%C5%A1insk%C3%BD/id1608900257" target="_blank" rel="noopener noreferrer" class="subscribe-button" aria-label="Odoberať na Apple Podcasts">
                             <svg xmlns="http://www.w3.org/2000/svg" width="1em" height="1em" fill="currentColor" class="bi bi-apple" viewBox="0 0 16 16" aria-hidden="true">
                                <path d="M11.182.008C10.148-.03 9.07 1.05 9.07 1.05s-1.068.983-1.068 2.657c0 1.675 1.021 2.578 1.021 2.578s.929 1.01 2.328 1.01c1.4 0 2.472-1.088 2.472-1.088s1.069-1.135 1.069-2.657c0-1.522-1.069-2.657-1.069-2.657s-1.02-1.116-2.198-1.116zm-2.112 6.025c.02-.018.04-.035.062-.053s.045-.036.068-.052c.18-.128.34-.26.478-.403.138-.142.25-.304.33-.488.08-.183.12-.386.12-.61s-.04-.427-.12-.61c-.08-.184-.192-.346-.33-.488-.138-.143-.299-.275-.478-.403-.023-.017-.046-.035-.068-.052s-.043-.035-.062-.053c-.06-.05-.116-.089-.168-.115-.052-.027-.103-.04-.15-.04H8.84c-.048 0-.099.013-.15.04-.052.026-.108.065-.168.115-.02.018-.04.035-.062.053s-.045.036-.068.052c-.18.128-.34.26-.478.403-.138.142-.25.304-.33.488-.08.183-.12.386-.12.61s.04.427.12.61c.08.184.192.346.33.488.138.143.299.275.478.403.023.017.046.035.068.052s.043.035.062.053c.06.05.116.089.168.115.052.027.103.04.15.04h.298c.048 0 .099-.013.15-.04.052-.026.108-.065.168-.115z"/>
                                <path d="M8.078 11.306c-.52-.026-1.026-.23-1.52-.638-.494-.408-.91-.94-1.26-1.6-.35-.66-.61-1.41-.79-2.24-.18-.83-.27-1.7-.27-2.58s.09-1.75.27-2.58c.18-.83.44-1.58.79-2.24.35-.66.766-1.192 1.26-1.6.494-.408 1-.612 1.52-.638.52-.026 1.03.096 1.512.362.482.266.89.644 1.217 1.134.327.49.565 1.07.712 1.735.147.665.22 1.38.22 2.145s-.073 1.48-.22 2.145c-.147.665-.385 1.245-.712 1.735-.327.49-.735.868-1.217 1.134-.482.266-.992.388-1.512.362z"/>
                             </svg>
                             Apple Podcasts
                         </a>
                         <a href="https://www.instagram.com/krvavydobsinsky/" target="_blank" rel="noopener noreferrer" class="subscribe-button" aria-label="Sledovať na Instagrame">
                             <svg xmlns="http://www.w3.org/2000/svg" width="1em" height="1em" fill="currentColor" class="bi bi-instagram" viewBox="0 0 16 16" aria-hidden="true">
                                 <path d="M8 0C5.829 0 5.556.01 4.703.048 3.85.088 3.269.222 2.76.42a3.9 3.9 0 0 0-1.417.923A3.9 3.9 0 0 0 .42 2.76C.222 3.268.087 3.85.048 4.703.01 5.555 0 5.827 0 8.001c0 2.172.01 2.444.048 3.297.04.852.174 1.433.372 1.942.205.526.478.972.923 1.417.444.445.89.719 1.416.923.51.198 1.09.333 1.942.372C5.555 15.99 5.827 16 8 16s2.444-.01 3.297-.048c.852-.04 1.433-.174 1.942-.372.526-.205.972-.478 1.417-.923.445-.444.719-.89.923-1.417.198-.51.333-1.09.372-1.942C15.99 10.445 16 10.173 16 8s-.01-2.445-.048-3.297c-.04-.852-.174-1.433-.372-1.942a3.9 3.9 0 0 0-.923-1.417A3.9 3.9 0 0 0 13.24.42c-.51-.198-1.09-.333-1.942-.372C10.445.01 10.173 0 8 0m0 1.442c2.136 0 2.389.007 3.232.046.78.035 1.204.166 1.486.275.373.145.64.319.92.599s.453.546.598.92c.11.282.24.705.275 1.485.039.843.047 1.096.047 3.233s-.008 2.389-.047 3.232c-.035.78-.166 1.203-.275 1.485a2.5 2.5 0 0 1-.599.92 2.5 2.5 0 0 1-.92.598c-.283.11-.705.24-1.485.276-.843.038-1.096.047-3.232.047s-2.39-.009-3.233-.047c-.78-.036-1.203-.166-1.485-.276a2.5 2.5 0 0 1-.92-.598 2.5 2.5 0 0 1-.598-.92c-.11-.282-.24-.705-.276-1.485C1.449 10.39 1.442 10.137 1.442 8s.007-2.39.046-3.233c.036-.78.166-1.204.276-1.486.145-.373.319-.64.599-.92s.546-.453.92-.598c.282-.11.705-.24 1.485-.276.843-.038 1.096-.047 3.232-.047M8 3.882a4.108 4.108 0 1 0 0 8.216 4.108 4.108 0 0 0 0-8.216m0 6.774a2.666 2.666 0 1 1 0-5.332 2.666 2.666 0 0 1 0 5.332m5.705-6.774a.96.96 0 1 0 0-1.92.96.96 0 0 0 0 1.92"/>
                             </svg>
                             Instagram
                         </a>
                         </div>
                </div>
            </div> <div id="contact-view" class="view">
                <div class="relative pl-5 mb-5 h-[40px] flex items-center section-indicator">
                    <h2 class="section-title">Kontaktujte ma</h2> </div>
                <div class="bg-custom-card rounded-lg p-6 md:p-8 shadow-lg">
                    <p class="text-custom-dark mb-4 leading-relaxed">Máte príbeh, ktorý vám nedá spávať?</p> <p class="text-custom-dark mb-4 leading-relaxed">Možno ste ho zažili na vlastnej koži. Možno vám ho rozprávala stará mama. Možno sa stal… a možno nie.</p> <p class="text-custom-dark mb-6 leading-relaxed">Ak vo vás niečo zostalo – pocit, spomienka, príbeh – napíšte mi. Občas vyberiem niektorý z nich a spracujem ho do epizódy podcastu.</p> <p class="text-custom-dark mb-8 font-semibold">Nebojte sa – stačia slová. Atmosféru už doladím ja.</p> <form id="contact-form" action="#" method="POST" onsubmit="handleContactFormSubmit(event)">
                        <div class="mb-4">
                            <label for="name" class="form-label">Vaše meno alebo prezývka <span class="form-note">(nepovinné)</span></label> <input type="text" id="name" name="name" class="form-input" autocomplete="name">
                        </div>
                        <div class="mb-4">
                            <label for="email" class="form-label">E-mail <span class="form-note">(nepovinné, ak chcete, aby som sa ozval)</span></label> <input type="email" id="email" name="email" class="form-input" autocomplete="email">
                        </div>
                        <div class="mb-4">
                            <label for="story-title" class="form-label">Názov príbehu <span class="form-note">(nepovinné)</span></label> <input type="text" id="story-title" name="story-title" class="form-input">
                        </div>
                        <div class="mb-6">
                            <label for="story" class="form-label">Váš príbeh <span class="text-red-600">*</span></label> <textarea id="story" name="story" class="form-textarea" required aria-required="true"></textarea>
                        </div>
                        <div>
                            <button type="submit" class="form-button">Odoslať príbeh</button> </div>
                    </form>
                     <p id="form-success-message" class="mt-4 text-green-700 font-semibold" style="display: none;">Ďakujem! Váš príbeh bol úspešne odoslaný (simulácia).</p> <p id="form-error-message" class="mt-4 text-red-700 font-semibold" style="display: none;">Chyba: Vyplňte prosím pole "Váš príbeh".</p> </div>
            </div> <div id="texts-view" class="view">
                 <div class="relative pl-5 mb-5 h-[40px] flex items-center section-indicator">
                     <h2 class="section-title">Texty</h2> </div>
                 <p class="text-custom-dark mb-6 leading-relaxed">Tu nájdete prepisy vybraných epizód alebo iné bonusové texty k podcastu Krvavý Dobšinský.</p> <div id="texts-grid" class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-6">
                     <div class="loading-placeholder col-span-full h-24">Načítavam texty...</div> </div>
                 <p id="texts-error" class="text-red-700 mt-4" style="display: none;">Nepodarilo sa načítať texty.</p> </div> </main>

        <footer class="bg-custom-dark text-custom-header-text text-center py-6 mt-auto rounded-t-xl">
            <p class="footer-text mb-2">© 2025 Krvavý Dobšinský. Všetky práva vyhradené.</p>
            <div class="flex justify-center space-x-4">
                <a href="https://open.spotify.com/show/1jpZ723mEpLld7bZeZ2wdE?si=3d80f84aed5d4515" target="_blank" rel="noopener noreferrer" class="text-custom-header-text hover:text-custom-gold transition-colors" aria-label="Odoberať na Spotify">
                    <svg xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="bi bi-spotify w-5 h-5" viewBox="0 0 16 16" aria-hidden="true">
                         <path d="M8 0a8 8 0 1 0 0 16A8 8 0 0 0 8 0m3.669 11.538a.5.5 0 0 1-.686.165c-1.879-1.147-4.243-1.407-7.028-.77a.5.5 0 0 1-.222-.973c3.048-.696 5.662-.397 7.77.892a.5.5 0 0 1 .166.686m.979-2.17a.618.618 0 0 1-.858.205c-2.15-1.321-5.428-1.704-7.972-.932a.618.618 0 0 1-.28-.618c.034-.333.358-.595.681-.508 2.94.85 6.473 1.297 8.832-.078a.618.618 0 0 1 .205.858m.083-2.29a.74.74 0 0 1-1.026.271c-2.52-1.562-6.94-1.95-9.034-1.074a.739.739 0 0 1-.342-.74c.052-.43.484-.747.923-.695 2.512.94 7.473 1.412 10.088-.114a.74.74 0 0 1 .271 1.026"/>
                     </svg>
                </a>
                <a href="https://podcasts.apple.com/sk/podcast/krvav%C3%BD-dob%C5%A1insk%C3%BD/id1608900257" target="_blank" rel="noopener noreferrer" class="text-custom-header-text hover:text-custom-gold transition-colors" aria-label="Odoberať na Apple Podcasts">
                     <svg xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="bi bi-apple w-5 h-5" viewBox="0 0 16 16" aria-hidden="true">
                        <path d="M11.182.008C10.148-.03 9.07 1.05 9.07 1.05s-1.068.983-1.068 2.657c0 1.675 1.021 2.578 1.021 2.578s.929 1.01 2.328 1.01c1.4 0 2.472-1.088 2.472-1.088s1.069-1.135 1.069-2.657c0-1.522-1.069-2.657-1.069-2.657s-1.02-1.116-2.198-1.116zm-2.112 6.025c.02-.018.04-.035.062-.053s.045-.036.068-.052c.18-.128.34-.26.478-.403.138-.142.25-.304.33-.488.08-.183.12-.386.12-.61s-.04-.427-.12-.61c-.08-.184-.192-.346-.33-.488-.138-.143-.299-.275-.478-.403-.023-.017-.046-.035-.068-.052s-.043-.035-.062-.053c-.06-.05-.116-.089-.168-.115-.052-.027-.103-.04-.15-.04H8.84c-.048 0-.099.013-.15.04-.052.026-.108.065-.168.115-.02.018-.04.035-.062.053s-.045.036-.068.052c-.18.128-.34.26-.478.403-.138.142-.25.304-.33.488-.08.183-.12.386-.12.61s.04.427.12.61c.08.184.192.346.33.488.138.143.299.275.478.403.023.017.046.035.068.052s.043.035.062.053c.06.05.116.089.168.115.052.027.103.04.15.04h.298c.048 0 .099-.013.15-.04.052-.026.108-.065.168-.115z"/>
                        <path d="M8.078 11.306c-.52-.026-1.026-.23-1.52-.638-.494-.408-.91-.94-1.26-1.6-.35-.66-.61-1.41-.79-2.24-.18-.83-.27-1.7-.27-2.58s.09-1.75.27-2.58c.18-.83.44-1.58.79-2.24.35-.66.766-1.192 1.26-1.6.494-.408 1-.612 1.52-.638.52-.026 1.03.096 1.512.362.482.266.89.644 1.217 1.134.327.49.565 1.07.712 1.735.147.665.22 1.38.22 2.145s-.073 1.48-.22 2.145c-.147.665-.385 1.245-.712 1.735-.327.49-.735.868-1.217 1.134-.482.266-.992.388-1.512.362z"/>
                     </svg>
                </a>
                <a href="https://www.instagram.com/krvavydobsinsky/" target="_blank" rel="noopener noreferrer" class="text-custom-header-text hover:text-custom-gold transition-colors" aria-label="Sledovať na Instagrame">
                     <svg xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="bi bi-instagram w-5 h-5" viewBox="0 0 16 16" aria-hidden="true">
                         <path d="M8 0C5.829 0 5.556.01 4.703.048 3.85.088 3.269.222 2.76.42a3.9 3.9 0 0 0-1.417.923A3.9 3.9 0 0 0 .42 2.76C.222 3.268.087 3.85.048 4.703.01 5.555 0 5.827 0 8.001c0 2.172.01 2.444.048 3.297.04.852.174 1.433.372 1.942.205.526.478.972.923 1.417.444.445.89.719 1.416.923.51.198 1.09.333 1.942.372C5.555 15.99 5.827 16 8 16s2.444-.01 3.297-.048c.852-.04 1.433-.174 1.942-.372.526-.205.972-.478 1.417-.923.445-.444.719-.89.923-1.417.198-.51.333-1.09.372-1.942C15.99 10.445 16 10.173 16 8s-.01-2.445-.048-3.297c-.04-.852-.174-1.433-.372-1.942a3.9 3.9 0 0 0-.923-1.417A3.9 3.9 0 0 0 13.24.42c-.51-.198-1.09-.333-1.942-.372C10.445.01 10.173 0 8 0m0 1.442c2.136 0 2.389.007 3.232.046.78.035 1.204.166 1.486.275.373.145.64.319.92.599s.453.546.598.92c.11.282.24.705.275 1.485.039.843.047 1.096.047 3.233s-.008 2.389-.047 3.232c-.035.78-.166 1.203-.275 1.485a2.5 2.5 0 0 1-.599.92 2.5 2.5 0 0 1-.92.598c-.283.11-.705.24-1.485.276-.843.038-1.096.047-3.232.047s-2.39-.009-3.233-.047c-.78-.036-1.203-.166-1.485-.276a2.5 2.5 0 0 1-.92-.598 2.5 2.5 0 0 1-.598-.92c-.11-.282-.24-.705-.276-1.485C1.449 10.39 1.442 10.137 1.442 8s.007-2.39.046-3.233c.036-.78.166-1.204.276-1.486.145-.373.319-.64.599-.92s.546-.453.92-.598c.282-.11.705-.24 1.485-.276.843-.038 1.096-.047 3.232-.047M8 3.882a4.108 4.108 0 1 0 0 8.216 4.108 4.108 0 0 0 0-8.216m0 6.774a2.666 2.666 0 1 1 0-5.332 2.666 2.666 0 0 1 0 5.332m5.705-6.774a.96.96 0 1 0 0-1.92.96.96 0 0 0 0 1.92"/>
                     </svg>
                </a>
            </div>
        </footer>

    </div> <script>
        // --- Configuration ---
        const rssFeedUrl = 'https://anchor.fm/s/8db2e1ec/podcast/rss'; // Anchor FM RSS Feed URL
        const defaultImageUrl = 'https://i.imgur.com/F9fKCIr.png'; // Default/Fallback image
        const maxDescriptionLengthPlayer = 200; // Max characters for description in the main player
        const maxDescriptionLengthGrid = 80; // Max characters for description in the episode grid cards
        const maxExcerptLengthTexts = 120; // Max characters for excerpt in the texts grid cards
        const initialEpisodesToShow = 6; // Number of episodes to show initially

        // --- Global variable to store all fetched podcast items ---
        let allPodcastItems = []; // Holds the parsed <item> elements from the RSS feed

        // --- DOM Element References ---
        // Cache frequently accessed DOM elements for performance
        const playerSection = document.getElementById('latest');
        const playerCard = document.getElementById('latest-episode-card');
        const playerImage = document.getElementById('latest-episode-image');
        const playerTitle = document.getElementById('latest-episode-title');
        const playerDate = document.getElementById('latest-episode-date');
        const playerDescription = document.getElementById('latest-episode-description');
        const playerAudio = document.getElementById('latest-episode-audio');
        const rssError = document.getElementById('rss-error');
        const allEpisodesGrid = document.getElementById('all-episodes-grid');
        const allEpisodesError = document.getElementById('all-episodes-error');
        const showMoreContainer = document.getElementById('show-more-container');
        const showMoreButton = document.getElementById('show-more-button');
        const textsGrid = document.getElementById('texts-grid');
        const textsError = document.getElementById('texts-error');
        const homeView = document.getElementById('home-view');
        const contactView = document.getElementById('contact-view');
        const aboutView = document.getElementById('about-view');
        const textsView = document.getElementById('texts-view');
        const subscribeView = document.getElementById('subscribe-view');
        const views = document.querySelectorAll('.view'); // Collection of all view divs
        const contactForm = document.getElementById('contact-form');
        const formSuccessMessage = document.getElementById('form-success-message');
        const formErrorMessage = document.getElementById('form-error-message');


        // --- View Management ---
        /**
         * Shows the specified view and hides others. Optionally scrolls to a specific element within the view.
         * @param {string} viewId - The ID of the view to show (e.g., 'home', 'about').
         * @param {string|null} [scrollToSelector=null] - Optional CSS selector for an element to scroll to within the view.
         */
        function showView(viewId, scrollToSelector = null) {
            console.log(`Switching to view: ${viewId}, scroll target: ${scrollToSelector || 'none'}`);
            views.forEach(view => view.classList.remove('active'));
            const activeView = document.getElementById(`${viewId}-view`);
            if (activeView) {
                activeView.classList.add('active');
                if (scrollToSelector) {
                    const elementToScroll = activeView.querySelector(scrollToSelector);
                    if (elementToScroll) {
                        setTimeout(() => elementToScroll.scrollIntoView({ behavior: 'smooth', block: 'start' }), 0);
                    } else {
                        console.warn(`Scroll target '${scrollToSelector}' not found in view '${viewId}'. Scrolling to top.`);
                        setTimeout(() => window.scrollTo({ top: 0, behavior: 'smooth' }), 0);
                    }
                } else {
                    setTimeout(() => window.scrollTo({ top: 0, behavior: 'smooth' }), 0);
                }
            } else {
                console.error(`View '${viewId}-view' not found. Defaulting to home.`);
                homeView.classList.add('active');
                window.scrollTo({ top: 0, behavior: 'smooth' });
            }
        }

        // --- Utility Functions ---
        /**
         * Formats a date string into Slovak locale format (DD. MMMM<y_bin_46>).
         * @param {string} dateString - The date string (e.g., from RSS pubDate).
         * @returns {string} - The formatted date string or the original string if formatting fails.
         */
        function formatSlovakDate(dateString) {
            try {
                const date = new Date(dateString);
                if (isNaN(date.getTime())) throw new Error("Invalid date");
                return date.toLocaleDateString('sk-SK', { year: 'numeric', month: 'long', day: 'numeric' });
            } catch (e) {
                console.error("Date formatting error:", dateString, e);
                return dateString;
            }
        }

        /**
         * Extracts plain text from an HTML string and shortens it.
         * Removes trailing URLs often found in descriptions.
         * @param {string} htmlString - The HTML string to process.
         * @param {number} [maxLength=100] - The maximum length of the returned text.
         * @returns {string} - The shortened plain text.
         */
        function extractAndShortenText(htmlString, maxLength = 100) {
            if (!htmlString) return "";
            const tempDiv = document.createElement('div');
            tempDiv.innerHTML = htmlString;
            let text = (tempDiv.textContent || tempDiv.innerText || "").trim();
            text = text.replace(/https?:\/\/[^\s]+$/, '').trim();
            return text.length > maxLength ? text.substring(0, maxLength).trim() + '...' : text;
        }

        /**
         * Creates an HTML card element for a single podcast episode.
         * @param {Element} item - The XML <item> element for the episode.
         * @returns {HTMLElement} - The created <article> element.
         */
        function createEpisodeCard(item) {
            const title = item.querySelector("title")?.textContent || "Neznáma epizóda";
            const pubDate = item.querySelector("pubDate")?.textContent || "";
            const descriptionHtml = item.querySelector("content\\:encoded")?.textContent || item.querySelector("description")?.textContent || "";
            const audioUrl = item.querySelector("enclosure")?.getAttribute("url") || "";
            const imageUrl = item.querySelector("itunes\\:image")?.getAttribute("href") || defaultImageUrl;

            const card = document.createElement('article');
            card.dataset.fullDesc = descriptionHtml;
            card.className = 'bg-custom-card rounded-lg p-5 flex flex-col h-[220px] shadow-lg hoverable-card';
            card.innerHTML = `
                <h3 class="card-episode-title text-custom-gold mb-1">${title}</h3>
                <p class="episode-date text-custom-date mb-2">${formatSlovakDate(pubDate)}</p>
                <p class="card-episode-desc text-custom-dark leading-normal mb-3 flex-grow overflow-hidden">${extractAndShortenText(descriptionHtml, maxDescriptionLengthGrid)}</p>
                <button class="play-button mt-auto" data-audio-src="${audioUrl}" data-title="${title.replace(/"/g, '"')}" data-img-src="${imageUrl}" aria-label="Prehrať epizódu ${title.replace(/"/g, '"')}">
                    <svg viewBox="0 0 24 24" width="1em" height="1em" fill="currentColor" aria-hidden="true"><path d="M8 5v14l11-7z"></path></svg> Prehrať </button>`;
            return card;
        }


        // --- Event Handlers ---
        /**
         * Handles clicks on "Play" buttons in the episode grid.
         * Updates the main player with the selected episode's details and starts playback.
         * @param {Event} event - The click event object.
         */
        function handlePlayButtonClick(event) {
            const button = event.target.closest('.play-button');
            if (!button) return;

            const audioSrc = button.dataset.audioSrc;
            const title = button.dataset.title;
            const imgSrc = button.dataset.imgSrc || defaultImageUrl;

            if (!audioSrc) { console.error("Audio source missing for play button."); return; }

            console.log(`Playing episode: ${title}`);

            playerTitle.textContent = title || "Neznáma epizóda";
            const parentArticle = button.closest('article');
            playerDate.textContent = parentArticle?.querySelector('.episode-date')?.textContent || '';
            playerDescription.textContent = extractAndShortenText(parentArticle?.dataset.fullDesc || '', maxDescriptionLengthPlayer) || "Popis nie je k dispozícii.";

            playerImage.src = imgSrc;
            playerImage.onerror = () => { playerImage.src = defaultImageUrl; playerImage.onerror = null; };

            if (playerAudio.src !== audioSrc) {
                playerAudio.src = audioSrc;
                playerAudio.load();
                playerAudio.play().catch(e => console.error("Audio playback error:", e));
            } else if (playerAudio.paused) {
                playerAudio.play().catch(e => console.error("Audio playback error:", e));
            }

            playerCard.classList.add('loaded');
            playerSection.scrollIntoView({ behavior: 'smooth', block: 'start' });
        }

        /**
         * Handles the submission of the contact form (simulation).
         * @param {Event} event - The form submission event object.
         */
        function handleContactFormSubmit(event) {
            event.preventDefault();
            formSuccessMessage.style.display = 'none';
            formErrorMessage.style.display = 'none';
            const storyText = document.getElementById('story').value.trim();
            if (!storyText) {
                formErrorMessage.textContent = 'Chyba: Pole "Váš príbeh" je povinné.';
                formErrorMessage.style.display = 'block';
                document.getElementById('story').focus();
                return;
            }
            console.log("Form submitted (simulation):", Object.fromEntries(new FormData(contactForm)));
            formSuccessMessage.style.display = 'block';
            contactForm.reset();
            setTimeout(() => { formSuccessMessage.style.display = 'none'; }, 5000);
        }

        /**
         * Handles the click on the "Show More" button for episodes.
         * Loads and appends the remaining episodes to the grid.
         */
        function handleShowMoreClick() {
            console.log("Showing more episodes...");
            // Get the remaining items (slice from the initial count onwards)
            const remainingItems = allPodcastItems.slice(initialEpisodesToShow);

            // Create and append cards for the remaining items
            remainingItems.forEach(item => {
                try {
                    const card = createEpisodeCard(item); // Use the helper function
                    allEpisodesGrid.appendChild(card);
                } catch(e) {
                    console.error("Error creating card for remaining episode:", e);
                }
            });

            // Hide the "Show More" button container
            showMoreContainer.style.display = 'none';
        }

        // --- Data Loading ---
        /**
         * Fetches and parses the RSS feed, stores all items, displays the initial batch,
         * and sets up the "Show More" button if necessary.
         */
        function loadRssData() {
            console.log("Loading RSS feed from:", rssFeedUrl);
            fetch(rssFeedUrl)
                .then(response => {
                    if (!response.ok) {
                        throw new Error(`Network error: ${response.statusText} (Status: ${response.status})`);
                    }
                    return response.text();
                })
                .then(str => new window.DOMParser().parseFromString(str, "text/xml"))
                .then(data => {
                    console.log("RSS Feed parsed successfully.");
                    // Store all items in the global variable after converting NodeList to Array
                    allPodcastItems = Array.from(data.querySelectorAll("item"));

                    if (allPodcastItems.length === 0) {
                        throw new Error("No episode items found in the RSS feed.");
                    }

                    // --- Populate Player (Latest Episode) ---
                    const firstItem = allPodcastItems[0];
                    try {
                        const title = firstItem.querySelector("title")?.textContent || "Neznámy názov";
                        const pubDate = firstItem.querySelector("pubDate")?.textContent || "";
                        const descriptionHtml = firstItem.querySelector("content\\:encoded")?.textContent || firstItem.querySelector("description")?.textContent || "";
                        const audioUrl = firstItem.querySelector("enclosure")?.getAttribute("url") || "";
                        const imageUrl = firstItem.querySelector("itunes\\:image")?.getAttribute("href") || data.querySelector("channel > itunes\\:image")?.getAttribute("href") || defaultImageUrl;

                        playerTitle.textContent = title;
                        playerDate.textContent = formatSlovakDate(pubDate);
                        playerDescription.textContent = extractAndShortenText(descriptionHtml, maxDescriptionLengthPlayer);
                        playerImage.src = imageUrl;
                        playerImage.onerror = () => { playerImage.src = defaultImageUrl; playerImage.onerror = null; };
                        playerAudio.src = audioUrl;
                        playerCard.classList.add('loaded');
                    } catch (e) {
                        console.error("Error processing latest episode:", e);
                        rssError.textContent = 'Chyba spracovania najnovšej epizódy.';
                        rssError.style.display = 'block';
                        playerCard.classList.add('loaded');
                        playerTitle.textContent = 'Chyba'; playerDate.textContent = '-'; playerDescription.textContent = 'Nepodarilo sa načítať.'; playerImage.src = defaultImageUrl; playerImage.style.display = 'block'; playerAudio.style.display = 'none';
                    }

                    // --- Populate Initial Episodes Grid ---
                    allEpisodesGrid.innerHTML = ''; // Clear loading placeholder
                    const initialItems = allPodcastItems.slice(0, initialEpisodesToShow); // Get only the first few items

                    initialItems.forEach(item => {
                         try {
                            const card = createEpisodeCard(item); // Use the helper function
                            allEpisodesGrid.appendChild(card);
                         } catch(e) {
                             console.error("Error creating card for initial episode:", e);
                         }
                    });

                    // Show "Show More" button if there are more items than initially shown
                    if (allPodcastItems.length > initialEpisodesToShow) {
                        showMoreContainer.style.display = 'block';
                    } else {
                         showMoreContainer.style.display = 'none';
                    }

                    // Handle case where feed was loaded but no cards could be created
                    if (allEpisodesGrid.children.length === 0 && allPodcastItems.length > 0) {
                         allEpisodesError.textContent = 'Nepodarilo sa zobraziť epizódy napriek úspešnému načítaniu feedu.';
                         allEpisodesError.style.display = 'block';
                         showMoreContainer.style.display = 'none'; // Hide button if grid is empty
                    }
                })
                .catch(error => {
                    console.error("Failed to load or parse RSS feed:", error);
                    rssError.textContent = `Chyba načítania podcastu: ${error.message}. Skontrolujte konzolu pre detaily.`;
                    rssError.style.display = 'block';
                    allEpisodesError.textContent = `Chyba načítania epizód: ${error.message}.`;
                    allEpisodesError.style.display = 'block';
                    playerCard.classList.add('loaded');
                    playerTitle.textContent = 'Chyba'; playerDate.textContent = '-'; playerDescription.textContent = 'Nepodarilo sa načítať.'; playerImage.src = defaultImageUrl; playerImage.style.display = 'block'; playerAudio.style.display = 'none';
                    allEpisodesGrid.innerHTML = `<p class="col-span-full text-center text-red-700 p-4">${allEpisodesError.textContent}</p>`;
                    showMoreContainer.style.display = 'none';
                });
        }

        /**
         * Loads placeholder data for the "Texts" section.
         */
        function loadTextsData() {
            console.log("Loading texts data (using placeholders)...");
            textsGrid.innerHTML = ''; // Clear loading placeholder

            const placeholderTexts = [
                { title: "Prepis: Zmiznutie v lese", excerpt: "Hlboko v hore sa stratil mladý muž. Nikdy ho nenašli, no miestni hovoria o šepotoch medzi stromami a svetlách, ktoré tam nemajú čo robiť...", link: "#" },
                { title: "Bonus: Pôvod legendy o poludnici", excerpt: "Poludnica, bytosť trestajúca tých, čo nedodržiavajú poludňajší pokoj. Aké sú korene tejto strašidelnej postavy slovanského folklóru?", link: "#" },
                { title: "Prepis: Dom na konci ulice", excerpt: "Opustený dom, ktorý láka deti svojimi tajomstvami. Ale čo ak dom nechce, aby odišli? Príbeh inšpirovaný skutočnými udalosťami.", link: "#" }
            ];

            if (placeholderTexts.length === 0) {
                textsGrid.innerHTML = `<p class="col-span-full text-center text-custom-dark p-4">Momentálne nie sú k dispozícii žiadne texty.</p>`;
                return;
            }

            placeholderTexts.forEach(text => {
                try {
                    const card = document.createElement('article');
                    card.className = 'bg-custom-card rounded-lg p-5 flex flex-col h-[220px] shadow-lg hoverable-card';
                    card.innerHTML = `
                        <h3 class="card-text-title text-custom-gold mb-2">${text.title}</h3>
                        <p class="card-text-excerpt text-custom-dark leading-normal mb-3 flex-grow overflow-hidden">${extractAndShortenText(text.excerpt, maxExcerptLengthTexts)}</p>
                        <button class="read-more-button mt-auto" onclick="alert('Funkcia Čítať viac ešte nie je implementovaná.')" aria-label="Čítať viac o ${text.title.replace(/"/g, '"')}">
                            <svg xmlns="http://www.w3.org/2000/svg" width="1em" height="1em" fill="currentColor" class="bi bi-book-half" viewBox="0 0 16 16" aria-hidden="true">
                              <path d="M8.5 2.687c.654-.689 1.782-.886 3.112-.752 1.234.124 2.503.523 3.388 1.17.953.712 1.04 1.73.108 2.686-.744.75-1.898 1.134-3.174 1.233C11.253 7.128 10 6.6 8.5 5.66z"/>
                              <path d="M16 14a2 2 0 0 1-2 2H6a2 2 0 0 1-2-2V1.5A.5.5 0 0 1 4.5 1H6v10.5A1.5 1.5 0 0 0 7.5 13h7a.5.5 0 0 1 .5.5"/>
                            </svg>
                            Čítať viac </button>`;
                    textsGrid.appendChild(card);
                } catch (e) {
                    console.error("Error creating text card:", e);
                }
            });
            console.log(`Populated texts grid with ${textsGrid.children.length} placeholder items.`);
        }


        // --- Initialization ---
        document.addEventListener('DOMContentLoaded', () => {
            // Delegate event listening for play buttons to the grid container
            allEpisodesGrid.addEventListener('click', handlePlayButtonClick);

            // Add event listener for the "Show More" button
            if (showMoreButton) {
                showMoreButton.addEventListener('click', handleShowMoreClick);
            }

            // Load dynamic data
            loadRssData(); // Load podcast episodes
            loadTextsData(); // Load text/blog posts (placeholders for now)

            console.log("DOM fully loaded and parsed. Initializing page functions.");
        });

    </script>

</body>
</html>
