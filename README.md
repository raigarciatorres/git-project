
<body>
    <h1>Esta página será útil apenas para mostrar oscomandos que sei utilizar dentro do Git.</h1>
    <p>Aqui segue a lista dos comandos que já sei utilizar:
        <ul>
            <li><code>git status</code></li>
            <li><code>git add .</code></li>
            <li><code>git commit -m " "</code></li>
            <li><code>git branch</code></li>
            <li><code>git pull</code></li>
            <li><code>git reflog</code></li>
            <li><code>git checkout</code></li>
            <li><code>git merge</code></li>
        </ul>
    </p>
    <h2>esta é uma linha adicional para usar o comando <code>git add .</code> e <code>git commit -m " "</code></h2>
    <p>primeiro usa-se o git status e verifica que há um arquivo modificado. Depois, é só usar <code>git add .</code> e, em seguida, <code>git commmit -m "(msg aqui)"</code></p>
    <p>para voltar a uma versão anterior, usa-se o comando <code>git reset --hard (id aqui)</code>, onde o id é conhecido a partir do comando <code>git reflog</code></p>
    <h1>branches</h1>
    <p>o conceito de branch é muito interessante, em que é possível "clonar" uma versão para alterar sem ter que alterar a versão "oficial". Dessa forma, tenta-se garantir a integridade.</p>
    <p>o comando para ver as branches disponíveis é <code>git branch</code></p>
    <p>pode-se criar novas branches, acessá-las e juntar suas alterações no branch principal do projeto.</p>
    <p>pra ver as branches, usa-se o comando <code>git branch</code></p>
    <p>cria-se uma branch nova com comando <code>git branch (nome da branch sem os parênteses)</code></p>
    <p>para trocar de branch (usar outra branch), usa-se o comando <code>git checkout "(nome da branch sem os parênteses)"</code></p>
    <p>agora as alterações terão efeito apenas na branch selecionada</p>
    <p>para fazer com que nova branch esteja viível no repoitório, usa-se o comando <code>git add .</code> e depois <code>git push</code></p>
    <h2>merge</h2>
    <p>agora com o código revisado e funcionando, você pode querer unir os códigos. Para isso, inicialmente é necessário selecionar a branch desejada, no caso a master a partir do comando <code>git checkout master</code></p>
    <p>depois, basta utilizar o comando <code>git merge (nome da branch sem os parênteses)</code></p>
    <h4>no entanto, antes de iniciar suas alterações e realizar o merge no final, é necessário usar o comando <code>git pull</code> para puxar a versão mais recente do repositório.</h4>
    <p>finalmente, use o comando <code>git push</code></p>
</body>
</html>
