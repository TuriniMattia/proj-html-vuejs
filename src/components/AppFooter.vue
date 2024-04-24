<template>
    <!-- footer della pagina -->
    <footer>
        <div class="container">
            <div class="d_flex ">
                <ul class="d_flex_list">
                    <li class=" col_25">
                        <h4>AVADA TECH FORUM</h4>
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Veniam eaque ipsa ad nesciunt
                            consequatur assumenda laborum placeat ipsum laudantium.</p>
                    </li>
                    <li class=" col_25">
                        <h4>POPULAR TOPICS</h4>
                        <ul class="inner_list">
                            <li>>lista footer numero 1</li>
                            <li>>lista footer numero 1</li>
                            <li>>lista footer numero 1</li>
                            <li>>lista footer numero 1</li>
                        </ul>
                    </li>
                    <li class=" col_25">
                        <h4>POPULAR TOPICS</h4>
                        <ul class="inner_list">
                            <li>>lista footer numero 2</li>
                            <li>>lista footer numero 2</li>
                            <li>>lista footer numero 2</li>
                            <li>>lista footer numero 2</li>
                        </ul>
                    </li>
                    <li class=" col_25">
                        <h4>POPULAR TOPICS</h4>
                        <ul class="inner_list">
                            <li>>lista footer numero 3</li>
                            <li>>lista footer numero 3</li>
                            <li>>lista footer numero 3</li>
                            <li>>lista footer numero 3</li>
                        </ul>
                    </li>

                </ul>
            </div>
            <!-- div conenente una lista con 4 colonne -->

            <div>
                <!-- div contenente crediti finali e una lista con 4 icone-->
                <!-- <p></p> -->
                <ul>
                    <!-- <li>f</li> -->
                    <!-- <li>x</li> -->
                    <!-- <li>ig</li> -->
                    <!-- <li>yt</li> -->
                </ul>
            </div>
        </div>
    </footer>


</template>

<script>
export default {
    data() {


        return {}
    }
}
</script>

<style lang="scss" scoped>
.d_flex_list {
    display: flex;
    justify-content: space-between;
}

.col_25 {
    width: 20%;
    line-height: 200%;
}

li>.inner_list {
    font-weight: bold;
    line-height: 300%;

}
</style>