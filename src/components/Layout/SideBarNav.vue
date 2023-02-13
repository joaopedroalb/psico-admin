<script setup>

</script>

<style scoped>
    .side-container{
        width: 120px;
        height: 100vh;
        background-color: var(--purple-900);
        display: flex;
        flex-direction: column;
        padding: 20px 0;
        gap: 1.5rem;
    }

    .header-container{
        display: flex;
        flex-direction: column;
        align-items: center; 
        justify-content: center;
        gap: 1;
    }

    .logo-img{
        width: 35px;
        height: 35px;
    }

    .title{
        font-size: 14px;
    }

    .links-container{
        display: flex;
        flex-direction: column;
        gap: 1rem;
    }

    li{
        font-size: 14.5px;
        padding: 5px 10px;
        user-select: none;
        transition: 400ms;
    }

    li:hover{
        background-color: #494b7a;
    }


</style>

<template>
    <nav class="side-container">
        <header class="header-container">
            <img src="../../assets/psicologia-logo.png" class="logo-img"/>
        </header>

        <ul class="links-container">
            <li class="pointer">Pacientes</li>
            <li class="pointer">Psicologos</li>
            <li class="pointer">Agendamentos</li>
            <li class="pointer">Calendario</li>
            <li class="pointer">Criar Paciente</li>
            <li class="pointer">Criar Psicologo</li>
        </ul>
    </nav>
</template>
