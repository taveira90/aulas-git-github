
 <h1>Resolvendo conflito de remoto e local</h1>
    <div>
        <p>
            O conflito mais comum de ocorrer é quando dois commits alteram o mesmo arquivo em um mesmo ponto.
            Exemplo: <br>
            Alterar o arquivo diretamente pelo GitHub e depois alterar o mesmo ponto pelo editor de código. <br>
            <br>
            Nesse caso, quando der um git push no terminal, irá ser apresentada a seguinte mensagem: <br>
            <img src="git push 1.png">
        </p>
    </div>
    <br><br>
    <div>
        <p>
            A primeira intenção que vem a cabeça é dar um git pull origin main, porém isso não ira funcionar,e irá retornar uma mensagem de erro:
            <img src="mensagem de erro git pull origin main.png" alt="">
            <br>
            Diz que o merge não funcionou pois há conflitos que precisam ser resolvidos primeiro.
            <br><br><br>
            No caso do VsCode, ele já traz uma marcação mostrando as duas alterações, e cabe a nós decidir qual delas deve ser mantida.
            <br>
            No exemplo da imagem são apenas duas linhas, então apaguei a que não queria e salvei o arquivo novamente.
            <img src="conflito marcado no vscode.png" alt="">
            <br>
        </p>
    </div>
    <div>
        <p>
            Após decidido qual será a alteração que deve permanecer, basta salvar e refazer o git add, o git  commit e o git push.
            <br>
            <label>git add</label><br>
            <img src="git add de resolução.png" alt="">
            <br>
            <label>git commit</label><br>
            <img src="commit de resolução.png" alt="">
            <br>
            <label>git push</label><br>
            <img src="git push de resolução.png" alt="">
        </p>
        <p>Pronto! Resolvido</p>
    </div>