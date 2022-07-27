<template>
    <section class="information-modal">
        <nav class="navbar-modal">
            <span class="close">X</span>
            <h4>Detalhes do usuário</h4>

        </nav>

        <div class="contain-all-information">
        </div>
    </section>
</template>

<script>

</script>
<style scoped>
.information-modal {
    width: 271px;
    height: 52px;
    flex-direction: column;
    border-radius: 10px;
    background-color: white;
    position: absolute;
    top: 13%;
    left: 85%;
    right: -50%;
    transform: translate(-50%, -50%);
    border: solid 2px black;

}

.navbar-modal {
    width: 100%;
    height: 45px;
    display: flex;
    align-items: center;
    justify-content: center;
}


.close {
    position: absolute;
    right: 20px;
    border: none;
    background-color: transparent;
}

.close:hover {
    cursor: pointer;
    transform: translateZ(0px) scale(1.2);
}

.close {
    width: 21px;
    height: 21px;
    color: rgb(75, 75, 75);
}
</style> 