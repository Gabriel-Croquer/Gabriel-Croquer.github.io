<!DOCTYPE html>
<html>

<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Story template</title>

    <!-- Google fonts -->
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Lora:ital,wght@0,400;0,700;1,400;1,700&display=swap"
        rel="stylesheet">
    <style>
        body {
            margin: 0;
            font-size: 20px;
            font-family: Georgia, 'Times New Roman', Times, serif;
            text-rendering: optimizeLegibility;
        }

        .content {
            max-width: 640px;
            margin: auto;
        }

        .header {
            padding: 3em 0;
        }

        a {
            color: #f05349;
        }

        .footer {
            background: #f4f4f4;
            text-align: center;
            font-size: 0.8em;
            margin-top: 4em;
            padding: 4em 0;
        }

        figure {
            margin: 0;
            padding-bottom: 1.2em;
        }

        figcaption {
            font-size: 0.8em;
            text-align: center;
            margin-top: 0.5em;
            color: #666;
        }

        h1 {
            font-family: 'Lora', Georgia, serif;
            font-weight: bold;
            font-size: 3em;
            line-height: 1.1;
        }

        .subhead {
            font-family: 'Lora', Georgia, serif;
        }

        iframe,
        img,
        video {
            max-width: 100%;
        }

        p {
            line-height: 1.6;
            margin: 0;
            padding-bottom: 1.2em;
        }

        ul {
            margin: 0;
            padding-bottom: 1em;
            line-height: 1.6;
        }

        iframe {
            padding-bottom: 1.2em;
        }

        code {
            font-family: 'Courier New', monospace;
            background: #fffbaf;
            font-size: 0.85em;
        }

        .full-width figure {
            text-align: center;
        }

        /* margin on mobile */
        @media (max-width: 640px) {
            body {
                font-size: 18px;
            }

            .content {
                padding-left: 0.5em;
                padding-right: 0.5em;
            }
        }
    </style>
</head>

<body>
    <div class="content">
        <div class="header">
            <h1>This is the headline of the story you are about to read</h1>
            <p class="subhead">Here is the subhead or additional content you want to add in</p>
        </div>
        <div class="byline">
            <p>By <a href="https://jonathansoma.com">Jonathan Soma</a></p>
        </div>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore
            magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea
            commodo consequat.</p>
        <p>You can change the fonts by using <a href="https://fonts.google.com/">Google Fonts</a> and some CSS. Right
            now we're using Lora for headlines and Georgia for body copy.</a></p>
        <p>Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
            Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est
            laborum.</p>

        <iframe title="The biggest pumpkins, by state (Copy)" aria-label="Bar Chart" id="datawrapper-chart-MLQxw"
            src="https://datawrapper.dwcdn.net/MLQxw/1/" scrolling="no" frameborder="0"
            style="width: 0; min-width: 100% !important; border: none;" height="757" data-external="1"></iframe>
        <script type="text/javascript">!function () { "use strict"; window.addEventListener("message", (function (a) { if (void 0 !== a.data["datawrapper-height"]) { var e = document.querySelectorAll("iframe"); for (var t in a.data["datawrapper-height"]) for (var r = 0; r < e.length; r++)if (e[r].contentWindow === a.source) { var i = a.data["datawrapper-height"][t] + "px"; e[r].style.height = i } } })) }();
        </script>

        <p>Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem
            aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo.
            Nemo enim ipsam voluptatem quia voluptas sit aspernatur aut odit aut fugit, sed quia consequuntur magni
            dolores eos qui ratione voluptatem sequi nesciunt.</p>

        <ul>
            <li>One thing</li>
            <li>A second thing</li>
            <li>A third thing</li>
        </ul>

        <p>Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem
            aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo.
            Nemo enim ipsam voluptatem quia voluptas sit aspernatur aut odit aut fugit, sed quia consequuntur magni
            dolores eos qui ratione voluptatem sequi nesciunt.</p>
        <figure>
            <img
                src="https://static01.nyt.com/images/2024/02/01/multimedia/01eu-hungary-orban-2-ghkw/01eu-hungary-orban-2-ghkw-superJumbo.jpg?quality=75&auto=webp">
            <figcaption>This is an image caption</figcaption>
        </figure>
        <p>Neque porro quisquam est, qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit, sed quia non
            numquam eius modi tempora incidunt ut labore et dolore magnam aliquam quaerat voluptatem. Ut enim ad minima
            veniam, quis nostrum exercitationem ullam corporis suscipit laboriosam, nisi ut aliquid ex ea commodi
            consequatur?</p>
    </div>
    <div class="full-width">
        <figure>
            <img
                src="https://static01.nyt.com/images/2024/02/01/multimedia/01eu-hungary-orban-2-ghkw/01eu-hungary-orban-2-ghkw-superJumbo.jpg?quality=75&auto=webp">
            <figcaption>This is another image caption, but this time it's a full-width image</figcaption>
        </figure>
    </div>
    <div class="content">
        <p>At vero eos et accusamus et iusto odio dignissimos ducimus qui blanditiis praesentium voluptatum deleniti
            atque corrupti quos dolores et quas molestias excepturi sint occaecati cupiditate non provident, similique
            sunt in culpa qui officia deserunt mollitia animi, id est laborum et dolorum fuga.</p>
        <p>Et harum quidem rerum facilis est et expedita distinctio. Nam libero tempore, cum soluta nobis est eligendi
            optio cumque nihil impedit quo minus id quod maxime placeat facere possimus, omnis voluptas assumenda est,
            omnis dolor repellendus.</p>
    </div>
    <div class="full-width">
        <figure>
            <video src="bg-video.mp4" preload="auto" tabindex="0" playsinline autoplay loop muted></video>
            <figcaption>This is an auto-play video. I had to edit the CSS from the original form a little, added
                <code>max-width: 100%</code> for the <code>video</code> tag.</figcaption>
        </figure>
    </div>
    <div class="content">
        <p>At vero eos et accusamus et iusto odio dignissimos ducimus qui blanditiis praesentium voluptatum deleniti
            atque corrupti quos dolores et quas molestias excepturi sint occaecati cupiditate non provident, similique
            sunt in culpa qui officia deserunt mollitia animi, id est laborum et dolorum fuga.</p>
        <p>Et harum quidem rerum facilis est et expedita distinctio. Nam libero tempore, cum soluta nobis est eligendi
            optio cumque nihil impedit quo minus id quod maxime placeat facere possimus, omnis voluptas assumenda est,
            omnis dolor repellendus.</p>
    </div>
    <div class="footer">
        <div class="content">
            <p>You can find the code for this template <a href="https://github.com/jsoma/page-templates/">here</a>.
                Delete these lines
                when you use it, and don't forget to change the <code>title</code> tag!!!</p>
        </div>
    </div>
</body>

</html>
