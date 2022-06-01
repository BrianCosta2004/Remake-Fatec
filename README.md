# Remake-Fatec
<bs5<!doctype html>
<html lang="pt-br">

<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    
    <title>Faculdade de Tecnologia de Campinas</title>
    <link  rel="stylesheet" type="text/css" href="style.css">

    <!-- bootstrap e CSS-->
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/5.0.0-alpha1/css/bootstrap.min.css"
        integrity="sha384-r4NyP46KrjDleawBgD5tp8Y7UzmLA05oM1iAEQ17CSuDqnUK2+k9luXQOfXJCJ4I" crossorigin="anonymous">

    <script src="https://stackpath.bootstrapcdn.com/bootstrap/5.0.0-alpha1/js/bootstrap.min.js"
        integrity="sha384-oesi62hOLfzrys4LxRF63OJCXdXDipiYWBnvTl9Y9/TRlw5xlKIEHpNyvvDShgf/"
        crossorigin="anonymous"></script>

    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.0/dist/umd/popper.min.js"
        integrity="sha384-Q6E9RHvbIyZFJoft+2mJbHaEWldlvI9IOYy5n3zV9zzTtmI3UksdQRVvoxMfooAo"
        crossorigin="anonymous"></script>

    <style>
        .bd-placeholder-img {
            font-size: 1.125rem;
            text-anchor: middle;
            -webkit-user-select: none;
            -moz-user-select: none;
            -ms-user-select: none;
            user-select: none;
        }

        @media (min-width: 768px) {
            .bd-placeholder-img-lg {
                font-size: 3.5rem;
            }
        }
    </style>


    <!-- estilos costumizados -->
    <link href="https://fonts.googleapis.com/css?family=Playfair&#43;Display:700,900&amp;display=swap" rel="stylesheet">
    
    <style>
       

        .blog-header {
            line-height: 1;
            border-bottom: 1px solid #5a2222;
            
        }

        .blog-header-logo {
            font-family: "Playfair Display", Georgia, "Times New Roman", serif;
            font-size: 2.25rem;
            text-decoration: none;
        }

        .blog-header-logo:hover {
            text-decoration: none;
        }

        h1,
        h2,
        h3,
        h4,
        h5,
        h6 {
            font-family: "Playfair Display", Georgia, "Times New Roman", serif;
        }

        .display-4 {
            font-size: 2.5rem;
            text-decoration: none;
        }

        @media (min-width: 768px) {
            .display-4 {
                font-size: 3rem;
                text-decoration: none;
            }
        }

        .nav-scroller {
            position: relative;
            z-index: 2;
            height: 2.75rem;
            overflow-y: hidden;
            
        }

        .nav-scroller .nav {
            display: flex;
            flex-wrap: nowrap;
            padding-bottom: 1rem;
            margin-top: -1px;
            overflow-x: auto;
            text-align: center;
            white-space: nowrap;
            -webkit-overflow-scrolling: touch;
            
        }

        .nav-scroller .nav-link {
            text-decoration: none;
            padding-top: .75rem;
            padding-bottom: .75rem;
            font-size: .875rem;
            
        }

        .card-img-right {
            height: 100%;
            border-radius: 0 3px 3px 0;
            
        }

        .flex-auto {
            flex: 0 0 auto;
            
        }

        .h-250 {
            height: 250px;
        }

        @media (min-width: 768px) {
            .h-md-250 {
                height: 250px;
            }
        }

        /* paginação */
        .blog-pagination {
            margin-bottom: 4rem;
            
        }

        .blog-pagination>.btn {
            border-radius: 2rem;
        }

        /* publicações */
        .blog-post {
            margin-bottom: 4rem;
        }

        .blog-post-title {
            margin-bottom: .25rem;
            font-size: 2.5rem;
        }

        .blog-post-meta {
            margin-bottom: 1.25rem;
            color: #2e2727;
        }

        /* rodapé */
        .blog-footer {
            padding: 2.5rem 0;
            color: #792828;
            text-align: center;
            background-color: #8b7b7b;
            border-top: .05rem solid #ddaaaa;
        }

        .blog-footer p:last-child {
            margin-bottom: 0;
        }

        a {
            text-decoration: none;
        }
    </style>
</head>

<body>

    <div class="container">
        <header class="blog-header py-3">
            <div class="row flex-nowrap justify-content-between align-items-center">
                <div class="col-4 pt-1">
                   
                </div>
                <div class="col-4 text-center">
                    <a class="blog-header-logo text-danger" href="#">Fatec Campinas</a>
                </div>
                <div class="col-4 d-flex justify-content-end align-items-center">
                    <a class="link-secondary" href="#" aria-label="Search">
                        <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" fill="none" stroke="currentColor"
                            stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="mx-3" role="img"
                            viewBox="0 0 24 24">
                            <title>Pesquisar</title>
                            <circle cx="10.5" cy="10.5" r="7.5" />
                            <path d="M21 21l-5.2-5.2" />
                        </svg>
                       
                    </a>
                    
                </div>
            </div>
        </header>

        <div class="nav-scroller">
            <nav class="nav d-flex justify-content-between">
                
                <li class="p-2 link-secondary dropdown">
                <a class="p-2 link-secondary dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown">Institucional</a>
                <ul class="dropdown-menu" aria-labelledby="navbarDropdown"> 
                    <li><a class="dropdown p-2 link-secondary" href="#">Action</a></li>
                    <li><a class="dropdown-item" href="#">Another action</a></li>
                    <li><a class="dropdown-item" href="#">Something else here</a></li>

                </ul>
                </li>
                
                <a class="p-2 link-secondary" href='https://www.fateccampinas.com.br/site/index.php/biblioteca/'>Biblioteca</a>

                <a class="p-2 link-secondary" href="https://www.fateccampinas.com.br/site/index.php/cpa/">CPA</a>

                <a class="p-2 link-secondary dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown">Graduação</a>

                <a class="p-2 link-secondary dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown">Concursos</a>

                <a class="p-2 link-secondary" href="https://www.fateccampinas.com.br/site/images/editais/Norma_Elei%C3%A7%C3%A3o%20Congrega%C3%A7%C3%A3o.pdf">Eleição da Congregação</a>

                <a class="p-2 link-secondary dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown">Revista</a>
                
                
                  
                    
            
            </nav>
        </div>

        <div class="p-4 p-md-5 mb-4 text-white rounded bg-danger">
            <div class="col-md-6 px-0">
                <h1 class="display-4 font-italic">Faculdade de Tecnologia de Campinas</h1>
                <p class="lead my-3">Cursos gratuitos e de qualidade! <br>Faça a sua incrição no nosso vestibular do 2° Semestre!</p>
                <p class="lead mb-0"><a href="#" class="text-white font-weight-bold">Clique aqui para saber mais!</a></p>
            </div>
        </div>

        <div class="row mb-2">
            <div class="col-md-6">
                <div
                    class="row g-0 border rounded overflow-hidden flex-md-row mb-4 shadow-sm h-md-250 position-relative">
                    <div class="col p-4 d-flex flex-column position-static">
                        <strong class="d-inline-block mb-2 text-primary">Interno</strong>
                        <h3 class="mb-0">Conheça o mais novo Diretor!</h3>
                        <div class="mb-1 text-muted">Jun 30</div>
                        <p class="card-text mb-auto">O Professor Jaime Ossada foi eleito com quase %80 dos votos!</p>
                        <a href="#" class="stretched-link">Saiba Mais</a>
                    </div>
                    <div class="col-auto d-none d-lg-block">
                        <img src="https://0.academia-photos.com/7572637/2749440/3203875/s200_jaime.ossada.jpg" class="img-thunbnail">

                    </div>
                </div>
            </div>
            <div class="col-md-6">
                <div
                    class="row g-0 border rounded overflow-hidden flex-md-row mb-4 shadow-sm h-md-250 position-relative">
                    <div class="col p-4 d-flex flex-column position-static">
                        <strong class="d-inline-block mb-2 text-success">Notificação</strong>
                        <h3 class="mb-0">Aulas Suspensas!</h3>
                        <div class="mb-1 text-muted">Jun 28</div>
                        <p class="mb-auto">A diretoria informa aos alunos que as aulas estão suspensas, devido a reparos na bomba dágua da instituição.</p>
                        <a href="#" class="stretched-link">Saiba Mais</a>
                    </div>
                    <div class="col-auto d-none d-lg-block">
                        <img src="data:image/jpeg;base64,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"class="img-thunbnail"> 

                    </div>
                </div>
            </div>
            <div class="col-md-6">
                <div
                    class="row g-0 border rounded overflow-hidden flex-md-row mb-4 shadow-sm h-md-250 position-relative">
                    <div class="col p-4 d-flex flex-column position-static">
                        <strong class="d-inline-block mb-2 text-success">Sucesso pela Frente</strong>
                        <h3 class="mb-0">Atlética Guará</h3>
                        <div class="mb-1 text-muted">Jun 20</div>
                        <p class="mb-auto">A Associação Atlética Acadêmica Guará está ativa novamente após a pandemia e com nova diretoria!</p>
                        <a href="#" class="stretched-link">Saiba Mais</a>
                    </div>
                    <div class="col-auto d-none d-lg-block">
                        <img src="data:image/jpeg;base64,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" class="img-thunbnail"> 

                    </div>
                </div>
            </div>
            <div class="col-md-6">
                <div
                    class="row g-0 border rounded overflow-hidden flex-md-row mb-4 shadow-sm h-md-250 position-relative">
                    <div class="col p-4 d-flex flex-column position-static">
                        <strong class="d-inline-block mb-2 text-primary">Eventos</strong>
                        <h3 class="mb-0">Choppada Universitária!</h3>
                        <div class="mb-1 text-muted">Jun 30</div>
                        <p class="card-text mb-auto">O evento está sendo organizado pela Diretoria de Eventos da Atlética.</p>
                        <a href="#" class="stretched-link">Saiba Mais</a>
                    </div>
                    <div class="col-auto d-none d-lg-block">
                        <img src="data:image/jpeg;base64,/9j/4AAQSkZJRgABAQAAAQABAAD/2wCEAAkGBxMUExYUFBMXFxYYGRkZGhgZGR8ZHBkfGx4bGx8ZHhoeHyoiGyInHhkcIzMjJystMDAwGiE2OzYvOiovMC0BCwsLDw4PHBERHC8nIig4Oi80LzMvMTEvMi8vLzEvLy0xLy8vLzExNC8vLy8vLy8vLy8vLzEvLy8vLy8vLy8vL//AABEIAOEA4QMBIgACEQEDEQH/xAAcAAABBQEBAQAAAAAAAAAAAAAGAAMEBQcBAgj/xABMEAACAQIEAwUFBAYGCQEJAAABAhEAAwQSITEFBkETIlFhcQcygZGhFEJSsSNicsHR4RUzU4KS8BY0Q1STorLS8SQXY3N0g5SzwuL/xAAZAQADAQEBAAAAAAAAAAAAAAABAgMEAAX/xAAuEQACAgEDAwIFBAIDAAAAAAABAgARAxIhMRNBUQRhIjJxkaFCgcHwFLEz0fH/2gAMAwEAAhEDEQA/ANvNKuGuUJ07SpUq6dO0orlKhc6dilXJpUYYhXaQpV0EVKmMViUtqXdgqjcmmk4jaZwguKWYEgAzIG8HalsQ0ZMrleblwASSAPEmKaXGWzs4PoZ/KuLAcmdUkUqZbFIN2A9dK927isJUgjyM1wYHgzqnuuVU4/jlu0WVwwIiJAAeRIymdp0nod6m4TGpcHdOsAlTuJEiRQ1KTU7SauSq5XRSNNBFXK7XKBnRUq5XaEaKlSpV06civJFe68sKUzoG/ClXIpVnqVhrSpVytsjO0qVKlgipUqVCdFXRXK7TTohUDinE0sgFjqSAB11nX00PyqRicSqCWMCYoZv4PtnBuFYU5nbplEnfp4egqbvWw5jqO5le5v3nudoy9mqwxY5EXc/GNDpvtUdOLLYRVw6yYK9uymW12QEmB/mKp+a+a1JCIv6IE5EBjPG7ufyH86h2uOC6gOXTw8I6VBrAsfeWVbNH7QxsWhcAd7pckTLHbyjpUyxAJWdPH1rNeL8wXLTBLRGwJJE76wB6fnRJyxxNr1h3PvLmmPTcfKplDp1eZ17kQoXCJ/afU1CFmbgyMUP4gYgUEYzme5bAIAJnQHb4xTmH5pe4oYqFI0aDpO8iekfvrum1XCDvUPMZijl7PEgXbUgi4mjKRsSP8/HamrnDSlz7StztLRUtK6QQZG24MRPTWs8TnFi0MhyHSZ1jxiPpRLy/zL2FyDPYse8PD9cD8x1FUAI2b7xQLFrC/hXMiNaD3JGoUGPfJMAKOprw3F3E+80ePd+lB3NgVuI4SxZYZUIvd0iFk9oTvHuICPUVe4zEk3Hy6yZ089a7M7qABzBjVWY3xC/h14vbVzuZ/MipVQOBmbKfH8zU+tQ4kTzORSiu1yuqdFSpUqWoZw0jXa4a6oLgZSrtKs+0rDOuUjTd2+qiWYAeZrUSBzJVHaVDnEedcDZEvfXWYygtOUwYCgzB0mqA+1KxcLrYtO5W1cuDPCZuzGYqNzOUE7dKmcq+Ywxse00KuFqxn/2k4zENlQW7Ce8zRmKIurNqROnSNSQOtVGL5vvXHJuXWNlyQFDMrKBsVZQNfHcE9Kk3qK4EouAnkzcb3FLKEBriAkgAFhJJ0AA60P4v2g4NCQrM5H4V/eYFZIuEZSL1ibmUhxJ74ggyVHvAHqpI8cu1XnEMD2d84hUm08XbSgSXa73lSN4BBYgdBHWs7+qfttKDCoO8M+LcxF0tkWyJMldyumkgeuuum1BHNvGcQoRVuBbdxwjKoMkGZkxpIjSZ2p7ivDrwthCw7wXMbhCkl5uPqxAAHZgdZof4+hS3bCsGdWRoUFp31OgDDYa61JCWcFjvKVpWhK7jOKzXdACBC+nU/UsPhVvyvldLiySymdYjUbbT92hnGObT5WGp1Jmfe737/rTnCL95nKWQJcQ0Hp1J8B/HzrWy2lAyKtT2Y/xfEgu7LESACDI0gSPEaGjD2a8UzJesldRbLT0O/wD3UJcXwDWywKnICAHOzHKDsDMTNM8Gu3VudpZYEpbdm1gBcpBGXrMgDzI9a40yUDBZDbiT+McRt3CAhMLIJ6E6ajy0qx5Ua2xdGOpEgbg6QR/LrQ7xHh5sOttt2tWng7jOisR6hpHwpqxfNsZllXBPeB6ERA+E6+dNqOnSIP1apPs2QLgVyAA0Md9t/wAqIG4jYE9+fIA/nFB1u83U/PepGGcuQoUyT/k+mlUJU7tAuocQs5Atm9jwDuUu6np+jKj4CQK0vgFm2LgtNbDEK2bOAxDDL1jaDQV7OLSWcUrMwJZGUnYLpOk+YAmj9VAv6RJdWzdTmLaT5AUC6sQVMBVhYMIVQAQBA8BXqlSq8lFSpVyjOipV2uUphuKvJNdmkaWdAylXZpVmqWmb8Q59x2Iwl1xdFt7d1AwtiP0dwMBvMEOsTPWh4cTvC2b967ce5cDJaDMTA1V7us/sLpuWP3RU/h6YQJeR7qo1+2bbWLLi6Cysro6XPdUypAQsff0PSnceto3PtC2rlzLkyIzpaRNPcICkr2e5BI1I3kmuJHcSwHiD1nGtYJtkAoYz2m7yT6dGG2ZYO4miHlvCBr1rEYeSltgbtltcqGVcq2zjIzaHXzY1UPjOz1U4W2ROiA33MkSS79os6H7w6+NK/wAWVoz3MTePgzi0mm0IM8fAilaGXvEuBLZQ2kuoA3evOXDNktmIVVkkA98yBJKD7tQ2w9h2JXt7oAELZtZVUDxuPJ9TkGs1Xvx26ScoRAY7oXMN5nvzqTBJ6kA7imbmOu3NHuMw8CTHwXYfKpEnvGEMsFdsWUDo1qySFOS4WusCNmyo8E7GSoPkKn3+Y7bxmxUCDCqlxAraiRFsyNZ1GhUbis7WnQ9QK3Gh9xZFCW2Ny2RmQKbodwP0WaTlHeOpAJG0zrU/A4LCtbBvXbQOwJYroAI8DG9DqW1fCAhizZVhd8hR8rEdRK5RHhtuaiYuz2tnue/kCiTAgGCdt4mPUUa3EFGoM8wXLd3EXGtFRbmF97UDTMZHXfykDpRNa5ftfZ7F3DXT9pVFYwGyuWEsh0EbkA/DzAVftOhyupU7wdKMOUePXCgw5IGQd09Sv4fUT8vTXXktUBWQUW1GQeZuNG4osqGtxBuC4RmDj7o0nKPEwT4Dq9ylgWu2cb7rE2Mq9SSczadd1WhzjeLN2/cuEzLRJ6he6PoBVxyVxk4e+A2lu4UVz+GG0aegEmfI+VMRS/CIAbbeO818Vt4i7be22i2ban9oZiRDeBaJqoL/ALPzG9SeOW8+Kvi0hIF24AEBOisVmB0MT8arr1lljMpWdpBE/OipoVFIjt0ecev8aI/Z3cRMSXuAlFtv7ozakqPymhIMRsaJ+S8Rl7UkCTkE/wCI0uU0hj4xbVDPmDGW7rWhZDM0kRlMn3Tp47TUy5jzYtrJPadwgTIBDlxLDTYDbxql4fiw+JCrkEiIZcymd5ykHr9Kk4y4LxVGVxHelIcmVCrCEhiIBPTpXnNzY8TUBwIRYbnO+tvMypcZYzgGNG1Rh5HbbePGrjA87WWQs6tbAZUkiRLAmNPJT9KBMNh10QXFciVNtgbbNbaS6kPoMsZgZMGfKpXF+Culq1bRhkXM73D7usACOpADadJ6DWmT1GRe/wB5NsSHtNNwPFrN0TbuK3odflU3NWC4niNu33LJInRrw0YjqF6KD5fM1Ns8yYq0ga3eYG2clxW7w/UfY6EDKSOoH4q1p6xv1CSb03gzay1eZrNbHtDu20tm/aVy+ckW9CoVsgMazLK/+Gr/AIdz5hLi5mZrYkCXECSYgHYn0qo9Qrc7SZxMIV0qi4fH2rnuXFbpowJ9IqQV86qGHaJVcwRpV2KVQ1Sk+fRxS4D3Mlv/AOGgU/49X/5qYdixJYkkmSSZJPjJpkNXZp5S46K9qaZV69I1KRCJJU08rVFFWXB+EXcS+S0skamTAHqamRGjPaVa8K4RevkBEJnbTf08vMwKKOA+zlgwbEMI/Auo+J6+lFuJ4xgsEOze6ltoEqJZz4EqoJA+EUAlwHJXEoeEcp4mzDBbMgyM7knaI7qxqDtJqtv8uYiyCOyaJmV7416SsmNtwKKuO852MOLRKXH7VBcTKAO6dicxBG+0VXcw89XLPZdnYU9rYt35dj3c+buwBrGXeetMcSzlZydhM84lwbEXLk9nGwEnoPGRP0q65a5MxAcXMpJExplXUR7zRPwFGfOHNbWLdpbcdtdQOTEhFI3AO5JkCZGh3odfj+Pw1632rs+ZFuFGIIZG6aAZTodtiOo3Lcae0dcTN8Q5lpd9nYuKQwtr17gg/MLTY9llqP664PQg/mlRPaHim+0LldgpsoYDEDUvrHj/AAqHwm7dw+MS3avdoDctqcp7rh8uYRJGmYiehFdQXbf7yg9MzLqscXxCXgvJn2Vy9u+rk6EOApj8Mg/u6CofG/Z/cxNwPnCKBoog7mSQZ+kdKqeN4S0+Ouq7BA14hnP3QTqdfCrDkO9cTFdklwtaYPI+7C6h46HQf4qQKNV3C3pyMdg9r4kjAey20urvm+bf9o+hq/w3JuGQQEPzy/8ASBWacTuveuX8QCYzF5nozBVHyIHwovx/FXbgyXFdldezQsrENKXAh1GuoH1pwAed5NsLJVHnaWGI5OAfPYuZD+sJj0Ijx6/OuDk0M2a7fYsY9xVTQCANc23lFA2E41xFLJxKYh2tpcFtg7Z9SAwlWB7pkCQZmtB4PzSt7BPimAU21ftFGwZBOnWCIIHnFd0l8Sb617zyeW3X+rxNzTYXQtwfkIqi4qmIsQLiNEnv2bmUOZkkypDHTYgaDTQVUcM9p2J7S2t63YKM6qzKrqQCQCZLkaAztWp4iyrqUcZlOhBpMmBYBkZTvMrfHWrh73ZNPW7b7JvTtLJIPq0VO4ThrbMrlSqquW53kvW7ibxKlSuWBEyfd3ioHOHAjYuEj3TrPiPH1B0PwPWhdiQZE+OlZ9NbTRYIsQs4rhLTOGRhfdFS2tnMLcECWZgxDGXZjkXx1PShzFNea5F8FSwyrnXKqQdAoiFWdDFI4682jqLg/wDeoH/5iJHwIp+xjzbCqDcST7tq5mTUzl7J807/AIp1qq+8WozdFx/0q5kupIuRIMjRW+Pun9YT1rUMHxPFWbVpVDXsqhbh7UZyyAKxAfQy6v8AeFAP+kNq0VcIt66wyuWUWRvI905QdpJnapJ47Ye+l+9mtkFZQDtPdIYkFDJVyzkmN500rmDMNhX9+84gXvC3+kn/AFfp/GlQd/TGD/31/wDhn/tpUml/f8ztK+BM5WnZpoV3LXoETNHQacVqaUV7Q60hEcR5TR17LMeEvujbsAR8JBH1n4GgMMam8PxNxLiNakuGGWPHwjwO3xqZE7kTdOauJnDYW9eWMyp3Z2zMQq+urDSs49mvL9rF3L97Eg3chTQsRmZ8xZmIgmIHWNT5Ua8xYR8Rg7tjTtGUEdBmQq4E+GZYrOeVOJY7BtcS1h3Y3MoKvbcwyzB0j8RnWDprVU3WSUS+9rCBb2HCgAC0QB4ANAEUOcca8ey7eSfs9rs4gfou9k93+9vrRJzNg7mMNgm5YF21hs2IXOCUYGX7iZjoaXGcFYufZHa+8PYSwoRAJ7JijMS7BlBLaDLOlAiasRAoTxz/AG3F6ycoAbC2gGO2maRPlof71e+aMSuKv2uwYsTat2wFBHeJYx5RmHyPhV3xbilq8l+xdws/ZoCMXIJIdbRMgKRuDoSDUC1dfDCy1pLVlrtvMbjZnKhnZRBuFsoyBSYFKwl8bGhtuOPHmR/aJZCXwonuYe2JP6uejjgHKmHsMtwKzPEqzNOUkdNAB6xNUfGcXdXD27ovLfa5cYdoiKsqojJOQaBg2vnS5UxuKe7eCXHvIlt4L/jiU0OokyPCBXCg05w7YRRoDn3lbjcD2mPZWko+IgyDsTG/76JuK8Ps4LC4i5Zt5WZCgcMSZbujVp0BMwPCqbl/ETiFF+/eW5nGhchW/UYaEa+UVJ4Rh71/E4u0b91BL5WDsSkXfugERoI9KC/7jZrsAnZQL5owSwHD7tzD37qOBbtjvqZBbIM8aaGNDrTljGqeG4iySJFy1cUSCYLKCRHQMB86u+VXv3Ll17mJc2rADOjHOLi9+QZOmi+Bqq5f4hcuYi0mIS21nEMylDatxI93XIGOV8gGtcoE7IxJINbUZS28fbXAXsNP6W5fVwADGVQmpOw1WI3qTbdrHBrkyPtOIAX9lQpY+h7Ir8a5xLGKmIxAGFwrJZdhldWBKi4LYAAcKx7w6bSelWPN3FrGJs4EvZuKlwPlW3cVBbIZLZEG2wYeHu6DzqgmbJ9PeAeJxCGzbthSHVrrM0+8HFsCB0jJ9a3ngvFFuYWziHIAa0rMT0MCfrIoB57fCWbNrhzPdU2ct0XRbVxr2gIYZlMnNm08qvsPwS9Y4elkXRcCMz5lU+42ZlIU75WYNE6ha5/luZjuRG+aOZsM9tkYwVPUrm8CMgJaSNIIHTwrLhfc/fb5mvOMwhtuyOBKnWDI11Bn70jXzmaba/AjznwP8hUdI5lhsKjz3SBEn9/xPx+lMHFZWB3IM+QgzpTDXTTZYUwUTi3iTON6Yi8Ogu3I9Mxioa3CDIMHxGlcuuWJJMk7k7+FNNTgQE73JP2+9/a3P8Z/jSqBNKnqLqMdyH0+Fdynz+VcVvT0ry7DwrqhjuRtwJ8RGopwWG/CfiKZRD4R61OwPDzc6k+QE/U6D50GIAuMqkxkWz0BHqD+daXyJyoQEv3NXiVHRJEz5tB9BPjEC39DqFGZkt5ZhswDR4EgEMPXWtDxWNHD7VhsrFHKoVHTuzoNm1ER57xpWdsqkgDvHfEyieueHu2MHduWmKODbAYbjNcRTHwJFBhe49zhhuXCxYW2JZixJ+0OJMnU6AfCj3jRs8Qwj2UuhDcCMCwIylWVxmU6gSsVD5Y5GuWns3cTiFuLYA7JLawBDMwliNQGJMR8Y0qysK2MzgaTvA24pS7iboLEdtessNh+lF0DTQfdPyFWF+7Fnhw7q63PP/b+ArRMPyvhgL02zcF5+0cOxILAswgbASx2+tT8PgLVsKqIiquiqqgQCZMRtJmhHGQCAHNvDb7Yu72Vu44uhWlVOXpILAad5J361c8e4BeuXrJsW0K2rVtJciO4ToQZJERpHWrrF8TsWzD3Bm/CO83+ESajDizfctxJ0L7n+4NT6TXWveN1GAFdp4x3LeIxFhLdx7KMrsYQQoVlAAChYmZO1e8Hy2bF97trEBVdYKZZIJHvaHo2oEeVPXFu5c1+6yL+EQCfLKNPnJr1Y4gBBX9Gm+ZlBY+kjSa4kXxF6r6avb6bRhOV3NxLl/EtdCQQMkEwZAJnafKfOvXCMCuGv3bzOxFwtpkIy5mz/iMxtsKuVv3nHcssR+K6co+R1/5a8XcHiI/qrR/ZOvzhfzrtD8gRTnLCmO3EGuGcvN2OJt279q4byqokEQATmDDU6qxG1V2N5LuWksXLbr2qPmebgySrBlyZh5a1a8RR0YF0K66Z95/VfQn0BNeOI3LhC276sVBkBpDagroYkyGI2O+mtJqI5EoHJN3/AHiBnF+XDdu4t5tzmd7cXFBYtcnJAY6lCxAjda880rcuJw8/Z3TIGR1FuFUhrYkQIAYd4ep8KPsC+DmIa26lic0ned8uqjU6EDen7llcmTD3bE5p0I2iAIBJkaeG3SiHPiAvfMx7mO5cxOJx962naIkhjmA7NUdQHAJ10skQOjE1qnIeN7bA4dtyE7M+tslD/wBM/GonE0vBiL16wttj3wWBzKdDbyNowyk6EEHwNVXHeZLFm2bGEtqoMnJbAtkzvCiMinqxAPgCdaY5ARVRNBJ2gXzpaU4juEABI1IGge5l/wCTL8IqieyfAfBhr9asf0bC695rvbMRkKgC2NvenWABAA6ddKhdgehU/SksS2mRGXzHzH8a8lPT5ipFwN1Qxt40wwUySdacRSIya8GfGvbpTNOIpnKVedaVNUWOKpHlXuJIGskwPP0qfcUm4FIBzMo6D3iNJ6evSnXVrB0YCSROWSCMrRrtuKXVLBJa8L5Exlwj9AVBg5rndAHSSdp9PCizhfs0vEfpMQiQYIXbQ/j0ifQxQ3wX2nYm1IuZrlswMofIdP18pfboGFEWH9qWDQSvDjm1hmuB2neSzAnfzoFCeYhcj5Z74hwjBWVdLK3L97SCTovj37Yhh13OhPWvfEOY3u2Vt3LJtkMFOVm7wgbSqkztG2+tCb86BiSy3IPQMIHod+p+dM4Diva3iQrTlkHN7sDUzMdaxlMhssJsTRtvZjj8SdXJyuZaczN1HQKBK/A+IpW+bsUnuswknYsvwBUiY85ptOG3mY523nKJzHXXWDAHr4V7+wp31LyyEAEmVGZQYEER3idfLYmaqCoiNjLS3wXNmNciXuiQSCzAAgbkEoNB1M1fphcVdfs77vI3Qvm+UvlII8qzy/aAMI8kysKRqYGkg6zMdfjTH+kF23NvJb7hK7EzB3OsE6RNHQX3EmQqzaeGcAt2QC727f61xluP/dtr+jU+YE1a4fGoDlw6ZnOhu3Dr9dvoPKsV4ZxG5dtybTN+kVP0cqIMe8Af5a7VeYXhYAthgty26hjcsoXa0WHusDI0gjp1ri/T7Rejr3J/E1C9gVGRrl0XHZ1DQwgDX/PQV7dU7Z8/vA9wTGg6r/Ks84Pw0KL0C5mthyjXFAzBQCGERofj1qfguYMc9gXvs9sd2Q73AAQOu09P50nVDHbaBsDD3ml4PGhWa27glQpBYgGDIg+MR9amfbbf9on+Ifxr564naxJsvjXu2rgYgEI05dYABAiPQ9aqeHY+/ebKizAzMdYRZAJJ6DUD4+daVymtu3vJ/wCONrPPtPpv7fa/tE/xj+NNvjrGk3Lem0sun1r5wOMdSR2ZOZsndJyiPInTSNTVQvHboBWEIMjUEx8Z/l5URmZuAJzemC8mfRHG+KWTdVGbDuhAMOVLSc8ZSWgaqBPia9XuTcNcAOV0bfRs8GNffzDyrHeA8ETEIl65dCm4G7ijRQpugwC8n+r6bFhW1cmgDBYfYDsrZAGkAounzmlX4mOqLkXQBpMrxyaiRlyuJGjTbMeZTQ/KqPmHlbDESmEZWkluz1E9SQDvofu6x50Qcz83WsMVU5ix2KiQI0hvCaG7vNql2ZhoTsboEHTTQfSs+d1Gyy2HHkPxGCj8sqXIS9l1gKwgjTqDGk6bROmtesbyNiUBfs7d1ACc3ulgNyNm+n7quMZzGEGqqxbvKh1gGdPOGH0HwH35muGV7RlWW0QlQZ6xtp5VnTI3cTY2M7cQWxBAOiOk6xM/9QqNikuu2tvXaAkHTy8aMFuXHt9szM7yUXtDm0nQz0IkkT+7Wrum8GLW7rq0yShAYkgEkse8Zk61oTKLk2xGpTYvl+9aAa7buWlbRc6FSxgEwDE6kCdqm4fgeEFtWvY5LRbXKB2jKAY1toCcx/CSNCNeleBii8l7ru8gTcObQAn3ifEUWjkTCtaD3MV2WIdS3Zs9oCdYGusaa6+NX6lHeRZKEDfsmA/3y5/9t/8A1Spv+jR+If8AFtf99KqaxF6fvGeJ6qHTrrpr+sNPj9KrsZjS8TuJ18SYk7eIq/bhyEC2ZhdRqTsdvd6hvCvVrhdtjcV9VQaS2oJ0EnLPy8KmuRFEq+J2MFlmKfRDE67x66TtvRPh+X7B11I07ofva9YjTbr4iveF4XYAV2JzZie6zQANM2iEjw1rj6hfeBfTNBUJ6VP4ZbYM0xEAeusx9KuL3D8L2d5rbhiolYeeoEQQJ1/OqbD4ozAyr/dX+Fdq1A1O0aGFy/W2ZQhwpYxlBgBZ1JBeSInpGm4qz4Ly4uJu3lbEC2id7NBhogZh3+k7yaCr2Jgx8B5f5/fT+A4mUZWBIykMNdDBB/MUnTYDaOXB2hHzXy/awIsXbV4Xs9xtYBXuBW0IOsk6+lC2IwF1rzhbNwsbhAUIxMsWIUADcgEgeAPhVjxfjlzFsi9czZVJG7D8RPXxJ3rn9NN9pW+EOYXlfIDMx90GPUT51VNQG43kmA4uGHI3C7trC3BetXLbG+sB1KEiE6NGk6TUTlTCCzea9du5IzMEB1yzuwGw1EDfUVUcw853sQ3cY2u6AwmBILHumZGhAkQTHoAzwzi9pGtAgqqw1y4ydoXYgZpBOqzsfQxO8MmFmDHzKo6ige0kcxc33r14NbJtBZC5SVMHxNUWKxl+7Od7j+MsW/fRDzBxHAXmY27d03CRDzlBMwZDGFgajp6UP3bRDkWxcgSSxGoG5Y5ZEAESRpT40AUUtRHsnm4RcIvqeF4m1PeDK8eRIH5iq/lbgrXma5OS3bBZnOwgaD1NVmHuXLauVJZTAYgHKM22YxA12mplzmO72HYjs0QnMQiwSZ3bXXbbSuKMLruZ2obX2hPZwo0nxj00G/h/4oHscOvXWYWrT3MpM5FLRqR0q6/0oZNOzRgYMSQRpsSOvptUXg3FXw95r2UMzKyjUhQzkQW8QPCfjSYMb4wxPJ4lMzI5AH7yVg8RetW1TvrCuCNokvoR8TvPWjXhHOT27CWlcmECR+EKN9pO1Zzc4g8kFdSzSuuYSdtd9fzrmOLoSCpBEAhkjKdDEzvMjWi+Jm71AGUdrhhjeMhjncKwaYJOoEkGRG2u3WTvrVjwbgly4QzWEtWtxnXvsJ0hIBE7yxHlNB3CuLXkuMMOlt2MBLjWwTaG0jN3U9SPjUviHMuOQur4lTDZWgLJka5WygnzI1Bik/x6FDmU61/SGfGeTLdxc1q4yONyZYHrtMrqZ0+VA/EOBYjDmbiEqNcy95T6n7vxAqPa5sxyKqi+2QbGAQB0BYgn4nWnMTxziGQ3Hu3AmbLrETHiB9aKYci7WCIpdW3oy04djM2GYgahnHQAAC0Z1/aFUGKul294AZUkmde6uunpXcTicTZtCWRkvF2kENJYKGOh0Iyga7GfOoGJw+IREuOrBXAyt0IAgegiN96omJQSRW8VshIog7RxWEnvKTO8H5ajp4+dRsSwJzAnpv00iK83Q4tq4EKSQDG5ESfqPrUi3wq447kkmCEjVh+JY3Ez8qsABuTJbnYCVmUedKrf+hm/tLf1pU2oRem0m28atxlttcY6BTPiZUtMbwZ8oqEuPt2rhb9MXBhgWAzRGjaSQYryvDj2YvBxmDlWSIIA0zjx3jbpWg8ucs4S9F+6rO12Ztkwq7Enxk+o61FmROeOP3lgMjC+/wDEz3EcRS5ce52b52kk9p/BRAjzrti4xYOtrXoxdiTA6mdaPOOcnWLZW9YPZlZJsuM6nQ6GDIBMDcj8qhcG5Te1iLWIRTiMP3s0LmPusPcGhgkGB9aAyoR8P23+07puDbfxKEYJC9wuuUKSqyNGiZO4mDHlqKr8bdQdwA5QI16HSeniDWgYbBXsU/YLbBVXU3DcAAtrKgnUaNowG5+Wl3c9k1p7/bNfzKXzNbCQDrMAzoPhQxte5jZiF+EETHsREwoIXScx7zeZ2ifD869Yi0YiB3SROh06CdtP31q3NHs0a5ixetaWjkzJqSCoC7zJBAE79aquNezm6LzuUZbACBAmrEhVBJWDEkE9TTlwP/JNQD+/uIDLwsjLcDW7ggMQjjuQRpdmMkj/AM1YDgt/EN2tq2ql3yhFaJbQEoZOYdSZ3D+Bpcy8FGGuAlCF6I4ie6DM5pI70awZBrvDuJYnD3VxEsPfAk90sVaAROwkNl9KOqwCISgFiv75lpguRbYz28ViUsXwCUQshBUDMWIBzBYHkdDVLw3hS3bqpbuLcb8GoBI/CzACCBM6Vacs8FOPxLvcdwJLPcdspYsp2MAaCDHhA2IqtxXAbtu9ctpFwIR3yBkcTAO5BG59BQLdiZyqb4ud4vwS7h3RriZNicmZiMo1J0gSfA9ateTsG963e7V0t4coVzsyIFJECCxBIGniNAKgcX5jchrYnIECEH/aBGJRiDt3coifjrXjmTgL4ZbZcgsc2izNsT3fTMNaXcijDwbWE2H9n9+xbNx2LWnRxd7IgypWVaATnAPl1naaobPLt7MRbtgWryDI+lwAHvKJP3zEadW3iasLPGMeBhvs7XGRrRy2VLOBFxxlK9YBUa9Imj/kFzeLjEYfscRaEZIZFZNMrKh0Goy6aaUDr7bxdQUW34gVwvlBGa5hXyhx+kN6CxZcygJpooBB858t2m5Wde3sXLakgqVuFhlSTClWImIOqnwPQVd898v30LNbxDA5QeyClZgn/aKwBOpgHrQLxm3eVVN4nPEatMSAZO/vCNvA1NSx2J3l9IqwNpZ2cIMSl02XXPZm5cvXBlIsqAQ6gTBBU6DoR41N4ZxC1dYPczOLl0WrgygBrbKE1+4pzd8tvIielE/AeQ7NuzeuLe/1jDtbBLd1A4BJkDUSBvVXx/jtm0lq0mgULsukrtoND0JrnbSBpFwY7cm49x/l1Wt23wipZTukNlBNzLBQwJPQmWj3qosXmuYW4btu0uIVgC6kZrqtrIQKRmmNRv60f3sarJbyohRgGZLgK5dJOkaHXrtvT2M4bbnC2bSlGusxP3oQLnZi0+IUabyPCpIztYG9feE6VrVYmPY7s2SytlMoyE3e8SS4Yhg2bQEBRGg3FbRy7wbB27amzbVv0YWHbPAicpElZO5PX0gUO838v4TBYe8tu5bV8Rr+mOoyhpa0ApMyV0jruKDfZXiH+3KJAU27kjTwB+c/vrUQa+kgSGFi4S+0Lh2HsXLdxcOgtlHNy2M+Vu8PdyoVRhJ1YqO916AbcxlmS2LKvZUgJZZiZiAoLddh01oz9pXCMRdxFsKRka2WVS3VWysY2902/n56h3NfC0shSmYAOUbMQZOUGV6kb6x4UEKkgHmU0sE1A7Sf9qfEq9i7hhZuDK6m3byAKD3iymdQNj/Koj4uzZs3rCOO0ui2naawBmlpicojeJmiP2M8bsW71y3dYB3WLZbrJErPiYGnWKrOeuTL/wBqv3LNvNbdu0VV3GfvEBY8SdqcKA25oeIuskEAX7wR+yW/7e1/z/8AZSqV/RWI/wB2v/8ACb+FKq7eZP8AaNYue+wuaOS2UanU9fD+VXnDOPXbFkXAMxXMhDfrwZ8f/PlQ48qo9Yj+VXNrD/1lloDMgO4aDoQZXTZh16VJwK3G00pdmtjX5kXH8z3LisB3MwCkAk92Z0JMjaPMVdezbi7WDeZny2QqltTGbNC6eME7eA3qo4VwxUzG9ba7IjIoM2ySCGZgywxj3ddCZilzBcXs0S1a7K2pOcGc5c7FwZI7oMake9rTaUoqsiTk+Z5c8y85XWuEYe84twJZZQuQN2gKTpoJ8Kdt863Ww4Fxs91TlUsA0rvnIO5g5Z8vOgSywDCZiRMbx1ir7i72SJS2bbAAiFEa9GObf4Gg2NaC1CrXbTaPZ9zSb9ki447VSgOymCpO0j8Df5FXX+mWDD9n9ptM8nQONI6EyRNfPVjHYlLTOgZLbxbZwCFY945S3jGbbpPSvfBeGG7eKXS6ACTpBG2+bYa0DagkmL0Q7bd4Q858z3MXiWAsI622K2hBJIB95svvTExtFXP9BPjbdlro7G2M1x0YNmgd0W183hzJiAB4xVLctYWwGCYi4HK5S4jONQYA0EH50a8l8Qs3rDpad8yMGZrjZmLMIDCTt3dvL5xLD5gOPrNBxlF03/qZ1xnmoXVNq3bNu2CIGbvQNgTGv8qLfZFwL7TaxBuoexzJ2dySpDrOYCDroVnpVTzByVcJdkDXr1wqwNsZVknvMQDpPh0PhWpcqIuGw1jCbXLaDOIIBZpZmBI7wLE6iqJ09JqRzHICN5XXfZfgGui4SzEEFgT3WjoQNANIgCh32wYG7bR7pE2nuBVy6he6BLT7p0IHoNelHxxgJuAMAVMMQdjo0beBHjvTHFbdu/Ye1d1tsozT4SDPrpSkrtfaTXqA3ftBblbHOMFZK4cWna2i5wS2cIqorsFWVzLbnYiAKtuD3S91G+0Wu0UuAFbtNDDFSQBA7n571ORbSoAqAgAKJ10Gg8ht0G1DCc54W0xdbbtlMZlRR8FzMNJ8aiWt9U0KhKFQIS4vBjEZ7l4G0loQ5IiQO8YPgB1G00PYBbGPc4Y28yiSCRl7qmFOhkGG/OrzD8wpj8LfSzPaC2wKEZW7wYDaQZ8RUD2ZYdUS7dPvM4t+gUAn6sPlTHGC619SYFdlRr5GwHiQfarhHtYRbVswndEg7hR7o8NhPjFZHwRDcv2rZJys6gjymvozmfhqX7ZW5GUSIiT3hlkHpoTrWc8ucjW7eJV+1JyliuUzsCNe6ANSD8KozBSV+0XENShvHMnY4nOcgJgr2g3IkpOh/VH0NFXDLlpLnaE5mFvIkasVJEgGYJYhfDaoeD4fbspJXtbjd1rjaNuTGnQGaouX5t3Exd4qbZV3W2C2ZC5DJp7pyrpGmseFZsa6DdzTlrIpAB/7j/tb5Z7bLdtwLig52PVQrELE9GA2/Ed6FPYxwhr17EOWKotnJnGjq7sCpXQiQEbedxprWu8PRMTZF1ho05Sd4k6gUzwvhFjChxai2rtJACgTsDpW0Me42M888UDuJ443wh3soiXMzIuXM2mYgAEyBpMVkftQ4KcPaw5JLFmu526Zotwo6xAb61s+Pu3AVRFLs2kAhVA6uSQSAPKfSo/HMFhMgXFFHDRCvGWRrI6zr4+FIqgPrqMMjaAlz5t4Hils3lvMguZJIQmAWg5ZjoGgx1iK1flz2rtfdLV1LdpiYBUSra6LqwyGNJJIJ+VAvtMwNqzjWWyoW2bdtgq7CRBj5TQthVl1ExLKNdtxvWitS3EqjVTfftrUqh9sPAfKlWOj5m3pr4mOX7qEyd9iZmfp4VacBNvJekQym26EAe6SUcE+HfQx+rQ9dWNIEb16N3atRWxUkHIaz2hOccyTbQKqDNcJJku526SNYEVScZvu+VnEEjYdQDofqal4+12mVwY0B+dP4XlTGYnO9q32ipAzSADoNFk6xNJjCg33lfUaqI3rt4g0tXZ4Tibtpr6WXayslnA003P86i8LwIN9Ld6UGfK8ggiNwfDwr6AtcWtWkVO7lHdjQACD08IBp3cKRchjxuUNTMeB8Lu4jh6W1tsw7XukahYILNGsaT4b+cV55kZlttAhgdYGoG5k7gTFbPylwexhLHZ25hmZzm3GYzliBAAgR5VU+0DA2WsNdygOCveGhiddeulQyJ+q+N6lcPqLPTrna589t4k1d8s8TuYd86gkMII8QCNjtNTsT2bjK0CNYFeLNoGy+RGhSmp6amB49aU5Qy0RNS+nKtdwx9n3HnN7I8mEuCNyYObpudPrWkXOKqCoI96YBBn5AaDXckdKxbkqTiBHUODIndSNutaM3ESbAZJEqdYyxOglddfI0qsVsCRz4QzAyyx0naFB3O5PrpFBPGcXi7jtbRCcrZZVjEbg7QPAnpRTi+MWrc9q9tV8WcT6RuaH7nFlvMxtFiFcRAiQdNAfKd+lI+28pgTsIuMYcphLiqWzCySWPvEkGSWmJ0PSskbGtGTSIj5VsmMvQu07+BnRtayvmLl65ZfuKzW2AKsBO/Q+dUwFbIM7MjhbEmckY25buXnRmBFkjQxPeU667QDWsck4u0uF7WdLl24xkxLEkGI/Zmsh4Vw6/bs3rygoUTtMxEnLmyRB2nMf8PlRTjbosYTDYRipKob1zxV7kspU7aKx06wKowq2H0kQoYBDzyYbYziLo6utztLbjuW/vE9Xme8okelQuJ3wGa6rG2VZe1WP60tAVZ+6dR3jpVRfVTfwyMrmLRIzPB1MTA02QaVH4pibX/q0yJMAiWJkoEIETWc7maVxgVUIeM8R7W2LRbsrl1WUQ0QABLKQfeUkHzEisbvcavhDba4+hKkEzAGmX4eNEPGeZFzWCttc9ls0rprpp9Kob3Y4i+1xmNpbjlmWJjMZOU+viOtaMQ+G2EhlUq1IfzN84JcFnBYZAZy2LQ9ZUEn5moly+ZuQCpOzBQJ21zsCJ+H5UP4DmTt4tZQoQrqp7pA2EbjYdTUjiNxZeAzEqqEaxAzExAMHvH6VDJk1GPj9NQAPMJeF4zQtmLFFCydzmg6wBroKg8R4sXtC4CAp3JuG3vpE9TJAjxrPcXxK/YL99rYuZSgBlcoUACNp+E7VC4lzi7WFsBQAFAZvvMZmR4CfyphqYVCcKqdUme0YYdyrOYvBAIBzERrDdI1OsyfhQ1yHw+2+LRbuoALoJgMykEDz0BMeVVeJxeYk7ydT1PxqOt2DIkEbEH99aUUhNNzNkKFwwHE2TIvgvyH8KVZL/S17+1uf42/jSqXQPmX66zTeJcp2Xs4e3GU2kMgbsz5SxY7kyPrQBzTgEs32tpBChfWcoNbhwPBWVthc5vO2YG40STJnKBosHbciBrpQtxr2c2r2Zlv3BcMwWAYehAAP+etOuoNZMQshUqFr+ZmNohrUeGn7xWtct8RtYfB2jddLaKgBgyGY94gAas2uoE6zWbcU4BewbBLojMJDDVWg9D4wRpUa3iiVytJA1WdhO8ep1pXE0KodRcLOP8RwtzFW79lWkqyvmXwiGifAka9B6VCv4tmxeHRh3O0TMJ0OVhpPXx+IoaxGNyAT4narLhHETeZRkGe1Dh5IYhfLYxp8BS6TeqobQDpg7zdOD3+1YguSFMTpLdY08Ovwqz4zwi3eQqwIkRoY/jQZyBekC4LpLZWzWyIXV/fBiScum8elFeL4ulpGuXGAVepMARuSaqmkr8U8zMrLk+HtMxHs+JxEPcIsgmTs4A6DSD6/SrTG8Bw+HssqZmYklS7SxYCBtA006UOcye1K47kYVEVBpncEs3mFnQesmhLE814m44e5cDkbBkUqNz7sR13pDiNUJrXN8WpoZcnWezxSMZAXwBPvSANB4xRfznaQ2b7Ex+iLADeT3T02kKY8S3jWecJ51JAtv+hO2eyqjN0AIYELEzIqxxnGWuvds53KheyBbQsYJz9OradIUGkClRTSzAZHDqYAXQO0OkRRlwXFi3bLsYAy9fPLqfCgi2e8Sa1n2XcGt4jvXUDW0VDB1DPqQCD4Rmj0p3TUQIq5RjRmlpgeG3sUoyJCnXtGKm3BG6mCWEHSPnRBe5MtlVVrj6ACVgAx5RpRLcxYGg6UO2+YySf0N0iRByldPPPG1N0sa87zH/kZ8htdhGMTyUjWHtWr9y1nRkY5bbhw2neDJOgJjKyxNCnOfKvECbzolu7badFPeVYEkK0QYXZZmizivNCWbqW2u20zD7zEMTPToB6/u1ssJxtXGjCRuJ2pqXicpzKS/N+ZlfaWjibEhWPYKJc5WEZ5BHjVXiMcinFZVtTmMQJOuUafPeifnhlt423cYIUe2QCyBoIJzDx+8D8aAOLYsZrwXLBf7ojTTY+FQ071PTVwUDQeL602DSuV7GHMA+PStW083cmajyXbW3YV3jO3fAie7AA1+HWhbmHmG6111DkKGIyjYwevjt6VH4FzQ1tVsupZA3dOcjLPlsR+WtV/M1kpebbvd7QyNf8AM/GoLipzc1tnvHa/vPGI4gGG0Hy0B+HT4VBuXZpomktXCgTI2Vm5nomvJpE0qaTM7mpVyKVdO3mocA44yqbVq4DljILxytBnMgZRqQ2skHQiiuxxfMvedVKiWBMFjoAgI3lmG3gaxHPO+vrRRwDGdoSW1NtSVHTMTAJ9JqBWp6JphQ2hbztg3vWrf6W0StzcHRRBDfDVfUxQtb5ZuE5UxFkr5knU9mApAnUs8Dxy1b2cF22HuWwZaM0eqmPoAfWs+VjpqRMbGNRRSu4kmVxsrfiX9/lQsuuJsdcsPO2cyfwjLbJ6mWURTH+i3ZkE4uwDmYCGmMqsxnTSQjAeJgdaouJWQuVhGoggCII/lUa0AWHqKuNOnYTC4fqGzvN05YwxW1bR7luLTtkdGMNJuqQdpHltqKp/aJau3rYRLqBEDOwze8wDNlnqdAMo6spqp4NfK4Rcm3aMpB330/Z1M+ETVLxXiSOhs3NlcsrKoJ70AowLAHYQdxFZ1IDcTa2NipOr8SNhuVi6hjibCaAkFjI7qNGg198CRVPwnCC6+VnCKBJY9Nh467/IGmr9lB7jEjwKwfoTTBBrRYmLQw5Ms+BcNF+6bfaC33ZBaACcyqAddNWBPkDRNwrghCknE2Z0I7+pOW2QNfJwJ8R5UCinsoz6HSdD5UrKGFGUxsytYMK+J8uAHMt+0SzquUNp3mdc/kBlB+NaxyHgPs/D7YLKSxa4SOoLQpH9xV086wRmBuDMTGgJGpjqQD5Vt+I4xaNhPs7qbaqqqPwhQAARupAHWkJocSpRnar2vxCbCXsw95ZJJ384/KqLFJbZyHxLTqcvaRExChfIwB61VcvcSD2DckSM+g/aYD8x9Kg8e4n9ne1bCoAUzOTGaZkDcHUkyddvjSar7SgwkHY/iWPFOAhmdbb2xdvmGZjnMAZYA8AFmOtEHBeUnsJlQCT7zMxLNEgSY022jrV3wrAWrao5toboAOaAWEjWGIkDpVsl6aquMHmY8nqcgNLx9ID8W5WxNxbYQqrIxOYkbFW066Tl6dKD+IcnPbF43zJcsxYKcgUeDaAkwD020nWthbiSFioYEjcA6iol26D/ACoNjXtGxeoy95844DgaXTcLXVtqgkagz720sJAyxprqKnnlNmUBcRZnUHU6Q0EgbkBQWnwBrYOJcv4a8SXsW2J+8UAPzEGs+5w9njCbuFBy9bQ3GkHLOrCPu7777UBtVyxJNlTV9pS8I5Mtgu167afKBCC5l7xUNDbH7yjQjfyrnEOWlYn/ANRZAAhYfNp3lAB8sgmehqjwGGZc5J0DJIbSW1Ov186h3EAuMqaqW0G/w/nTEgmBcbKoBPPO0tW5UgqPtVg5hm7rE6SAdSIB7ynXeT4GnRygJAGKskMSq6wZGYSdYAlfHY1Svwx9dCKhXEjQjWnDA8SD4XTcmesTayOyyGysVzDYwYkeRpqrbAcFe7ba4GUBQTBnWOmggep0quxGHdGKupVhuCIOu1AGcVI5jc0q5SowyWKuOXdrv7H8aVKombhNE5I/2vw/fWUYj3m/aP5mlSoCMeY3xL3R61Dsbj1H51ylVk+WYM3/ADTRuD/6t/8AVf8A6TQdjN3/AG/3mu0qgOZ6DfKZBfcVx9j60qVWmRu8ZFOLuK7SomIs9P71T3974UqVTbtNeLkw75O/1Nv2l/8A1qT7QP6t/wBlf+paVKp95QcTW+ifs/uqSNvhSpVqnjmBHAf9Zv8Arc//ACtRIKVKpzSInph6VKgYwmTc/wD+s3/W3+VCfK/+sH0b8xSpUo7zQf0S6xu1CeO96lSpcfMbN8sJOVv6r4tUbnb3MF/8pb/NqVKqryZmy/KIM0qVKmkp/9k=" class="img-thunbnail">

                    </div>
                </div>
            </div>
        </div>
    </div>

    <main class="container">
        
        <div class="row">
            <div class="col-md-8">
                <h3 class="pb-4 mb-4 font-italic border-bottom">
                   Fique por dentro das noticias
                </h3>

                <div class="blog-post">
                    <h2 class="blog-post-title">Atlética Guará está de volta!</h2>
                    <p class="blog-post-meta">30 de Junho por <a href="#">Gabriel Odorcik</a></p>

                    <p>This blog post shows a few different types of content that’s supported and styled with Bootstrap.
                        Basic typography, images, and code are all supported.</p>
                    <hr>
                    <p>Cum sociis natoque penatibus et magnis <a href="#">dis parturient montes</a>, nascetur ridiculus
                        mus. Aenean eu leo quam. Pellentesque ornare sem lacinia quam venenatis vestibulum. Sed posuere
                        consectetur est at lobortis. Cras mattis consectetur purus sit amet fermentum.</p>
                    <blockquote>
                        <p>Curabitur blandit tempus porttitor. <strong>Nullam quis risus eget urna mollis</strong>
                            ornare vel eu leo. Nullam id dolor id nibh ultricies vehicula ut id elit.</p>
                    </blockquote>
                    <p>Etiam porta <em>sem malesuada magna</em> mollis euismod. Cras mattis consectetur purus sit amet
                        fermentum. Aenean lacinia bibendum nulla sed consectetur.</p>
                    <h2>Heading</h2>
                    <p>Vivamus sagittis lacus vel augue laoreet rutrum faucibus dolor auctor. Duis mollis, est non
                        commodo luctus, nisi erat porttitor ligula, eget lacinia odio sem nec elit. Morbi leo risus,
                        porta ac consectetur ac, vestibulum at eros.</p>
                    <h3>Sub-heading</h3>
                    <p>Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus.</p>
                    <pre><code>Example code block</code></pre>
                    <p>Aenean lacinia bibendum nulla sed consectetur. Etiam porta sem malesuada magna mollis euismod.
                        Fusce dapibus, tellus ac cursus commodo, tortor mauris condimentum nibh, ut fermentum massa.</p>
                    <h3>Sub-heading</h3>
                    <p>Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Aenean
                        lacinia bibendum nulla sed consectetur. Etiam porta sem malesuada magna mollis euismod. Fusce
                        dapibus, tellus ac cursus commodo, tortor mauris condimentum nibh, ut fermentum massa justo sit
                        amet risus.</p>
                    <ul>
                        <li>Praesent commodo cursus magna, vel scelerisque nisl consectetur et.</li>
                        <li>Donec id elit non mi porta gravida at eget metus.</li>
                        <li>Nulla vitae elit libero, a pharetra augue.</li>
                    </ul>
                    <p>Donec ullamcorper nulla non metus auctor fringilla. Nulla vitae elit libero, a pharetra augue.
                    </p>
                    <ol>
                        <li>Vestibulum id ligula porta felis euismod semper.</li>
                        <li>Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus.</li>
                        <li>Maecenas sed diam eget risus varius blandit sit amet non magna.</li>
                    </ol>
                    <p>Cras mattis consectetur purus sit amet fermentum. Sed posuere consectetur est at lobortis.</p>
                </div><!-- /.blog-post -->

                <div class="blog-post">
                    <h2 class="blog-post-title">Another blog post</h2>
                    <p class="blog-post-meta">December 23, 2013 by <a href="#">Jacob</a></p>

                    <p>Cum sociis natoque penatibus et magnis <a href="#">dis parturient montes</a>, nascetur ridiculus
                        mus. Aenean eu leo quam. Pellentesque ornare sem lacinia quam venenatis vestibulum. Sed posuere
                        consectetur est at lobortis. Cras mattis consectetur purus sit amet fermentum.</p>
                    <blockquote>
                        <p>Curabitur blandit tempus porttitor. <strong>Nullam quis risus eget urna mollis</strong>
                            ornare vel eu leo. Nullam id dolor id nibh ultricies vehicula ut id elit.</p>
                    </blockquote>
                    <p>Etiam porta <em>sem malesuada magna</em> mollis euismod. Cras mattis consectetur purus sit amet
                        fermentum. Aenean lacinia bibendum nulla sed consectetur.</p>
                    <p>Vivamus sagittis lacus vel augue laoreet rutrum faucibus dolor auctor. Duis mollis, est non
                        commodo luctus, nisi erat porttitor ligula, eget lacinia odio sem nec elit. Morbi leo risus,
                        porta ac consectetur ac, vestibulum at eros.</p>
                </div><!-- /.blog-post -->

                <div class="blog-post">
                    <h2 class="blog-post-title">New feature</h2>
                    <p class="blog-post-meta">December 14, 2013 by <a href="#">Chris</a></p>

                    <p>Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Aenean
                        lacinia bibendum nulla sed consectetur. Etiam porta sem malesuada magna mollis euismod. Fusce
                        dapibus, tellus ac cursus commodo, tortor mauris condimentum nibh, ut fermentum massa justo sit
                        amet risus.</p>
                    <ul>
                        <li>Praesent commodo cursus magna, vel scelerisque nisl consectetur et.</li>
                        <li>Donec id elit non mi porta gravida at eget metus.</li>
                        <li>Nulla vitae elit libero, a pharetra augue.</li>
                    </ul>
                    <p>Etiam porta <em>sem malesuada magna</em> mollis euismod. Cras mattis consectetur purus sit amet
                        fermentum. Aenean lacinia bibendum nulla sed consectetur.</p>
                    <p>Donec ullamcorper nulla non metus auctor fringilla. Nulla vitae elit libero, a pharetra augue.
                    </p>
                </div><!-- /.blog-post -->

                <nav class="blog-pagination">
                    <a class="btn btn-outline-primary" href="#">Older</a>
                    <a class="btn btn-outline-secondary disabled" href="#" tabindex="-1" aria-disabled="true">Newer</a>
                </nav>

            </div>

            <aside class="col-md-4">
                

                <div class="p-4">
                    <h4 class="font-italic ">Secretaria Acadêmica</h4>
                    <ol class="list-unstyled mb-0 ">
                        <li><a href="#">Calendário Acadêmico 2022</a></li>
                        <li><a href="#">Edital de Monitoria</a></li>
                        <li><a href="#">Empresas Parceiras</a></li>
                        <li><a href="#">Estacionamento</a></li>                                                
                        <li><a href="#">Regimento Geral das FATECS</a></li>
                        <li><a href="#">Regulamento Geral dos Cursos de Graduação</a></li>
                        <li><a href="#">Sistema de Reserva de Salas de Aula</a></li>
                        <li><a href="#">Provas e Gabaritos dos Vestibulares</a></li>
                      
                    </ol>
                </div>

                <div class="p-4">
                    <h4 class="font-italic">Últimas Notícias</h4>
                    <ol class="list-unstyled">
                        <li><a href="#">Inscrições abertas para o vestibular 2º semestre 2022</a></li>
                        <li><a href="#">Imposto de renda 2022</a></li>
                        <li><a href="#">RELAÇÃO DOS CANDIDATOS CONVOCADOS NA 7ª CHAMADA DO VESTIBULAR 1º SEMESTRE DE 2022</a></li>
                        <li><a href="#">RELAÇÃO DOS CANDIDATOS CONVOCADOS NA 6ª CHAMADA DO VESTIBULAR 1º SEMESTRE DE 2022</a></li>
                        <li><a href="#">Inscrições INOVA</a></li>
                        <li><a href="#">RELAÇÃO DOS CANDIDATOS CONVOCADOS NA 5ª CHAMADA DO VESTIBULAR 1º SEMESTRE DE 2022</a></li>
                        <li><a href="#">4ª CHAMADA DO VESTIBULAR 1º SEMESTRE DE 2022</a></li>
                        <li><a href="#">3ª CHAMADA DO VESTIBULAR 1º SEMESTRE DE 2022</a></li>
                        <li><a href="#">Informativo nº 01/2022 – Faculdade de Tecnologia de Campinas</a></li>
                        <li><a href="#">Cronograma Processo Seletivo Vestibular 1º Semestre 2022</a></li>
                    </ol>
                </div>

                <div class="p-4">
                    <h4 class="font-italic ">Inova</h4>
                    <ol class="list-unstyled mb-0 ">
                        <li><a href="#">MOOC</a></li>
                        <li><a href="#">Escopo da ficha de inscrição</a></li>
                        <li><a href="#">Áreas e sub áreas enquadramento do projeto</a></li>
                      
                    </ol>
                </div>

                <div class="p-4">
                    <h4 class="font-italic ">Links Interessantes</h4>
                    <ol class="list-unstyled mb-0 ">
                        <li><a href="#">Clube de Arduino</a></li>
                        <li><a href="#">Ciência sem Fronteiras</a></li>
                        <li><a href="#">CNPQ</a></li>
                        <li><a href="#">Currículo Lattes</a></li>                                                
                        <li><a href="#">EBC Notícias</a></li>
                        <li><a href="#">Emprega Campinas</a></li>
                        <li><a href="#">EMTU</a></li>
                        <li><a href="#">FAPESP</a></li>
                        <li><a href="#">Ministério da Educação - MEC</a></li>
                        <li><a href="#">SBC</a></li>
                        <li><a href="#">Conselho Regional de Química</a></li>
                      
                    </ol>
                </div>
            </aside>

        </div><!-- /.row -->

    </main><!-- /.container -->

    <footer class="blog-footer">
        <p>© 2022 Fatec Campinas, SP | Telefone: +55 19 3216.6474</p>
        <p>
            <a href="#">Home</a>
        </p>
    </footer>



</body>

</html>

