<!DOCTYPE html>
<html lang="en">

<head>
    <!-- Meta Tags -->
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta http-equiv="X-UA-Compatible" content="ie=edge" />
    <meta name="description" content="" />
    <meta name="keywords" content="" />
    <meta name="theme-color" content="#252525" />

    <title>BloxLuck - Error</title>

    <!-- Scripts -->
    <script src="js/jquery.min.js"></script>
    <script src="js/sweetalert2.all.min.js"></script>
    <script src="js/textFit.min.js"></script>
    <script src="js/socket.io.min.js"></script>

    <!-- Links -->
    <link rel="stylesheet" href="css/style.css" />
    <link rel="icon" href="img/favicon.png" />
    <link rel="stylesheet" href="css/sweetalert2-dark.css" />

    <!-- Google Analytics (keep your tag) -->
    <script async src="https://www.googletagmanager.com/gtag/js?id=G-YOURTAGHERE"></script>
    <script>
        window.dataLayer = window.dataLayer || [];
        function gtag() { dataLayer.push(arguments); }
        gtag('js', new Date());
        gtag('config', 'G-YOURTAGHERE');
    </script>
</head>

<body>
    <header>
        <div class="logo">
            <img src="img/favicon.png" alt="BloxLuck" />
        </div>
        <nav>
            <button onclick="toggleMenu()" class="btn-primary mobile mobile-only">
                <!-- hamburger icon -->
                <svg xmlns="http://www.w3.org/2000/svg" width="25" height="25" viewBox="0 0 16 16" fill="currentColor">
                    <path fill-rule="evenodd" d="M2.5 12a.5.5 0 0 1 .5-.5h10a.5.5 0 0 1 0 1H3a.5.5 0 0 1-.5-.5zm0-4a.5.5 0 0 1 .5-.5h10a.5.5 0 0 1 0 1H3a.5.5 0 0 1-.5-.5zm0-4a.5.5 0 0 1 .5-.5h10a.5.5 0 0 1 0 1H3a.5.5 0 0 1-.5-.5z" />
                </svg>
            </button>

            <!-- Since no PHP session, replace user login with a static login button -->
            <button onclick="login()" class="btn-primary mobile">
                <!-- login icon -->
                <svg xmlns="http://www.w3.org/2000/svg" width="1em" height="1em" fill="currentColor" viewBox="0 0 1024 1024">
                    <path d="M532.528 661.408c-12.512 12.496-12.513 32.752-.001 45.248c6.256 6.256 14.432 9.376 22.624 9.376s16.368-3.12 22.624-9.376l189.008-194L577.775 318.64c-12.496-12.496-32.752-12.496-45.248 0c-12.512 12.496-12.512 32.752 0 45.248l115.744 115.76H31.839c-17.68 0-32 14.336-32 32s14.32 32 32 32h618.448zM960.159 0h-576c-35.36 0-64.017 28.656-64.017 64v288h64.432V103.024c0-21.376 17.344-38.72 38.72-38.72h496.704c21.408 0 38.72 17.344 38.72 38.72l1.007 818.288c0 21.376-17.311 38.72-38.72 38.72H423.31c-21.376 0-38.72-17.344-38.72-38.72V670.944l-64.432.08V960c0 35.344 28.656 64 64.017 64h576c35.344 0 64-28.656 64-64V64c-.016-35.344-28.672-64-64.016-64z" />
                </svg>
                Login
            </button>
        </nav>
    </header>

    <div class="main" style="display:flex;align-items:center;justify-content:center;text-align:center;height:80vh;">
        <div id="error-content" style="font-size: 24px; line-height: 1.5;">

            <!-- We'll fill this with JS -->
        </div>
    </div>

    <script>
        // Define error codes and descriptions
        const codes = {
            200: "Under Construction",
            400: "Bad Request",
            401: "Unauthorized",
            402: "Payment Required",
            403: "Forbidden",
            404: "Not Found",
            405: "Method Not Allowed",
            406: "Not Acceptable",
            407: "Proxy Authentication Required",
            408: "Request Timeout",
            409: "Conflict",
            410: "Gone",
            411: "Length Required",
            412: "Precondition Failed",
            413: "Request Entity Too Large",
            414: "Request-URI Too Long",
            415: "Unsupported Media Type",
            416: "Requested Range Not Satisfiable",
            417: "Expectation Failed",
            418: "I'm a teapot",
            422: "Unprocessable Entity",
            423: "Locked",
            424: "Method Failure",
            426: "Upgrade Required",
            428: "Precondition Required",
            429: "Too Many Requests",
            431: "Request Header Fields Too Large",
            451: "Unavailable For Legal Reasons",
            500: "Internal Server Error",
            501: "Not Implemented",
            502: "Bad Gateway",
            503: "Service Unavailable",
            504: "Gateway Timeout",
            505: "HTTP Version Not Supported",
            506: "Variant Also Negotiates",
            507: "Insufficient Storage",
            508: "Loop Detected",
            510: "Not Extended",
            511: "Network Authentication Required"
        };

        // Try to get error code from URL query param ?code=404
        function getErrorCode() {
            const urlParams = new URLSearchParams(window.location.search);
            let code = urlParams.get('code');
            if (code && codes[code]) {
                return code;
            }
            return 200; // default
        }

        const code = getErrorCode();
        const description = codes[code] || "Unknown Error";

        // Display error content
        const errorDiv = document.getElementById('error-content');
        if (code != 200) {
            errorDiv.innerHTML = `<strong>Error ${code}</strong><br>${description}`;
        } else {
            errorDiv.textContent = "Website Under Maintenance, we'll be back in a few hours / discord.gg/bloxluck";
        }

        // textFit if you want
        if (window.textFit) {
            textFit([errorDiv], { multiLine: true });
        }

        // Login placeholder (since no backend)
        function login() {
            Swal.fire({
                icon: 'info',
                title: 'Login',
                text: 'Login functionality is not available in static HTML version.'
            });
        }

        function toggleMenu() {
            // Just an example: toggle a class for mobile menus
            document.querySelector('.main').classList.toggle('desktop-only');
        }
    </script>
</body>
</html>
