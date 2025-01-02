<template>
    <div class="default">
        <div class="container">
            <div class="content">
                <nav class="navbar" role="navigation" aria-label="main navigation">
                    <div class="navbar-brand">
                        <a class="navbar-item" href="/">
                            <img class="imglogo" src="/images/logo.png" alt="Fucina del Tag srl">
                        </a>

                        <button class="button navbar-burger" onclick="document.querySelector('.navbar-menu').classList.toggle('is-active');">
                            <span></span>
                            <span></span>
                            <span></span>
                        </button>
                    </div>
                </nav>
                <!-- <nav class="navbar" role="navigation" aria-label="main navigation">
                    <div class="navbar-menu">
                        <div class="navbar-start">
                            <a v-for="item in menuItems" class="navbar-item" v-bind:href="'/' + item.link" v-bind:class="item.isActive">{{item.name}}</a>
                        </div>
                    </div>
                </nav> -->
                <section class="hero is-primary is-bold">
                    <div class="hero-body">
                        <div class="container">
                            <h1 class="title">
                                Fucina del Tag
                            </h1>
                            <h2 class="subtitle">
                                Web Marketing e Sviluppo Tecnico
                            </h2>
                        </div>
                    </div>
                </section>

                <nuxt />


            </div>
        </div>
        <footer class="footer">
            <div class="container">

                <div class="columns">
                    <div class="column">
                        <p class="title is-4">
                            Perché scegliere Fucina del Tag
                        </p>
                        <ol>
                            <li>
                                <strong>Lavoriamo per raggiungere i VOSTRI obiettivi</strong>, non i NOSTRI!
                            </li>
                            <li>
                                Se quello che volete da noi non vi porta risultati, <strong>vi consigliamo di NON farlo</strong>
                            </li>
                            <li>
                                <strong>Curiamo internamente tutti gli aspetti</strong> di una campagna marketing
                            </li>
                            <li>
                                <strong>Siamo agili, veloci ed efficaci</strong>. Programmatore, copy, art director, digital advertiser... abbiamo tutte le professionalità al nostro interno.
                            </li>
                            <li>
                                <strong>Non devi preoccuparti di gestire diversi fornitori. Gestiamo noi tutta la filiera</strong>, dalla produzione della creatività, alla gestione dei canali pubblicitari, alla tecnologia.
                            </li>
                            <li>
                                <strong>Ci prendiamo le nostre responsabilità</strong>. Quando sbagliamo sappiamo ammetterlo e agire per rimediare.
                            </li>
                        </ol>
                    </div>
                    <div id="form" class="column">
                        <p class="title is-4">
                            Richiedi un Preventivo
                        </p>
                        <p class="subtitle is-6">
                            Scrivici un messaggio e ti risponderemo il prima possibile.
                        </p>
                        <section>
                            <form accept-charset="UTF-8" action="https://formkeep.com/f/5fb420fec4c8" method="POST">
                                <div class="field">
                                    <label class="label is-small">Email:</label>
                                    <p class="control">
                                        <input required class="input" type="email" name="email" placeholder="Email">
                                    </p>
                                </div>
                                <div class="field">
                                    <label class="label is-small">Messaggio:</label>
                                    <p class="control">
                                        <textarea required class="textarea" name="messaggio" placeholder="Messaggio"></textarea>
                                    </p>
                                </div>
                                <div class="control has-text-centered">
                                    <button class="button is-warning">Invia la tua richiesta!</button>
                                </div>
                            </form>

                        </section>
                    </div>
                    <div class="column has-text-centered">

                        <div class="has-text-centered">
                            <strong>Fucina del Tag srl</strong>
                            <br> V.le Monza, 259
                            <br>20126 Milano
                            <br>P.IVA 12077140965

                        </div>
                        <br>
                        <div>
                            <a href="//www.iubenda.com/privacy-policy/369660" class="iubenda-white no-brand iubenda-embed" title="Privacy Policy">Privacy Policy</a>
                        </div>
                    </div>

                </div>
            </div>
        </footer>
    </div>
</template>

<style></style>
