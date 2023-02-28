<!DOCTYPE html>
<html>
    <head>
        <meta charset="UF-8" />
        <meta http-equiv="X-UA-Compatible" content="IE=edge" />
        <meta name="viewport" content="width=device-width, initial-scale=1.0" />
        <title>Mini Cooper 🚗 </title>
        <style>
            body {
                background-image: linear-gradient(to top, #e71515 0%, #080000 100%);
                color: #fff;
                width: 50%;
                margin: 60px auto;
                font-family:'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            }

            h1 {
                text-align: center;
                font-weight: bolder;
                border: 1px solid rgba(247, 6, 2);
                padding: 20px;
                border-radius: 4px;
            }

            h2 {
                text-align: center;
            }

            p {
                line-height: 2;
                font-size: 26px;
                margin: 20px 0 10px;
            }

            image {
                margin: 0 auto;
                display: block;
                border-radius: 10px;
                margin-left: auto;
                margin-right: auto;

            }

            button {
                background: rgba(0, 0, 0, 0.87);
                border:#e91515;
                font-size: 42px;
                border-radius: 4px;
                text-transform: uppercase;
                color: #fff;
                display: block;
                padding: 10px 20px;
                transition: opacity 150ms ease;
                cursor: pointer;
                opacity: 1;
                box-shadow: 0 1px 20px rgba(0, 0, 0, 0.5);
                margin: 30px auto;
            }

            button:hover {
                opacity: 0.9;
                cursor: pointer;
            }

            a {
                color: #fff;
            }
        </style>
    </head>

    <body>
        <h1>Mini Cooper Countryman</h1>
        <h2>2014 Cooper S</h2>
        <hr />

        <image src="https://s3.amazonaws.com/shecodesio-production/uploads/files/000/006/519/original/MINI_COOPER.jpeg?1617588264"
        alt="MINI COOPER S" width="720"
        />
        <hr />
        <p>
            <strong>Mini</strong> is a British automotive marque founded in 1969, owned by German automotive company BMW since 2000, and used by them for a range of small cars.
        </p>
        <small><a href="https://en.wikipedia.org/wiki/Mini_(marque)" target="_blank">Read on Wikipedia</a> </small>
        <br>
        <button class="btn"> Buy Your Own Mini 🚗
        </button>
        <p class="footer">
            This page was built by Zana Asanaj
        </p>
    </div>
    <script>
        document.querySelector(".btn").addEventListener("click", buy);
        function buy() {
            let name = prompt("What is your name?");
            let email = prompt("What is your email address?");
            alert("Thank you " + name + "! We'll email you a store link to the MiniShop website. Have fun car shopping! 🛍️");
        }

        if (snaptr) {
          snaptr('track', 'PAGE_VIEW');
        }
  
        if (fbq) {
          fbq('track', "PageView");
        }
    </script>
    </body>
</html>

