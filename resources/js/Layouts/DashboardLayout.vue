<template>
    <html>
        <head>
            <meta charset="utf-8" />
            <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no" />
            <meta name="description" content="Start your development with a Dashboard for Bootstrap 4." />
            <meta name="author" content="Creative Tim" />
            <title>Argon Dashboard PRO - Premium Bootstrap 4 Admin Template</title>

            <link rel="canonical" href="https://www.creative-tim.com/product/argon-dashboard-pro" />
            <meta name="keywords"
                content="dashboard, bootstrap 4 dashboard, bootstrap 4 design, bootstrap 4 system, bootstrap 4, 
                bootstrap 4 uit kit, bootstrap 4 kit, argon, argon ui kit, creative tim, html kit, html css template, 
                web template, bootstrap, bootstrap 4, css3 template, frontend, responsive bootstrap template, bootstrap 
                ui kit, responsive ui kit, argon dashboard" />
            <meta name="description" content="Start your development with a Dashboard for Bootstrap 4." />

            <meta itemprop="name" content="Argon - Premium Dashboard for Bootstrap 4 by Creative Tim" />
            <meta itemprop="description" content="Start your development with a Dashboard for Bootstrap 4." />
            <meta itemprop="image"
                content="https://s3.amazonaws.com/creativetim_bucket/products/137/original/opt_adp_thumbnail.jpg" />

            <meta name="twitter:card" content="product" />
            <meta name="twitter:site" content="@creativetim" />
            <meta name="twitter:title" content="Argon - Premium Dashboard for Bootstrap 4 by Creative Tim" />
            <meta name="twitter:description" content="Start your development with a Dashboard for Bootstrap 4." />
            <meta name="twitter:creator" content="@creativetim" />
            <meta name="twitter:image"
                content="https://s3.amazonaws.com/creativetim_bucket/products/137/original/opt_adp_thumbnail.jpg" />

            <meta property="fb:app_id" content="655968634437471" />
            <meta property="og:title" content="Argon - Premium Dashboard for Bootstrap 4 by Creative Tim" />
            <meta property="og:type" content="article" />
            <meta property="og:url" content="https://demos.creative-tim.com/argon-dashboard/index.html" />
            <meta property="og:image"
                content="https://s3.amazonaws.com/creativetim_bucket/products/137/original/opt_adp_thumbnail.jpg" />
            <meta property="og:description" content="Start your development with a Dashboard for Bootstrap 4." />
            <meta property="og:site_name" content="Creative Tim" />

            <link rel="icon" href="../../assets/img/brand/favicon.png" type="image/png" />
        </head>
        <body>
            <SideBar />
            <div class="main-content" id="panel">
                <NavBar />
                <slot name="header" />
                <div class="container-fluid mt--6">
                    <slot name="content" />
                    <Footer />
                </div>
            </div>
        </body>
    </html>
</template>

<script setup>

    import SideBar from '../Components/Dashboard/SideBar.vue';
    import NavBar from '../Components/Dashboard/NavBar.vue';
    import Footer from '../Components/Footer.vue';
    
</script>

<style>
</style>