
<!DOCTYPE html>
<html lang="pl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Galaxy Animations | Minecraft</title>

<style>
* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
}

html {
    scroll-behavior: smooth;
}

body {
    background: #0b0812;
    color: white;
    font-family: Arial, sans-serif;
}

header {
    background: #151020;
    padding: 22px 8%;
    display: flex;
    justify-content: space-between;
    align-items: center;
    flex-wrap: wrap;
    gap: 15px;
    border-bottom: 1px solid #35224e;
}

.logo {
    font-size: 24px;
    font-weight: bold;
    color: #b77aff;
}

nav a {
    color: #ddd;
    text-decoration: none;
    margin-left: 20px;
}

nav a:hover {
    color: #b77aff;
}

.hero {
    padding: 100px 20px;
    text-align: center;
    background: radial-gradient(ellipse at top, #39205e, #0b0812 65%);
}

.hero h1 {
    font-size: 48px;
    margin-bottom: 20px;
}

.hero h1 span {
    color: #b77aff;
}

.hero p {
    color: #c7bfd5;
    font-size: 18px;
    margin-bottom: 30px;
    line-height: 1.6;
}

.button {
    display: inline-block;
    background: #914cff;
    color: white;
    padding: 15px 28px;
    border-radius: 10px;
    text-decoration: none;
    font-weight: bold;
    border: none;
    cursor: pointer;
    transition: 0.2s;
}

.button:hover {
    background: #a96cff;
    transform: translateY(-2px);
}

.discord-button {
    background: #5865F2;
}

.discord-button:hover {
    background: #4752c4;
}

section {
    padding: 65px 8%;
}

.section-title {
    text-align: center;
    font-size: 32px;
    margin-bottom: 35px;
}

.cards {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
    gap: 20px;
}

.card {
    background: #191323;
    border: 1px solid #35224e;
    border-radius: 15px;
    padding: 25px;
    transition: 0.2s;
}

.card:hover {
    transform: translateY(-5px);
    border-color: #914cff;
}

.card h3 {
    color: #c59aff;
    margin-bottom: 15px;
}

.card p {
    color: #c7bfd5;
    line-height: 1.6;
}

.price {
    font-size: 28px;
    font-weight: bold;
    margin: 18px 0;
    color: white;
}

.order {
    max-width: 700px;
    margin: auto;
    background: #191323;
    border: 1px solid #35224e;
    padding: 30px;
    border-radius: 15px;
}

label {
    display: block;
    margin: 18px 0 8px;
    color: #d8c7f0;
}

input, select, textarea {
    width: 100%;
    padding: 13px;
    background: #0e0a16;
    color: white;
    border: 1px solid #493361;
    border-radius: 8px;
    font-size: 15px;
}

textarea {
    min-height: 120px;
    resize: vertical;
}

input:focus, select:focus, textarea:focus {
    outline: 1px solid #a96cff;
}

.order button {
    width: 100%;
    margin-top: 25px;
    font-size: 16px;
}

.note {
    color: #aaa;
    font-size: 13px;
    margin-top: 15px;
    line-height: 1.5;
}

.steps {
    max-width: 850px;
    margin: auto;
    display: grid;
    gap: 18px;
}

.step {
    display: flex;
    gap: 20px;
    align-items: flex-start;
    background: #191323;
    border: 1px solid #35224e;
    padding: 22px;
    border-radius: 14px;
}

.step-number {
    min-width: 42px;
    height: 42px;
    border-radius: 50%;
    background: #914cff;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 20px;
    font-weight: bold;
}

.step h3 {
    color: #c59aff;
    margin-bottom: 8px;
}

.step p {
    color: #c7bfd5;
    line-height: 1.6;
}

.price-box {
    margin-top: 25px;
    padding: 20px;
    border: 1px solid #493361;
    border-radius: 12px;
    background: #0e0a16;
}

.price-box h3 {
    color: #c59aff;
    margin-bottom: 12px;
}

.total-price {
    font-size: 30px;
    font-weight: bold;
    color: white;
    margin-top: 10px;
}

.discord-section {
    text-align: center;
    background: #151020;
}

.discord-section p {
    color: #c7bfd5;
    margin-bottom: 25px;
    line-height: 1.6;
}

footer {
    text-align: center;
    padding: 30px;
    background: #0b0812;
    color: #aaa;
    line-height: 1.8;
}

@media (max-width: 600px) {
    .hero h1 {
        font-size: 36px;
    }

    header {
        justify-content: center;
        text-align: center;
    }

    nav a {
        margin: 8px;
        display: inline-block;
    }

    .step {
        padding: 18px;
    }
}
</style>
</head>

<body>

<header>
    <div class="logo">GALAXY ANIMATIONS</div>

    <nav>
        <a href="#portfolio">Portfolio</a>
        <a href="#cennik">Cennik</a>
        <a href="#jak-dziala">Jak zamówić?</a>
        <a href="#zamow">Zamów</a>
        <a href="#discord">Discord</a>
    </nav>
</header>

<div class="hero">
    <h1>
        Twoja wizja.<br>
        <span>Animacja Minecraft.</span>
    </h1>

    <p>
        Tworzę animacje Minecraft do YouTube,
        intro, cinematiców i Shorts.
    </p>

    <a href="#zamow" class="button">
        Zamów animację
    </a>

    <br><br>

    <a href="https://discord.gg/bgysAHRcB"
       class="button discord-button"
       target="_blank"
       rel="noopener noreferrer">
        Dołącz do Discorda
    </a>
</div>

<!-- PORTFOLIO -->

<section id="portfolio">
    <h2 class="section-title">Moje portfolio</h2>

    <div class="cards">
        <div class="card">
            <h3>Minecraft Cinematic</h3>
            <p>
                Filmowe ujęcia, klimatyczne sceny
                i wyjątkowa atmosfera.
            </p>
        </div>

        <div class="card">
            <h3>Intro YouTube</h3>
            <p>
                Krótkie animacje na rozpoczęcie
                Twoich filmów.
            </p>
        </div>

        <div class="card">
            <h3>PvP Animation</h3>
            <p>
                Dynamiczne sceny walki
                i prezentacje postaci.
            </p>
        </div>
    </div>
</section>

<!-- CENNIK -->

<section id="cennik">
    <h2 class="section-title">Cennik</h2>

    <div class="cards">
        <div class="card">
            <h3>Basic</h3>
            <p>Krótka animacja Minecraft.</p>
            <div class="price">10 zł</div>
            <p>Prosta scena i jedna postać.</p>
        </div>

        <div class="card">
            <h3>Standard</h3>
            <p>Animacja do YouTube.</p>
            <div class="price">25 zł</div>
            <p>Więcej ujęć i efekty.</p>
        </div>

        <div class="card">
            <h3>Premium</h3>
            <p>Zaawansowany cinematic.</p>
            <div class="price">50 zł+</div>
            <p>Indywidualna scena i zaawansowane efekty.</p>
        </div>
    </div>

    <h2 class="section-title" style="margin-top:50px">
        Opcjonalne dodatki
    </h2>

    <div class="cards">
        <div class="card">
            <h3>Montaż podstawowy</h3>
            <p>
                Przycinanie, łączenie scen,
                przejścia i podstawowa korekcja.
            </p>
            <div class="price">+5 zł</div>
        </div>

        <div class="card">
            <h3>Montaż premium</h3>
            <p>
                Efekty, napisy, muzyka,
                dźwięki i dynamiczny montaż.
            </p>
            <div class="price">+15 zł</div>
        </div>

        <div class="card">
            <h3>Format YouTube Shorts</h3>
            <p>
                Pionowy format 9:16,
                przygotowany do Shorts.
            </p>
            <div class="price">+2–5 zł</div>
        </div>
    </div>

    <p class="note" style="text-align:center">
        Cena końcowa zależy od długości i trudności animacji.
        Dokładna wycena zostanie potwierdzona przed rozpoczęciem pracy.
    </p>
</section>

<!-- JAK DZIAŁA ZAMÓWIENIE -->

<section id="jak-dziala">
    <h2 class="section-title">Jak działa zamówienie?</h2>

    <div class="steps">

        <div class="step">
            <div class="step-number">1</div>
            <div>
                <h3>Wysyłasz zamówienie</h3>
                <p>
                    Wypełnij formularz, wybierz rodzaj animacji,
                    długość i opcjonalne dodatki.
                    Opisz dokładnie swoją wizję.
                </p>
            </div>
        </div>

        <div class="step">
            <div class="step-number">2</div>
            <div>
                <h3>Ustalamy szczegóły</h3>
                <p>
                    Kontaktuję się z Tobą przez Discord.
                    Potwierdzamy cenę, termin i szczegóły
                    animacji przed rozpoczęciem pracy.
                </p>
            </div>
        </div>

        <div class="step">
            <div class="step-number">3</div>
            <div>
                <h3>Tworzę animację</h3>
                <p>
                    Przygotowuję scenę, postacie,
                    ruchy kamery i efekty.
                    Jeśli wybierzesz montaż, przygotuję
                    również gotowy film.
                </p>
            </div>
        </div>

        <div class="step">
            <div class="step-number">4</div>
            <div>
                <h3>Otrzymujesz podgląd</h3>
                <p>
                    Wysyłam podgląd animacji.
                    Możesz zgłosić poprawki zgodnie
                    z ustaleniami zamówienia.
                </p>
            </div>
        </div>

        <div class="step">
            <div class="step-number">5</div>
            <div>
                <h3>Odbierasz gotowy film</h3>
                <p>
                    Po potwierdzeniu płatności
                    otrzymujesz gotową animację
                    w ustalonym formacie.
                </p>
            </div>
        </div>

    </div>
</section>

<!-- FORMULARZ ZAMÓWIENIA -->

<section id="zamow">
    <h2 class="section-title">Zamów animację</h2>

    <div class="order">

        <form action="https://formsubmit.co/okusgg0276@gmail.com"
              method="POST">

            <input type="hidden"
                   name="_subject"
                   value="Nowe zamówienie Galaxy Animations">

            <input type="hidden"
                   name="_captcha"
                   value="false">

            <input type="hidden"
                   name="_template"
                   value="table">

            <!-- EMAIL -->

            <label>Email (opcjonalny)</label>
            <input type="email"
                   name="Email klienta"
                   placeholder="Twój email">

            <!-- NICKI -->

            <label>Twój nick Minecraft (opcjonalny)</label>
            <input type="text"
                   name="Nick Minecraft 1"
                   placeholder="Wpisz swój nick">

            <label>Drugi nick Minecraft (opcjonalny)</label>
            <input type="text"
                   name="Nick Minecraft 2"
                   placeholder="Nick drugiej postaci">

            <p class="note">
                Nick Minecraft jest opcjonalny, ale zalecany.
                Dzięki niemu możemy użyć Twojego skina.
            </p>

            <!-- RODZAJ ANIMACJI -->

            <label>Rodzaj animacji</label>
            <select name="Rodzaj animacji" required>
                <option value="">Wybierz animację</option>
                <option>Cinematic</option>
                <option>Intro YouTube</option>
                <option>PvP Animation</option>
                <option>Animacja postaci</option>
                <option>Inna animacja</option>
            </select>

            <!-- PAKIET -->

            <label>Pakiet animacji</label>
            <select name="Pakiet animacji" id="pakiet" required>
                <option value="">Wybierz pakiet</option>
                <option value="10">Basic — 10 zł</option>
                <option value="25">Standard — 25 zł</option>
                <option value="50">Premium — 50 zł</option>
            </select>

            <!-- DŁUGOŚĆ -->

            <label>Długość animacji</label>
            <select name="Długość animacji">
                <option>Do 15 sekund</option>
                <option>15–30 sekund</option>
                <option>30–60 sekund</option>
                <option>Powyżej 60 sekund</option>
            </select>

            <!-- MONTAŻ -->

            <label>Opcjonalny montaż</label>
            <select name="Montaż" id="montaz">
                <option value="0">Bez montażu — 0 zł</option>
                <option value="5">Montaż podstawowy — +5 zł</option>
                <option value="15">Montaż premium — +15 zł</option>
            </select>

            <p class="note">
                Montaż obejmuje między innymi przejścia,
                przycinanie scen, napisy i efekty
                w zależności od wybranego pakietu.
            </p>

            <!-- FORMAT SHORTS -->

            <label>Format YouTube Shorts</label>
            <select name="Format YouTube Shorts" id="shorts">
                <option value="0">Nie — standardowy format</option>
                <option value="2">Tak — +2 zł</option>
                <option value="3">Tak — +3 zł</option>
                <option value="4">Tak — +4 zł</option>
                <option value="5">Tak — +5 zł</option>
            </select>

            <p class="note">
                YouTube Shorts: pionowy format 9:16.
                Cena dodatku wynosi od 2 do 5 zł.
            </p>

            <!-- SKIN -->

            <label>Link do skina (opcjonalny)</label>
            <input type="url"
                   name="Link do skina"
                   placeholder="https://">

            <!-- OPIS -->

            <label>Opis zamówienia</label>
            <textarea name="Opis zamówienia"
                      placeholder="Opisz, jak ma wyglądać animacja, jakie sceny, postacie i efekty chcesz..."
                      required></textarea>

            <!-- DISCORD -->

            <label>Kontakt Discord</label>
            <input type="text"
                   name="Discord klienta"
                   placeholder="Twój nick Discord"
                   required>

            <!-- CENA -->

            <div class="price-box">
                <h3>Szacowana cena</h3>

                <p class="note">
                    Cena dodatków zostanie doliczona do
                    wybranego pakietu.
                </p>

                <div class="total-price" id="cena">
                    Wybierz pakiet
                </div>

                <input type="hidden"
                       name="Szacowana cena"
                       id="cena-formularza">
            </div>

            <button class="button" type="submit">
                Wyślij zamówienie
            </button>

            <p class="note">
                Wysłanie formularza nie oznacza jeszcze
                rozpoczęcia realizacji. Najpierw potwierdzimy
                szczegóły, cenę i termin przez Discord.
            </p>

        </form>
    </div>
</section>

<!-- DISCORD -->

<section id="discord" class="discord-section">
    <h2 class="section-title">Dołącz do Discorda</h2>

    <p>
        Masz pytania lub chcesz omówić swoją animację?
        <br>
        Dołącz na mój serwer Discord!
    </p>

    <p>
        Discord: <strong>okusgamerek_13527</strong>
    </p>

    <a href="https://discord.gg/bgysAHRcB"
       class="button discord-button"
       target="_blank"
       rel="noopener noreferrer">
        Wejdź na mój serwer
    </a>
</section>

<footer>
    <p>© 2026 Galaxy Animations</p>
    <p>Minecraft Animation Studio</p>
    <p>Discord: okusgamerek_13527</p>
</footer>

<!-- AUTOMATYCZNE OBLICZANIE CENY -->

<script>
const pakiet = document.getElementById("pakiet");
const montaz = document.getElementById("montaz");
const shorts = document.getElementById("shorts");

const cena = document.getElementById("cena");
const cenaFormularza = document.getElementById("cena-formularza");

function obliczCene() {
    const cenaPakietu = Number(pakiet.value);
    const cenaMontazu = Number(montaz.value);
    const cenaShorts = Number(shorts.value);

    if (!pakiet.value) {
        cena.textContent = "Wybierz pakiet";
        cenaFormularza.value = "";
        return;
    }

    const suma = cenaPakietu + cenaMontazu + cenaShorts;

    cena.textContent = suma + " zł";
    cenaFormularza.value = suma + " zł";
}

pakiet.addEventListener("change", obliczCene);
montaz.addEventListener("change", obliczCene);
shorts.addEventListener("change", obliczCene);
</script>

</body>
</html>
