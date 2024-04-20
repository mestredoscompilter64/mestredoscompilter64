<!DOCTYPE html>

<html lang="pt-br">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="tentativa de site 4">
    <meta name="keyword" content="tentativa,site">
    <meta name="author" content="lucas luciano borges da rocha">
    <title>tentativa de site 4</title>
    <style type="text/css">
        body{
            margin: 0px;
            background: gray;
        }

        .conteinertop{
            background: black;
            height: 120px;
            width: 100%;
        }
        .conteinerlinks {
            padding: 0px 0px 0px 70px;
            display: flex;
        }
        .link{
            padding-top: 35px;
        }
        .link a{
            text-decoration: none;
            font: normal 20px arial;
            margin: 0px 50px 0px 100px;
            padding: 0px 0px 0px 0px;
            color: white;
        }

        .botaotoop{
            padding: 10px 50px 10px 50px;
            background: #2A9BE2;
            font: normal 20px arial;
            border-radius: 50px;
        }
        .botaotoop:hover{
            padding: 10px 50px 10px 50px;
            background: #FF7E00;
            font: normal 20px arial;
            border-radius: 50px;
        }

        .conteinertext1{
            margin: 100px 0px 0px 20px;
            height: 350px;
            width: 1200px;
            border:3px solid black;
        }
        .imgtext1{
            margin: 0px 0px 0px 0px;
            float: left;
            height: 350px;
            width: 300px;
        }

        .conteudo{
            border: 3px solid black;
            padding: 50px;
        }
        .ctnrodape{
            font: normal 20px arial;
            background-color: black;
            height: 250px;
            color: white;
        }

        .imgconteudo1{
            float: right;
            height: 350px;
            width: 350px;
        }

        .imgredes{
            display: flex-block;
            margin: 0px 15px 0px 15px;
        }


        .imgface{
            border-radius: 100px;
            background: gray;
            height: 50px;
            width: 50px;
            margin: 0px 15px 0px 15px;
        }
        .nameredes{
            display: block;
            margin: 0px 50px 0px 10px;
        }
        .nomeredes{
            margin: 0px 10px 0px 0px;
        }
        .author h3{
            background-color: gray;
            padding: 6px 0px 0px 0px;
            color: white;
        }

    </style>
</head>

<body>
<!--topo-->
<div class="conteinertop">
    <div class="conteinerlinks">
        <div class="link">
            <button id="idbutton" onclick="clicar()" class="botaotoop">botão</button>
            <a id="idlink" href="#">seilamano</a>
            <a id="idlink" href="#">seilamano</a>
            <a id="idlink" href="#">seilamano</a>
        </div>
    </div>
</div>

<div class="conteudo">
    <h1>titulo principal</h1>
    <hr>
    <div class="textconteudo">
        <img class="imgconteudo1" src="https://w0.peakpx.com/wallpaper/308/447/HD-wallpaper-paisagem-preto-branco-natureza-branco-preto-luz-montanha.jpg" alt="">

        <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Incidunt iure ratione voluptate consequuntur harum cum illo a. Voluptatibus iusto facere vel pariatur eos rem ipsum sit modi. Porro, possimus, voluptatem.</p>
        <p>Assumenda non architecto nulla impedit ullam porro sit dolor cum? Minima a veritatis deleniti error non velit nisi corrupti laboriosam possimus sapiente? Mollitia voluptate hic sapiente unde eius autem tempore.</p>
        <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Deserunt dolore dolorem tempora vel, est at maxime corporis beatae! Pariatur quasi, nulla adipisci illo excepturi vitae? Velit praesentium et eum, amet!</p>
        <p>Quibusdam itaque, repellendus, laudantium blanditiis dolor ducimus nam neque laborum possimus deleniti assumenda. Fugit adipisci, recusandae qui quam, excepturi ducimus, impedit veritatis molestias fugiat unde hic repellat obcaecati. Amet, dolorum?</p>
        <p>Incidunt soluta ut veritatis tenetur earum quis at odit quibusdam dolor, et quam id, nostrum eaque voluptate aliquam error quas dolorum, omnis temporibus, alias. Et cupiditate sequi voluptatum eum sapiente!</p>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Atque quibusdam, similique quam error expedita excepturi accusamus est. Corrupti fugiat officiis tenetur quia commodi consequatur enim, natus error molestias aut soluta!</p>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing, elit. Iste, nostrum. Recusandae iure vel quos sit totam neque eius expedita sequi consequatur, debitis. Temporibus libero, itaque quidem fuga quos nihil, voluptate?</p>
        <hr>
    </div>
</div>

<div class="pairodape">
    <div class="ctnrodape">
        <h2><u><i>redes sociais do criador.</i></u></h2>
        <div class="imgredes">
            <img class="imgface" src="C:\Users\julianee\Downloads\icones/github.png" alt="github">
            <img class="imgface" src="C:\Users\julianee\Downloads\icones/facebook.png" alt="">
            <img class="imgface" src="C:\Users\julianee\Downloads\icones/instagram.png" alt="">
            <img class="imgface" src="C:\Users\julianee\Downloads\icones/pinterest.png" alt="">
            <img class="imgface" src="C:\Users\julianee\Downloads\icones/youtube.png" alt="">
            <br>

            <div class="nameredes">
                <label class="nomeredes" for="">hitnub</label>
                <label class="nomeredes" for="">facebook</label>
                <label class="nomeredes" for="">intagram</label>
                <label class="nomeredes" for="">pinterest</label>
                <label class="nomeredes" for="">youtube</label>
                <br><br><br>
                    <h3> <i>Author:</i> <u>Lucas luciano Borges da Rocha</u></h3>
            </div>
        </div>
    </div>
</div>

<script type="text/javascript">
    function clicar(){

    }
</script>    

</body>

</html>
