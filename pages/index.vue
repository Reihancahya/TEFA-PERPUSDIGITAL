<template>
    <div class="container-fluid">
        <div class="row my-5">
            <div class="col-lg-6">
                <nuxt-link to="/pengunjung/tambah">
                    <div class="card 1 bg-pengunjung rounded-5">
                        <div class="card-body">
                            <h2>pengunjung</h2>
                        </div>
                    </div>
                </nuxt-link>
            </div>

            <div class="col-lg-6">
                <nuxt-link to="/buku">
                    <div class="card bg-buku rounded-5">
                        <div class="card-body">
                            <h2>cari buku</h2>
                        </div>
                    </div>
                </nuxt-link>
            </div>
        </div>
    </div>
    <h1>STATISTIK</h1>
    <div class="container-fluid">
        <div class="row my-5">
            <div class="col-lg-6">
                    <div class="card rounded-5">
                        <div class="card-body">
                            <h2 class="pengunjung">3 pengunjung</h2>
                        </div>
                    </div>
            </div>

            <div class="col-lg-6">
                <div class="card  rounded-5">
                    <div class="card-body">
                        <div class="buku">
                            <h2>180 Buku</h2> 
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>

    
</template>


<style scoped>
.card {
    height: 250px;
    color: white;
    box-shadow: 1px 1px 10px #000000;
    background-color: rgb(0, 81, 255);
}
.card.bg-pengunjung {
    background-image: url('~/assets/img/bg-home-kunjungan.jpeg');
    background-repeat: no-repeat;
    background-position: center center;
    background-size: cover;
    color: 
    0rgb(255, 255, 255);
    
}
.card.bg-buku.rounded-5{
    background: url('~/assets/img/bg-home-cari-buku.jpg') no-repeat center center;
    background-size: cover;
    color: FFFFFF;
}
.statistik {
    left: reight;
}
</style>