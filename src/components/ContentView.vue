<template>
    <div class="discount text-center">
        <h1 class="font-rubys">Dapatkan discount 10% untuk pembelian ditempat!</h1>
    </div>
    <div class="container  d-flex justify-content-center">
        <img class="logorubys" src="../assets/rubyscake.png" alt="">
    </div>

    <!--Navbar Midle-->
    <div class="">
        <nav class="navbar navbar-midle navbar-expand-lg navbar-light ">
            <div class="container">
                <button class="navbar-toggler " type="button" data-toggle="collapse" data-target="#navbarNav"
                    aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon d-flex"></span>
                </button>
                <div class="collapse navbar-collapse" id="navbarNav">
                    <ul class="navbar-nav mx-auto midle-font">
                        <li class="nav-item">
                            <a class="nav-link" href="#">Home</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#about">About</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#">Catalog</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#contact">Contact</a>
                        </li>
                    </ul>
                </div>
            </div>
        </nav>
    </div>
    <!--Navbar Midle End-->

    <div>
        <div id="carouselExampleIndicators" class="carousel mt-4 shadow  img-carousel slide" data-ride="carousel">
            <ol class="carousel-indicators  ">
                <li data-target="#carouselExampleIndicators" data-slide-to="0" class="active"></li>
                <li data-target="#carouselExampleIndicators" data-slide-to="1"></li>
                <li data-target="#carouselExampleIndicators" data-slide-to="2"></li>
            </ol>
            <div class="carousel-inner ">
                <div class="carousel-item active">
                    <img src="../assets/kue1.jpg" class="d-block w-100 rounded img-carousel" alt="image1">
                    <div class="carousel-caption d-none d-md-block">
                        <h5>Kue Pandan Keju</h5>
                        <p>Kue pandan dengan parutan keju</p>
                    </div>
                </div>
                <div class="carousel-item">
                    <img src="../assets/kue2.jpg" class="d-block w-100" alt="image2">
                    <div class="carousel-caption d-none d-md-block">
                        <h5>Rainbow Cake</h5>
                        <p>Kue dengan banyak warna dan rasa yang manis</p>
                    </div>
                </div>
                <div class="carousel-item">
                    <img src="../assets/kue3.jpg" class="d-block w-100" alt="image3">
                    <div class="carousel-caption d-none d-md-block">
                        <h5>Image 3</h5>
                        <p>Description for Image 3</p>
                    </div>
                </div>
            </div>
            <a class="carousel-control-prev" href="#carouselExampleIndicators" role="button" data-slide="prev">
                <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                <span class="sr-only">Previous</span>
            </a>
            <a class="carousel-control-next" href="#carouselExampleIndicators" role="button" data-slide="next">
                <span class="carousel-control-next-icon" aria-hidden="true"></span>
                <span class="sr-only">Next</span>
            </a>
        </div>

        <div id="about" class="about mt-4">
            <div class="container">
                <div class="row align-items-center">
                    <div class="col">
                        <img class="img-intro" src="../assets/chef.jpg" alt="">
                    </div>
                    <div class="col mt-5">
                        <h1 class=" font-rubys">About Rubys Cake</h1>
                        <div>
                            <p class="font-rubys">
                                Rubys Cake adalah toko kue yang menyediakan bermacam-macam kue seperti kue ulang tahun,
                                kue bolu, kue nastar, roti dan juga hampers. Kue yang diciptakan khas seperti buatan
                                rumahan karena dibuat oleh tangan-tangan ahli seperti ibu rumah tangga.
                                .</p>
                        </div>
                    </div>

                </div>
            </div>
        </div>

        <div class="container " style="margin-top: 200px;">
            <h1 class="text-center font-rubys">Paling Banyak dipesan pada Rubys Cake</h1>
        </div>
        <!--Top Pesan-->
        <div class=" my-5 top-pesan">
            <div class="row ">
                <div class="col-lg-4 col-md-6 col-sm-12 mb-4 mt-4">
                    <div class="card">
                        <img src="../assets/kue-bolu.jpg" class="card-img-top" alt="Image 1"
                            style="width: 100%; height: 200px; object-fit: cover;">
                        <div class="card-body">
                            <h3 class="font-rubys">Kue Bolu</h3>
                            <p class="card-text ">Bolu atau kue bolu adalah kue bulat nan memanjang berbahan dasar
                                tepung, gula, dan telur.</p>
                        </div>
                    </div>
                </div>
                <div class="col-lg-4 col-md-6 col-sm-12 mb-4 mt-4">
                    <div class="card">
                        <img src="../assets/kue-nastar.jpg" class="card-img-top" alt="Image 2"
                            style="width: 100%; height: 200px; object-fit: cover;">
                        <div class="card-body">
                            <h3 class="font-rubys">Kue Nastar</h3>
                            <p class="card-text">Nastar adalah kue kering dari adonan tepung terigu, mentega, dan telur
                                yang diisi dengan selai nanas.</p>
                        </div>
                    </div>
                </div>
                <div class="col-lg-4 col-md-6 col-sm-12 mb-4 mt-4">
                    <div class="card">
                        <img src="../assets/kue-ultah.jpg" class="card-img-top" alt="Image 3"
                            style="width: 100%; height: 200px; object-fit: cover;">
                        <div class="card-body">
                            <h3 class="font-rubys">Kue Ulang Tahun</h3>
                            <p class="card-text">Kue ulang tahun adalah kue lapis dengan hiasan yang disajikan dengan
                                lilin kecil menyala di atasnya.</p>
                        </div>
                    </div>
                </div>
                <div class="col-lg-4 col-md-6 col-sm-12 mb-4 mt-4">
                    <div class="card">
                        <img src="../assets/lapis-legiy.jpg" class="card-img-top" alt="Image 3"
                            style="width: 100%; height: 200px; object-fit: cover;">
                        <div class="card-body">
                            <h3 class="font-rubys">Kue Lapis Legit </h3>
                            <p class="card-text">Lapis legit atau spekuk adalah salah satu jenis kue basah tradisional
                                dari Indonesia</p>
                        </div>
                    </div>
                </div>
                <div class="col-lg-4 col-md-6 col-sm-12 mb-4 mt-4">
                    <div class="card">
                        <img src="../assets/rotipizza.jpg" class="card-img-top" alt="Image 3"
                            style="width: 100%; height: 200px; object-fit: cover;">
                        <div class="card-body">
                            <h3 class="font-rubys">Roti</h3>
                            <p class="card-text">Roti yang tersedia ada beraneka ragam, yang paling lezat adalah roti
                                pizza</p>
                        </div>
                    </div>
                </div>
                <div class="col-lg-4 col-md-6 col-sm-12 mb-4 mt-4">
                    <div class="card">
                        <img src="../assets/hampers.jpg" class="card-img-top" alt="Image 3"
                            style="width: 100%; height: 200px; object-fit: cover;">
                        <div class="card-body">
                            <h3 class="font-rubys">Hampers</h3>
                            <p class="card-text">Di Rubys Cake juga tersedia hampers kue bagi kamu yang membuthkan
                                sebagai hadiah</p>
                        </div>
                    </div>
                </div>

                <!-- Add more columns for additional images -->
            </div>
        </div>

        <!--Breadcumb-->
        <div class="container mb-5 ">
            <h1 class="font-rubys text-center">Ingin pesan secara online?</h1>
            <h5 class="font-rubys text-center">Kamu juga bisa pesan secara online loh, caranya bisa menghubungi nomor
                Whatsapp kami atau bisa kirimkan email dengan tombol dibawah ini</h5>
        </div>

        <!--contact-->

        <div id="contact" class="container mb-4">
            <div class="row">
                <div class="col">
                    <div class="card ">
                        <div class="card-header text-dark" style="background-color: #edcffc;"><i
                                class="fa  fa-envelope"></i> Contact us.
                        </div>
                        <div class="card-body">
                            <form>
                                <div class="form-group">
                                    <label for="name">Name</label>
                                    <input type="text" class="form-control" id="name" aria-describedby="emailHelp"
                                        placeholder="Enter name" required>
                                </div>
                                <div class="form-group">
                                    <label for="email">Email address</label>
                                    <input type="email" class="form-control" id="email" aria-describedby="emailHelp"
                                        placeholder="Enter email" required>
                                    <small id="emailHelp" class="form-text text-muted">We'll never share your email with
                                        anyone else.</small>
                                </div>
                                <div class="form-group">
                                    <label for="message">Message</label>
                                    <textarea class="form-control" id="message" rows="6" required></textarea>
                                </div>
                                <div class="mx-auto">
                                    <button type="submit" class="btn btn-primary text-right">Submit</button>
                                </div>
                            </form>
                        </div>
                    </div>
                </div>
                <div class="col-12 col-sm-4">
                    <div class="card bg-light mb-3">
                        <div class="card-header text-dark text-uppercase" style="background-color: #edcffc;"><i
                                class="fa fa-home"></i> Address
                        </div>
                        <div class="card-body">
                            <p>Jl. H.Mencong, RT.001/RW.008, Paninggilan, Kec. Ciledug, Kota Tangerang, Banten 15153</p>
                            <p>Buka : 09.00 - 22.00</p>
                            <p>Email : rubyscakeciledug@gmail.com</p>
                            <p>088808405599</p>

                            <body>
                                <a href="https://wa.me/6288808405599" class="btn btn-primary">Pesan Melalui Whatsapp</a>
                            </body>
                        </div>

                    </div>
                </div>
            </div>
        </div>







    </div>






</template>





<script>


export default {
    name: 'ContenView',

};


</script>



<style>

</style>