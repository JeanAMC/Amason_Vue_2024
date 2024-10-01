<template>
    <div>
    <section>
        <p class = "title-category">Categorias</p>
        <div class="container-categories">
            <div class="card-category category-electronics">
                <p>Electronicos</p>
                <span>ver más</span>                    
            </div>    
            <div class="card-category category-home">
                <p>Hogar</p>
                <span>ver más</span>                    
            </div>    
            <div class="card-category category-clothes">
                <p>Ropa para ti</p>
                <span>ver más</span>                    
            </div>    
            <div class="card-category category-houseAppliances">
                <p>Eletrodomesticos</p>
                <span>ver más</span>                    
            </div>    
            <div class="card-category category-furniture">
                <p>Muebles</p>
                <span>ver más</span>                    
            </div>    
            <div class="card-category category-tools">
                <p>Herramientas</p>
                <span>ver más</span>                    
            </div>    
        </div>
    </section>
</div>
<div>
    
    <section>
        <p class = "title-category">Ejemplos</p>
        <div class="container-categories">
            <div class="card-category category-electronics">
                <p>Electronicos</p>
                <span>ver más</span>                    
            </div>    
            <div class="card-category category-home">
                <p>Hogar</p>
                <span>ver más</span>                    
            </div>    
            <div class="card-category category-clothes">
                <p>Ropa</p>
                <span>ver más</span>                    
            </div>    
            <div class="card-category category-houseAppliances">
                <p>Eletrodomesticos</p>
                <span>ver más</span>                    
            </div>    
            <div class="card-category category-furniture">
                <p>Muebles</p>
                <span>ver más</span>                    
            </div>    
            <div class="card-category category-tools">
                <p>Herramientas</p>
                <span>ver más</span>                    
            </div>    
        </div>
    </section>
</div>
  </template>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Oswald:wght@400;700&display=swap');
.container-categories {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 2rem;
    row-gap: 2rem;
    padding: 4rem 0;
    margin: 0 5rem; 
    width: 85%;

}
section {
    width: 60%;
    margin: 50px auto; /* Esto centra el componente y aplica un margen superior/inferior de 50px */
    box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);
    background-color: aliceblue;
    padding: 20px;

}
.card-category {
    height: 10rem;
    width: 18rem;
    display: flex;
    flex-direction: column;
    gap: 6rem;
    width: 100%;

}

.card-category span{
    background-color: rgba(0, 0, 0, 0.7);
    font-size: 0.8rem;
    color: #fff;
    cursor: pointer;
    text-align: left;
    margin-top: 30px; 
    padding-left: 2px;
}
.card-category span:hover{
    color: var(--primary-color);
}
.card-category p{
    background-color: rgba(0, 0, 0, 0.7);
    color: #fff;

}
.title-category{
    font-size: 2rem;
    color: #000000;
    font-family: 'Oswald', sans-serif;
    margin-left: 20px;
}
.category-electronics {
    background-image: url('src/assets/imagen_ejemplo_electronicos.jpg');
    background-size: cover;
    background-position: bottom;
    background-repeat: no-repeat;
}
.category-home{    
    background-image:url('src/assets/imagen_ejemplo_Hogar.jpg');
    background-size: cover;
    background-position: bottom;
    background-repeat: no-repeat;

}
.category-clothes{
    background-image: url('src/assets/ejemplo_imagen_ropa.jpg');
    background-size: cover;
    background-position: bottom;
    background-repeat: no-repeat;


}
.category-houseAppliances {
    background-image: url('src/assets/ejemplo_imagen_electrodomesticos.jpg');
    background-size: cover;
    background-position: bottom;
    background-repeat: no-repeat;


}
.category-furniture {

    background-image: url('src/assets/imagen_ejemplo_Muebles.jpg');
    background-size: cover;
    background-position: bottom;
    background-repeat: no-repeat;

}
.category-tools {

    background-image: url('src/assets/imagen_ejemplo_herramientas.jpg');
    background-size: cover;
    background-position: bottom;
    background-repeat: no-repeat;

}
@media (max-width: 768px) {
    .container-categories {
        grid-template-columns: repeat(2, 1fr); 
        margin: 0 20%; 
    }
}

@media (max-width: 768px) {
    .container-categories {
        grid-template-columns: 1fr; 
        margin: 0 2%; 
    }

    section {
        margin-left: 20; 
    }
}

</style>