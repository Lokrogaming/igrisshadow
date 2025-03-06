<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
    <title>Black0815xx</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background-color: black;
            color: red;
            margin: 0;
            padding: 0;
            overflow: hidden;
        }

        canvas {
            position: fixed;
            top: 0;
            left: 0;
            width: 100vw;
            height: 100vh;
            z-index: -1;
        }

        .button-container {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin-top: 20px;
        }

        .button-wrapper {
            display: flex;
            flex-direction: column;
            align-items: center;
        }

        .button {
            width: 200px;
            height: 150px;
            border: none;
            color: white;
            padding: 10px;
            display: flex;
            align-items: center;
            justify-content: center;
            border-radius: 35px;
            cursor: pointer;
            transition: transform 0.2s ease-in-out;
        }

        .button:hover {
            transform: scale(1.05);
        }

        .button img {
            max-height: 100%;
            object-fit: contain;
        }

        .button-twitch {
            background-color: #6643a7;
        }

        .button-youtube {
            background-color: #fa0404;
        }

        .button-discord {
            background-color: #5b64f3;
        }

        .button-label {
            margin-top: 5px;
            font-size: 18px;
            font-weight: bold;
            color: white;
        }
        

        div.title {
            align-items: center;
            justify-content: center;
            margin-top: 50px;
            width: 75%;
            position: center;
            center:0;
        }
        div.autor {
            position: fixed;
            color: #a4acb1;
            background: transparent;
            left: 0;
            bottom:0;
        }
        
    </style>
</head>
<body>
    <canvas id="fire"></canvas>
    <div id="title" class="title">
        <img src="logo-black0815xx.png" width="500px" height="500px" alt="logo1">
        <h3 id="titletxt">Black0815xx - Streamer, Youtuber</h3>
    </div>
    

    <div class="button-container">
        <div class="button-wrapper">
            <button class="button button-twitch" onclick="window.location.href='https://www.twitch.tv/Black0815xx'">
                <img src="twitch.png" alt="Twitch Icon">
            </button>
            <span class="button-label">Twitch</span>
        </div>

        <div class="button-wrapper">
            <button class="button button-youtube" onclick="window.location.href='https://youtube.com/@black0815xx?si=xWxYagdGRkiVQ3BA'">
                <img src="IMG_0556-removebg-preview.png" alt="YouTube Icon">
            </button>
            <span class="button-label">YouTube</span>
        </div>

        <div class="button-wrapper">
            <button class="button button-discord" onclick="window.location.href='https://discord.gg/EV65vE2J54'">
                <img src="discord.png" alt="Discord Icon">
            </button>
            <span class="button-label">Discord</span>
        </div>
    </div>
    <div class="autor">
        <p>Made with ❤️ by Lokrogamer</p>
        <a href="lokrogaming.github.io/lokrogaming/about-me.html">Show me more!</a>
    </div>
        

    <script>
        const canvas = document.getElementById('fire');
        const ctx = canvas.getContext('2d');
        let width, height;
        let particles = [];

        function resizeCanvas() {
            width = canvas.width = window.innerWidth;
            height = canvas.height = window.innerHeight;
            particles = particles.map(() => new Particle());
        }

        window.addEventListener('resize', resizeCanvas);
        resizeCanvas();

        class Particle {
            constructor() {
                this.reset();
            }

            reset() {
                this.x = Math.random() * width;
                this.y = Math.random() * height;
                this.radius = Math.random() * 3 + 1;
                this.speed = Math.random() * 2 + 1;
                this.wind = Math.random() * 1.5 - 0.75;
                this.color = this.getRandomFireColor();
            }

            getRandomFireColor() {
                const colors = ["#ff4500", "#ff6f1a", "#ff8c00", "#ff0000", "#ffae42"];
                return colors[Math.floor(Math.random() * colors.length)];
            }

            update() {
                this.y += this.speed;
                this.x += this.wind;

                if (this.y > height) this.reset();
                if (this.x > width || this.x < 0) this.reset();
            }

            draw() {
                ctx.beginPath();
                ctx.arc(this.x, this.y, this.radius, 0, Math.PI * 2);
                ctx.fillStyle = this.color;
                ctx.fill();
                ctx.closePath();
            }
        }

        function createParticles(count) {
            particles = Array.from({ length: count }, () => new Particle());
        }

        function animate() {
            ctx.clearRect(0, 0, width, height);
            particles.forEach(particle => {
                particle.update();
                particle.draw();
            });
            requestAnimationFrame(animate);
        }

        createParticles(150);
        animate();
    </script>
</body>
</html>
