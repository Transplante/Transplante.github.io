<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Transplante de Órgãos e Tecidos: Um Ato de Amor</title>
    <style>
        /* Reset básico para garantir consistência */
        * { margin: 0; padding: 0; box-sizing: border-box; }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.7; /* Um pouco mais de espaçamento entre linhas */
            color: #333;
            background-color: #e0f7fa; /* Fundo azul claro suave */
            /* Sua imagem de fundo, ajustada para ser inspiradora e não ofuscar o conteúdo */
            background-image: url('https://images.unsplash.com/photo-1584515247777-7703c0369015?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80'); /* Nova imagem de fundo inspiradora */
            background-size: cover;
            background-attachment: fixed; /* Mantém a imagem fixa ao rolar */
            background-position: center; /* Centraliza a imagem de fundo */
            margin: 0;
            padding: 20px;
        }

        .container {
            max-width: 960px; /* Largura um pouco maior para melhor visualização */
            margin: 40px auto;
            background-color: rgba(255, 255, 255, 0.95); /* Fundo branco mais opaco para leitura */
            padding: 35px;
            border-radius: 15px;
            box-shadow: 0 12px 30px rgba(0, 0, 0, 0.25); /* Sombra mais pronunciada */
            border: 1px solid #b3e5fc; /* Borda sutil azul clara */
        }

        h1, h2, h3 {
            color: #0056b3; /* Azul mais escuro para títulos */
            text-align: center;
            margin-bottom: 20px;
            text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.1); /* Sombra suave nos títulos */
        }

        h1 {
            font-size: 3.2em; /* Título principal maior */
            margin-bottom: 25px;
        }

        h2 {
            font-size: 2.4em; /* Títulos de seção maiores */
            margin-top: 35px;
        }

        h3 {
            font-size: 1.9em; /* Títulos de subtópicos */
            margin-top: 30px;
        }

        p {
            margin-bottom: 25px;
            text-align: justify;
            font-size: 1.1em; /* Tamanho de fonte um pouco maior para parágrafos */
        }

        .highlight {
            color: #d32f2f; /* Vermelho para destaque de importância */
            font-weight: bold;
        }

        .emoji {
            font-size: 1.6em; /* Emojis um pouco maiores */
            vertical-align: middle;
            margin: 0 8px; /* Espaçamento em torno do emoji */
            display: inline-block; /* Garante que o margin funcione corretamente */
        }

        .section-organ {
            background-color: #e3f2fd; /* Azul muito claro */
            padding: 30px;
            border-radius: 12px;
            margin-bottom: 35px;
            border-left: 10px solid #0277bd; /* Borda azul mais forte */
            box-shadow: 0 6px 12px rgba(0, 0, 0, 0.15);
        }

        .section-tissue {
            background-color: #fff9c4; /* Amarelo muito claro */
            padding: 30px;
            border-radius: 12px;
            margin-bottom: 35px;
            border-left: 10px solid #fbc02d; /* Borda amarela forte */
            box-shadow: 0 6px 12px rgba(0, 0, 0, 0.15);
        }

        .cta-button {
            display: inline-block;
            background-color: #4CAF50; /* Verde vibrante */
            color: white;
            padding: 15px 30px; /* Botão um pouco maior */
            text-align: center;
            text-decoration: none;
            border-radius: 30px; /* Bordas mais arredondadas */
            font-size: 1.2em; /* Fonte do botão maior */
            font-weight: bold;
            margin-top: 20px;
            transition: background-color 0.3s ease, transform 0.3s ease, box-shadow 0.3s ease;
            box-shadow: 0 8px 20px rgba(0, 0, 0, 0.25); /* Sombra mais forte no botão */
            border: none; /* Remove borda padrão */
        }

        .cta-button:hover {
            background-color: #45a049;
            transform: translateY(-3px); /* Efeito de "subir" */
            box-shadow: 0 10px 25px rgba(0, 0, 0, 0.35);
        }

        .footer {
            text-align: center;
            margin-top: 50px;
            font-size: 1em; /* Tamanho de fonte do rodapé */
            color: #555;
            border-top: 1px solid #ccc; /* Linha divisória sutil no rodapé */
            padding-top: 25px;
        }

        a {
            color: #007bff;
            text-decoration: none;
            font-weight: bold;
            transition: color 0.3s ease;
        }

        a:hover {
            text-decoration: underline;
            color: #0056b3; /* Azul mais escuro ao passar o mouse */
        }

        /* Estilos para a página de variedades */
        .varieties-container {
            background-color: #f0f4f8; /* Fundo azul claro para a página de variedades */
            padding: 30px;
            border-radius: 12px;
            margin-top: 30px;
            border: 1px solid #c5d6e9;
            box-shadow: inset 0 0 10px rgba(0,0,0,0.05); /* Sombra interna */
        }

        .varieties-container h3 {
            color: #0056b3;
            font-size: 2.2em;
            margin-bottom: 20px;
            border-bottom: 2px dashed #0277bd;
            padding-bottom: 10px;
        }

        .varieties-list {
            list-style: none; /* Remove marcadores de lista padrão */
            padding-left: 0;
        }

        .varieties-list li {
            background-color: #ffffff;
            margin-bottom: 15px;
            padding: 15px 20px;
            border-radius: 8px;
            border-left: 6px solid #007bff;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            font-size: 1.15em;
            transition: transform 0.2s ease, box-shadow 0.2s ease;
        }

        .varieties-list li:hover {
            transform: translateX(5px);
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.15);
        }

        .varieties-list li strong {
            color: #0056b3;
        }

        .emoji-list {
            margin-right: 10px; /* Espaço para emojis na lista */
            font-size: 1.2em;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1 align="center">
            <span class="emoji">💖</span> Doação de Órgãos e Tecidos: Um Ato de Amor que Salva Vidas <span class="emoji">💖</span>
        </h1>

        <div class="section-organ">
            <h2><span class="emoji">🌟</span> O que é Transplante de Órgãos? <span class="emoji">🌟</span></h2>
            <p>
                O transplante de órgãos é um procedimento cirúrgico que consiste em substituir um órgão doente ou em falência por um órgão saudável de um doador, seja ele vivo ou falecido. Esse procedimento é a única esperança de vida ou de melhoria da qualidade de vida para milhares de pacientes com doenças crônicas em estágio terminal, como insuficiência renal, hepática ou cardíaca.
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
