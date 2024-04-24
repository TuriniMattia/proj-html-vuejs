<template>
    <div class="col_4">
        <div class="forum_card">
            <font-awesome-icon class="icon" :icon="['fas', 'file']" />
            <h5>News & Community</h5>
        </div>
    </div>
    <div class="col_4">
        <div class="forum_card">
            <font-awesome-icon class="icon" :icon="['fab', 'apple']" />
            <h5>Apple Forum</h5>
        </div>
    </div>
    <div class="col_4">
        <div class="forum_card">
            <font-awesome-icon class="icon" :icon="['fab', 'windows']" />
            <h5>Microsoft Forum</h5>
        </div>
    </div>
    <div class="col_4">
        <div class="forum_card">
            <font-awesome-icon class="icon" :icon="['fab', 'android']" />
            <h5>Android Forum</h5>
        </div>
    </div>
    <div class="col_4">
        <div class="forum_card">
            <font-awesome-icon class="icon" :icon="['fas', 'mug-saucer']" />
            <h5>General Discussion</h5>
        </div>
    </div>
    <div class="col_4">
        <div class="forum_card">
            <font-awesome-icon class="icon" :icon="['fas', 'cubes']" />
            <h5>Apps & Software</h5>
        </div>
    </div>
    <div class="col_4">
        <div class="forum_card">
            <font-awesome-icon class="icon" :icon="['fas', 'laptop']" />
            <h5>Gadgets & Stuff</h5>
        </div>
    </div>

    <div class="col_4">
        <div class="forum_card">
            <font-awesome-icon class="icon" :icon="['fas', 'wrench']" />
            <h5>Tutorials & Guides</h5>
        </div>
    </div>



</template>

<script>
export default {
    data() {


        return {}
    }
}
</script>

<style lang="scss" scoped>
.col_4 {
    width: calc(3 * 100% / 12);
    display: flex;
    justify-content: center;
    gap: 20px;


}

.forum_card {
    background-color: white;
    text-align: center;
    width: 70%;
    margin-top: 30px;
    border-top: rgb(40, 175, 195) solid;
    padding: 50px;
    display: flex;
    flex-direction: column;
    align-items: center;
    text-align: center;
    cursor: pointer;
}

.icon {
    font-size: 10px;
    padding: 10px;
    color: white;
    background-color: rgb(255, 141, 97);
    width: 30px;
    height: 30px;
    border-radius: 50%;
    display: flex;
    align-items: center;
    text-align: center;
    cursor: pointer;

}
</style>