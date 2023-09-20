# API-KEYBOARD-3D

Peguei o arquivo 3D no site da Logitech:

https://www.logitech.com/pt-br/products/keyboards/mx-keys-s.920-011563.html



Como pegar arquivo 3D no site da Logitech

• Abra ferramentas do desenvolvedor

• Vá ate network

• Encontre o arquivo.glb

• Clica com botão direito em cima dele

• Open in new tab



Como consumir API para o modelo 3D

• Acesse o site: https://modelviewer.dev/

• Crie um index.html

• No frame Quick Start vamos pegar somente o script

<!-- Import the component -->
<script type="module" src="https://ajax.googleapis.com/ajax/libs/model-viewer/3.1.1/model-viewer.min.js"></script>

• Coloque esse script no seu index


Como usar no modelo 3D no HTML

• Coloque Tag <model-viewer></model-viewer>

• Dentro da Tag acresente o caminho/source <model-viewer scr="..."></model-viewer>

• Acrescente camera-controls na tag model-viewer
(comando responsavel por enquadrar o modelo 3D)

Tag completa:

<model-viewer src="mxkeyss-graphite-ar-360.glb" camera-controls></model-viewer>

Estilização

