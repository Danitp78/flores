<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Campo de Girasoles con Pasto Alto</title>
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
            height: 180px; /* Pasto más alto */
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
            bottom: 90px; /* Ajustado para el pasto más alto */
            transform-origin: left center;
            opacity: 0.7;
        }

        /* 🌻 Girasoles en forma de V */
        .sunflowers-container {
            position: absolute;
            bottom: 180px; /* Ajustado para el pasto más alto */
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
            width: 100px;
            height: 180px;
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
            width: 10px;
            height: 120px;
            background: linear-gradient(to top, #388e3c, #81c784);
            border-radius: 5px;
            position: relative;
            z-index: 2;
        }

        .leaf {
            position: absolute;
            width: 30px;
            height: 20px;
            background: linear-gradient(to top, #388e3c, #81c784);
            border-radius: 0 50% 50% 0;
            left: 5px;
            z-index: 1;
        }

        .leaf:nth-child(1) {
            top: 25px;
            transform: rotate(-15deg);
        }

        .leaf:nth-child(2) {
            top: 65px;
            transform: rotate(15deg);
            left: -5px;
            border-radius: 50% 0 0 50%;
        }

        .head {
            position: absolute;
            top: -80px;
            width: 90px;
            height: 90px;
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
            width: 50px;
            height: 50px;
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
            width: 35px;
            height: 20px;
            background: linear-gradient(to bottom, #ffeb3b, #fbc02d);
            border-radius: 50% 50% 50% 50%;
            transform-origin: center bottom;
            z-index: 1;
            box-shadow: 0 0 5px rgba(251, 192, 45, 0.5);
        }

        .petal-medium {
            position: absolute;
            width: 30px;
            height: 18px;
            background: linear-gradient(to bottom, #fff176, #ffd54f);
            border-radius: 50% 50% 50% 50%;
            transform-origin: center bottom;
            z-index: 1;
        }

        .petal-small {
            position: absolute;
            width: 25px;
            height: 15px;
            background: linear-gradient(to bottom, #ffeb3b, #ffc107);
            border-radius: 50% 50% 50% 50%;
            transform-origin: center bottom;
            z-index: 1;
        }

        .seed {
            position: absolute;
            width: 5px;
            height: 5px;
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
    </style>
</head>
<body>
    <div class="container" id="container">
        <!-- Conectores entre girasoles -->
        <div class="connectors-container" id="connectors-container"></div>
        
        <!-- 🌻 Girasoles en forma de V -->
        <div class="sunflowers-container">
            <!-- Girasol central (más alto) -->
            <div class="sunflower" style="--delay: 1; bottom: -60px; left: 50%; transform: translateX(-50%)">
                <div class="stem">
                    <div class="leaf"></div>
                    <div class="leaf"></div>
                </div>
                <div class="head" id="head-1"></div>
            </div>
            
            <!-- Girasoles laterales (formando la V) -->
            <div class="sunflower" style="--delay: 2; bottom: -60px; left: 30%;">
                <div class="stem">
                    <div class="leaf"></div>
                    <div class="leaf"></div>
                </div>
                <div class="head" id="head-2"></div>
            </div>
            
            <div class="sunflower" style="--delay: 3; bottom: -60px; left: 70%;">
                <div class="stem">
                    <div class="leaf"></div>
                    <div class="leaf"></div>
                </div>
                <div class="head" id="head-3"></div>
            </div>

            <div class="sunflower" style="--delay: 3; bottom: -60px; left: 40%;">
                <div class="stem">
                    <div class="leaf"></div>
                    <div class="leaf"></div>
                </div>
                <div class="head" id="head-3"></div>
            </div>

<div class="sunflower" style="--delay: 3; bottom: -60px; left: 20%;">
                <div class="stem">
                    <div class="leaf"></div>
                    <div class="leaf"></div>
                </div>
                <div class="head" id="head-3"></div>
            </div>

	
            <div class="sunflower" style="--delay: 4; bottom: -60px; left: 60%;">
                <div class="stem">
                    <div class="leaf"></div>
                    <div class="leaf"></div>
                </div>
                <div class="head" id="head-4"></div>
            </div>
            
            <div class="sunflower" style="--delay: 5; bottom: -60px; left: 80%;">
                <div class="stem">
                    <div class="leaf"></div>
                    <div class="leaf"></div>
                </div>
                <div class="head" id="head-5"></div>
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
                for (let i = 0; i < 40; i++) {
                    const grassDetail = document.createElement('div');
                    grassDetail.className = 'grass-detail';
                    
                    // Posición aleatoria en el pasto
                    const leftPosition = Math.random() * 100;
                    const height = 20 + Math.random() * 30;
                    
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
                // Posiciones de los girasoles (coordenadas relativas al contenedor)
                const sunflowerPositions = [
                    { left: 50, bottom: 0 },    // Central
                    { left: 30, bottom: 20 },   // Lateral izquierdo 1
                    { left: 70, bottom: 20 },   // Lateral derecho 1
                    { left: 20, bottom: 40 },   // Lateral izquierdo 2
                    { left: 80, bottom: 40 }    // Lateral derecho 2
                ];
                
                // Conectar cada girasol con sus vecinos
                for (let i = 0; i < sunflowerPositions.length; i++) {
                    for (let j = i + 1; j < sunflowerPositions.length; j++) {
                        const pos1 = sunflowerPositions[i];
                        const pos2 = sunflowerPositions[j];
                        
                        // Solo conectar girasoles cercanos
                        const distance = Math.sqrt(
                            Math.pow(pos1.left - pos2.left, 2) + 
                            Math.pow(pos1.bottom - pos2.bottom, 2)
                        );
                        
                        if (distance < 35) {
                            const connector = document.createElement('div');
                            connector.className = 'connector';
                            
                            // Calcular ángulo y longitud
                            const deltaX = pos2.left - pos1.left;
                            const deltaY = pos2.bottom - pos1.bottom;
                            
                            const length = Math.sqrt(deltaX * deltaX + deltaY * deltaY);
                            const angle = Math.atan2(deltaY, deltaX) * 180 / Math.PI;
                            
                            connector.style.width = `${length}%`;
                            connector.style.left = `${pos1.left}%`;
                            connector.style.transform = `rotate(${angle}deg)`;
                            
                            connectorsContainer.appendChild(connector);
                        }
                    }
                }
            }
            
            function createSunflowerPetals() {
                for (let i = 1; i <= 5; i++) {
                    const head = document.getElementById(`head-${i}`);
                    
                    // Crear pétalos grandes (capa exterior)
                    for (let j = 0; j < 16; j++) {
                        const petal = document.createElement('div');
                        petal.className = 'petal-large';
                        petal.style.transform = `rotate(${j * (360/16)}deg) translateY(-12px)`;
                        head.appendChild(petal);
                    }
                    
                    // Crear pétalos medianos (capa media)
                    for (let j = 0; j < 16; j++) {
                        const petal = document.createElement('div');
                        petal.className = 'petal-medium';
                        petal.style.transform = `rotate(${j * (360/16) + 10}deg) translateY(-7px)`;
                        head.appendChild(petal);
                    }
                    
                    // Crear pétalos pequeños (capa interior)
                    for (let j = 0; j < 16; j++) {
                        const petal = document.createElement('div');
                        petal.className = 'petal-small';
                        petal.style.transform = `rotate(${j * (360/16) + 5}deg) translateY(-3px)`;
                        head.appendChild(petal);
                    }
                }
            }
            
            function createSeeds() {
                for (let i = 1; i <= 5; i++) {
                    const head = document.getElementById(`head-${i}`);
                    
                    // Crear semillas en el centro
                    for (let j = 0; j < 24; j++) {
                        const seed = document.createElement('div');
                        seed.className = 'seed';
                        
                        const angle = j * (360/24);
                        const radius = 20;
                        
                        seed.style.transform = `rotate(${angle}deg) translate(${radius}px)`;
                        
                        head.appendChild(seed);
                    }
                }
            }
            
            function createFallingFlowers() {
                // Crear 6 flores que caen (pocas)
                for (let i = 0; i < 6; i++) {
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
        });
    </script>
</body>
</html>
