body {
    display: flex;
    align-items: center;
    justify-content: center;
    height: 100vh;
    margin: 0;
    background-color: #ffffff;
}

.container {
    text-align: center;
}

#gifContainerImg {
    width: 60%;
    height: 60%;
}

button {
    padding: 10px 20px;
    font-size: 16px;
    margin: 10px;
    cursor: pointer;
}
#siBtn {
    padding: 10px 20px; 
    font-size: 16px;
    margin: 10px;
    cursor: pointer;
    background-color: #009705; /* Verde */
    color: white;
    border: 2px solid #FFC0CB; /* Bordes rosa */
    border-radius: 10px; /* Esquinas redondeadas */
}

#noBtn {
    padding: 10px 20px;
    font-size: 16px;
    margin: 10px;
    cursor: pointer;
    background-color: #FF5733; /* Rojo */
    color: white;
    border: 2px solid #FFC0CB; /* Bordes rosa */
    border-radius: 10px; /* Esquinas redondeadas */
}
#noBtn span {
    font-size: 18px;
    color: #fcf4f4; /* Cambia el color del texto según tus preferencias */
    /* Otras propiedades de estilo aquí */
}

#siBtn:hover{
    background-color: #053a03; /* Cambia a otro color en hover, puedes ajustar el valor según tus preferencias */
}
#noBtn:hover {
    background-color: #641e0d; /* Cambia a otro color en hover, puedes ajustar el valor según tus preferencias */
}
.bg-green {
    background-color: #ffffff; /* Nuevo color de fondo verde */
}

#messageContainer {
    font-size: 30px;
    color: #FF0000; /* Color rojo */
    font-family: 'YourDesiredFont', sans-serif; /* Reemplaza 'YourDesiredFont' con la fuente que desees */
    text-shadow: 2px 2px 4px #000; /* Borde simulado */
    animation: pulse 0.5s infinite alternate; /* Animación de palpitación más rápida */
}

@keyframes pulse {
    from {
        transform: scale(1);
    }
    to {
        transform: scale(1.3); /* Zoom más grande */
    }
}
