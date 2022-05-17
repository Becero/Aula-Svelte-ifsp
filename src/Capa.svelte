<script>
import CaixaDeIcones from "./CaixaDeIcones.svelte";
</script>

<div class="fundo">
    <div class="centro">
        <img src="./img/1.jpg" alt="foto de perfil" class="foto">
        <h1 class="titulo"> Luis Guilherme</h1>
        <h2 class="descricao">Analista de Marketing</h2>
        <CaixaDeIcones />


    </div>
</div>

<style>
    .fundo {
        width: 100%;
        min-height: 100vh;
        background-color: #1f0d85;
    }

    .centro{
        color: white;
        text-align: center;
        position: absolute;
        top: 50%;
        left: 50%;
        transform: translate(-50%, -50%);
    }

    .foto{
        width: 250px;
        border-radius: 50%;

    }
    .titulo{
        font-size: 40px;
    }
    .descricao{
        font-size: 25px;

    }

</style>