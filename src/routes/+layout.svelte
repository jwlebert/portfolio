<style>
    nav {
        width: 100vw;
        height: 8vh;
        background-color: tan;

        display: flex;
        justify-content: center;
    }

    nav > ul {
        display: flex;
        
        flex-grow: 0.5;
        align-items: center;

        margin: 0;
        padding: 0;
    }

    nav > ul > li {
        flex-grow: 1;
        list-style-type: none;
        text-align: center;
    }
</style>

<nav>
    <ul>
        <li><a href = "/">Home</a></li>
        <li><a href = "/">Home</a></li>
        <li><a href = "/">Home</a></li>
        <li><a href = "/">Home</a></li>
        <li><a href = "/">Home</a></li>
    </ul>
</nav>

<slot />