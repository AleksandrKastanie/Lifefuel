<script>
    export default{
        data(){
            return{
                pagecall:''
            }
        }
    }
</script>
<template>
    <div class="header-wrap">
        <div class="left-btn-wrap"><button class="btn-show-page">Home</button></div>
        <div class="right-btn-wrap">
            <img class="notif-btn-pic" src="/icons/bell.badge.svg">
            <img class="account-btn-pic" src="/photo/photo_2023-04-24_17-51-05.jpg">
        </div>
    </div>
</template>
<style>
.header-wrap{
    display: flex;
    justify-content: space-around;
}
.left-btn-wrap{
    display: flex;
    align-self: center;
}
.right-btn-wrap{
    display: flex;
    gap: 4px 10px;
    
}
.btn-show-page{
    all: unset;
}
.notif-btn-pic{
    border-radius: 50%;
    width: 30px;
    height: 30px;
}
.account-btn-pic{
    border-radius: 50%;
    width: 30px;
    height: 30px;
}
</style>