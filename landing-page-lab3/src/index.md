---
layout: layouts/base.njk
templateEngineOverride: njk
title: Centrul Comercial Augustin
hero_subtitle: Bun venit la
hero_title: Centrul Augustin
hero_description: Centrul tău local pentru cumpărături și servicii. Descoperă o varietate de magazine și servicii esențiale chiar în cartierul tău.
about_image: /assets/images/augustin.jpg
about_subtitle: Despre Noi
about_title: Destinația Ta Locală Principală
shops_subtitle: Directorul Centrului
shops_title: Descoperă Ce Se Află Înăuntru
shops_description: De la produse esențiale zilnice la cele mai noi electronice, explorează trei etaje de magazine și servicii dedicate.
shops_list:
  - number: '02'
    name: Articole Bisericești
    description: Un magazin liniștit care oferă o varietate de articole religioase, cărți și cadouri pentru tine sau cei dragi.
    floor: Etajul 1
  - number: '01'
    name: Farmacie
    description: Farmacia ta locală de încredere pentru rețete, sfaturi de sănătate și produse de wellness.
    floor: Etajul 1
  - number: '03'
    name: TechnoPlus
    description: Un magazin uriaș de electronice cu electrocasnice, televizoare, mașini de spălat și multe altele.
    floor: Etajul 2
  - number: '04'
    name: Spații de Birouri
    description: Zone moderne și spațioase disponibile pentru viitoare închirieri de birouri și afaceri.
    floor: Etajul 2
  - number: '05'
    name: Copii și Jucării
    description: Un magazin distractiv, orientat spre copii, plin de jucării, jocuri și activități pentru copii de toate vârstele.
    floor: Etajul -1
  - number: '06'
    name: Magazin de Dulciuri
    description: Satisface-ți pofta de dulce cu o selecție largă de bomboane, ciocolată și bunătăți.
    floor: Etajul -1
footer_title: Centrul Augustin
footer_description: Centrul tău local pentru cumpărături, servicii și comunitate în inima cartierului. Tot ce ai nevoie sub același acoperiș.
social_links:
  - name: Facebook
    url: "#"
  - name: Instagram
    url: "#"
  - name: Twitter
    url: "#"
footer_copyright: "&copy; 2026 Centrul Comercial Augustin. Toate drepturile rezervate."
---

<section id="home" class="min-h-[calc(100vh-74px)] flex items-center justify-center text-center py-16 relative bg-gradient-to-b from-blue-100 via-bg-color to-bg-color">
    <!-- Subtle dot pattern background -->
    <div class="absolute inset-0 z-0 opacity-[0.15]" style="background-image: radial-gradient(#1e40af 2px, transparent 2px); background-size: 32px 32px; mask-image: linear-gradient(to bottom, white, transparent); -webkit-mask-image: linear-gradient(to bottom, white, transparent);"></div>
    <div class="w-[90%] max-w-[1200px] mx-auto relative z-10">
        <div class="max-w-[900px] mx-auto">
            <span class="inline-block text-[0.85rem] uppercase tracking-[3px] text-secondary mb-[0.8rem] font-bold">{{ hero_subtitle }}</span>
            <h2 class="text-3xl sm:text-4xl md:text-[4.5rem] font-[800] text-gray-900 mb-6 leading-[1.1] tracking-[-1px]">{{ hero_title }}</h2>
            <p class="text-lg md:text-[1.3rem] text-gray-600 mb-10 max-w-[700px] mx-auto leading-[1.6]">{{ hero_description }}</p>
            <div class="flex flex-col sm:flex-row gap-4 justify-center">
                <a href="#shops" class="w-full sm:w-auto inline-block bg-secondary text-white py-3 px-[30px] no-underline rounded-[5px] text-[1.1rem] font-bold transition-all duration-300 ease-in-out hover:bg-accent-hover hover:-translate-y-[2px]">Explorează Magazinele</a>
                <a href="#about" class="w-full sm:w-auto inline-block bg-transparent text-gray-900 py-3 px-[30px] no-underline rounded-[5px] text-[1.1rem] font-bold border-2 border-solid border-secondary transition-all duration-300 ease-in-out hover:bg-secondary hover:text-secondary hover:-translate-y-[2px]">Află Mai Multe</a>
            </div>
        </div>
    </div>
</section>

<!-- Section 2: About Us -->
<section id="about" class="py-16 md:py-24 bg-white scroll-mt-[74px]">
    <div class="w-[90%] max-w-[1200px] mx-auto">
        <div class="flex flex-col md:flex-row gap-10 md:gap-16 items-center">
            <div class="w-full md:flex-[1_1_400px] relative before:content-[''] before:absolute before:-top-2 before:-left-2 md:before:-top-5 md:before:-left-5 before:w-full before:h-full before:border-2 before:border-solid before:secondary before:rounded-xl before:z-0">
                <img src="{{ about_image }}" alt="Centrul Comercial Augustin" class="w-full h-auto rounded-xl shadow-[0_20px_40px_rgba(0,0,0,0.1)] block border border-solid border-gray-200 relative z-10">
            </div>
            <div class="w-full md:flex-[1_1_500px] flex flex-col gap-8">
                <div>
                    <span class="inline-block text-[0.85rem] uppercase tracking-[3px] text-secondary mb-[0.8rem] font-bold">{{ about_subtitle }}</span>
                    <h2 class="text-3xl md:text-[2.5rem] text-gray-900 mb-6">{{ about_title }}</h2>
                    <p class="text-base md:text-[1.1rem] mb-4 text-gray-600 leading-[1.8]">Bun venit la Centrul Augustin, destinația ta principală pentru toate nevoile zilnice. Ne mândrim cu oferirea unei game diverse de magazine și servicii într-un mediu convenabil și prietenos.</p>
                    <p class="text-base md:text-[1.1rem] mb-4 text-gray-600 leading-[1.8]">Fie că ești în căutarea unei farmacii, vrei să-ți răsfeți copiii cu jucării sau cauți tehnologie pentru casă, centrul nostru reunește afaceri locale de încredere sub același acoperiș pentru a servi mai bine comunitatea.</p>
                </div>
                <div class="flex flex-col sm:flex-row gap-6">
                    <div class="w-full sm:flex-[1_1_248px] bg-card-bg p-6 rounded-lg border-t-[3px] border-solid border-secondary shadow-[0_4px_15px_rgba(0,0,0,0.05)] transition-transform duration-300 ease-in-out hover:-translate-y-[5px]">
                        <h3 class="text-xl md:text-[1.3rem] text-gray-900 mb-2">Locație Convenabilă</h3>
                        <p class="text-sm md:text-base text-gray-500">Ușor accesibil în inima cartierului, cu locuri de parcare și acces direct la bazarul nostru.</p>
                    </div>
                    <div class="w-full sm:flex-[1_1_248px] bg-card-bg p-6 rounded-lg border-t-[3px] border-solid border-secondary shadow-[0_4px_15px_rgba(0,0,0,0.05)] transition-transform duration-300 ease-in-out hover:-translate-y-[5px]">
                        <h3 class="text-xl md:text-[1.3rem] text-gray-900 mb-2">Magazine Diverse</h3>
                        <p class="text-sm md:text-base text-gray-500">De la farmacii la utilități pentru casă, găsești tot ce ai nevoie.</p>
                    </div>
                </div>
            </div>
        </div>
    </div>
</section>

<!-- Section 3: Our Shops -->
<section id="shops" class="py-16 md:py-20 bg-white scroll-mt-[74px]">
    <div class="w-[90%] max-w-[1200px] mx-auto">
        <div class="text-center mb-12 md:mb-16">
            <span class="inline-block text-[0.85rem] uppercase tracking-[3px] text-secondary mb-[0.8rem] font-bold">{{ shops_subtitle }}</span>
            <h2 class="text-3xl md:text-[2.8rem] text-gray-900 mb-4">{{ shops_title }}</h2>
            <p class="text-base md:text-[1.1rem] text-gray-600 max-w-[600px] mx-auto">{{ shops_description }}</p>
        </div>

        <div class="flex overflow-x-auto snap-x snap-mandatory gap-6 md:gap-8 pb-8 md:flex-wrap md:justify-center md:overflow-visible md:snap-none [&::-webkit-scrollbar]:hidden [-ms-overflow-style:none] [scrollbar-width:none]">
            {% for shop in shops_list %}
            <div class="group bg-card-bg p-6 md:p-8 rounded-[10px] text-center shadow-[0_4px_15px_rgba(0,0,0,0.05)] transition-all duration-300 ease-in-out border-t-[5px] border-solid border-secondary snap-center shrink-0 w-[85%] sm:w-auto sm:flex-[1_1_314px] sm:max-w-[364px] hover:-translate-y-[10px] hover:shadow-[0_10px_25px_rgba(0,0,0,0.1)]">
                <div class="text-3xl md:text-[2.5rem] font-[800] text-secondary opacity-30 mb-4 inline-block font-mono transition-all duration-300 ease-in-out group-hover:opacity-100 group-hover:text-secondary">{{ shop.number }}</div>
                <h3 class="text-xl md:text-[1.5rem] text-gray-900 mb-4">{{ shop.name }}</h3>
                <p class="text-sm md:text-base text-gray-500 mb-6 min-h-[60px]">{{ shop.description }}</p>
                <span class="block text-[0.9rem] text-secondary font-bold pt-4 border-t border-solid border-gray-300">{{ shop.floor }}</span>
            </div>
            {% endfor %}
        </div>
    </div>
</section>

<!-- Section 4: Contact & Location -->
<section id="contact" class="py-16 md:py-20 bg-bg-color scroll-mt-[74px]">
    <div class="w-[90%] max-w-[1200px] mx-auto">
        <div class="text-center mb-12 md:mb-16">
            <span class="inline-block text-[0.85rem] uppercase tracking-[3px] text-secondary mb-[0.8rem] font-bold">Contactează-ne</span>
            <h2 class="text-3xl md:text-[2.8rem] text-gray-900 mb-4">Vizitează-ne Astăzi</h2>
            <p class="text-base md:text-[1.1rem] text-gray-600 max-w-[600px] mx-auto">Așteptăm cu nerăbdare vizita ta!</p>
        </div>

        <div class="flex flex-col md:flex-row gap-12 justify-between">
            <div class="w-full md:flex-[1_1_300px] flex flex-col gap-8">
                <div>
                    <h3 class="text-xl md:text-[1.3rem] text-gray-900 mb-2 flex items-center gap-2">Locație</h3>
                    <p class="text-sm md:text-base text-gray-600 leading-[1.8]">str. 31 August 1989 28<br>Florești</p>
                </div>
                <div>
                    <h3 class="text-xl md:text-[1.3rem] text-gray-900 mb-2 flex items-center gap-2">Program General</h3>
                    <p class="text-sm md:text-base text-gray-600 leading-[1.8]">Luni - Duminică: 8:00 - 19:00</p>
                </div>
                <div>
                    <h3 class="text-xl md:text-[1.3rem] text-gray-900 mb-2 flex items-center gap-2">Contact</h3>
                    <p class="text-sm md:text-base text-gray-600 leading-[1.8]">Telefon: +373 60-707-147<br>Email: info@augustincenter.md</p>
                </div>
            </div>

            <div class="w-full md:flex-[1_1_464px] bg-card-bg p-6 md:p-8 rounded-[10px] shadow-[0_4px_15px_rgba(0,0,0,0.05)] border-t-[5px] border-solid border-secondary">
                <h3 class="text-xl md:text-[1.5rem] text-gray-900 mb-6 text-center">Ai întrebări sau sugestii?</h3>
                <form class="flex flex-col gap-[1.2rem]">
                    <div class="flex flex-col gap-2">
                        <label for="name" class="text-gray-600 font-medium">Nume</label>
                        <input type="text" id="name" name="name" required placeholder="Numele tău" class="p-3 border border-solid border-gray-300 rounded-[5px] bg-bg-color text-gray-900 placeholder-gray-400 font-inherit text-[1rem] transition-colors duration-300 ease-in-out focus:outline-none focus:border-secondary leading-normal">
                    </div>
                    <div class="flex flex-col gap-2">
                        <label for="email" class="text-gray-600 font-medium">Email</label>
                        <input type="email" id="email" name="email" required placeholder="Email-ul tău" class="p-3 border border-solid border-gray-300 rounded-[5px] bg-bg-color text-gray-900 placeholder-gray-400 font-inherit text-[1rem] transition-colors duration-300 ease-in-out focus:outline-none focus:border-secondary leading-normal">
                    </div>
                    <div class="flex flex-col gap-2">
                        <label for="message" class="text-gray-600 font-medium">Mesaj</label>
                        <textarea id="message" name="message" rows="4" required placeholder="Cu ce te putem ajuta?" class="p-3 border border-solid border-gray-300 rounded-[5px] bg-bg-color text-gray-900 placeholder-gray-400 font-inherit text-[1rem] transition-colors duration-300 ease-in-out focus:outline-none focus:border-secondary leading-normal"></textarea>
                    </div>
                    <button type="submit" class="bg-secondary text-white py-3 px-5 border-none rounded-[5px] text-[1.1rem] font-bold cursor-pointer transition-all duration-300 ease-in-out mt-4 hover:bg-accent-hover hover:-translate-y-[2px]">Trimite Mesajul</button>
                </form>
            </div>
        </div>
    </div>
</section>
