# Kingdom-Choices-Grupo-3-4-4-2026
Hoy en Algoritmos lo que hice fue terminar el trabajo pendiente que me quedo de ayer. Ya que no sumaba los 375 de oro (si tenias las minas al nivel máximo) , si no que solo te sumaba lo de una mina osea +125 ,+125 ,+125 y así. Lo que me había faltado agregar , que lo agregue hoy, era un foreach para recorrer las torres , con un if hice si la torre construida es igual a una mina dependiendo su nivel sumaba la cantidad de oro exacta , 
Fragmento de código:
foreach (Torre t in torres) 
{
    if (t.Tipo == TipoEdificio.Mineria)
    {
        if (t.Nivel == 1) partidaActual.datosJugador.Oro += 20;
        else if (t.Nivel == 2) partidaActual.datosJugador.Oro += 50;
        else if (t.Nivel == 3) partidaActual.datosJugador.Oro += 125;
    }
}
También arregle un tema de los sprites que estaban descentrados del cartel que sale cuando ocurre un evento (por un tema de coordenadas). Nada más , use de sprites las minas de clash of clans para probar si la logica y como quedaba en el juego estaba bien , pero ahora los actualizare a los sprites finales.
