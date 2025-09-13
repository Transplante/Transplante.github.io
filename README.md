<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Doação de Órgãos e Tecidos</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: #333;
            background-color: #e0f7fa; /* Fundo azul claro suave */
            /* Use um gradiente suave sobre a imagem de fundo para melhorar a legibilidade em qualquer tela */
            background-image: linear-gradient(rgba(224, 247, 250, 0.8), rgba(224, 247, 250, 0.8)), url('https://images.unsplash.com/photo-1507537528715-e72538d1e667?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80');
            background-size: cover;
            background-attachment: fixed; /* Fundo fixo para uma experiência mais agradável */
            margin: 0;
            padding: 15px; /* Reduzido o padding geral para telas menores */
        }

        .container {
            max-width: 900px;
            margin: 30px auto; /* Margem superior e inferior um pouco menor em telas maiores */
            background-color: rgba(255, 255, 255, 0.95); /* Fundo branco mais opaco para o conteúdo */
            padding: 25px; /* Padding interno reduzido para telas menores */
            border-radius: 15px;
            box-shadow: 0 10px 25px rgba(0, 0, 0, 0.2);
        }

        h1, h2, h3 {
            color: #0056b3; /* Azul mais escuro para títulos */
            text-align: center;
        }

        h1 {
            font-size: 2.4em; /* Tamanho de fonte ligeiramente menor para o título principal */
            margin-bottom: 20px;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.1);
        }

        h2 {
            font-size: 1.9em; /* Tamanho de fonte reduzido para subtítulos */
            margin-top: 30px;
            margin-bottom: 15px;
        }

        h3 {
            font-size: 1.6em; /* Tamanho de fonte reduzido para outros títulos */
            margin-top: 25px;
            margin-bottom: 10px;
        }

        p {
            margin-bottom: 20px;
            text-align: justify;
            font-size: 1.05em; /* Fonte um pouco menor para melhor ajuste */
        }

        .highlight {
            color: #d32f2f; /* Vermelho para destaque de importância */
            font-weight: bold;
        }

        .emoji {
            font-size: 1.4em; /* Tamanho de emoji ajustado */
            vertical-align: middle;
            margin-right: 8px;
        }

        .section-organ,
        .section-tissue {
            background-color: #e3f2fd; /* Azul muito claro */
            padding: 25px;
            border-radius: 12px;
            margin-bottom: 30px;
            border-left: 8px solid #0277bd; /* Borda azul mais forte */
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        .section-tissue {
            background-color: #fff9c4; /* Amarelo muito claro */
            border-left-color: #fbc02d; /* Borda amarela forte */
        }

        .cta-button {
            display: inline-block;
            background-color: #4CAF50; /* Verde vibrante */
            color: white;
            padding: 12px 25px;
            text-align: center;
            text-decoration: none;
            border-radius: 25px;
            font-size: 1.05em; /* Tamanho de fonte ajustado para o botão */
            font-weight: bold;
            margin-top: 15px;
            transition: background-color 0.3s ease, transform 0.3s ease;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.2);
        }

        .cta-button:hover {
            background-color: #45a049;
            transform: translateY(-2px);
        }

        .footer {
            text-align: center;
            margin-top: 40px;
            font-size: 0.9em;
            color: #666;
        }

        a {
            color: #007bff;
            text-decoration: none;
            font-weight: bold;
        }

        a:hover {
            text-decoration: underline;
        }

        /* Media Query para telas menores (celulares e tablets em modo retrato) */
        @media (max-width: 768px) {
            body {
                padding: 10px; /* Padding geral bem menor em telas pequenas */
            }
            .container {
                margin: 20px auto; /* Margens menores */
                padding: 15px; /* Padding interno bem menor */
            }
            h1 {
                font-size: 1.8em; /* Título principal bem menor */
            }
            h2 {
                font-size: 1.5em; /* Subtítulos menores */
            }
            h3 {
                font-size: 1.3em; /* Outros títulos menores */
            }
            p {
                font-size: 1em; /* Fonte do parágrafo menor */
                text-align: left; /* Alinhamento à esquerda pode ser mais legível em telas pequenas */
            }
            .emoji {
                font-size: 1.2em; /* Emojis menores */
            }
            .cta-button {
                font-size: 1em; /* Botão com fonte menor */
                padding: 10px 20px; /* Botão um pouco menor */
                width: 100%; /* Botão ocupa a largura total */
                box-sizing: border-box; /* Para que padding e border não afetem a largura total */
            }
            .section-organ,
            .section-tissue {
                padding: 15px; /* Padding menor nas seções */
                margin-bottom: 20px; /* Margem menor entre seções */
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>
            <span class="emoji">💖</span> Doação de Órgãos e Tecidos: Um Ato de Amor que Salva Vidas <span class="emoji">💖</span>
        </h1>

        <div class="section-organ">
            <h2><span class="emoji">🌟</span> O que é Transplante de Órgãos? <span class="emoji">🌟</span></h2>
            <p>
                O transplante de órgãos é um procedimento cirúrgico que consiste em substituir um órgão doente ou em falência por um órgão saudável de um doador, seja ele vivo ou falecido. Esse procedimento é a única esperança de vida ou de melhoria da qualidade de vida para milhares de pacientes com doenças crônicas em estágio terminal, como insuficiência renal, hepática ou cardíaca. O sucesso do transplante depende de uma rigorosa compatibilidade entre doador e receptor, além do uso de medicamentos imunossupressores para evitar a rejeição do novo órgão pelo corpo do paciente.
            </p>
            <p align="center">
                <a href="variedades.html" class="cta-button">
                    <span class="emoji">➡️</span> Descubra a Variedade de Transplantes <span class="emoji">⬅️</span>
                </a>
            </p>
        </div>

        <div class="section-tissue">
            <h2><span class="emoji">✨</span> O que é Transplante de Tecidos? <span class="emoji">✨</span></h2>
            <p>
                O transplante de tecidos, por sua vez, é um procedimento que envolve a transferência de tecidos humanos, como córnea, pele, ossos, cartilagem e tendões, de um doador para um receptor. Diferentemente do transplante de órgãos, o de tecidos geralmente não visa salvar a vida do paciente, mas sim restaurar funções, corrigir deformidades ou melhorar a qualidade de vida. Por exemplo, o transplante de córnea pode restaurar a visão, enquanto o transplante de pele é essencial para pacientes com queimaduras graves. A compatibilidade de tecidos também é importante, mas o risco de rejeição é menor do que no transplante de órgãos.
            </p>
        </div>

        <div class="footer">
            <p>
                Lembre-se: A sua atitude de se informar e compartilhar conhecimento sobre doação de órgãos e tecidos já é um grande passo para fazer a diferença na vida de muitas pessoas! <span class="emoji">🚀</span>
            </p>
        </div>
    </div>
</body>
</html>
