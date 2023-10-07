<!--<h1>Welcome to SvelteKit</h1>
<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>-->
<script>

</script>

<header>
    <h1>image here</h1>
</header>

<main>
    <h1>Welcome !!!</h1>
</main>

<nav>
    <!--imgs src: https://gamesdb.launchbox-app.com/games/results/persona-->
    <ul>
        <section>
            <img src="https://images.launchbox-app.com/00f2985d-3694-4d27-960f-d097f56c4965.png" 
            alt="Japanese cover of Persona 2: Innocent Sin for the original PlayStation."/>
            <img src="https://images.launchbox-app.com/af5eeaa0-aaa9-46cf-9f47-42d81c19222b.png"
            id="ogdisc" alt="Japanese disc of Persona 2: Innocent Sin for the original PlayStation."/>
        </section>
        
        <section>
            <img src="https://images.launchbox-app.com/17cd71a7-aaa9-4653-9318-b8c2db4fb59a.png" 
            alt="Japanese cover of Persona 2: Eternal Punishment for the original PlayStation."/>
            <img src="https://images.launchbox-app.com/3a001e8d-56b3-4c1e-b571-50aeace18ea5.png"
            id="ogdisc" alt="Japanese disc of Persona 2: Eternal Punishment for the original PlayStation."/>
        </section>
        <li>Persona 2</li>
        <section>
            <img src="https://images.launchbox-app.com/7c17c06b-8e63-4921-81eb-982dee98c89e.png" 
            alt="North American cover of Persona 3 for the PlayStation 2."/>
            <img src="https://images.launchbox-app.com/e596504d-7ab8-40a3-879b-9fd3e280ec16.png"
            id="ps2disc" alt="North American disc of Persona 3 for the PlayStation 2."/>
        </section>
        <li>Persona 3</li>
        <section>
            <img src="https://images.launchbox-app.com/32771b56-d9f9-4be0-80f3-0cb9f76f22dd.png" 
            alt="North American cover of Persona 4 for the PlayStation2."/>
            <img src="https://images.launchbox-app.com/d46151e3-5279-4070-a7e0-769ae59221e2.png" 
            id="ps2disc" alt="North American disc of Persona 4 for the PlayStation 2."/>
        </section>
        <li>Persona 4</li>
    </ul>
        <ul>
            <section>
                <img src="https://images.launchbox-app.com/931c9aa5-fd59-4a9e-860b-e042307c90bd.png"
                alt="North American cover of Sonic The Hedgehog for the Sega Genesis."/>
                <img src="https://images.launchbox-app.com/1d938413-e31c-4748-b314-e1693d0b02f9.png"
                id="cartridge" alt="North American game cartridge of Sonic The Hedgehog for the Sega Genesis."/>
            </section>
            <li>Sonic The Hedgehog</li>
            <section>
                <img src="https://images.launchbox-app.com/54892c6e-2617-4e10-b6a1-81968a70e120.png"
                alt="Half-life game cover for PC."/>
                <img src="https://images.launchbox-app.com/f7a235b4-145f-47c1-830e-5240aeff299e.png"
                id="ogdisc" alt="Half-Life disc for PC."/>
            </section>
            <li>Half-Life</li>
            <section>
                <img src="https://images.launchbox-app.com/f3f5ad00-6273-4556-8a91-1641ee8141bf.png"
                alt="Team Fortress 2 game cover for PC."/>
                <img src="https://images.launchbox-app.com/98926f5b-0874-4ff5-bd07-cd53045d2deb.png"
                id="ogdisc" alt="Team Fortress 2 disc for PC."/>
            </section>
            <li>Team Fortress 2</li>
        </ul>
</nav>

<style>
    header {
        background-color: yellow;
    }

    main {
        display: flex;
        background-color: pink;
        width: 1000px;
    }

    nav {
        display: flex;
        background-color: lightblue;
        padding: 2px;
        flex-wrap: wrap;
    }

    img {
        position: absolute;
        transform: rotateX(-10deg) rotateY(30deg) rotateZ(3deg);
        height: 150px; 
        object-fit: contain;
        transition: .3s;
    }

    img:hover{
        transform: translate(60px);
    }

    #cartridge {
        height: 50%;
        object-fit: contain;
    }

    section {
        position: relative;
        display: grid;
        column-gap: 10px;
        grid-template-rows: 100px 60px;
        perspective: 1000px;
    }
</style>
