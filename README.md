            color: black;
            font-weight: 600;
            border-radius: 5px;
            border: 2px solid black;
        }
    </style>
    <title>Pedido Irrecusável</title>
</head>
<body>
    <div class="box">
        <p>Cuzinho hoje?</p>
        <div class="button-containers">
            <button><a href="https://www.google.com/search?q=noice&oq=noice&gs_lcrp=EgZjaHJvbWUyBggAEEUYOTIHCAEQABiABDIHCAIQABiABDIHCAMQABiABDIHCAQQABiABDIHCAUQABiABDIJCAYQABgKGIAEMgkIBxAAGAoYgAQyCQgIEAAYChiABDIJCAkQABgKGIAE0gEHOTQxajBqN6gCALACAA&sourceid=chrome&ie=UTF-8#fpstate=ive&vld=cid:c000df66,vid:a8c5wmeOL9o">Sim</a></button>
            <button id="no">Não</button>
        </div>
    </div>
</body>
<script>
    let button = document.getElementById('no');
    let height = window.innerHeight - 50;
    let width = window.innerWidth - 50;

    button.addEventListener('mouseover', function () {
        button.style.position = "absolute"
        button.style.top = Math.random() * height + "px";
        button.style.left = Math.random() * width + "px";
    })
</script>
</html>
