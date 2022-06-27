<template>
<footer class="footer">
    <div class="content has-text-centered">
        <div class="socials">
            <a target="_blank" href="https://www.linkedin.com/in/lieke-van-der-zee/" class="social"
            ><i class="fa-brands fa-linkedin"></i
            ></a>
            <a target="_blank" href="https://github.com/AlycaMaris" class="social github"
            ><i class="fa-brands fa-github"></i
            ></a>
            <a target="_blank" href="mailto:me@liekevanderzee.com" class="social"
            ><i class="fa-solid fa-envelope"></i
            ></a>
        </div>
        <p class="copyright">
            Made with <i class="fa-solid fa-heart"></i> &copy; {{ new Date().getFullYear() }}
        </p>
    </div>
</footer>
</template>

<style scoped>

.footer {
    background-color: #393939;
    color: #EFF0EB;
}
.socials {
    text-align: center;
    padding-bottom: 15px;
}
.social {
    font-size: 24px;
    width: 40px;
    height: 40px;
    line-height: 40px;
    display: inline-block;
    text-align: center;
    margin: 0 8px;
    color: inherit;

}

.social:hover {
    color: #549E54;
}
.copyright {
    text-align: center;
    font-size: 15px;
    font-weight: bold;

    margin-bottom: 0;
}
</style> 