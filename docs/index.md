## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/idrilogic/idri-squid/edit/main/docs/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sqiud</title>

    <style>
        body{margin: 0;padding: 0}
        .container   {
            background-color: rgb(33, 36, 41);
            height: 100vh;
            display: flex;justify-content: center;align-items: center;
        }
        .circle {
            border: 6px solid rgb(255, 56, 56);
            height: 200px;
            width: 200px;
            border-radius: 50%;
        }

        .tra {
            border-width: 100px;
            border-style: solid;
            transform: translateY(-106px);
            border-color:transparent transparent rgb(255, 56, 56) transparent ;
        }

        .square {
            transform: translateY(-90px);
            border: 6px solid rgb(255, 56, 56);
            height: 200px; width: 200px;
        }
    </style>

</head>
<body>
    
    <div class="container">
        <div class="gather">
            <div class="circle"></div>
            <div class="tra"></div> 
            <div class="square"></div>
        </div>
    </div>

</body>
</html>
