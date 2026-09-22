/* =========================================================
   ABHILESH KUMAR — PROFESSIONAL PORTFOLIO
   Dark Navy / Electric Blue / Glassmorphism
   ========================================================= */

:root {
    --bg: #050d1a;
    --bg-soft: #081426;
    --surface: rgba(12, 29, 52, 0.78);
    --surface-strong: #0b1c32;
    --surface-light: rgba(23, 51, 86, 0.55);

    --blue: #2f8cff;
    --blue-light: #66b1ff;
    --blue-dark: #1767d2;

    --text: #f7faff;
    --text-soft: #c7d6e8;
    --text-muted: #8fa6c0;

    --border: rgba(117, 169, 230, 0.16);
    --border-blue: rgba(47, 140, 255, 0.45);

    --shadow: 0 20px 60px rgba(0, 0, 0, 0.30);
    --blue-glow: 0 0 45px rgba(47, 140, 255, 0.22);

    --radius: 18px;
    --transition: 0.3s ease;
}

/* =========================================================
   RESET
   ========================================================= */

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

html {
    scroll-behavior: smooth;
}

body {
    font-family: Inter, "Segoe UI", Arial, Helvetica, sans-serif;
    background:
        radial-gradient(circle at 80% 10%, rgba(47, 140, 255, 0.10), transparent 28%),
        radial-gradient(circle at 10% 40%, rgba(47, 140, 255, 0.06), transparent 25%),
        var(--bg);
    color: var(--text);
    line-height: 1.6;
    overflow-x: hidden;
}

body::before {
    content: "";
    position: fixed;
    inset: 0;
    pointer-events: none;
    z-index: -1;
    background-image:
        linear-gradient(rgba(255,255,255,0.018) 1px, transparent 1px),
        linear-gradient(90deg, rgba(255,255,255,0.018) 1px, transparent 1px);
    background-size: 60px 60px;
    mask-image: linear-gradient(to bottom, black, transparent 80%);
}

a {
    text-decoration: none;
    color: inherit;
}

ul {
    list-style: none;
}

img {
    max-width: 100%;
    display: block;
}

button,
input,
textarea {
    font: inherit;
}

/* =========================================================
   HEADER / NAVBAR
   ========================================================= */

header {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    z-index: 1000;

    background: rgba(5, 13, 26, 0.78);
    backdrop-filter: blur(18px);
    -webkit-backdrop-filter: blur(18px);

    border-bottom: 1px solid rgba(255, 255, 255, 0.06);
}

.navbar {
    max-width: 1240px;
    height: 76px;
    margin: auto;
    padding: 0 28px;

    display: flex;
    align-items: center;
    justify-content: space-between;
}

.logo {
    font-size: 27px;
    font-weight: 800;
    letter-spacing: -0.8px;
    color: var(--text);
}

.logo span {
    color: var(--blue);
}

.nav-links {
    display: flex;
    align-items: center;
    gap: 34px;
}

.nav-links a {
    position: relative;
    color: var(--text-soft);
    font-size: 15px;
    font-weight: 600;
    padding: 27px 0;
    transition: var(--transition);
}

.nav-links a::after {
    content: "";
    position: absolute;
    left: 50%;
    bottom: 17px;
    width: 0;
    height: 2px;
    border-radius: 10px;
    background: var(--blue);
    transform: translateX(-50%);
    transition: var(--transition);
    box-shadow: 0 0 12px rgba(47, 140, 255, 0.8);
}

.nav-links a:hover,
.nav-links a.active {
    color: #ffffff;
}

.nav-links a:hover::after,
.nav-links a.active::after {
    width: 100%;
}

.menu-icon {
    display: none;
    font-size: 25px;
    color: #fff;
    cursor: pointer;
}

/* =========================================================
   COMMON SECTION
   ========================================================= */

.section {
    padding: 110px 25px;
    max-width: 1240px;
    margin: auto;
}

.section-title {
    position: relative;
    width: fit-content;
    margin: 0 auto 55px;
    text-align: center;

    font-size: clamp(30px, 4vw, 42px);
    line-height: 1.15;
    font-weight: 800;
    letter-spacing: -1px;
}

.section-title::after {
    content: "";
    display: block;
    width: 55px;
    height: 4px;
    margin: 15px auto 0;
    border-radius: 20px;
    background: linear-gradient(90deg, var(--blue-dark), var(--blue-light));
    box-shadow: 0 0 18px rgba(47, 140, 255, 0.5);
}

/* =========================================================
   HERO
   ========================================================= */

.hero {
    position: relative;
    min-height: 100vh;
    max-width: 1240px;
    margin: auto;

    padding: 125px 28px 75px;

    display: flex;
    align-items: center;
    justify-content: space-between;
    gap: 65px;
}

.hero::before {
    content: "";
    position: absolute;
    width: 520px;
    height: 520px;
    right: -140px;
    top: 110px;
    border-radius: 50%;
    background: rgba(47, 140, 255, 0.13);
    filter: blur(80px);
    pointer-events: none;
}

.hero-content {
    position: relative;
    z-index: 2;
    flex: 1;
    max-width: 700px;
}

.small-title {
    display: inline-flex;
    align-items: center;
    gap: 9px;

    padding: 8px 15px;
    margin-bottom: 22px;

    color: #ddecff;
    font-size: 14px;
    font-weight: 700;

    border: 1px solid rgba(47, 140, 255, 0.25);
    border-radius: 30px;
    background: rgba(47, 140, 255, 0.10);

    box-shadow: inset 0 0 18px rgba(47, 140, 255, 0.06);
}

.small-title::before {
    content: "";
    width: 8px;
    height: 8px;
    border-radius: 50%;
    background: #19e68c;
    box-shadow: 0 0 12px rgba(25, 230, 140, 0.8);
}

.hero h1 {
    font-size: clamp(43px, 6vw, 68px);
    line-height: 1.04;
    letter-spacing: -2.5px;
    margin-bottom: 22px;
    font-weight: 850;
}

.hero h1 span {
    color: var(--blue);
    text-shadow: 0 0 35px rgba(47, 140, 255, 0.20);
}

.hero h2 {
    color: #e9f2ff;
    font-size: clamp(22px, 3vw, 30px);
    line-height: 1.3;
    margin-bottom: 22px;
    font-weight: 700;
}

.hero-description {
    max-width: 650px;
    color: var(--text-soft);
    font-size: 17px;
    line-height: 1.85;
    margin-bottom: 32px;
}

.hero-buttons {
    display: flex;
    align-items: center;
    flex-wrap: wrap;
    gap: 14px;
    margin-bottom: 30px;
}

.btn {
    display: inline-flex;
    align-items: center;
    justify-content: center;
    min-height: 52px;
    padding: 0 25px;

    border-radius: 30px;
    font-weight: 700;
    font-size: 15px;

    transition: transform var(--transition),
                box-shadow var(--transition),
                background var(--transition),
                border-color var(--transition);
}

.btn:hover {
    transform: translateY(-3px);
}

.primary-btn {
    color: #fff;
    background: linear-gradient(135deg, #2685ff, #1767d2);
    box-shadow: 0 12px 35px rgba(47, 140, 255, 0.28);
}

.primary-btn:hover {
    box-shadow: 0 17px 45px rgba(47, 140, 255, 0.42);
}

.secondary-btn {
    color: #fff;
    border: 1px solid var(--border-blue);
    background: rgba(8, 25, 46, 0.65);
}

.secondary-btn:hover {
    background: rgba(47, 140, 255, 0.12);
    border-color: var(--blue);
}

.social-icons {
    display: flex;
    align-items: center;
    gap: 16px;
}

.social-icons a {
    width: 43px;
    height: 43px;

    display: grid;
    place-items: center;

    border: 1px solid var(--border);
    border-radius: 50%;
    background: rgba(255, 255, 255, 0.035);

    color: #dce9f8;
    transition: var(--transition);
}

.social-icons a:hover {
    color: #fff;
    border-color: var(--blue);
    background: rgba(47, 140, 255, 0.13);
    transform: translateY(-4px);
    box-shadow: 0 8px 25px rgba(47, 140, 255, 0.18);
}

/* HERO PROFILE */

.hero-card {
    position: relative;
    width: 380px;
    display: flex;
    justify-content: center;
    align-items: center;
}

/* Blue glow behind photo */
.hero-card::before {
    content: "";
    position: absolute;
    width: 350px;
    height: 350px;
    border-radius: 50%;
    background: rgba(47, 140, 255, 0.18);
    filter: blur(35px);
}

.photo-circle {
    position: relative;

    width: 430px;
    height: 500px;

    border-radius: 20px 20px 0 0;

    overflow: hidden;

    border: none;

    box-shadow: none;

    z-index: 1;
}

.photo-circle img {
    width: 100%;
    height: 100%;

    object-fit: cover;

    object-position: center top;
}
/* =========================================================
   ABOUT
   ========================================================= */

.about-container {
    display: grid;
    grid-template-columns: 230px minmax(0, 1fr) 230px;
    gap: 55px;
    align-items: center;
}

.about-image {
    display: flex;
    justify-content: center;
}

.about-image img {
    width: 195px;
    height: 240px;
    object-fit: cover;
    object-position: center top;

    border-radius: 16px;
    border: 2px solid var(--blue);

    box-shadow:
        0 20px 45px rgba(0, 0, 0, 0.35),
        0 0 30px rgba(47, 140, 255, 0.16);
}

.about-text {
    max-width: 670px;
}

.about-text h3 {
    position: relative;
    color: #fff;
    font-size: clamp(28px, 3vw, 36px);
    line-height: 1.2;
    margin-bottom: 18px;
}

.about-text h3::before {
    content: "About Me";
    display: block;
    color: var(--blue);
    font-size: 16px;
    font-weight: 700;
    letter-spacing: 0.2px;
    padding-left: 39px;
    margin-bottom: 10px;
}

.about-text h3::after {
    content: "";
    position: absolute;
    top: 9px;
    left: 0;
    width: 29px;
    height: 3px;
    border-radius: 20px;
    background: var(--blue);
    box-shadow: 0 0 12px rgba(47, 140, 255, 0.6);
}

.about-text > p {
    color: var(--text-soft);
    font-size: 16px;
    line-height: 1.85;
    margin-bottom: 22px;
}

.about-box {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 14px;
}

.about-item {
    padding: 16px 8px;
    border-top: 1px solid var(--border);
}

.about-item i {
    color: var(--blue);
    font-size: 22px;
    margin-bottom: 8px;
}

.about-item h4 {
    color: #fff;
    font-size: 14px;
    margin-bottom: 4px;
}

.about-item p {
    color: var(--text-muted);
    font-size: 12px;
}

.about-skills {
    padding-left: 28px;
    border-left: 1px solid rgba(255, 255, 255, 0.10);
}

.about-skills li {
    display: flex;
    align-items: center;
    gap: 12px;
    color: #edf5ff;
    font-size: 15px;
    margin-bottom: 17px;
}

.about-skills li i {
    width: 38px;
    height: 38px;
    display: grid;
    place-items: center;

    border-radius: 50%;
    background: rgba(47, 140, 255, 0.10);
    color: var(--blue);
    border: 1px solid rgba(47, 140, 255, 0.10);
}

/* =========================================================
   SKILLS
   ========================================================= */

.skills-section {
    background: linear-gradient(
        180deg,
        rgba(8, 20, 38, 0.45),
        rgba(4, 14, 27, 0.75)
    );
}

.skills-container {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 20px;
}

.skill-card {
    position: relative;
    overflow: hidden;

    padding: 28px 25px;

    background: linear-gradient(
        145deg,
        rgba(14, 38, 67, 0.88),
        rgba(7, 23, 42, 0.88)
    );

    border: 1px solid var(--border);
    border-radius: var(--radius);

    box-shadow: 0 15px 40px rgba(0, 0, 0, 0.16);

    transition: var(--transition);
}

.skill-card::before {
    content: "";
    position: absolute;
    width: 100px;
    height: 100px;
    top: -55px;
    right: -45px;
    border-radius: 50%;
    background: rgba(47, 140, 255, 0.16);
    filter: blur(5px);
}

.skill-card:hover {
    transform: translateY(-7px);
    border-color: var(--border-blue);
    box-shadow: var(--blue-glow);
}

.skill-card i {
    color: var(--blue);
    font-size: 30px;
}

.skill-card h3 {
    color: #fff;
    margin-top: 14px;
    font-size: 18px;
}

.skill-card p {
    color: var(--text-muted);
    font-size: 14px;
    margin-top: 6px;
}

/* =========================================================
   PROJECTS
   ========================================================= */

.projects-container {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    gap: 24px;
}

.project-card {
    position: relative;
    overflow: hidden;

    padding: 30px;

    background: linear-gradient(
        145deg,
        rgba(13, 34, 60, 0.90),
        rgba(7, 20, 38, 0.92)
    );

    border: 1px solid var(--border);
    border-radius: var(--radius);

    box-shadow: 0 18px 50px rgba(0, 0, 0, 0.18);

    transition: transform var(--transition),
                border-color var(--transition),
                box-shadow var(--transition);
}

.project-card::before {
    content: "";
    position: absolute;
    width: 180px;
    height: 180px;
    right: -90px;
    top: -90px;
    border-radius: 50%;
    background: rgba(47, 140, 255, 0.12);
    filter: blur(10px);
}

.project-card:hover {
    transform: translateY(-8px);
    border-color: var(--border-blue);
    box-shadow: 0 22px 55px rgba(0, 0, 0, 0.28),
                0 0 35px rgba(47, 140, 255, 0.08);
}

.project-icon {
    width: 52px;
    height: 52px;

    display: grid;
    place-items: center;

    margin-bottom: 20px;

    border-radius: 14px;

    color: #fff;
    background: linear-gradient(135deg, #2f8cff, #175fc0);

    box-shadow: 0 10px 25px rgba(47, 140, 255, 0.22);
}

.project-content h3 {
    color: #fff;
    font-size: 21px;
    margin-bottom: 10px;
}

.project-content p {
    color: var(--text-muted);
    font-size: 14px;
    line-height: 1.75;
}

.project-tags {
    display: flex;
    flex-wrap: wrap;
    gap: 8px;
    margin-top: 20px;
}

.project-tags span {
    padding: 6px 11px;

    color: #a9d0ff;
    background: rgba(47, 140, 255, 0.09);

    border: 1px solid rgba(47, 140, 255, 0.14);
    border-radius: 20px;

    font-size: 12px;
    font-weight: 600;
}

.project-buttons {
    display: flex;
    flex-wrap: wrap;
    gap: 10px;
    margin-top: 22px;
}

.project-btn {
    padding: 9px 16px;

    border: 1px solid rgba(47, 140, 255, 0.30);
    border-radius: 20px;

    color: #dcecff;
    background: rgba(47, 140, 255, 0.07);

    font-size: 13px;
    font-weight: 700;

    transition: var(--transition);
}

.project-btn:hover {
    background: var(--blue);
    border-color: var(--blue);
    color: #fff;
}

/* =========================================================
   RESUME
   ========================================================= */

.resume-section {
    position: relative;
    overflow: hidden;
}

.resume-box {
    max-width: 900px;
    margin: auto;
    padding: 50px 40px;

    text-align: center;

    background:
        radial-gradient(circle at 50% 0%, rgba(47, 140, 255, 0.15), transparent 55%),
        linear-gradient(145deg, rgba(13, 36, 64, 0.90), rgba(7, 21, 39, 0.90));

    border: 1px solid var(--border-blue);
    border-radius: 24px;

    box-shadow: var(--shadow);
}

.resume-box h3 {
    font-size: 30px;
    margin-bottom: 10px;
}

.resume-box p {
    color: var(--text-muted);
    max-width: 650px;
    margin: 0 auto 25px;
}

/* =========================================================
   CONTACT
   ========================================================= */

.contact-container {
    display: grid;
    grid-template-columns: 0.9fr 1.1fr;
    gap: 35px;
}

.contact-info,
.contact-form {
    padding: 30px;

    background: rgba(11, 28, 50, 0.78);
    border: 1px solid var(--border);
    border-radius: var(--radius);
    box-shadow: var(--shadow);
}

.contact-item {
    display: flex;
    align-items: center;
    gap: 15px;

    padding: 16px 0;
    border-bottom: 1px solid rgba(255, 255, 255, 0.07);
}

.contact-item:last-child {
    border-bottom: 0;
}

.contact-item i {
    width: 43px;
    height: 43px;

    display: grid;
    place-items: center;

    border-radius: 12px;

    color: var(--blue);
    background: rgba(47, 140, 255, 0.10);
}

.contact-item h4 {
    color: #fff;
    font-size: 14px;
}

.contact-item p,
.contact-item a {
    color: var(--text-muted);
    font-size: 13px;
}

.contact-form input,
.contact-form textarea {
    width: 100%;

    padding: 14px 16px;
    margin-bottom: 14px;

    color: #fff;
    background: rgba(255, 255, 255, 0.035);

    border: 1px solid rgba(255, 255, 255, 0.10);
    border-radius: 12px;

    outline: none;
    transition: var(--transition);
}

.contact-form textarea {
    min-height: 150px;
    resize: vertical;
}

.contact-form input:focus,
.contact-form textarea:focus {
    border-color: var(--blue);
    box-shadow: 0 0 0 3px rgba(47, 140, 255, 0.08);
}

/* =========================================================
   FOOTER
   ========================================================= */

footer {
    padding: 30px 25px;

    background: #030914;
    border-top: 1px solid rgba(255, 255, 255, 0.06);

    color: var(--text-muted);
    text-align: center;
}

.footer-content {
    max-width: 1100px;
    margin: auto;
}

.footer-social {
    display: flex;
    justify-content: center;
    gap: 12px;
    margin-top: 15px;
}

.footer-social a {
    width: 38px;
    height: 38px;
    display: grid;
    place-items: center;

    border-radius: 50%;
    border: 1px solid var(--border);

    transition: var(--transition);
}

.footer-social a:hover {
    color: #fff;
    background: var(--blue);
    border-color: var(--blue);
    transform: translateY(-3px);
}

.copyright {
    margin-top: 15px;
    font-size: 13px;
}

/* =========================================================
   RESPONSIVE — TABLET
   ========================================================= */

@media (max-width: 1000px) {

    .hero {
        gap: 35px;
    }

    .hero-card {
        width: 40%;
        min-width: 290px;
    }

    .profile-circle {
        width: 320px;
        height: 430px;
    }

    .about-container {
        grid-template-columns: 190px minmax(0, 1fr);
    }

    .about-skills {
        grid-column: 1 / -1;
        border-left: 0;
        border-top: 1px solid var(--border);
        padding: 25px 0 0;
        display: grid;
        grid-template-columns: repeat(2, 1fr);
        gap: 5px 30px;
    }
}

/* =========================================================
   RESPONSIVE — MOBILE
   ========================================================= */

@media (max-width: 760px) {

    .navbar {
        height: 68px;
        padding: 0 20px;
    }

    .nav-links {
        position: absolute;
        top: 68px;
        left: 0;
        width: 100%;

        display: none;
        flex-direction: column;
        gap: 0;

        padding: 12px 20px 20px;

        background: rgba(5, 13, 26, 0.98);
        backdrop-filter: blur(18px);

        border-bottom: 1px solid var(--border);
    }

    .nav-links.active {
        display: flex;
    }

    .nav-links a {
        width: 100%;
        padding: 14px 5px;
    }

    .nav-links a::after {
        bottom: 5px;
        left: 0;
        transform: none;
    }

    .menu-icon {
        display: block;
    }

    .hero {
        min-height: auto;
        padding: 110px 20px 70px;
        flex-direction: column-reverse;
        text-align: center;
    }

    .hero-content {
        max-width: 700px;
    }

    .small-title {
        margin-bottom: 18px;
    }

    .hero h1 {
        letter-spacing: -1.5px;
    }

    .hero-description {
        font-size: 15px;
        margin-left: auto;
        margin-right: auto;
    }

    .hero-buttons,
    .social-icons {
        justify-content: center;
    }

    .hero-card {
        width: 100%;
        min-width: 0;
    }

    .profile-circle {
        width: min(310px, 82vw);
        height: 390px;
    }

    .section {
        padding: 80px 20px;
    }

    .about-container {
        grid-template-columns: 1fr;
        text-align: center;
    }

    .about-text {
        margin: auto;
    }

    .about-text h3::before {
        padding-left: 0;
    }

    .about-text h3::after {
        display: none;
    }

    .about-box {
        grid-template-columns: 1fr;
        text-align: center;
    }

    .about-skills {
        grid-template-columns: 1fr 1fr;
        text-align: left;
    }

    .skills-container,
    .projects-container,
    .contact-container {
        grid-template-columns: 1fr;
    }

    .resume-box {
        padding: 38px 22px;
    }
}

@media (max-width: 480px) {

    .logo {
        font-size: 22px;
    }

    .hero h1 {
        font-size: 39px;
    }

    .hero h2 {
        font-size: 20px;
    }

    .hero-buttons {
        flex-direction: column;
        width: 100%;
    }

    .btn {
        width: 100%;
    }

    .profile-circle {
        width: 270px;
        height: 350px;
    }

    .about-skills {
        grid-template-columns: 1fr;
    }

    .project-card,
    .contact-info,
    .contact-form {
        padding: 24px 20px;
    }
}

/* =========================================================
   ACCESSIBILITY / REDUCED MOTION
   ========================================================= */

@media (prefers-reduced-motion: reduce) {
    html {
        scroll-behavior: auto;
    }

    *,
    *::before,
    *::after {
        transition: none !important;
        animation: none !important;
    }
}
