# hbd
cake

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <title>Candle Blow</title>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/normalize/5.0.0/normalize.min.css" />
    <link rel="stylesheet" href="./style.css" />
    <script src="https://cdnjs.cloudflare.com/ajax/libs/prefixfree/1.0.7/prefixfree.min.js"></script>
</head>
<body>
</body>
</html>
    <audio id="birthdaySong" autoplay loop>
        <source src="lagu ultah.mp3" type="audio/mpeg">
        Your browser does not support the audio element.
    </audio>
    
    <div class="candle-count-display">
        HAPPY BIRTHDAY CALYN!
    </div>



    <div class="cake">
        <div id="candleCount" style="display:none;"></div>
        <div class="plate"></div>
        <div class="layer layer-bottom"></div>
        <div class="layer layer-middle"></div>
        <div class="layer layer-top"></div>
        <div class="icing"></div>
        <div class="drip drip1"></div>
        <div class="drip drip2"></div>
        <div class="drip drip3"></div>
        <div class="candle" id="candle" onclick="blowCandle()">
            <div class="flame"></div>
        </div>
    </div>
    <button id="blowButton" onclick="blowCandle()"/button>
    <div class="footer">
        Developed By: Lily &nbsp; | &nbsp; Made with <svg class="heart" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" stroke=""><g id="SVGRepo_bgCarrier" stroke-width="0"></g><g id="SVGRepo_tracerCarrier" stroke-linecap="round" stroke-linejoin="round" stroke="#CCCCCC" stroke-width="1.488"></g><g id="SVGRepo_iconCarrier"> <path d="M2 9.1371C2 14 6.01943 16.5914 8.96173 18.9109C10 19.7294 11 20.5 12 20.5C13 20.5 14 19.7294 15.0383 18.9109C17.9806 16.5914 22 14 22 9.1371C22 4.27416 16.4998 0.825464 12 5.50063C7.50016 0.825464 2 4.27416 2 9.1371Z" fill="#ff6999"></path> </g></svg>
    </div>
    <script src="script.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/canvas-confetti@1.3.2"></script>
    
    <script>
        // JavaScript untuk memutar lagu
        window.onload = function() {
            var audio = new Audio('lagu ultah.mp3'); // Ganti dengan nama file audio Anda
            audio.loop = true; // Jika ingin lagu berulang
            audio.play().catch(function(error) {
                console.log('Audio playback was prevented:', error);
            });
        };

        function blowCandle() {
            const candle = document.getElementById('candle');
            const flame = candle.querySelector('.flame');
            candle.classList.toggle('out'); // Menambahkan kelas untuk menyalakan/mematikan lilin
            flame.classList.toggle('out'); // Menyembuny
        }ing birthday web.html…]()
