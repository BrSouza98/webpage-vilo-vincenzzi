
<template>
  <footer class="footer">
    <div class="container">
      <div class="row justify-content-around">
        <div>
          <h2>Vilo Vincenzzi</h2>
          <p><a href="sobre">Sobre</a></p>
          <p><a href="metodologia">Metodologia</a></p>
        <p><a href="corpodocente">Corpo docente</a></p>
          <p><a  href="https://vilovicenzzi.wordpress.com/"
                  target="_blank">Blog</a></p>
                            <p><a href="contato">Fale conosco</a></p>

        </div>

        <div>
          <h3>Informações de contato</h3>
          <p class="margem">
            <svg
              width="1em"
              height="1em"
              viewBox="0 0 16 16"
              class="bi bi-house-fill"
              fill="currentColor"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                fill-rule="evenodd"
                d="M8 3.293l6 6V13.5a1.5 1.5 0 0 1-1.5 1.5h-9A1.5 1.5 0 0 1 2 13.5V9.293l6-6zm5-.793V6l-2-2V2.5a.5.5 0 0 1 .5-.5h1a.5.5 0 0 1 .5.5z"
              />
              <path
                fill-rule="evenodd"
                d="M7.293 1.5a1 1 0 0 1 1.414 0l6.647 6.646a.5.5 0 0 1-.708.708L8 2.207 1.354 8.854a.5.5 0 1 1-.708-.708L7.293 1.5z"
              />
            </svg>
            Av Cap. José Camargo Lima, 341, Jardim São Sebastião Taquaritinga/SP
          </p>
          <p>
            <svg
              width="1em"
              height="1em"
              viewBox="0 0 16 16"
              class="bi bi-telephone-plus-fill"
              fill="currentColor"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                fill-rule="evenodd"
                d="M1.885.511a1.745 1.745 0 0 1 2.61.163L6.29 2.98c.329.423.445.974.315 1.494l-.547 2.19a.678.678 0 0 0 .178.643l2.457 2.457a.678.678 0 0 0 .644.178l2.189-.547a1.745 1.745 0 0 1 1.494.315l2.306 1.794c.829.645.905 1.87.163 2.611l-1.034 1.034c-.74.74-1.846 1.065-2.877.702a18.634 18.634 0 0 1-7.01-4.42 18.634 18.634 0 0 1-4.42-7.009c-.362-1.03-.037-2.137.703-2.877L1.885.511zM12.5 1a.5.5 0 0 1 .5.5V3h1.5a.5.5 0 0 1 0 1H13v1.5a.5.5 0 0 1-1 0V4h-1.5a.5.5 0 0 1 0-1H12V1.5a.5.5 0 0 1 .5-.5z"
              />
            </svg>
            (16) 3252-7799
          </p>
          <p>
            <svg
              width="1em"
              height="1em"
              viewBox="0 0 16 16"
              class="bi bi-alarm-fill"
              fill="currentColor"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                fill-rule="evenodd"
                d="M6 .5a.5.5 0 0 1 .5-.5h3a.5.5 0 0 1 0 1H9v1.07a7.001 7.001 0 0 1 3.274 12.474l.601.602a.5.5 0 0 1-.707.708l-.746-.746A6.97 6.97 0 0 1 8 16a6.97 6.97 0 0 1-3.422-.892l-.746.746a.5.5 0 0 1-.707-.708l.602-.602A7.001 7.001 0 0 1 7 2.07V1h-.5A.5.5 0 0 1 6 .5zM.86 5.387A2.5 2.5 0 1 1 4.387 1.86 8.035 8.035 0 0 0 .86 5.387zM11.613 1.86a2.5 2.5 0 1 1 3.527 3.527 8.035 8.035 0 0 0-3.527-3.527zM8.5 5.5a.5.5 0 0 0-1 0v3.362l-1.429 2.38a.5.5 0 1 0 .858.515l1.5-2.5A.5.5 0 0 0 8.5 9V5.5z"
              />
            </svg>
            Horário de funcionamento: 07h às 17h
          </p>
          <p>
            <svg
              width="1em"
              height="1em"
              viewBox="0 0 16 16"
              class="bi bi-envelope-fill"
              fill="currentColor"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                fill-rule="evenodd"
                d="M.05 3.555A2 2 0 0 1 2 2h12a2 2 0 0 1 1.95 1.555L8 8.414.05 3.555zM0 4.697v7.104l5.803-3.558L0 4.697zM6.761 8.83l-6.57 4.027A2 2 0 0 0 2 14h12a2 2 0 0 0 1.808-1.144l-6.57-4.027L8 9.586l-1.239-.757zm3.436-.586L16 11.801V4.697l-5.803 3.546z"
              />
            </svg>
            vilovicenzzi@gmail.com
          </p>
        </div>
      </div>
    </div>

    <div style="background-color: rgb(40, 40, 40)" class="d-flex justify-content-center">
      Fatec - Taquaritinga {{ new Date().getFullYear() }}
    </div>
    
  </footer>
</template>

<style scoped>
.footer {
  background-color:  #333;
  color: #fff;
  font-size: 18px;
  box-sizing: border-box;
}
</style>

 