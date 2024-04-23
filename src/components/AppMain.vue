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
        <section class="main_section">
            <div class="container">
                <h5 class="upr-title">PHASELLUS EGET METUS</h5>
                <h1>All the latest news</h1>
                <hr class="red_bar">

            </div>
            <!-- div contenente 3 card piccole -->
            <div>


            </div>
            <div>
                <!-- card piu grande larga quanto tutto il conteiner e con background un immagine, con all'interno un titolo , un testo e un button -->
            </div>
            <!-- div contenente 3 card piccole -->
            <div>
                <!-- 3 card allineate con stessa dimensione e un paragrafo sotto -->
            </div>
            <div>
                <!-- div con all'interno una card piu grossa che occupa il 60% del container , con un paragrafo e un bottone -->
                <!-- una card con all'interno 3 card piu piccole -->

            </div>


        </section>
        <!-- sezione con sfondo nero e un'ancora  -->
        <section>
            <!-- <a href=""></a> -->
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
export default {
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
    text-align: center;
    padding: 30px;
    word-spacing: 15px;
}

// MAIN SECTION //

.main_section {
    display: flex;
    justify-content: center;

}

.red_bar {
    width: 80px;
    border-color: rgb(255, 141, 97);
    margin: 0 auto;
    margin-top: 30;

}
</style>
