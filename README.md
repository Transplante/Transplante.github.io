<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Doação de Órgãos e Tecidos</title>
    <style>
        /* Estilos gerais para a página */
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: #333;
            background-color: #e0f7fa; /* Fundo azul claro suave */
            background-image: linear-gradient(rgba(224, 247, 250, 0.8), rgba(224, 247, 250, 0.8)), url('https://images.unsplash.com/photo-1507537528715-e72538d1e667?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80'); /* Imagem de fundo com gradiente */
            background-size: cover;
            background-attachment: fixed;
            margin: 0;
            padding: 20px;
        }

        .container {
            max-width: 900px;
            margin: 40px auto;
            background-color: rgba(255, 255, 255, 0.95); /* Fundo branco mais opaco */
            padding: 30px;
            border-radius: 15px;
            box-shadow: 0 10px 25px rgba(0, 0, 0, 0.2);
        }

        h1, h2, h3 {
            color: #0056b3; /* Azul mais escuro para títulos */
            text-align: center;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.1);
        }

        h1 {
            font-size: 2.8em;
            margin-bottom: 20px;
        }

        h2 {
            font-size: 2.2em;
            margin-top: 30px;
            margin-bottom: 15px;
        }

        h3 {
            font-size: 1.8em;
            margin-top: 25px;
            margin-bottom: 10px;
        }

        p {
            margin-bottom: 20px;
            text-align: justify;
            font-size: 1.1em; /* Tamanho de fonte legível */
        }

        .highlight {
            color: #d32f2f; /* Vermelho para destaque */
            font-weight: bold;
        }

        .emoji {
            font-size: 1.5em;
            vertical-align: middle;
            margin-right: 8px;
        }

        .section-organ, .section-tissue {
            background-color: #e3f2fd; /* Azul muito claro */
            padding: 25px;
            border-radius: 12px;
            margin-bottom: 30px;
            border-left: 8px solid #0277bd; /* Borda azul forte */
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        .section-tissue {
            background-color: #fff9c4; /* Amarelo muito claro */
            border-left: 8px solid #fbc02d; /* Borda amarela forte */
        }

        .cta-button {
            display: inline-block;
            background-color: #4CAF50; /* Verde vibrante */
            color: white;
            padding: 12px 25px;
            text-align: center;
            text-decoration: none;
            border-radius: 25px;
            font-size: 1.1em;
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

        /* --- Estilos para Mobile (Media Queries) --- */
        @media (max-width: 768px) { /* Para telas com largura máxima de 768px (tablets e celulares) */
            .container {
                margin: 20px auto; /* Margem menor para telas menores */
                padding: 20px; /* Padding menor */
            }

            h1 {
                font-size: 2.2em; /* Título menor */
            }

            h2 {
                font-size: 1.8em; /* Subtítulo menor */
            }

            h3 {
                font-size: 1.5em; /* Título de seção menor */
            }

            p {
                font-size: 1em; /* Fonte um pouco menor para melhor encaixe */
                text-align: left; /* Alinhamento à esquerda pode ser mais fácil de ler em telas estreitas */
            }

            .emoji {
                font-size: 1.3em; /* Emojis um pouco menores */
            }

            .cta-button {
                padding: 10px 20px; /* Botão menor */
                font-size: 1em;
            }

            .section-organ, .section-tissue {
                padding: 20px; /* Padding menor nas seções */
                margin-bottom: 20px;
            }

            .background-image-container { /* Ajuste para a imagem de fundo */
                background-attachment: scroll; /* Fixa pode causar problemas em algumas versões de mobile */
            }
        }

        @media (max-width: 480px) { /* Para telas ainda menores (smartphones) */
            body {
                padding: 10px; /* Padding mínimo no corpo */
            }

            .container {
                margin: 10px auto;
                padding: 15px;
            }

            h1 {
                font-size: 1.8em;
            }

            h2 {
                font-size: 1.6em;
            }

            p {
                font-size: 0.95em;
            }

            .emoji {
                font-size: 1.2em;
            }

            .cta-button {
                padding: 8px 15px;
                font-size: 0.95em;
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
