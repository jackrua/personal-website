<script>
    let menuOpen = true; 
</script>

<header>
    <h1><a href="#about">  Giacomo Ruà </a></h1>
    <nav>
        <ul class="menu">
            <li> <a href="#blog"> Blog </a> </li>
            <li> <a href="#contributions"> Contributions </a> </li>
            <li> <a href="#projects"> Projects </a> </li>
        </ul>

    </nav>

</header>

<main>
    <div id="about-content">
    <div>
    <img src="/propic.JPG" alt="Profile pic taken by my beautiful gf" class="profile-pic" />
    </div>
    <div>
    <section id="about">      
            <div class="about-text">
                <p>I am a machine learning engineer based in Milan.</p>
                <p>I am currently employed at Fineco Bank and I do some freelance work on the side.</p>   
            </div>
    </section>

    <section id="blog">
        <h2>Blog</h2>
        <p>This is where your blog will appear</p>
    </section>

    <section id="contributions">
        <h2>Contributions</h2>
        <p>This is where the contributions will go</p>
    </section>

    <section id="projects">
        <h2>Projects</h2>
        <p>This is where the projects will go</p>
    </section>
    </div>    
    </div>
</main>


<style>
    header {
        display: flex; 
        justify-content: space-between;
        align-items: center;
    }

    h1 {
        font-size: 2rem;
    }

    h2 {
        font-size: 1.5rem; 
    }

    .menu {
        list-style: none; 
        display: flex;
        gap: 1rem; 
        margin: 0;
        padding: 0;
    }

    .menu li a {
        text-decoration: none;
        color: black;
        transition: color 0.3s ease;
    }

    .menu li a:hover {
        color: #0077cc;
    }

    .profile-pic {
        display: block; 
        width:250px;
        margin: 1.5rem auto;
        clip-path: inset(0 0 0 35px);
        align-self: flex-start;
    }

    section {
        margin-bottom: 3rem;
    }

    #about-content {
        display: flex;
        flex-direction: row;
        align-items: flex-start;
        justify-content: center;
        flex-wrap: wrap;
        flex-flow: center;
        gap: 1rem;
    }

    .about-text {
        max-width: 500px;
    }

    @media (min-width: 600px) {
        #about-content {
            flex-direction: row;
            align-items: flex-start;
            justify-content: center;
            text-align: left;

        }

        .profile-pic {
            margin: 1.5 rem auto; 
        }
    }

</style>