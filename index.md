<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Curriculo</title>
</head>
<body>
     <ul>
        <li>Endereço</li>
        <li>Cidade, Estado e CEP</li>
        <li>Telefone</li>
        <li>Email</li>
    </ul>
    <h1>Eduardo</h1>
    <hr>
    <h1>OBJETIVO:</h1>
    <p>Ser o melhor</p>
    <hr>
    <h2>Habilidades e competências</h2>
    <p>Flexibilidade: Todas</p>
    <p>Capacidade para resolver problemas: Alta</p>
    <p>Trabalho em equipe: Suficiente</p>
    <p>Esforçado: pra cacete</p>
    <p>Proativo: Quase sempre</p>
    <p>Altamente qualificado: O suficiente pro cargo</p>
    <p>Comunicativo: Muito</p>
    <hr>
    <h2>Experiência</h2>
    <ul>
        <li>
            Estagiário, CBIU UNIFESSPA - 03/02 a 08/07
        </li>
    </ul>
    <h2>Educação</h2>
    <ul>
        <li>Unifesspa, Campus 2, Sistemas de informação</li>    
    </ul>
    <h2>Comunicação</h2>
    <p>Suficiente</p>
    <hr>
    <h2>Referências</h2>
    <ol>
        <li>Alessandra Helena,Coordenadora Geral do CBIU, CBIU, (94) 2101-7186</li>
    </ol>
</body>
</html>


<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tabela</title>
    <style>
        table{
            width: 43%;
            border-collapse: collapse;
        }
        td, th{
            border: 1px solid black;
            padding: 8px;
        }
        tr.primeiros_head{
            background-color: black;
        }
        tr.primeiros_head{
            color: white;
        }
    </style>
</head>
<body>
    <h1>Cursos de Extensão da UNIFESSPA - Informática para Todos</h1>
    <table>
        <thead>
            <tr class="primeiros_head">
                <th scope="col">Modalidade</th>
                <th scope="col">Cursos</th>
                <th scope="col">Carga horária</th>
                <th scope="col">Idade Mínima</th>
                <th scope="col">Início</th>
                <th scope="col">Valor</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <th rowspan="3" scope="rowgroup" align="left">On-line</th>
                <td>Excel Básico</td>
                <td>24 Horas</td>
                <td>14 anos</td>
                <td>Fevereiro, Março e Abril</td>
                <td>50,00</td>
            </tr>
            <tr>
                <td>Excel Avançado</td>
                <td>39 Horas</td>
                <td>16 anos</td>
                <td>Fevereiro, Março e Abril</td>
                <td>75,00</td>
            </tr>
            <tr>
                <td>Informática Para Maturidade</td>
                <td>36 Horas </td>
                <td>Acima de 40 anos</td>
                <td>Fevereiro e Maio</td>
                <td>50,00</td>
            </tr>
            <tr>
                <th colspan="5" scope="rowgroup" align="left" >Investimento</th> 
                <td>175,00</td>
            </tr>
            <tr>
                <th rowspan="4" scope="rowgroup" align="left">Presencial</th>
                <td>Operador de Computador</td>
                <td>160 Horas</td>
                <td>16 anos</td>
                <td>Março e Outubro</td>
                <td>100,00</td>
            </tr>
            <tr>
                <td>PowerPoint</td>
                <td>20 Horas</td>
                <td>14 anos</td>
                <td>Março e Junho</td>
                <td>25,00</td>
            </tr>
            <tr>
                <td>Projetc</td>
                <td>20 Horas</td>
                <td>16 anos</td>
                <td>Fevereiro e Abril</td>
                <td>50,00</td>
            </tr>
            <tr>
                <td>Word</td>
                <td>24 Horas</td>
                <td>14 anos</td>
                <td>Março e Junho</td>
                <td>25,00</td>
            </tr>
            <tfoot>
                <tr>
                    <th colspan="5" scope="colgroup" align="left">Investimento</th>
                    <td>200,00</td>
                </tr>
            </tfoot>
        </tbody>
    </table>
</body>
</html>


!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Formulario</title>
</head>
<body>
    <h1>Informações Pessoais</h1>
    <form action="">
        <fieldset>
            <legend>Cadastro do Cliente</legend> 
            <div>
                <label for="nome">Nome:
                    <input size="50" type="text" name="nome" id="nome" required>
                </label>
            </div>

            <div>
                <label for="sexo">Sexo:
                    <input type="radio" name="sexo" id="masc" value="Masculino">Masculino
                    <input type="radio" name="sexo" id="fem" value= "Feminino">Feminino
                </label>
            </div>
            <div>
                <label for="idade"> Idade:
                    <input type="number" name="Idade" id="idade" min="1" oninput="this.value = !!this.value && Math.abs(this.value) >= 0 ? Math.abs(this.value) : null">
                </label>
            </div>

            <div>
                <label for="endereco">Endereço:
                    <input size="60" type="text" name="endereco" id="endereco" placeholder="Digite o endereço">
                </label>
            </div>

            <div>
                <label for="cidade">Cidade:
                    <input size="40" type="text" name="cidade" id="cidade" placeholder="Digite a cidade">
                </label>
            </div>

            <div>
                <label for="estado">Estado</label>
                    <select name="estado" id="estado">
                        <option selected disabled value="">UF</option>
                        <option value="AC">Acre</option>
                        <option value="AL">Alagoas</option>
                        <option value="AP">Amapá</option>
                        <option value="AM">Amazonas</option>
                        <option value="BA">Bahia</option>
                        <option value="CE">Ceará</option>
                        <option value="DF">Distrito Federal</option>
                        <option value="ES">Espírito Santo</option>
                        <option value="GO">Goiás</option>
                        <option value="MA">Maranhão</option>
                        <option value="MT">Mato Grosso</option>
                        <option value="MS">Mato Grosso do Sul</option>
                        <option value="MG">Minas Gerais</option>
                        <option value="PA">Pará</option>
                        <option value="PB">Paraíba</option>
                        <option value="PR">Paraná</option>
                        <option value="PE">Pernambuco</option>
                        <option value="PI">Piauí</option>
                        <option value="RJ">Rio de Janeiro</option>
                        <option value="RN">Rio Grande do Norte</option>
                        <option value="RS">Rio Grande do Sul</option>
                        <option value="RO">Rondônia</option>
                        <option value="RR">Roraima</option>
                        <option value="SC">Santa Catarina</option>
                        <option value="SP">São Paulo</option>
                        <option value="SE">Sergipe</option>
                        <option value="TO">Tocantins</option>
                        <option value="EX">Estrangeiro</option>
                    </select>
            </div>
            
            <div>
                <label for="cep">CEP:
                <input maxlength="9" size= "10"type="text" name="cep" id= "cep" placeholder="XXXXX-XXX">
                </label>
            </div>

            <div>
                <label for="tel/res">Tel/Res:
                    <input maxlength="13" size="15" type="text" name="tel/res" id="tel/res" placeholder="(99) 99999-9999">
                </label>
            </div>

            <div>
                <label for="tel/cel">Tel/Cel: 
                    <input maxlength="13" size="15" type="text" name="tel/cel" id="tel/cel" placeholder="(99) 99999-9999">
                </label>
            </div>

            <div>
                <label for="email">Email:
                    <input size="50" type="email" name="email" id="email" placeholder="Digite o endereço email">
                </label>
            </div>

        </fieldset>
        <br>
        <button>incluir</button>
        </form>
    <style>
        div {
            padding-bottom: 15px;
        }
        fieldset{
            margin-right: 1000px;
            padding-top: 15px;
        }


    </style>
    
</body>
</html>









<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Wikipedia</title>
</head>
<body>
<div>
    <a href="#Definição">Definição</a> <a href="#Video">Vídeo</a> <a href="#Estrutura">Estrutura e Interface</a> <a href="#Referencias">Referências</a>
    
</div>
<hr>
    <div id="Definição">
        <h1>Twitter</h1>
        <img src="https://upload.wikimedia.org/wikipedia/pt/thumb/3/3d/Twitter_logo_2012.svg/1200px-Twitter_logo_2012.svg.png" alt="Simbolo do Twitter(Pequeno Pássaro)" width="200px;">
        <p>O <b>Twitter</b> é uma rede social e um serviço de microblog, que permite aos usuários enviar e receber atualizações pessoais de outros contatos (em textos de até 280 caracteres, conhecidos como "tweets"), por meio do website do serviço</p>
        <p>O <b>Twitter</b> foi criado em Março de 2006 por Jack Dorsey, Evan Williams, Biz Stone e Noah Glass e foi lançado em Julho de 2006 nos EUA. A ideia inicial dos fundadores era que o Twitter fosse uma espécie de "SMS da internet" com a limitação de caracteres de uma mensagem de celular. Inicialmente chamada Twttr (sem vogais), o nome da rede social, em inglês, significa gorjear. A ideia é que o usuário da rede social está "piando" pela internet. Desde sua criação, o Twitter ganhou extensa notabilidade e popularidade por todo mundo. Algumas vezes é descrito como o "SMS da Internet"</p>
    </div>
<hr>
    <div id="Video">
        <h2>Vídeo explicativo sobre o Twitter</h2>
        <p>O Github Pages não acha o diretorio do meu video e da minha legenda aqui nem ferrando cara.<p>
        <img src="https://media0.giphy.com/media/BtT6KZqoT9UWPSKzuC/giphy.gif?cid=790b7611a465ff5b1929ef9a873c2343a1e03af18c59bf5e&rid=giphy.gif&ct=g">
        <video poster="https://www.hardware.com.br/static/wp/2022/04/25/Elon-Musk-with-Twitter-logo.jpg?fm=pjpg&ixlib=php-3.3.0" src=AtividadeWikipedia/mim-sugarão-o-meu-rostinho.kkkkkkkkkk.mp4"controls width="275" height="500">
            <track kind="subtitles" src="AtividadeWikipedia/LegendaMim.vtt" srclang="pt"
            label="Português(Brasil)" default>
        </video>
    </div>
<hr>
    <div id="Estrutura">  
        <h2>Estrutura e Interface</h2>  
        <p>Desenvolvido como qualquer outra aplicação Web, a Interface do Twitter pode parecer talvez assustadora para pessoas que usam apenas aplicativos de mensagens instântaneas e redes sociais com interface mais amigável como o Instagram, Mas de forma geral não é tão complicado quanto pode parece</p>
        <p>Segue a Interface do Twitter em navegadores pc:</p>
        <img src="https://s2.glbimg.com/7ziXcqWSVlc8aPHnbRNC24yPp5c=/0x0:1235x618/984x0/smart/filters:strip_icc()/i.s3.glbimg.com/v1/AUTH_08fbf48bc0524877943fe86e43087e7a/internal_photos/bs/2019/d/j/atAdJpS6esAw8eSJAHsw/perfil.png" alt="Imagem da Interface do Twitter" width="500">
        <p>Interface Mobile:    </p>
        <img src="https://img.freepik.com/vetores-gratis/modelo-de-interface-do-twitter_23-2148582529.jpg?w=2000" alt="Interface Mobile do Twitter" width="500">
    </div>
<hr> 
    <div id="Referencias">      
        <h3>Referências</h3>
        <ol>
            <li><a href="https://pt.wikipedia.org/wiki/Twitter"> Artigo Wikipédia Original sobre o Twitter </a></li>
            <li><a href="https://www.facebook.com/groups/issoehmim">Grupo do Facebook da qual a explicação sobre o Twitter foi retirada</a></li>
            <li><a href="https://www.hardware.com.br/noticias/2022-04/elon-musk-compra-o-twitter-por-44-bilhoes.html">Elon Musk compra Twitter por 44 Bilhões(Thumb Vídeo Explicação)</a></li>
            <li><a href="https://www.techtudo.com.br/noticias/2019/07/novo-twitter-site-faz-mudanca-radical-na-interface-veja-novidades.ghtml">Novo Twitter: Site faz Mudança Radical na Interface</a></li>
            <li><a href="https://br.freepik.com/vetores-gratis/modelo-de-interface-do-twitter_8851847.htm">Modelo de Interface do Twitter - Vetor Gratis</a></li>
        </ol>
    </div>
</body>
</html>
