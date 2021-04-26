<template>
    <section id="main">
        <div class="container">
            <div class="row">
                <div class="col">
                    <h2 class="text-uppercase oswald-font">Bike features</h2>
                </div>
            </div>
            <div class="row d-flex justify-content-center align-items-center mt-5">
                <div class="col-md-6">
                    <!-- number 01 -->
                    <span class="custom-number-styles text-white">01</span>
                </div>
                <div class="col-md-6">
                    <!-- card start -->
                    <div class="card c-border-top shadow rounded-0 p-5" style="width: 24rem;">
                        <div class="card-body">
                            <h5 class="card-title text-uppercase">Motiondrive&trade; System</h5>
                            <p class="card-text mt-4">EVELO MotionDrive&trade; is an exclusive electric bike drivetrain technology bringin together the efficiency of a mid-drive motor with the convenience of an internal hub transmission.</p>
                        </div>
                    </div>
                    <!-- card end -->
                </div>
            </div>
            <div class="row c-margin-top">
                <div class="col-md-4">
                   <div class="card border-0 shadow" style="width: 18rem;">
                        <div class="card-body">
                            <h5 class="card-title">Card title</h5>
                            <p class="card-text mt-4">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-4">
                   <div class="card border-0 shadow" style="width: 18rem;">
                        <div class="card-body">
                            <h5 class="card-title">Card title</h5>
                            <p class="card-text mt-4">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                        </div>
                    </div>

                </div>
                <div class="col-md-4">
                   <div class="card border-0 shadow" style="width: 18rem;">
                        <div class="card-body">
                            <h5 class="card-title">Card title</h5>
                            <p class="card-text mt-4">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

</template>

<script>
export default {

}
</script>

<style scoped lang="scss">
    #main {
        height: 130vh;
        background-image: linear-gradient(180deg, rgba(229,235,238,1) 12%, rgba(229,235,238,0.8412407199207808) 50%),linear-gradient(0deg, rgba(229,235,238,1) 15%, rgba(229,235,238,0.57513427734375) 32%), url('~@/assets/chris-kendall.jpg');
        background-size: cover;

        .oswald-font {
            font-family: 'Oswald', sans-serif;
            font-size: 5rem;
            width: 40%;
        }
        .custom-number-styles {
            font-size: 20rem;
            font-family: 'Oswald', sans-serif;
        }
        .card-title {
            font-family: 'Oswald', sans-serif;
            font-size: 1.5rem;
            font-weight: 500;
        }
        .card-body {
            font-family: sans-serif;
            font-size: .8rem;
            line-height: 1.2rem;
        }
        .c-border-top {
            border-top: 4px solid #F76846;
        }
        .c-margin-top {
            margin-top: 15rem;
        }
    }
</style>
