<section class="hero">
    <img src="https://th.bing.com/th/id/OIP.WJMkL1eHOT9KeaKLUIclgAHaIK?w=161&h=180&c=7&r=0&o=5&pid=1.7" alt="">
    <h1>Střední odborné učiliště</h1>
    <p>Pojťe stavět naší budoucnost u nás na škole , kde podorujeme praxi se vzděláním</p>
    <div class="hero-buttons">
        <a href="/about">Login</a>
        <a href="/" id="ghost">About</a>
    </div>
    
</section>

<style>
    .hero{
        width: 100%;
        max-width: 1300px;
        min-height: clac(100vh - 100px);
        display: flex;
        flex-direction:column;
        justify-content: center;
        align-items: center;
        text-align: center;
        margin-top: 20px;
    }

    .hero img{
        width: 250px;
    }

    .hero-buttons{
        display: flex;
        gap:36px;
    }

    .hero-buttons a{
        color: white;
        background-color: blue;
        text-decoration: none;
        width: 150px;
        height: 50px;
        display:flex ;
        justify-content: center;
        align-items: center;
        border-radius: 10px;
        font-weight: 500px;
        transition: ease 0,5s;
    }
    
    #ghost{
        color: black;
        background: none;
        border: 1px solid black;
        transition: ease 0,5s;
    }

    #ghost:hover{
        color: white;
        background-color: red;
        border: none;
    }

    .hero-buttons a:hover{
        color: white;
        background-color: red;

    }
</style>