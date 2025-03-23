# TailWindCSS-


<h2>Instalação e Configuração</h2>
<h3>1. Instalar as dependências mais recentes</h3>
<pre><code>npm install tailwindcss@latest postcss@latest autoprefixer@latest

<h3>2. Solução alternativa para problemas de configuração</h3>
<pre><code>npm install -y
<h2>Exemplo de Estrutura de Arquivos</h2>
<pre><code>/projeto
<h3>Exemplo de <code>index.html</code></h3>
<pre><code>&lt;!DOCTYPE html&gt;

<h2>Executando o Tailwind CSS</h2>
<p>Para compilar os estilos e mantê-los atualizados em tempo real, utilize:</p>
<pre><code>npx tailwindcss -i ./src/css/styles.css -o ./src/css/build.css --watch</code></pre>
<p>Isso garantirá que qualquer alteração nos arquivos CSS seja aplicada imediatamente no projeto.</p>

<h2>📌 Dicas</h2>
<ul>
    <li>Certifique-se de que o caminho do CSS no HTML está correto.</li>
    <li>Utilize <code>live-server</code> para visualizar alterações em tempo real:</li>
</ul>
<pre><code>npx live-server</code></pre>

<p>Caso tenha problemas, sinta-se à vontade para abrir uma <strong>issue</strong> no repositório. 🚀</p>