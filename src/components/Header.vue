<template>
    <div>
    <header id="home" class="header slider-fade" data-scroll-index="0">
    <div class="owl-carousel owl-theme">
        <!-- The opacity on the image is made with "data-overlay-dark="number". You can change it using the numbers 0-9. -->
        <div class="text-right item bg-img" data-overlay-dark="3" data-background="/img/slider/1.jpg">
            <div class="v-middle caption mt-30">
                <div class="container">
                    <div class="row">
                        <div class="col-md-7 offset-md-5">
                                <h1>Home</h1>
                                <p id="p">Architecture viverra tellus nec massa dictum the euismoe.
                                    <br>Curabitur viverra the posuere aukue velit.
                                </p>
                                <div class="butn-light mt-30 mb-30"><a href="/item/bauen-architecture-interior-template/30110777.html" target="_blank"><span>Contact</span></a></div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div class="text-right item bg-img" data-overlay-dark="4" data-background="/img/slider/2.jpg">
            <div class="v-middle caption mt-30">
                <div class="container">
                    <div class="row">
                        <div class="col-md-7 offset-md-5">
                                <h1>Home</h1>
                                <p id="p">Architecture viverra tellus nec massa dictum the euismoe.
                                    <br>Curabitur viverra the posuere aukue velit.
                                </p>
                                <div class="butn-light mt-30 mb-30"><a href="/item/bauen-architecture-interior-template/30110777.html" target="_blank"><span>Buyurtma</span></a></div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <!-- Corner -->
    <div class="hero-corner"></div>
    <div class="hero-corner3"></div>
    <!-- Left Panel -->
    <div class="left-panel">
        <ul class="social-left clearfix">
            <li><a style="font-size: 18px;" href="#"><i class="fab fa-telegram-plane"></i></a></li>
            <li><a href="#"><i class="ti-instagram"></i></a></li>
            <li><a href="#"><i class="ti-twitter"></i></a></li>
            <li><a href="#"><i class="ti-facebook"></i></a></li>
        </ul>
    </div>
        </header>
        <section class="content-lines-wrapper">
            <div class="content-lines-inner">
                <div class="content-lines"></div>
            </div>
        </section> 
        <nav class="navbar navbar-expand-lg">
        <div class="small-lg">
        <!-- Logo -->
        <div class="logo-wrapper valign">
            <div class="logo">
                <a href="#">
                    <img src="img/logo.png" class="logo-img" alt="">
                    <h2>IDEAL<span>NAFIS DIZAYN</span></h2>
                </a>
            </div>
        </div>

        <!-- Responsive Language -->
   
        <li class="nav-item-lan dropdown res-lan">

                <a class="text-warning" href="/?clang=ru"><img src="https://cdn.countryflags.com/thumbs/russia/flag-400.png" alt="ru flag"
                    style="width: 30px; height: 20px;">Ru</a>
        </li>

        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent"
            aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation"> <span
                class="icon-bar"><i class="ti-line-double"></i></span> </button>

         </div>
        <!-- Navbar links -->
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav ml-auto">
                <li class="nav-item"><a class="nav-link active" href="#" data-scroll-nav="0">Home</a></li>
                <li class="nav-item"><a class="nav-link" href="#" data-scroll-nav="1">About</a></li>
                <li class="nav-item"><router-link class="nav-link" to="/Project" data-scroll-nav="2">Project</router-link></li>
                <li class="nav-item"><a class="nav-link" href="#" data-scroll-nav="3">Services</a></li>
                <li class="nav-item"><a class="nav-link" href="#" data-scroll-nav="4">Team</a></li>
                <li class="nav-item"><a class="nav-link" href="#" data-scroll-nav="5">Contact</a></li>
                <li class="nav-item dropdown nav-lan desktop-lan" style="display: flex; justify-content: center; align-items: center; width: 200px;">
                        <a class="text-warning" href="/?clang=ru"><img src="https://cdn.countryflags.com/thumbs/russia/flag-400.png" alt="ru flag"
                            style="width: 30px; height: 20px;">Ru</a>
                </li>
                <li class="nav-item dropdown eye">
                    <a class="nav-link apperance-btn dropdown-toggle" href="#" id="apperanceDropdown" role="button"
                        data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
                        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/6/68/Eye_open_font_awesome.svg/512px-Eye_open_font_awesome.svg.png"
                            style="width: 30px; height: 30px;" alt="#"></a>

                    <ul style="left: -50px;" class="dropdown-menu show" aria-labelledby="navbarDropdown">
                        <div class="apperance-item">
                            <div class="special-title">
                            </div>
                            <div class="app-item-stat zaif-button">
                                <div class="btn btn-secondary normal" data-name="normal" data-toggle="tooltip"
                                    data-placement="top" title="Оддий кўриниш"> A </div>
                                <div class="btn btn-secondary white-black" data-name="blackAndWhite"
                                    data-toggle="tooltip" data-placement="top" title="Оқ-қора"> A </div>
                                <div class="btn btn-secondary black" data-name="blackAndWhiteInvert"
                                    data-toggle="tooltip" data-placement="top" title="Қорайтирилган"> A </div>
                            </div>
                        </div>
                        <div class="apperance-item">
                            <div class="special-title">
                            </div>
                            <div class="app-item-stat zaif-shrift">
                                <input type="range" min="0" max="100" value="0" step="10" class="slider" id="fontRange">
                            </div>
                        </div>
                    </ul>
                </li>
                <li class="nav-item" style="display: flex;">
                    <div class="search-box">
                        <input class="search-txt" name="keyword" type="search">
                        <button data-search="next" class="btn-search">&darr;</button>
                        <button data-search="prev" class="btn-search">&uarr;</button>
                        <button data-search="clear" class="btn-search">✖</button>
                    </div>
                    <button class="search-btn" id="search-btn">
                        <i class="fas fa-search"></i>
                    </button>
                </li>
            </ul>
        </div>
        </nav>
    </div>
</template>

<script>
export default {
    name: "Header",
}
</script>