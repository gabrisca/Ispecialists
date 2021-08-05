<template>
    <body class="d-flex flex-column">
        <!-- For demo purpose -->
        <div class="container-fluid flex-grow-1 flex-shrink-0">
            <div class="px-lg-5">
                <div class="row py-5">
                    <div class="col-lg-12 mx-auto text-white text-center">
                        <h1 class="display-4">iSpecialists</h1>
                        <p class="lead mb-0">
                            Il futuro delle piattaforme mediche
                        </p>
                    </div>
                </div>
            </div>
        </div>
        <!-- End -->

        <!-- Footer -->
        <footer class="bg-white">
            <div class="container py-5">
                <div class="row py-4">
                    <div class="col-lg-4 col-md-6 mb-4 mb-lg-0">
                        <img
                            src="https://www.pngjoy.com/pngl/867/10215693_doctor-icon-physician-png-download.png"
                            alt=""
                            height="130"
                            width="130"
                            class="mb-3"
                        />
                        <p class="font-italic text-muted">
                            Per rimanere aggiornato seguici sui nostri social
                        </p>
                        <ul class="list-inline mt-4">
                            <li class="list-inline-item">
                                <a href="#" target="_blank" title="twitter"
                                    ><i class="fab fa-facebook-square"></i
                                ></a>
                            </li>
                            <li class="list-inline-item">
                                <a href="#" target="_blank" title="facebook"
                                    ><i class="fab fa-linkedin"></i
                                ></a>
                            </li>
                            <li class="list-inline-item">
                                <a href="#" target="_blank" title="instagram"
                                    ><i class="fab fa-youtube"></i
                                ></a>
                            </li>
                            <li class="list-inline-item">
                                <a href="#" target="_blank" title="pinterest"
                                    ><i class="fab fa-instagram"></i
                                ></a>
                            </li>
                            <li class="list-inline-item">
                                <a href="#" target="_blank" title="vimeo"
                                    ><i class="fab fa-twitter-square"></i
                                ></a>
                            </li>
                        </ul>
                    </div>
                    <div class="col-lg-2 col-md-6 mb-4 mb-lg-0">
                        <h6 class="text-uppercase font-weight-bold mb-4">
                            F.A.Q
                        </h6>
                        <ul class="list-unstyled mb-0">
                            <li class="mb-2">
                                <router-link
                                    class="mb-2 text-muted"
                                    :to="{ name: 'team' }"
                                    >Chi</router-link
                                >
                            </li>
                            <li class="mb-2">
                                <router-link
                                    class="mb-2 text-muted"
                                    :to="{ name: 'team' }"
                                    >Dove?</router-link
                                >
                            </li>
                            <li class="mb-2">
                                <router-link
                                    class="mb-2 text-muted"
                                    :to="{ name: 'team' }"
                                    >Quando?</router-link
                                >
                            </li>
                            <li class="mb-2">
                                <router-link
                                    class="mb-2 text-muted"
                                    :to="{ name: 'team' }"
                                    >Perché?</router-link
                                >
                            </li>
                        </ul>
                    </div>
                    <div class="col-lg-2 col-md-6 mb-4 mb-lg-0">
                        <h6 class="text-uppercase font-weight-bold mb-4">
                            The Company
                        </h6>
                        <ul class="list-unstyled mb-0">
                            <li class="mb-2">
                                <router-link
                                    class="mb-2 text-muted"
                                    :to="{ name: 'team' }"
                                    >Team3</router-link
                                >
                            </li>
                            <li class="mb-2">
                                <router-link
                                    class="mb-2 text-muted"
                                    :to="{ name: 'team' }"
                                    >Chi siamo</router-link
                                >
                            </li>
                            <li class="mb-2">
                                <router-link
                                    class="mb-2 text-muted"
                                    :to="{ name: 'team' }"
                                    >Cosa facciamo</router-link
                                >
                            </li>
                            <li class="mb-2">
                                <router-link
                                    class="mb-2 text-muted"
                                    :to="{ name: 'team' }"
                                    >Domande?</router-link
                                >
                            </li>
                        </ul>
                    </div>
                    <div class="col-lg-4 col-md-6 mb-lg-0">
                        <img style="width:100%" src="../../../public/img/anticovid.png" alt="">
                    </div>
                </div>
            </div>

            <!-- Copyrights -->
            <div class="bg-light py-4">
                <div class="container text-center">
                    <p class="text-muted mb-0 py-2">
                        © 2021 Team3 All rights reserved
                    </p>
                </div>
            </div>
        </footer>
        <!-- End -->
    </body>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
body {
    background: #ff5f6d;
    background: -webkit-linear-gradient(to right, #26a69a, #b2dfdb);
    background: linear-gradient(to right, #26a69a, #b2dfdb);
    min-height: 50vh;
}

#button-addon1 {
    color: #b2dfdb;
}

i {
    color: #b2dfdb;
}

.form-control::placeholder {
    font-size: 0.95rem;
    color: #aaa;
    font-style: italic;
}

.form-control.shadow-0:focus {
    box-shadow: none;
}
</style>
