# styling-web-page
CSS page
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Page | Home</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>My Home Page</h1>
    </header>
    <nav>
        <a href="#">Home</a>
        <a href="#">Library</a>
        <a href="#">Videos</a>
        <a href="#">Photos</a>
        <a href="#">Login/Signup</a>
    </nav>
    <main>
        <section>
            <h2>Videos</h2>
            <video src="https://www.youtube.com/watch?v=h9Am4CYaLng" width="400" heoght="300" controls></video>
            <video src="https://www.youtube.com/watch?v=65P3H1idDQE" width="400" heoght="300" controls></video>
            <video src="videos1/jarra jarra.mp4" width="400" heoght="300" controls></video>
            <br><br>
            <video src="https://www.youtube.com/watch?v=h9Am4CYaLng" width="400" heoght="300" controls ></video>
            <video src="https://www.youtube.com/watch?v=65P3H1idDQE" width="400" heoght="300" controls></video>
            <video src="videos1/jarra jarra.mp4" width="400" heoght="300" controls></video>
        </section>
        <section>
            <h2>Movie Songs</h2>	
            <iframe width="360" height="50" src="https://www.youtube.com/embed/h9Am4CYaLng" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        </section>
        <section>
            <h2>Notes</h2>
            <a href="CHINESE LANGUAGE/lesson1.pdf" width="350" height="300"></a>
            <a href="CHINESE LANGUAGE/lesson2.pdf" width="350" height="300"></a>
            <a href="CHINESE LANGUAGE/lesson3.pdf" width="350" height="300"></a>
            <a href="CHINESE LANGUAGE/lesson4.pdf" width="350" height="300"></a>
        </section>
        <section>
            <h2>Photos</h2>
            <img src="https://tse1.mm.bing.net/th?id=OIP._h7s27M_cYLoJ7SzE7XRZQHaEK&pid=Api" width="300" height="250">
            <img src="https://tse1.mm.bing.net/th?id=OIP.fBYQQAMqYDFxOh5dWobzLgHaFj&pid=Api" width="300" height="250">
            <img src="https://tse1.mm.bing.net/th?id=OIP.5TFdq1ah-13yRK4aqMqt8wHaFj&pid=Api" width="300" height="250">
            <img src="https://tse1.mm.bing.net/th?id=OIP.IumWkT1hfQ3DbUZJ47fYiQHaFj&pid=Api" width="300" height="250">
        </section>
        <section> 
            <h2>Other</h2>
            <img src="https://tse3.mm.bing.net/th?id=OIP.yv3PTOjnpSPBT3Qe4a3XggHaEY&pid=Api" alt="image" width="300" height="350">
            <h3> India</h3>
            <a href="https://www.google.com" target="_blank" rel="noopener noreferrer">Google</a>&nbsp;&nbsp;|&nbsp;&nbsp;
            <a href="https://www.youtube.com" target="_blank">YouTube</a>&nbsp;&nbsp;|&nbsp;&nbsp;
            <a href="https://www.facebook.com" target="_blank">facebook</a>
            <!--%nbsp is space in html-->
            <h4>Lorem ipsum dolor sit amet consectetur adipisicing elit. Iure dicta quo corporis minus, earum nostrum reprehenderit? Necessitatibus harum aperiam, earum veritatis repellendus, dolore numquam laboriosam mollitia fugit porro laborum omnis.</h4>
        </section>
    </main>
    <footer>
        <a href="#">Content</a>
        <a href="#">FAQ</a>
        <a href="#">Email</a>
        <a href="#">Privacy Policy</a>
        <a href="#">&copy;Copy right always</a>
    </footer>
</body>
</html>



CSS file to the above html code :
 

* {
    box-sizing: border-box;
}

body {
    margin: 0px;
    font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
}

header h1 {
    text-align: center;
    font-size: 40px;
    color: white;
}

header {
    padding: 40px;
    background-color: rgb(17, 124, 143);
}

nav {
    background-color: #333;
    overflow: hidden;
}

nav a {
    text-decoration: none;
    padding: 20px;
    text-align: center;
    float: left;
    color: white;
}

main {
    background-color: white;
    text-align: center;
}

h2 {
    padding: 20px;
}

section:nth-child(even) {
    background-color: rgb(241, 241, 241);
}

section {
    min-height: 100vh;
}

video {
    padding: 10px;
}

iframe {
    height: 75vh;
}

img {
    padding: 10px;
}

section h5 {
    margin: 40px;
}

footer {
    background-color: #333;
    overflow: hidden;
}

footer a {
    text-decoration: none;
    padding: 20px;
    text-align: center;
    float: left;
    color: white;
}
