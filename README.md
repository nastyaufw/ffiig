<!DOCTYPE html>
<html lang="uk">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Спортивна школа: танці, хобіхорсінг, квадробінг, повітряна гімнастика для дітей та дорослих.">
    <meta name="keywords" content="спорт, танці, хобіхорсінг, квадробінг, повітряна гімнастика">
    <meta name="author" content="Спортивна Школа">
    <title>Спортивна Школа</title>
    <style>
      body {
            font-family: Arial, sans-serif;
            background-image: url('https://i.pinimg.com/564x/6e/82/0f/6e820f2b4e385705163fd82459584920.jpg');
            background-size: cover;
            background-attachment: fixed;
            background-position: center;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #ff5733;
            color: white;
            padding: 20px;
            text-align: center;
            animation: fadeIn 2s ease-in-out;
        }

        header h1 {
            animation: pulse 2s infinite;
        }

        nav {
            background-color: #333;
            overflow: hidden;
        }

        nav a {
            float: left;
            display: block;
            color: white;
            text-align: center;
            padding: 14px 20px;
            text-decoration: none;
            transition: background-color 0.3s, color 0.3s;
        }

        nav a:hover, nav a.active {
            background-color: #ff5733;
            color: white;
        }

        section {
            padding: 20px;
            margin: 10px;
            background-color: white;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease;
            animation: fadeInUp 1s ease-out;
        }

        section:hover {
            transform: translateY(-5px);
        }

        h2 {
            color: #ff5733;
            animation: slideIn 1.5s ease-in;
        }

        footer {
            text-align: center;
            padding: 10px;
            background-color: #333;
            color: white;
            position: relative;
            bottom: 0;
            width: 100%;
            animation: fadeIn 2s ease-in-out;
        }

        img {
            width: 400px;
            height: 250px;
            object-fit: cover;
            display: block;
            margin-left: auto;
            margin-right: auto;
            transition: transform 0.3s ease;
        }

        img:hover {
            transform: scale(1.1);
        }

        iframe {
            display: block;
            margin: 20px auto;
            width: 560px;
            height: 315px;
        }

        #backToTop {
            position: fixed;
            bottom: 20px;
            right: 20px;
            padding: 10px 15px;
            background: #ff5733;
            color: white;
            border: none;
            border-radius: 50%;
            display: none;
            cursor: pointer;
        }

        #backToTop.show {
            display: block;
        }

        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }

        @keyframes fadeInUp {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }

        @keyframes slideIn {
            from { opacity: 0; transform: translateX(-20px); }
            to { opacity: 1; transform: translateX(0); }
        }

        @keyframes pulse {
            0%, 100% { transform: scale(1); }
            50% { transform: scale(1.05); }
        }

        @media (max-width: 740px) {
            nav a {
                float: none;
                text-align: left;
                padding: 10px;
                border-bottom: 1px solid #fff;
            }

            section {
                padding: 10px;
            }

            img {
                width: 100%;
                height: auto;
            }

            iframe {
                width: 100%;
                height: auto;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Спортивна Школа</h1>
        <p>Танці, Хобіхорсінг, Квадробінг, Повітряна гімнастика</p>
    </header>

    <nav>
        <a href="#dances" class="active">Танці</a>
        <a href="#hobby-horsing">Хобіхорсінг</a>
        <a href="#quadribing">Квадробінг</a>
        <a href="#aerial-gymnastics">Повітряна гімнастика</a>
    </nav>

    <section id="intro">
        <h2>Запрошуємо всіх бажаючих приєднатися до нашої спортивної школи, де ви зможете займатися:</h2>
    </section>

    <section id="dances">
       <h2>Танці</h2>
        <p>У нашій школі ви можете займатися різними стилями танців:</p>
        <ul>
            <li><strong>Джаз фанк</strong> – поєднання ритму та динаміки. Поєднайте елементи джазу, хіп-хопу та поп-танцю. Цей стиль відрізняється динамічністю, емоційністю та енергією, що дозволяє кожному танцюристу проявити свою індивідуальність.</li>
            <img class="photo" src="https://one-life.lviv.ua/assets/images/blog/jazz-funk/1-min.jpg">
            <li><strong>Хіп-хоп</strong> – сучасний стиль, що поєднує енергію та рухи вулиць. Вивчайте ритми та енергію міських танців! Вивчайте базові рухи та складні комбінації, розвивайте свій стиль і ритм. Хіп-хоп – це не лише танець, а й спосіб самовираження, де ви зможете відчути енергію та культуру вуличних танців.</li>
            <img class="photo" src="https://cdn.prod.website-files.com/5e2b8863ba7fff8df8949888/65b013ac8798875d4c45e357_5e28eadaff920783b494509b_hIP-HOP-DANCE-BLOG.jpeg">
            <li><strong>К-поп</strong> – популярний стиль танцю, що надихається корейською музикою. Пориньте у світ корейської поп-культури! Ви навчитеся виконувати хореографії з популярних кліпів, а також отримаєте уявлення про корейські традиції в танці.</li>
            <img class="photo" src="https://static01.nyt.com/images/2021/11/20/multimedia/20sp-gifts-kpop-inyt1/merlin_197637654_e222968c-3e39-425b-9a99-b15ccc4abf55-jumbo.jpg?quality=75&auto=webp">
        </ul>
    </section> 

    <section id="hobby-horsing">
        <h2>Хобіхорсінг</h2>
        <p>Хоббіхорсинг – це веселий і креативний вид спорту, який ідеально підходить для дітей та дорослих.
           Ви навчитеся виконувати різноманітні трюки та елементи з "кіньми на паличках", розвиваючи фізичну активність, уяву та командну роботу. Це заняття приносить не лише радість, але й допомагає зміцнити дружні зв'язки.</p>
        <img class="photo" src="https://comments.ua/img/publications/850x478/4p3vspF8HJvIt_6E0N3mQ9jBwxYly45_.jpg">
        <iframe src="https://www.youtube.com/embed/MmgNL6PT7Ts" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </section>

    <section id="quadribing">
        <h2>Квадробінг</h2>
        <p>Квадробінг – це новий вид спорту, що поєднує елементи бігу, акробатики та командних змагань. Ви будете тренувати свою фізичну підготовку, координацію та спритність, виконуючи завдання з квадробінгом у спеціально облаштованих зонах. Це чудова можливість для активних людей, які хочуть отримати адреналін та відчути командний дух!</p>
        <img class="photo" src="https://static.espreso.tv/uploads/photobank/357000_358000/357691_460312388_1191825941935056_7289354947251123102_n_new_960x380_0.webp">
    </section>

    <section id="aerial-gymnastics">
        <h2>Повітряна гімнастика</h2>
        <p>Повітряна гімнастика – це мистецтво виконання акробатичних трюків на висоті. Відкрийте для себе магію повітряної гімнастики! Цей вид спорту поєднує акробатику, йогу та танець, дозволяючи вам розвивати силу, гнучкість і витривалість. Навчання проходить під керівництвом досвідчених тренерів, які допоможуть вам освоїти різноманітні елементи: від простих трюків до складних акробатичних комбінацій. Це не лише фізична активність, а й можливість виразити себе через рух!</p>
        <img class="photo" src="https://onedeal.com.ua/wp-content/uploads/2021/12/photo5357548239915693385.jpg">
    </section>
    <footer>
        <p>© 2024 Спортивна Школа. Усі права захищені.</p>
    </footer>

    <button onclick="scrollToTop()" id="backToTop">⬆️</button>
    <script>
        document.querySelectorAll('nav a').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });
        function scrollToTop() {
            window.scrollTo({ top: 0, behavior: 'smooth' });
        }
        window.addEventListener('scroll', () => {
            document.getElementById('backToTop').classList.toggle('show', window.scrollY > 300);
        });
    </script>
</body>
</html>
