<section id="profile">
    <a href="https://aubs.dev">
        <img
            src="profile.png"
            alt="cute smily face logo with big eye lashes"
            width="200px"
        />
    </a>
    <h1>- Aubrey Dominik -</h1>

    <div class="section-align">
        <p>Curious programmer making games/engines and tools from scratch.</p>

        <p>
            Here are my <a
                href="https://github.com/aubs-dev/dotfiles"
                target="_blank"><span>Dotfiles</span></a
            >.
        </p>

        <div class="button-container">
            <a href="mailto:hello@aubs.dev" target="_blank"
                ><button>Contact Me</button></a
            >
            <a href="https://github.com/aubs-dev" target="_blank"
                ><button>Github</button></a
            >
            <a href="https://bsky.app/profile/aubs.dev" target="_blank"
                ><button>Bluesky</button></a
            >
        </div>
    </div>
</section>

<style>
    @import url("https://fonts.googleapis.com/css2?family=Fredoka:wght@600&display=swap");
    @import url("https://fonts.googleapis.com/css2?family=Nunito:wght@300..700&display=swap");

    * {
        margin: 0;
        padding: 0;
        list-style: none;
        text-decoration: none;
    }

    section {
        width: 100vw;
        height: 100vh;
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
    }

    .section-align {
        width: 500px;
    }

    h1 {
        margin-top: -0.25em;
        margin-bottom: 0.25em;
        font-family: "Fredoka", sans-serif;
        font-size: 2.75em;
        font-weight: 600;
        color: #000000;
    }

    p {
        margin-bottom: 0.5em;
        font-family: "Nunito", sans-serif;
        font-size: 1.5em;
        font-weight: 500;
        color: #00021c;
    }

    span {
        color: #0b8be6;
        font-weight: 700;
    }

    span:hover {
        color: #d9214f;
        transition: all;
        transition-duration: 150ms;
    }

    a > span:hover {
        text-decoration: underline;
    }

    .button-container {
        margin-top: 1em;
        width: 100%;
        display: flex;
        flex-direction: row;
        align-items: center;
        justify-content: center;
    }

    button {
        width: 9rem;
        height: 3rem;
        margin-right: 1em;
        font-family: "Nunito", sans-serif;
        font-size: 1.25rem;
        font-weight: 600;
        color: #f0edd8;
        background-color: #0b8be6;
        border-style: solid;
        border-color: #0b8be6;
        border-width: 4px;
        border-radius: 5px;
        transition: all;
        transition-duration: 150ms;
        cursor: pointer;
    }

    button:hover {
        background-color: #d9214f;
        border-color: #d9214f;
        box-shadow: -5px 5px 0px 0px #00021c;
        transform: scale(1.1, 1.1);
    }
</style>
