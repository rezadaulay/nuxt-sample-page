<template>
    <div id="header">
        <b-navbar toggleable="lg" type="light">
            <div class="container">
                <b-navbar-brand href="/"><img src="~/static/img/elemes-logo.png" alt=""></b-navbar-brand>
                <b-btn variant="primary" class="d-lg-none">Daftar Sekarang</b-btn>
                <!-- <b-navbar-toggle target="nav-collapse"></b-navbar-toggle> -->

                <b-collapse id="nav-collapse" is-nav>
                    <b-navbar-nav class="mx-auto">
                        <b-nav-item href="#">Home</b-nav-item>
                        <b-nav-item href="#">About</b-nav-item>
                        <b-nav-item href="#" class="promotions">Promotions <b-badge variant="danger">HOT</b-badge></b-nav-item>
                        <b-nav-item href="#">Blogs</b-nav-item>
                        <b-nav-item href="#">Contact Us</b-nav-item>
                    </b-navbar-nav>

                    <b-navbar-nav class="ml-auto">
                        <b-nav-item href="#" right>Masuk</b-nav-item>
                        <b-nav-item href="#" right class="signup">
                            Daftar Sekarang
                        </b-nav-item>
                    </b-navbar-nav>
                </b-collapse>
            </div>
        </b-navbar>
    </div>
</template>