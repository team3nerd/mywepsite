<!DOCTYPE html>
<html lang="am">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ሳፊ ላዉንድሪ</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>ሳፊ ላዉንድሪ</h1>
        <nav>
            <ul>
                <li><a href="#home">መነሻ</a></li>
                <li><a href="#services">አገልግሎቶች</a></li>
                <li><a href="#contact">እናገኛለን</a></li>
            </ul>
        </nav>
    </header>

    <section id="home">
        <h2>እንኳን ወደ ሳፊ ላዉንድሪ በደህና መጡ</h2>
        <p>እኛ በከተማው በጥሩ የሆነ ላዉንድሪ አገልግሎት እንሰጣለን። ታማኝ ፣ በፍጥነት እና በርካታ!</p>
        <img src="https://i.postimg.cc/YqmCCkhQ/laundry.jpg" alt="ሳፊ ላዉንድሪ" style="width: 100%; max-width: 600px; height: auto;">
        <button onclick="showOrderForm()">አሁን ይዘዙ</button>
    </section>

    <section id="services">
        <h2>አገልግሎቶች</h2>
        <ul>
            <li>ሙሉ ልብስ</li>
            <li>ሀበሻ ልብስ</li>
            <li>ጋቢ/ነጠላ</li>
            <li>ቀሚስ ሙሉ/ጉርድ</li>
            <li>ቲሸርት/ፓካውት</li>
            <li>ሱሪ/ቁምጣ</li>
            <li>ሸሚዝ/ከረቫት</li>
            <li>ኮት/ጃኬት/ጋውን</li>
            <li>ቱታ/ሹራብ</li>
            <li>አንሶላ/ፎጣ</li>
            <li>ብርድ ልብስ/አልጋ ልብስ</li>
            <li>ኮምፈርት</li>
            <li>መጋረጃ</li>
            <li>ጫማ/ካልሲ</li>
        </ul>
    </section>

    <section id="contact">
        <h2>እናገኛለን</h2>
        <p>አድራሻ: ቦሌ ከፍለ ከተማ ጀርባ ዳግም ክትፎ ጎን</p>
        <p>ስልክ: +251 91 241 8177</p>
        <p>ቴሌግራም: <a href="https://t.me/nahneg">https://t.me/nahneg</a></p>
    </section>
    
    <script>
        function showOrderForm() {
            alert('የትዕዛዝ ቅጽ በፍጥነት እየተዘጋጀ ነው!');
        }
    </script>
</body>
</html>
