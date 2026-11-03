<style>
    * {
        box-sizing: border-box;
    }

    body {
        margin: 0;
        font-family: Arial, Helvetica, sans-serif;
        background: #f4f6f8;
        color: #1f2937;
        line-height: 1.6;
    }

    .cv {
        max-width: 1100px;
        margin: 40px auto;
        background: white;
        box-shadow: 0 10px 35px rgba(0,6,0,0.10);
        border-radius: 15px;
        overflow: hidden;
    }

    /* HEADER */


.photo-profil{
    width: 200px;
    height: 200px;
    border-radius: 50%;
    object-fit: cover;
    border: 5px solid #2563eb;
    box-shadow: 0 0 20px rgba(37,99,235,0.5);
    transition: 0.3s;
}

.photo-profil:hover{
    transform: scale(1.05);
}





    .header {
        background: #111827;
        color: white;
        padding: 55px 50px;
        text-align: center;
    }

    .header h1 {
        font-size: 42px;
        margin: 0 0 10px;
        letter-spacing: 1px;
    }
strong{box-shadow:black}
    .header h2 {
        font-size: 21px;
        font-weight: normal;
        color: #60a5fa;
        margin: 0 0 20px;
    }

    .header p {
        margin: 6px 0;
        color: #d1d5db;
    }

    .buttons {
        margin-top: 25px;
    }

    .button {
        display: inline-block;
        padding: 12px 22px;
        margin: 5px;
        border-radius: 8px;
        text-decoration: none;
        font-weight: bold;
        background: #2563eb;
        color: white;
    }

    .button:hover {
        background: #1d4ed8;
    }

    /* CONTENU */
    .content {
        padding: 45px 50px;
    }

    .section {
        margin-bottom: 45px;
    }

    .section-title {
        font-size: 27px;
        color: #111827;
        border-bottom: 3px solid #2563eb;
        padding-bottom: 8px;
        margin-bottom: 25px;
    }

    /* A PROPOS */
    .about {
        font-size: 17px;
        color: #4b5563;
    }

    /* COMPETENCES */
    .skills {
        display: grid;
        grid-template-columns: repeat(2, 1fr);
        gap: 20px;
    }

    .skill {
        background: #f8fafc;
        padding: 22px;
        border-radius: 12px;
        border-left: 5px solid #2563eb;
    }

    .skill h3 {
        margin-top: 0;
        color: #111827;
    }

    .skill ul {
        margin-bottom: 0;
        padding-left: 20px;
    }

    /* PROJETS */
    .projects {
        display: grid;
        grid-template-columns: repeat(2, 1fr);
        gap: 22px;
    }

    .project {
        padding: 25px;
        border: 1px solid #e5e7eb;
        border-radius: 12px;
        background: white;
        transition: 0.2s;
    }

    .project:hover {
        transform: translateY(-3px);
        box-shadow: 0 8px 20px rgba(0,0,0,0.08);
    }

    .project h3 {
        color: #2563eb;
        margin-top: 0;
    }

    .technologies {
        font-size: 14px;
        font-weight: bold;
        color: #6b7280;
    }

    /* EXPERIENCE */
    .experience {
        border-left: 4px solid #2563eb;
        padding-left: 25px;
        margin-bottom: 25px;
    }

    .experience h3 {
        margin-bottom: 3px;
        color: #111827;
    }

    .date {
        color: #2563eb;
        font-weight: bold;
    }

    /* FORMATION */
    .formation {
        background: #f8fafc;
        padding: 22px;
        border-radius: 12px;
        margin-bottom: 15px;
    }

    .formation h3 {
        margin: 0;
    }

    /* STAGE */
    .stage {
        background: #eff6ff;
        border-radius: 12px;
        padding: 30px;
        text-align: center;
    }

    .stage h3 {
        color: #1d4ed8;
        font-size: 23px;
    }

    /* CONTACT */
    .contact {
        text-align: center;
        background: #111827;
        color: white;
        padding: 35px;
        border-radius: 12px;
    }

    .contact h2 {
        margin-top: 0;
    }

    .contact a {
        color: #60a5fa;
        text-decoration: none;
    }

    /* MOBILE */
    @media (max-width: 700px) {

        .cv {
            margin: 0;
            border-radius: 0;
        }

        .header {
            padding: 40px 25px;
        }

        .header h1 {
            font-size: 32px;
        }
h2 strong{ background: rgb(67, 69, 174);
border-radius: 34px;
    box-shadow: 7px 7px 2px rgba(13, 13, 13, 0.678);
}

        .content {
            padding: 35px 25px;
        }

        .skills,
        .projects {
            grid-template-columns: 1fr;
        }
    }
</style>


<div class="cv">

    <!-- HEADER -->
    <header class="header">
   



<img src=" https://portfolio-jean-ives.org.uk/wp-content/uploads/2026/10/jives.png" alt="Photo de profil" class="photo-profil">





        <h1>Koua Ebrin Jean Ives</h1>

        <h2>
            Stagiaire Technicien Informatique / Support Informatique Linux / DevOps Junior /Linux Débutant / Docker CI/CD / Exploitation Informatique /  Réseaux et Système.
        </h2>

        <p>
            Étudiant en DevOp's 1ere année - Développement et Exploitation de Parcs Informatiques(DSP)- CNAM Paris
        </p>

        <p>
            📍 Île-de-France &nbsp; | &nbsp;
           <a href="mailto:ebrinjeanivesk@gmail.com"> 📧 ebrinjeanivesk@gmail.com </a>
        </p>

        <div class="buttons">

            <a class="button" href="#contact">
                Me contacter
            </a>

            <a class="button" href="https://portfolio-jean-ives.org.uk/wp-content/uploads/2026/10/Cv-stage-informatique-1-1.pdf-1.pdf" target="_blank">
                Télécharger mon CV
            </a>

        </div>

    </header>


    <main class="content">

        <!-- A PROPOS -->
        <section class="section">

            <h2 class="section-title">
                À propos
            </h2>

            <p class="about">
                Étudiant en première année de formation
                <strong>Développement et Exploitation de Parcs Informatiques (DSP)</strong>
                au CNAM Paris, je développe mes compétences dans les domaines
                des systèmes, réseaux, support informatique et administration Linux.
            </p>

            <p class="about">
                Je réalise des projets pratiques sur Ubuntu, VirtualBox,
                Apache, MariaDB, WordPress et les VPN afin de renforcer
                mes compétences techniques et ma capacité à résoudre
                des problèmes informatiques.
<br>
</p><h2><strong>Et je suis de niveau débutant dans ces compétences.</strong></h2>
            <p></p>

        </section>


        <!-- COMPETENCES -->
        <section class="section">

            <h2 class="section-title">
                Compétences
            </h2>

            <div class="skills">

                <div class="skill">

                    <h3>🖥️ Systèmes</h3>

                    <ul>
                        <li>Ubuntu / Linux</li>
                        <li>Windows</li>
                        <li>SSH</li>
                        <li>Gestion des utilisateurs</li>
                        <li>Permissions Linux</li>
                        <li>Services système</li>
                        <li>Diagnostic et dépannage</li>
                    </ul>

                </div>


                <div class="skill">

                    <h3>🌐 Réseaux</h3>

                    <ul>
                        <li>TCP/IP</li>
                        <li>Adressage IP</li>
                        <li>DNS / DHCP</li>
                        <li>Ports et protocoles</li>
                        <li>Routage</li>
                        <li>Diagnostic réseau</li>
                    </ul>

                </div>


                <div class="skill">

                    <h3>🔐 VPN &amp; Sécurité</h3>

                    <ul>
                        <li>OpenVPN</li>
                        <li>WireGuard</li>
                        <li>iptables</li>
                        <li>Pare-feu</li>
                        <li>Sécurisation SSH</li>
                    </ul>

                </div>


                <div class="skill">

                    <h3>🐳 DevOps &amp; Serveurs</h3>

                    <ul>
                        <li>Docker</li>
                        <li>VirtualBox</li>
                        <li>Apache2</li>
                        <li>MariaDB / MySQL</li>
                        <li>Git / GitHub</li>
                        <li>Cloudflare Tunnel</li>
                    </ul>

                </div>

            </div>

        </section>


        <!-- PROJETS -->
        <section class="section">

            <h2 class="section-title">
                Projets informatiques
            </h2>

            <div class="projects">


                <div class="project">

                    <h3>🔐 Serveur VPN</h3>

                    <p class="technologies">
                        Ubuntu Server · OpenVPN · WireGuard · iptables
                    </p>

                    <p>
                        Installation et configuration d'un serveur VPN
                        sous Ubuntu. Configuration du réseau, du routage,
                        du transfert IP et du NAT.
                    </p>

                </div>


                <div class="project">

                    <h3>🌐 Serveur Web Apache</h3>

                    <p class="technologies">
                        Ubuntu · Apache2 · VirtualHost
                    </p>

                    <p>
                        Installation et configuration d'un serveur web
                        Apache avec création d'un VirtualHost et
                        hébergement d'un site.
                    </p>

                </div>


                <div class="project">

                    <h3>🗄️ Serveur MariaDB</h3>

                    <p class="technologies">
                        Linux · MariaDB · SQL
                    </p>
<p><strong> Niveau débutant</strong></p>
                    <p>
                        Installation et configuration d'une base de données
                        MariaDB avec création de bases, utilisateurs
                        et permissions.
                    </p>

                </div>


                <div class="project">

                    <h3>📝 WordPress</h3>

                    <p class="technologies">
                        WordPress · PHP · Apache2 · MariaDB
                    </p>

                    <p>
                        Installation et configuration de WordPress
                        sur un serveur Ubuntu avec Apache2, PHP
                        et MariaDB.
                    </p>

                </div>






                <div class="project">

                    <h3>🖥️ Installation de Linux sur pc HP Windows</h3>

                    <p class="technologies">
                        Linux · Windows · Administration système
                    </p>

                    <p>
                        Installation et configuration d'une distribution Linux sur un PC HP
                    sous Windows, gestion du démarrage UEFI/Dual Boot et paramétrage
                   de l'environnement système. Projet réalisé individuellement et
                   validé par le professeur.
                    </p>

                </div>


                <div class="project">

                    <h3>🐳 Docker</h3>

                    <p class="technologies">
                        Linux · Docker · Conteneurs
                    </p>

                    <p>
                        Mise en pratique de la conteneurisation avec
                        Docker et déploiement de services dans
                        des conteneurs.
                    </p>

                </div>


                <div class="project">

                    <h3>☁️ Cloudflare Tunnel</h3>

                    <p class="technologies">
                        Linux · Cloudflare · Tunnel
                    </p>

                    <p>
                        Mise en place d'un tunnel permettant
                        d'exposer un service web local de manière
                        sécurisée.
                    </p>

                </div>

            </div>

        </section>


        <!-- EXPERIENCE -->
        <section class="section">

            <h2 class="section-title">
                Expériences professionnelles
            </h2>


            <div class="experience">

                <h3>
                    Animateur périscolaire — Mairie de Verneuil-sur-seine 78480
                </h3>

                <div class="date">
                    Déc.2025 – Juil.2026
                </div>

                <p>
                    Encadrement des enfants, travail en équipe,
                    organisation des activités et respect des consignes.
                </p>

            </div>


            <div class="experience">

                <h3>
                    Equipier Polyvalent - Mcdo - Orgeval(78)
                </h3>

                <div class="date">
                    Sep.2026 à aujourd'hui
                </div>

                <p>
                    Travail en équipe, autonomie et respect
                    des consignes de sécurité.
                </p>

            </div>


            <div class="experience">

                <h3>
                    Equipier Polyvalent - Burger King - Flins-sur-seine
                </h3>

                <div class="date">
                    Déc.2025 - Jan.2026
                </div>

                <p>
                    Travail en équipe, respect des procédures
                    et organisation du travail.
                </p>

            </div>

        </section>


        <!-- FORMATION -->
        <section class="section">

            <h2 class="section-title">
                Formation
            </h2>


            <div class="formation">

                <h3>
                    CNAM - Paris
                </h3>

                <p>
                    Développement et Exploitation de Parcs Informatiques (DSP)- DevOp's 1er année
                </p>

                <strong>
                    2026 – 2027
                </strong>

            </div>


           


            <div class="formation">

                <h3>
                    BTS CIEL - CNED
                </h3>

                <p>
                    Cybersécurité, Informatique et réseaux,
                    Électronique — option Informatique et Réseaux
</p>
                    <strong>2025 - 2026</strong>
            

            </div>




<div class="formation">

                <h3>
                    Université Sorbonne paris Nord
                </h3>

                <p>
                    Licence Physique chimie 1
                </p>

                <strong>
                    2024 – 2025
                </strong>

            </div>



        </section>


        <!-- RECHERCHE DE STAGE -->
        <section class="section">

            <div class="stage">

                <h2>
                    🔎 Recherche de stage
                </h2>

                <h3>
                    Stage informatique — 2 mois
                </h3>

                <p>
                    <strong>À partir du 1er mars 2027 pour le stage.</strong>
                </p>



                <p>
                    Je recherche un stage dans les domaines du
                    support informatique, systèmes et réseaux,
                    administration Linux ou DevOps junior.
                </p>

                <p><strong>Je recherche à partir de septembre 2027 une alternance en informatique 2ème année.</strong></p>

            </div>

        </section>


        <!-- CONTACT -->
        <section class="section" id="contact">

            <div class="contact">

                <h2>
                    Contact
                </h2>

                <p>
                    <strong>Koua Ebrin Jean Ives</strong>
                </p>

                <p>
                    📧
                    <a href="mailto:votre-email@example.com">
                        ebrinjeanivesk@gmail.com
                    </a>
                </p>

                <p>
    <a href="+33758233258">+33758233258</a>
                </p>

                <p>
                        <a href="https://github.com/kejives">💻 GitHub</a>
 ·     <a href="https://www.linkedin.com/in/ebrinjeanives-koua/">💻 Linkedln</a>

                </p>

            </div>

        </section>

    </main>

</div>
