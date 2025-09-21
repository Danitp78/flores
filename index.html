<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Campo de Girasoles Responsive</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            background: linear-gradient(to bottom, #c9f1ff, #f9fdff);
            min-height: 100vh;
            overflow: hidden;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
        }
        
        .container {
            position: relative;
            width: 100%;
            height: 100vh;
            max-width: 1200px;
        }
        
        /* Flores que caen desde arriba */
        .falling-flower {
            position: absolute;
            top: -60px;
            animation: fall linear forwards;
            opacity: 0.7;
            filter: blur(0.8px);
            z-index: 5;
        }
        
        .flower {
            position: relative;
            display: flex;
            justify-content: center;
        }
        
        .petals {
            position: relative;
            width: 36px;
            height: 36px;
            animation: rotate 20s linear infinite;
        }
        
        .petal {
            position: absolute;
            width: 18px;
            height: 18px;
            background: linear-gradient(to bottom, #fffdd0, #ffe6a7);
            border-radius: 50% 50% 50% 0;
            transform-origin: bottom right;
            box-shadow: 0 0 5px rgba(255, 235, 150, 0.5);
        }
        
        .center {
            position: absolute;
            width: 10px;
            height: 10px;
            background: radial-gradient(#f4a261, #e76f51);
            border-radius: 50%;
            top: 13px;
            left: 13px;
            z-index: 10;
        }
        
        /* Pasto más alto en la parte inferior */
        .grass {
            position: absolute;
            bottom: 0;
            width: 100%;
            height: 25vh; /* Altura relativa para móviles */
            background: linear-gradient(to top, #2e7d32, #4caf50, #81c784);
            border-top-left-radius: 50% 40px;
            border-top-right-radius: 50% 40px;
            box-shadow: 0 -8px 20px rgba(0, 0, 0, 0.25);
            z-index: 10;
            overflow: hidden;
        }

        /* Detalles de hierba en el pasto */
        .grass-detail {
            position: absolute;
            bottom: 0;
            width: 15px;
            background: linear-gradient(to top, transparent, #388e3c);
            border-radius: 50% 50% 0 0;
        }

        /* Conectores entre girasoles */
        .connector {
            position: absolute;
            height: 3px;
            background: linear-gradient(to right, #81c784, #4caf50, #81c784);
            border-radius: 2px;
            z-index: 8;
            bottom: 15vh; /* Ajustado para el pasto más alto */
            transform-origin: left center;
            opacity: 0.7;
        }

        /* 🌻 Girasoles en forma de V */
        .sunflowers-container {
            position: absolute;
            bottom: 25vh; /* Ajustado para el pasto más alto */
            left: 50%;
            transform: translateX(-50%);
            display: flex;
            justify-content: center;
            z-index: 9;
            width: 90%;
            max-width: 800px;
        }

        .sunflower {
            position: absolute;
            width: 14vmin; /* Tamaño relativo para móviles */
            height: 25vmin; /* Tamaño relativo para móviles */
            display: flex;
            flex-direction: column;
            align-items: center;
            opacity: 0;
            transform: scale(0.2);
            animation: bloom 2s ease forwards, sway 5s ease-in-out infinite;
            animation-delay: calc(var(--delay) * 0.5s);
            transform-origin: bottom center;
        }

        .stem {
            width: 1.5vmin;
            height: 18vmin;
            background: linear-gradient(to top, #388e3c, #81c784);
            border-radius: 5px;
            position: relative;
            z-index: 2;
        }

        .leaf {
            position: absolute;
            width: 4vmin;
            height: 3vmin;
            background: linear-gradient(to top, #388e3c, #81c784);
            border-radius: 0 50% 50% 0;
            left: 0.5vmin;
            z-index: 1;
        }

        .leaf:nth-child(1) {
            top: 4vmin;
            transform: rotate(-15deg);
        }

        .leaf:nth-child(2) {
            top: 10vmin;
            transform: rotate(15deg);
            left: -1vmin;
            border-radius: 50% 0 0 50%;
        }

        .head {
            position: absolute;
            top: -12vmin;
            width: 12vmin;
            height: 12vmin;
            border-radius: 50%;
            background: #ffeb3b;
            box-shadow: 0 0 25px rgba(255, 235, 59, 0.8);
            display: flex;
            align-items: center;
            justify-content: center;
            overflow: hidden;
            z-index: 3;
        }

        .head::before {
            content: '';
            width: 6vmin;
            height: 6vmin;
            background: radial-gradient(circle, #5d4037, #3e2723);
            border-radius: 50%;
            z-index: 2;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.3);
        }

        .head::after {
            content: '';
            position: absolute;
            width: 100%;
            height: 100%;
            background: radial-gradient(circle, transparent 60%, #5d4037 61%);
            border-radius: 50%;
            z-index: 1;
        }

        .petal-large {
            position: absolute;
            width: 5vmin;
            height: 3vmin;
            background: linear-gradient(to bottom, #ffeb3b, #fbc02d);
            border-radius: 50% 50% 50% 50%;
            transform-origin: center bottom;
            z-index: 1;
            box-shadow: 0 0 5px rgba(251, 192, 45, 0.5);
        }

        .petal-medium {
            position: absolute;
            width: 4vmin;
            height: 2.5vmin;
            background: linear-gradient(to bottom, #fff176, #ffd54f);
            border-radius: 50% 50% 50% 50%;
            transform-origin: center bottom;
            z-index: 1;
        }

        .petal-small {
            position: absolute;
            width: 3vmin;
            height: 2vmin;
            background: linear-gradient(to bottom, #ffeb3b, #ffc107);
            border-radius: 50% 50% 50% 50%;
            transform-origin: center bottom;
            z-index: 1;
        }

        .seed {
            position: absolute;
            width: 0.7vmin;
            height: 0.7vmin;
            background: #3e2723;
            border-radius: 50%;
            z-index: 3;
        }

        /* Animacion florecer */
        @keyframes bloom {
            0%   { transform: scale(0.2); opacity: 0; }
            60%  { transform: scale(1.1); opacity: 1; }
            100% { transform: scale(1); opacity: 1; }
        }

        /* Movimiento suave izquierda-derecha */
        @keyframes sway {
            0%   { transform: rotate(0deg); }
            25%  { transform: rotate(2deg); }
            50%  { transform: rotate(0deg); }
            75%  { transform: rotate(-2deg); }
            100% { transform: rotate(0deg); }
        }

        /* Animaciones de caída */
        @keyframes fall {
            to {
                transform: translateY(110vh) rotate(360deg);
                opacity: 0.3;
            }
        }
        
        @keyframes rotate {
            from { transform: rotate(0deg); }
            to   { transform: rotate(360deg); }
        }

        /* Media queries para dispositivos móviles */
        @media (max-width: 768px) {
            .sunflowers-container {
                width: 95%;
                bottom: 22vh;
            }
            
            .sunflower {
                width: 12vmin;
                height: 22vmin;
            }
            
            .stem {
                height: 15vmin;
            }
            
            .head {
                top: -10vmin;
                width: 10vmin;
                height: 10vmin;
            }
            
            .head::before {
                width: 5vmin;
                height: 5vmin;
            }
            
            .petal-large {
                width: 4vmin;
                height: 2.5vmin;
            }
            
            .petal-medium {
                width: 3.5vmin;
                height: 2vmin;
            }
            
            .petal-small {
                width: 2.5vmin;
                height: 1.5vmin;
            }
            
            .leaf:nth-child(2) {
                top: 8vmin;
            }
            
            .grass {
                height: 22vh;
            }
            
            .connector {
                bottom: 12vh;
            }
        }

        @media (max-width: 480px) {
            .sunflowers-container {
                width: 98%;
                bottom: 20vh;
            }
            
            .sunflower {
                width: 10vmin;
                height: 20vmin;
            }
            
            .head {
                top: -9vmin;
                width: 9vmin;
                height: 9vmin;
            }
            
            .stem {
                height: 14vmin;
            }
            
            .petal-large {
                width: 3.5vmin;
                height: 2vmin;
            }
            
            .grass {
                height: 20vh;
            }
            
            .connector {
                display: none; /* Ocultamos conectores en móviles muy pequeños */
            }
            
            /* Ajustamos posiciones de los girasoles para pantallas pequeñas */
            .sunflower:nth-child(1) { left: 50% !important; }
            .sunflower:nth-child(2) { left: 25% !important; }
            .sunflower:nth-child(3) { left: 75% !important; }
            .sunflower:nth-child(4) { left: 10% !important; }
            .sunflower:nth-child(5) { left: 90% !important; }
            .sunflower:nth-child(6) { left: 40% !important; }
            .sunflower:nth-child(7) { left: 60% !important; }
        }

        /* Ajustes para orientación horizontal */
        @media (max-height: 500px) and (orientation: landscape) {
            .grass {
                height: 35vh;
            }
            
            .sunflowers-container {
                bottom: 35vh;
            }
            
            .connector {
                bottom: 22vh;
            }
            
            .sunflower {
                width: 12vmin;
                height: 22vmin;
            }
        }
    </style>
</head>
<body>
    <div class="container" id="container">
        <!-- Conectores entre girasoles -->
        <div class="connectors-container" id="connectors-container"></div>
        
        <!-- 🌻 Girasoles en forma de V -->
        <div class="sunflowers-container">
            <!-- Girasol central (más alto) -->
            <div class="sunflower" style="--delay: 1; bottom: -10vmin; left: 50%; transform: translateX(-50%)">
                <div class="stem">
                    <div class="leaf"></div>
                    <div class="leaf"></div>
                </div>
                <div class="head" id="head-1"></div>
            </div>
            
            <!-- Girasoles laterales (formando la V) -->
            <div class="sunflower" style="--delay: 2; bottom: -10vmin; left: 30%;">
                <div class="stem">
                    <div class="leaf"></div>
                    <div class="leaf"></div>
                </div>
                <div class="head" id="head-2"></div>
            </div>
            
            <div class="sunflower" style="--delay: 3; bottom: -10vmin; left: 70%;">
                <div class="stem">
                    <div class="leaf"></div>
                    <div class="leaf"></div>
                </div>
                <div class="head" id="head-3"></div>
            </div>

            <div class="sunflower" style="--delay: 4; bottom: -10vmin; left: 40%;">
                <div class="stem">
                    <div class="leaf"></div>
                    <div class="leaf"></div>
                </div>
                <div class="head" id="head-4"></div>
            </div>

            <div class="sunflower" style="--delay: 5; bottom: -10vmin; left: 20%;">
                <div class="stem">
                    <div class="leaf"></div>
                    <div class="leaf"></div>
                </div>
                <div class="head" id="head-5"></div>
            </div>
            
            <div class="sunflower" style="--delay: 6; bottom: -10vmin; left: 60%;">
                <div class="stem">
                    <div class="leaf"></div>
                    <div class="leaf"></div>
                </div>
                <div class="head" id="head-6"></div>
            </div>
            
            <div class="sunflower" style="--delay: 7; bottom: -10vmin; left: 80%;">
                <div class="stem">
                    <div class="leaf"></div>
                    <div class="leaf"></div>
                </div>
                <div class="head" id="head-7"></div>
            </div>
        </div>

        <div class="grass" id="grass"></div>
    </div>

    <script>
        document.addEventListener('DOMContentLoaded', function() {
            const container = document.getElementById('container');
            const connectorsContainer = document.getElementById('connectors-container');
            const grass = document.getElementById('grass');
            
            // Crear detalles de hierba en el pasto
            createGrassDetails();
            
            // Crear conectores entre girasoles
            createConnectors();
            
            // Crear pétalos para los girasoles
            createSunflowerPetals();
            
            // Crear semillas en el centro de los girasoles
            createSeeds();
            
            // Crear flores que caen desde arriba
            createFallingFlowers();
            
            function createGrassDetails() {
                // Crear briznas de hierba en el pasto
                for (let i = 0; i < 30; i++) {
                    const grassDetail = document.createElement('div');
                    grassDetail.className = 'grass-detail';
                    
                    // Posición aleatoria en el pasto
                    const leftPosition = Math.random() * 100;
                    const height = 15 + Math.random() * 25;
                    
                    grassDetail.style.left = `${leftPosition}%`;
                    grassDetail.style.height = `${height}px`;
                    
                    // Alternar la dirección de la hierba
                    if (Math.random() > 0.5) {
                        grassDetail.style.transform = 'scaleX(-1)';
                    }
                    
                    grass.appendChild(grassDetail);
                }
            }
            
            function createConnectors() {
                // Solo crear conectores en pantallas grandes
                if (window.innerWidth < 480) return;
                
                // Posiciones de los girasoles (coordenadas relativas al contenedor)
                const sunflowerPositions = [
                    { left: 50, bottom: 0 },    // Central
                    { left: 30, bottom: 0 },   // Lateral izquierdo 1
                    { left: 70, bottom: 0 },   // Lateral derecho 1
                    { left: 20, bottom: 0 },   // Lateral izquierdo 2
                    { left: 80, bottom: 0 },    // Lateral derecho 2
                    { left: 40, bottom: 0 },   // Lateral izquierdo 3
                    { left: 60, bottom: 0 }    // Lateral derecho 3
                ];
                
                // Conectar cada girasol con sus vecinos
                for (let i = 0; i < sunflowerPositions.length; i++) {
                    for (let j = i + 1; j < sunflowerPositions.length; j++) {
                        const pos1 = sunflowerPositions[i];
                        const pos2 = sunflowerPositions[j];
                        
                        // Solo conectar girasoles cercanos
                        const distance = Math.abs(pos1.left - pos2.left);
                        
                        if (distance < 35) {
                            const connector = document.createElement('div');
                            connector.className = 'connector';
                            
                            // Calcular ángulo y longitud
                            const deltaX = pos2.left - pos1.left;
                            
                            const length = Math.abs(deltaX);
                            const angle = deltaX > 0 ? 0 : 180;
                            
                            connector.style.width = `${length}%`;
                            connector.style.left = `${pos1.left}%`;
                            connector.style.transform = `rotate(${angle}deg)`;
                            
                            connectorsContainer.appendChild(connector);
                        }
                    }
                }
            }
            
            function createSunflowerPetals() {
                for (let i = 1; i <= 7; i++) {
                    const head = document.getElementById(`head-${i}`);
                    if (!head) continue;
                    
                    // Crear pétalos grandes (capa exterior)
                    for (let j = 0; j < 14; j++) {
                        const petal = document.createElement('div');
                        petal.className = 'petal-large';
                        petal.style.transform = `rotate(${j * (360/14)}deg) translateY(-40%)`;
                        head.appendChild(petal);
                    }
                    
                    // Crear pétalos medianos (capa media)
                    for (let j = 0; j < 14; j++) {
                        const petal = document.createElement('div');
                        petal.className = 'petal-medium';
                        petal.style.transform = `rotate(${j * (360/14) + 10}deg) translateY(-25%)`;
                        head.appendChild(petal);
                    }
                    
                    // Crear pétalos pequeños (capa interior)
                    for (let j = 0; j < 14; j++) {
                        const petal = document.createElement('div');
                        petal.className = 'petal-small';
                        petal.style.transform = `rotate(${j * (360/14) + 5}deg) translateY(-10%)`;
                        head.appendChild(petal);
                    }
                }
            }
            
            function createSeeds() {
                for (let i = 1; i <= 7; i++) {
                    const head = document.getElementById(`head-${i}`);
                    if (!head) continue;
                    
                    // Crear semillas en el centro
                    for (let j = 0; j < 20; j++) {
                        const seed = document.createElement('div');
                        seed.className = 'seed';
                        
                        const angle = j * (360/20);
                        const radius = 40;
                        
                        seed.style.transform = `rotate(${angle}deg) translate(${radius}%)`;
                        
                        head.appendChild(seed);
                    }
                }
            }
            
            function createFallingFlowers() {
                // Menos flores cayendo en móviles para mejor rendimiento
                const flowerCount = window.innerWidth < 768 ? 4 : 6;
                
                for (let i = 0; i < flowerCount; i++) {
                    setTimeout(() => {
                        createFallingFlower();
                        // Crear una nueva flor cada 7 segundos (lentas)
                        setInterval(createFallingFlower, 7000);
                    }, i * 1200);
                }
            }
            
            function createFallingFlower() {
                const flower = document.createElement('div');
                flower.className = 'falling-flower';
                
                const leftPosition = 5 + Math.random() * 90;
                const fallDuration = 18 + Math.random() * 12; // Muy lentas
                const rotation = Math.random() * 360;
                
                flower.style.left = `${leftPosition}%`;
                flower.style.animationDuration = `${fallDuration}s`;
                
                flower.innerHTML = `
                    <div class="flower">
                        <div class="petals">
                            ${createPetals(rotation)}
                            <div class="center"></div>
                        </div>
                    </div>
                `;
                
                container.appendChild(flower);
                
                // Eliminar la flor después de que termine de caer
                setTimeout(() => {
                    flower.remove();
                }, fallDuration * 1000);
            }
            
            function createPetals(rotation) {
                let petalsHTML = '';
                for (let i = 0; i < 8; i++) {
                    petalsHTML += `<div class="petal" style="transform: rotate(${i * 45 + rotation}deg)"></div>`;
                }
                return petalsHTML;
            }

            // Reajustar en redimensionamiento
            window.addEventListener('resize', function() {
                // Limpiar conectores existentes
                connectorsContainer.innerHTML = '';
                // Volver a crear conectores (si es necesario)
                createConnectors();
            });
        });
    </script>
</body>
</html>
