<template>
    <div>
    <section>
        <p>Categorias</p>
        <div class="container-categories">
            <div class="card-category category-electronics">
                <p>Electronicos</p>
                <span>ver más productos</span>                    
            </div>    
            <div class="card-category category-home">
                <p>Productos para el hogar</p>
                <span>ver más productos</span>                    
            </div>    
            <div class="card-category category-clothes">
                <p>Ropa para ti</p>
                <span>ver más productos</span>                    
            </div>    
            <div class="card-category category-houseAppliances">
                <p>Eletrodomesticos para tu cocina</p>
                <span>ver más productos</span>                    
            </div>    
            <div class="card-category category-furniture">
                <p>Muebles para tu hogar</p>
                <span>ver más productos</span>                    
            </div>    
            <div class="card-category category-tools">
                <p>Herramientas</p>
                <span>ver más productos</span>                    
            </div>    
        </div>
    </section>
</div>
<div>
    <p>Ejemplos</p>
    <section>
        <div class="container-categories">
            <div class="card-category category-electronics">
                <p>Electronicos</p>
                <span>ver más productos</span>                    
            </div>    
            <div class="card-category category-home">
                <p>Productos para el hogar</p>
                <span>ver más productos</span>                    
            </div>    
            <div class="card-category category-clothes">
                <p>Ropa para ti</p>
                <span>ver más productos</span>                    
            </div>    
            <div class="card-category category-houseAppliances">
                <p>Eletrodomesticos para tu cocina</p>
                <span>ver más productos</span>                    
            </div>    
            <div class="card-category category-furniture">
                <p>Muebles para tu hogar</p>
                <span>ver más productos</span>                    
            </div>    
            <div class="card-category category-tools">
                <p>Herramientas</p>
                <span>ver más productos</span>                    
            </div>    
        </div>
    </section>
</div>
  </template>

<style scoped>

.container-categories {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 2rem;
    row-gap: 2rem;
    padding: 4rem 0;
    margin: 0 14rem; 

}
section {
    margin-left: 100px;

    box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);
    background-color: aliceblue;
    margin: 50px; 
    padding: 20px;
align-self: center;
}
.card-category {
    height: 18rem;
    width: 25rem;
    display: flex;
    flex-direction: column;
    gap: 6rem;
    margin: 5px;  

}

.card-category span{
    background-color: rgba(0, 0, 0, 0.7);
    font-size: 1rem;
    color: #fff;
    cursor: pointer;
    text-align: left;
    margin-top: 155px; 
    padding-left: 2px;
}
.card-category span:hover{
    color: var(--primary-color);
}
.card-category p{
    background-color: rgba(0, 0, 0, 0.7);
    color: #fff;
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

</style>