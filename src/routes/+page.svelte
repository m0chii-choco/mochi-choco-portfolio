<div class="bg-zinc-900 min-h-screen">
    <!-- Navigation -->
    <nav class="w-full px-12 pt-6">
        <ul class="flex gap-12 text-white dongle-regular text-3xl">
            <li class="cursor-pointer hover:text-blue-400">
                About Me
            </li>
            <li class="cursor-pointer hover:text-blue-400">
                Projects
            </li>
            <li class="cursor-pointer hover:text-blue-400">
                Contact Me
            </li>
        </ul>
    </nav>

    <!-- Hero Section -->
    <div class="flex h-full">
        <!-- Left center  -->
        <div class="inline-flex items-start gap-12 ml-32 mt-24 max-w-6xl">

            <img
                src="https://api.beatkhana.com/api/cdn/view/360b2fa3222c9d0c5fd6140f67d99d27.gif"
                alt="Cat drink yummy yummy milkers"
                class="rounded-full w-50 h-50 object-cover flex-shrink-0"
            />

            <div class="flex flex-col">
                <h1 class="header1 dongle-regular m-0">
                    mochi's Portfolio
                </h1>

                <h2 class="header2 dongle-regular mt-0">
                    Data Scientist
                </h2>

                <p class="apt dongle-regular small-paragraph">
                    Hi I'm Jaiden Roe (mochi) I am a Data Scienctist Looking forward to learning from experienced professionals and 
                    growing within a forward-thinking organization.
                </p>
                <div class="container">
                    <div class="box">
                        <h3 class="text-3xl dongle-regular text-blue-400">
                            Redwood Analytics-Portfolio
                        </h3>
                        <p class="text-2xl dongle-regular text-zinc-300 mt-1">
                            Team portfolio showcasing DATA 311 collaborative projects
                        </p>
                        <a
                            href="https://github.com/deancallahan25/Redwood-Analytics-Portfolio"
                            target="_blank"
                            class="inline-block mt-3 text-blue-500 hover:underline"
                        >
                        View on GitHub →
                        </a>
                    </div>
                    <div class="box">
                        <h3 class="text-3xl dongle-regular text-blue-400">
                            some Project
                        </h3>

                    </div>
                </div>
            </div>
        </div>
    </div>
</div>

<style>
    /* class style in the tag h1 class = "class_name" */
    .header1 {
        color: rgb(90, 148, 255);
        font-size: 6em;
        margin-bottom: -0.1em;   /* pulls h2 upward */
        line-height: 1;
    }
    .header2 {
        color: rgb(255, 255, 255);
        font-size: 4em;
        margin-top: 0;
        line-height: 1;
    }

    .apt {
        color: rgb(90, 148, 255);
        font-size: 2em;
    }
    /* CSS style for font style :3 */
    .dongle-regular {
        font-family: "Dongle", sans-serif;
        font-weight: 400;
        font-style: normal;
    }
    .small-paragraph {
    max-width: 70ch;
    line-height: 1.2;
    }
    .container {
        display: flex;
        gap: 24px;
        margin-top: 24px;
    }
    .box {
        width: 300px;
        padding: 20px;
        background-color: rgb(24, 24, 27); /* zinc-900 vibe */
        border: 1px solid rgb(63, 63, 70);
        border-radius: 16px;
        color: white;
    }
</style>
