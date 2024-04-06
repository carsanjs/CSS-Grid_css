##FRACCION
es una unidad especial que nos permite indicar el tamaño de las columnas de forma proporcional (fr)

1fr ---> 100%
1fr 1fr ---> 50% 50%
1fr 1fr 1fr---> 33.33% 33.33% 33.33%

1fr 100px : // 100% - 100px --> ? ancho de la fraccion
1fr 100px 50px: // 100% - 100px   50px --> ? ancho de la fraccion
1fr 2fr--- >


/* grid-template-columns: 100px 100px 100px; */
/* grid-template-columns: 50% 100px auto 10vmin;  no es aconsejable */
/* grid-template-columns: 1fr 1fr;
/* grid-template-columns: 100px 1fr 50px; */

/* gap  --> columnas y filas
/* column-gap  la antigua, conpatibilidad con los navegadores */
/* grid-column-gap: 1rem; */

/* -repeat */
/* grid-template-columns: repeat(3,1fr); */
/* grid-template-columns: 100px repeat(3,1fr) 15px; */
/* grid-template-columns: 25px 50px 25px 50px; grid-template-columns: repeat(3,25px, 50px);

/* -ninmax */
/* cual es el tamaño minimo que debe tener la columan, y si llega al tamaño minimo como se tendria que comportar por default */
/* grid-template-columns:minmax(100px, 1fr)1fr; */


ya nada de css mediaquery cuando se utiliza grid

/* @media (width > 300px){
    .container{
        grid-template-columns: 1fr 1fr;
    }
}

@media (width > 600px){
    .container{
        grid-template-columns: 1fr 1fr 1fr;
    }
} */

/* 

/* diferencia entre auto-fill (rellena el espacio) y auto-fit (ajusta el espacio)*/
/* 
auto-fill , ocupan el numero de columna que ocupan el año, mientras su año sea de ninmax("valor") */
/* grid-template-columns: repeat(
    auto-fill, 
    minmax(100px, 1fr)); */

grid-column-start: 2;
grid-column-end: 4; */

/* grid-column-start: span 3;
grid-row-start: span 2; */

