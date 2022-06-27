<template>
    <nav class="navbar is-primary">
        <div class="containernav">
            <div class="navbar-brand">
                <div class="buttons socials">
                    <a target="_blank" href="https://www.linkedin.com/in/lieke-van-der-zee/" class="social git-button"
                    ><i class="fa-brands fa-linkedin"></i
                    ></a>
                    <a target="_blank" href="https://github.com/AlycaMaris" class="social git-button"
                    ><i class="fa-brands fa-github"></i
                    ></a>
                    <a target="_blank" href="mailto:me@liekevanderzee.com" class="social git-button"
                    ><i class="fa-solid fa-envelope"></i
                    ></a>
                </div>
            </div>
        </div>
    </nav>
</template>

<style>
.containernav {
    margin: auto;
    text-align: center;
}

.socials {
    padding-bottom: 15px;
}

.git-button {
    text-decoration: none;
    color: white;
    transition: all 0.1s ease;
}

.git-button:hover {
    color: #549E54;
}

.social:hover {
    opacity: 0.9;
}

.navi {
    margin: auto;
    text-align: center;
    color: #EFF0EB;
}

.git-button {
    text-decoration: none;
    color: white;
    margin-right: 1.5rem;
    margin-left: 1.5rem;
    margin-top: 1.5rem;
    font-size: 3rem;
    transition: all 0.1s ease;
}

</style>