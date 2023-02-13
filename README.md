# encurtadordeurl
Um encurtador de url

Resumo
Este código permite ao usuário encurtar uma URL longa e exibir o resultado de forma elegante e moderna. Além disso, ele conta o número de URLs encurtadas até o momento, iniciando o contador em 3.345.

Input
O usuário deve inserir a URL longa na caixa de texto, clicando no botão "Encurtar URL".

Output
O resultado da operação será exibido na tela, com a URL encurtada em negrito e o site de origem ao lado, em itálico. Além disso, será mostrado o número atual de URLs encurtadas.

Tecnologias Utilizadas
HTML: é a linguagem de marcação utilizada para estruturar o conteúdo da página.
JavaScript: é a linguagem de programação utilizada para realizar a lógica de encurtamento de URL e atualização da tela.
CSS: é a linguagem de estilo utilizada para melhorar a aparência da página, tornando-a moderna e responsiva.
Detalhes da Implementação
O JavaScript é responsável por fazer a requisição à API TinyURL, que é responsável por encurtar a URL longa. O resultado é armazenado na variável "shortURL", que é exibida na tela, junto com o site de origem (que é derivado da URL longa) e o número atual de URLs encurtadas. A aparência é melhorada com a adição de CSS moderno e responsivo.
Summary
This code allows the user to shorten a long URL and display the result in a stylish and modern way. Additionally, it counts the number of URLs shortened so far, starting the counter at 3,345.

Input
The user must enter the long URL in the text box and click the "Shorten URL" button.

Output
The result of the operation will be displayed on the screen, with the shortened URL in bold and the source site next to it, in italics. Additionally, the current number of shortened URLs will be shown.

Technologies Used
HTML: is the markup language used to structure the content of the page.
JavaScript: is the programming language used to perform the URL shortening logic and update the screen.
CSS: is the style language used to enhance the appearance of the page, making it modern and responsive.
Implementation Details
JavaScript is responsible for making the request to the TinyURL API, which is responsible for shortening the long URL. The result is stored in the "shortURL" variable, which is displayed on the screen, along with the source site (which is derived from the long URL) and the current number of shortened URLs. The appearance is improved with the addition of modern and responsive CSS.

Spanish
Documentación básica para el código HTML/JavaScript para acortar URL
Resumen
Este código permite al usuario acortar una URL larga y mostrar el resultado de una manera elegante y moderna. Además, cuenta el número de URLs acortadas hasta ahora, comenzando el contador en 3.345.

Entrada
El usuario debe ingresar la URL larga en el cuadro de texto y hacer clic en el botón "Acortar URL".

Salida
El resultado de la operación se mostrará en la pantalla, con la URL acortada en negrita y el sitio de origen junto a ella, en cursiva. Además, se mostrará el número actual de URLs acortadas.

Tecnologías utilizadas
HTML: es el lenguaje de marcado utilizado para estructurar el contenido de la página.
JavaScript: es el lenguaje de programación utilizado para realizar la lógica de acortamiento de URL y actualización de la pantalla.
CSS: es el lenguaje de estilo utilizado para mejorar la apariencia de la página, haciéndola moderna y responsiva.
Detalles de implementación
JavaScript es responsable de hacer la solicitud a la API TinyURL, que es responsable de acortar la URL larga. El resultado se almacena en la variable "shortURL", que se muestra en la pantalla, junto con el sitio de origen (que se deriva de la URL larga) y el número actual de URLs acortadas. La apariencia se mejora con la adición de CSS modernoEste código HTML/JavaScript permite acortar una URL larga utilizando la API de TinyURL.

La función shortenURL() realiza la acción de acortar la URL.
Se obtiene el valor de la URL larga desde el elemento de entrada de texto con el ID "longURL".
Se crea una nueva solicitud de XMLHttpRequest y se abre una conexión GET con la API de TinyURL, pasando la URL larga codificada como un parámetro.
Se establece un controlador de evento onreadystatechange para manejar la respuesta de la API. Si la solicitud se ha completado y se ha recibido un estado de 200 (éxito), se obtiene la URL corta de la respuesta y se muestra en el elemento de span con el ID "shortURL".
Se envía la solicitud y se muestra la URL corta en el elemento de span correspondiente.
Además, se muestra un contador de URL cortas hasta el momento, que ya inició con 3,345 URLs cortas.
El texto "URL acortada:" está en negrita y el sitio web de origen se muestra al lado en cursiva.

