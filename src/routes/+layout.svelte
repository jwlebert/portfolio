<style>
    :root {
        --background: tan;
        --text: navy;
    }

    nav {
        width: 100vw;
        height: 8vh;
        background-color: var(--background);

        display: flex;
        justify-content: center;
    }

    nav > ul {
        display: flex;
        
        flex-grow: 0.25;
        align-items: center;

        margin: 0;
        padding: 0;
    }

    nav > ul > li {
        flex-grow: 1;
        list-style-type: none;
        text-align: center;
    }

    nav > ul > li > a {
        color: var(--text);
        font-size: 24px;
        font-weight: bold;
        text-decoration: none;
    }
</style>

<nav>
    <ul>
        <li><a href = "/">Home</a></li>
        <li><a href = "/#about">About</a></li>
        <li><a href = "/#projects">Projects</a></li>
        <li><a href = "/#skills">Skills</a></li>
        <li><a href = "/#contact">Contact</a></li>
    </ul>
</nav>

<slot />