<template>
    <div>
        <section class="content-lines-wrapper">
    <div class="content-lines-inner">
        <div class="content-lines"></div>
    </div>
        </section> 
        <section class="banner-header banner-img valign bg-img bg-fixed" data-overlay-light="3" data-background="img/banner.jpg">
            <div class="left-panel"></div>
        </section>
        <section class="section-padding2">
            <div class="container">
                <div class="row">
                    <div class="col-md-12">
                        <h2 class="section-title2">title</h2>
                    </div>
                </div>
                <div class="row">
                    <div class="col-md-8">
                            <p>description</p>
                    </div>
                    <div class="col-md-4">
                        <p><b>Year : </b>year</p>
                        <p><b>Company : </b>firma</p>
                            <p><b>Project Name : </b>project_name</p>
                            <p><b>Location : </b>location</p>
                    </div>
                </div> 
                <div class="row mt-30"> 
                    <div class="col-md-6 gallery-item">
                        <a href="/uploads/projects/1.png" title="title" class="img-zoom">
                            <div class="gallery-box">
                                <div class="gallery-img"> <img style="height: 300px;" src="/uploads/projects/1.png" class="img-fluid mx-auto d-block" alt="work-img"> </div>
                            </div>
                        </a>
                    </div>     
                </div>
            </div>
        </section>
    </div>
</template>

<script>
export default {
    name: "Project",
}
</script>

<style scoped>
.nav-link{
        color: #272727 !important;
        transition: all 0.5s ease;
    }
    .nav-link:hover{ 
        color: #b19777 !important;
    }
    .pro_top{
        width: 100%;
        height: 200px;
    }
</style>