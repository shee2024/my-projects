<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Telehealth platform</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <nav class="nav-bar" id="n\av-bar">
        <section class="navsec">
            <section class="logo">telehealth</section>
            <ul class="side-bar">
                <li onclick=hideSidebar()><a href="#"><svg xmlns="http://www.w3.org/2000/svg" height="24px" viewBox="0 -960 960 960" width="24px" fill="#e8eaed"><path d="m256-200-56-56 224-224-224-224 56-56 224 224 224-224 56 56-224 224 224 224-56 56-224-224-224 224Z"/></svg></a></li>
                <li><a href="#HOME">HOME</a</li>
                <li><a href="#ABOUT">ABOUT</a></li>
                <li><a href="#CONTACTS">CONTACTS</a></li>
                <li><a href="#SUPPORT">SUPPORT</a></li>
                <lI><a href="#APPOINTMENTS">APPOINTMENTS</a></li>
                <li><a href="#PROFILE">PROFILE</a></li>
                <button><a href="#">Register</a></button>
                <button><a href="#">SignIn</a></button>
            </ul>
            <ul>
            <li class="hideOnMobile"><a href="#HOME">HOME</a</li>
            <li class="hideOnMobile"><a href="#ABOUT">ABOUT</a></li>
            <li class="hideOnMobile"><a href="#CONTACTS">CONTACTS</a></li>
            <li class="hideOnMobile"><a href="#SUPPORT">SUPPORT</a></li>
            <li class="hideOnMobile"><a href="#APPOINTMENTS">APPOINTMENTS</a></li>
            <li class="hideOnMobile"><a href="#PROFILE">PROFILE</a></li>
            <button class="hideOnMobile"><a href="#">Register</a></button>
            <button class="hideOnMobile"><a href="#">SignIn</a></button>
            <li class="menu-button" onclick=showSidebar()><a href="#"><svg xmlns="http://www.w3.org/2000/svg" height="24px" viewBox="0 -960 960 960" width="24px" fill="#e8eaed"><path d="M120-240v-80h720v80H120Zm0-200v-80h720v80H120Zm0-200v-80h720v80H120Z"/></svg></a></li>
        </ul>
        </section>
    </nav>
    <script>
        function showSidebar(){
            const sidebar = document.querySelector('.side-bar')
            sidebar.style.display = 'flex'
        }
        function hideSidebar(){
            const sidebar = document.querySelector('.side-bar')
            sidebar.style.display = 'none'
        }
    </script>
</body>
</html>
