<template>
    <div class="main-container d-flex justify-content-center align-items-center vh-100">
        <div class="container">
            <div class="wrapper p-3 rounded-1">
                <Header />
                <form>
                    <InputPin />
                    <EnterBtn />
                    <ForgotPin />
                </form>                                                                                                              
            </div>
        </div>
    </div>
</template>

<script>
import InputPin from './InputPin.vue';
import EnterBtn from '../Buttons/EnterBtn.vue';
import Header from '../Header/Header.vue';
import ForgotPin from '../ForgotPin/ForgotPin.vue';

export default {
    components: {
        InputPin,
        EnterBtn,
        Header,
        ForgotPin,
    }
}
</script>

<style lang="scss" scoped>
.main-container {
    box-sizing: border-box;

    .wrapper {
        border: 1px solid black;
    }
}
</style>