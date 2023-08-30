<template>
    <div class="retangulo-cinza">
        <p class="titulo-habilidades">HABILIDADES</p>
        <div class="linha-preta"></div>
        <ul class="habilidades">
            <li>Trabalho em equipe;</li>
            <li>Domínio da linguagem de programação [Java];</li>
            <li>Pensamento criativo;</li>
            <li>Conhecimento em frameworks;</li>
            <li>Domínio em Front-End;</li>
            <li>Conhecimentos em lógica de programação;</li>
            <li>Programação de Banco de Dados;</li>
        </ul>
        <p class="titulo-habilidades-idiomas">IDIOMAS</p>
        <div class="linha-preta-idiomas"></div>
        <ul class="habilidades">
            <li>Português - Nativo</li>
            <li>Inglês - Médio </li>
            <li>Espanhol - Básico</li>
        </ul>
    </div>
</template>

<style>
.retangulo-cinza {
    width: 290px;
    height: 40%;
    background-color: rgb(219, 215, 215);
    position: absolute;
    top: 38%;
    left: 0;
    border-top-left-radius: 0;
    border-bottom-left-radius: 0;
    border-top-right-radius: 10px;
    border-bottom-right-radius: 10px;
    display: flex;
    flex-direction: column;
    justify-content: center;
    padding: 20px;
}

.titulo-habilidades {
    font-family: "Source Sans Pro Bold", sans-serif;
    color: #5BA7D1;
}

.titulo-habilidades {
    margin-left: -165px;
    font-weight: bold;
}

.titulo-habilidades-idiomas {
    margin-left: -210px;
    color: #5BA7D1;
    font-weight: bold;
}

.linha-preta {
    background-color: black;
    height: 1px;
    width: 20%;
    margin-left: 7px;
    margin-top: 5px;
    margin-bottom: 5px;
}

.linha-preta-idiomas {
    background-color: black;
    height: 1px;
    margin-left: 7px;
    width: 20%;
    margin-top: 5px;
    margin-bottom: 5px;
}

.habilidades {
    font-size: 11px;
    margin-left: -90px;
    font-weight: bold;

    line-height: 1.5;
}

.habilidades li::before {
    margin-right: 10px;
    color: #5BA7D1;
    display: inline-block;
    width: 1em;
}

.habilidades li {
    text-align: left;
    margin-left: 70px;
}
</style>