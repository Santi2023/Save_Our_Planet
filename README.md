# Save_Our_Planet
Pagina Web 

const title_form= document.querySelector(".title_form");
const button = document.querySelector(".button")

btn.addEventListener("click", cambiar_color);

function cambiar_color(){
    title_form.style.color = "blue";
}


.title_form.blue{
    color: blue;
}

<button onclick="cambiar_color()" class="button">hola</button>


const ocult = document.getElementById("obj1");

const button = document.getElementById("enviar");

enviar.addEventListener("click", ocultar);

volver.addEventListener("click", mostrar);

function ocultar() {
    document.getElementById('obj1').style.display = 'none';
    document.getElementById('obj2').style.display = 'block';
}

function mostrar() {
    document.getElementById('obj1').style.display = 'block';
    document.getElementById('obj2').style.display = 'none';
}

#obj2 {
    text-align: center;
    display: none;
}


<div>
                        <input type="button" name="enviar" class="button" id="enviar" onchange="click" value="enviar">
                    </div>
                </form>

                <div id="obj2">
                    <h1>Su formulario ha sido enviado</h1>
                    <button id="volver">Volver</button>
