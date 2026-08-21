# Niver

Um convite de aniversário em formato de site. A página tem um contador regressivo no topo mostrando quantos dias, horas, minutos e segundos faltam para a festa, informações de local e data, um botão de "reserve sua mesa" e algumas seções contando um pouco sobre o evento, cada uma com uma imagem e uma animação suave que aparece conforme rola a página.

Esse foi um projeto mais focado em HTML e CSS puros (usando Sass pra organizar melhor os estilos em arquivos separados por seção — hero, evento, rodapé etc.) e em um pouco de JavaScript vanilla pra fazer a lógica do contador: pegar a data do evento, calcular a diferença pro momento atual e atualizar o texto na tela a cada segundo com `setInterval`. Também aprendi a integrar uma biblioteca externa (AOS, de animações ao rolar a página) direto via CDN e a usar o Parcel como bundler pra não precisar configurar nada na mão.

Tecnologias e ferramentas usadas: HTML5, Sass/SCSS, JavaScript, Parcel (bundler) e a biblioteca AOS para as animações de scroll.
