<main id="hero">
    <p>Hello, I'm</p>
    <h2>Vaishnav Wakchaure</h2>
    <h3 class="dark-gray">Fullstack Developer</h3>
</main>

<style>
    main {
        background: radial-gradient(
            circle,
            #0d0c0e,
            #0c1019,
            #3a014f,
            #3d7c88,
            #0d4680
        );
        background-size: 400% 400%;
        animation: gradientAnimation 80s infinite;

        display: flex;
        flex-direction: column;
        height: calc(100vh - 80px - 88px);
        justify-content: center;
        align-items: center;
    }

    h2 {
        color: white;
        font-size: 4rem;
        margin: 0;
        text-align: left;
        width: 100%;
        max-width: 600px;
    }

    h3 {
        color: white;
        font-size: 2rem;
        margin: 0;
        text-align: left;
        width: 100%;
        max-width: 600px;
    }

    .dark-gray {
        color: #888889;
    }

    p {
        color: #7feaff;
        text-align: left;
        font-size: 2rem;
    }

    @media (max-width: 768px) {
        h2 {
            font-size: 2rem; /* Smaller font size for mobile */
            text-align: center;
        }

        p {
            font-size: 1rem;
        }
    }

    @keyframes gradientAnimation {
        0% {
            background-position: 0% 50%;
        }
        50% {
            background-position: 100% 50%;
        }
        100% {
            background-position: 0% 50%;
        }
    }
</style>
