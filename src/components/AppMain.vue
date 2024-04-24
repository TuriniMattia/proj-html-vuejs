<template>
    <!-- main della pagina -->
    <main>
        <!-- prima sezione con background un immagine, un h1, un h4 e un button -->
        <section class="hero_section">
            <div class="container hro">
                <h1 class="big_title">Tech Forum!</h1>
                <p class="paragraph">Discuss all the latest tecnology news and trends</p>
                <button class="button blue">GET AVADA NOW! ></button>
            </div>

        </section>
        <!-- seconda sezione contenente un paragrafo con un titolo a cenmtro pagina e un background colorato -->
        <section class="upper_section">
            <div class="container_sm">
                <h5 class="upr-title">AVADA FORUM IS THE PLACE TO BE</h5>
                <p class="upr-paragraph">Lorem ipsum dolor sit amet consectetur adipisicing elit. Cumque necessitatibus
                    mollitia ad nihil a
                    quaerat sed, laborum deleniti provident nobis nesciunt. Quaerat labore eius asperiores magnam quasi
                    nostrum id mollitia.</p>
            </div>
        </section>
        <!-- sezione principale contenente una serie di card con diverse strutture  -->
        <section>
            <div class="container">
                <div class="main_section">
                    <h5 class="upr-title">PHASELLUS EGET METUS</h5>
                    <h1>All the latest news</h1>
                    <hr class="red_bar">
                </div>

                <!-- div contenente 3 card piccole -->
                <div class="card_container">
                    <AppCard />
                </div>

                <div class="big_card_container">
                    <AppBigCard />
                </div>

                <div class="card_container">
                    <AppCard />
                </div>
                <!-- div con all'interno una card piu grossa che occupa il 60% del container , con un paragrafo e un bottone -->
                <!-- una card con all'interno 3 card piu piccole -->
                <div class="d_flex mnsc_footer">
                    <div class="rew_card ">
                        <h5>FEATURED ARTICLE</h5>
                        <h1>Lorem, ipsum dolor sit amet consectetur adipisicing elit.</h1>
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Distinctio, quibusdam corporis? Sed
                            voluptatum dicta
                            ad corporis expedita pariatur possimus soluta iure nobis cumque repudiandae, porro
                            distinctio, quod fugit
                            laudantium ipsam?
                        </p>
                        <button class="button black">READ MORE > </button>
                    </div>
                    <div class="tutorial_card ">
                        <h2>Tutorials & Guides</h2>
                        <hr class="red_bar">
                        <div class="card_container_column ">
                            <div class="card d_flex">
                                <img src="/public/post_feat_img_23-147x118.jpg" alt="">
                                <div class="card_text_container">
                                    <h5>Lorem ipsum dolor, sit amet consectetur adipisicing elit. </h5>
                                    <p class="card_text">October, 11th,2015 &VerticalLine; Comments off</p>
                                </div>

                            </div>
                            <div class="card d_flex">
                                <img src="/public/post_feat_img_22-147x118.jpg" alt="">
                                <div class="card_text_container">
                                    <h5>Lorem ipsum dolor, sit amet consectetur adipisicing elit. </h5>
                                    <p class="card_text">October, 11th,2015 &VerticalLine; Comments off</p>
                                </div>
                            </div>
                            <div class="card d_flex">
                                <img src="/public/post_feat_img_20-147x118.jpg" alt="">
                                <div class="card_text_container">
                                    <h5>Lorem ipsum dolor, sit amet consectetur adipisicing elit. </h5>
                                    <p class="card_text">October, 11th,2015 &VerticalLine; Comments off</p>
                                </div>
                            </div>
                        </div>

                    </div>

                </div>

            </div>



        </section>
        <!-- sezione con sfondo nero e un'ancora  -->

        <section class="black_section">
            <h4><a href="">READ OUR BLOG &RightArrow;</a></h4>
        </section>
        <!-- forum section contenente una serie di card tutte uguali che occupano tutto il container e con icone all'interno -->
        <section>
            <div>
                <!-- card -->
            </div>
        </section>
        <!-- sezione con sfondo nero e un'ancora  -->
        <section>
            <!-- <a href=""></a> -->
        </section>
        <!-- sezione contenente un titolo centrale, un paragrafo e un button -->
        <section>
            <!-- <h1></h1> -->
            <!-- <p></p> -->
            <!-- <button></button> -->
        </section>
        <!-- sezione per iscriversi alla news letter con un input e un button -->
        <section>
            <!-- <input type="text"> -->
            <!-- <button>
                cerca
            </button> -->
        </section>

    </main>
</template>

<script>
import AppCard from './AppCard.vue';
import AppBigCard from './AppBigCard.vue';
export default {
    components: {
        AppCard,
        AppBigCard,
    },
    data() {


        return {}
    }
}
</script>

<style lang="scss" scoped>
// HERO SECTION //
.hero_section {
    background-image: url(/public/home_slider_bg.jpg);
    height: 600px;
}

.hro {
    padding: 150px 0;
}



.big_title {
    font-size: 100px;
    color: white;

}

.paragraph {
    color: white;
    padding-bottom: 30px;
}

// UPPER SECTION //

.upper_section {
    background-color: rgb(242, 242, 242);
    height: 200px;
}

.container_sm {
    max-width: 800px;
    margin: 0 auto;
    display: flex;
    flex-direction: column;
    align-items: center;

}

.upr-title {
    word-spacing: 8px;
    padding-top: 30px;
    text-align: center;
}

.upr-paragraph {

    word-spacing: 15px;
}

// MAIN SECTION //

.main_section {
    display: flex;
    flex-direction: column;
    align-items: center;

}

.red_bar {
    width: 80px;
    border-color: rgb(255, 141, 97);
    margin-top: 30px;

}

// CARD CONTAINER //

.card_container {
    display: flex;
    padding-top: 50px;
    justify-content: space-between;

}

// BIG CONTAINER //
.big_card_container {
    margin: 50px 0;
    background-image: url(/public/featured_article_1_bg.jpg);
    background-size: 100%;
    image-rendering: auto;
    height: 500px;
    width: 100%;
}


//MAIN_SECTION FOOTER //
.mnsc_footer {
    margin-top: 80px;
}

.rew_card {
    width: calc(8 * 100% / 12);
    height: 500px;
    background-image: url(/public/featured_article_2_bg.jpg);
    background-size: 100%;
    color: white;
    padding: 80px 80px;
    line-height: 250%;
}

.tutorial_card {
    width: calc(4 * 100% / 12);
    height: 500px;
    padding-left: 60px;

}

.card_container_column {
    display: flex;
    flex-direction: column;

}

.card {
    margin-top: 25px;
}

.card_text_container {
    padding-left: 10px;
    text-align: left;
}

.card_text {
    font-size: 12px;
    word-spacing: 8px;
    padding-top: 5px;
    color: rgb(112, 112, 112);
}

// BLACK SECTION //

.black_section {
    color: white;
    background-color: black;
    text-align: center;
    padding: 30px;
}
</style>
