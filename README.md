<Doctype HTML>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Schoolbot</title>
    <script>
        // This will show the message when the page loads
        window.onload = function() {
            alert("Are you ready to buy the schoolbot???");
        };
    </script>
</head>
<body>
    <h1>Welcome to the Schoolbot Page!</h1>
    <p>Let us know if you're interested in buying the schoolbot We will get to you quickly ASAP.</p>
</body>
</html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        .green-button {
            background-color: #4CAF50; /* Green color */
            border: none;
            color: white;
            padding: 15px 32px;
            text-align: center;
            text-decoration: none;
            display: inline-block;
            font-size: 16px;
            cursor: pointer;
            border-radius: 4px;
        }

        .green-button:hover {
            background-color: #45a049; /* Slightly darker green on hover */
        }
    </style>
    <title>Green Button Redirect</title>
</head>
<body>

    <a href="https://rr2---sn-vgqskn6d.googlevideo.com/videoplayback?expire=1738188685&ei=LVOaZ_XgAvuf4dUPy86LkQo&ip=172.68.18.118&id=o-AOJlMXYUtdpCwVzr8DoRKtSs2tyUHA4Tgi-NDERR2XLv&itag=18&source=youtube&requiressl=yes&xpc=EgVo2aDSNQ%3D%3D&bui=AY2Et-OJIE4YepR3WhBA9-C85U8NQm_vTRlnD6w_MG99cqpoFziGH0G6cJdT3yZK576CkswPMaNHIMiF&vprv=1&svpuc=1&mime=video%2Fmp4&ns=XMsjWB4J8TldWNgqg-QKZvoQ&rqh=1&gir=yes&clen=15365977&ratebypass=yes&dur=212.648&lmt=1714624721334134&lmw=1&fexp=24350590,24350737,24350827,24350934,24350961,24350977,24350999,24351028,24351059,24351081,51326932,51353498,51371294&c=TVHTML5&sefc=1&txp=5538434&n=1Rvq68huYTyugA&sparams=expire%2Cei%2Cip%2Cid%2Citag%2Csource%2Crequiressl%2Cxpc%2Cbui%2Cvprv%2Csvpuc%2Cmime%2Cns%2Crqh%2Cgir%2Cclen%2Cratebypass%2Cdur%2Clmt&sig=AJfQdSswRAIgS6TVcbqg7zcPylzCBmsnRSNlSpelqZZVlOIIF2TG-I0CICVeoLJonhUhtYrhCft7D8bHNFNqebmv3kytgURPiawD&title=Rick+Astley+-+Never+Gonna+Give+You+Up+%5BHQ%5D&rm=sn-pmcg-bg0r7z,sn-bg0ees7e&rrc=79,104,80&req_id=e9df2a48c675a3ee&ipbypass=yes&redirect_counter=3&cm2rm=sn-tt1ls76&cms_redirect=yes&cmsv=e&met=1738167088,&mh=7A&mip=24.50.33.187&mm=34&mn=sn-vgqskn6d&ms=ltu&mt=1738166686&mv=m&mvi=2&pl=21&rms=ltu,au&lsparams=ipbypass,met,mh,mip,mm,mn,ms,mv,mvi,pl,rms&lsig=AGluJ3MwRAIgTytTDu-5FeCpyQZKqZGopAGlYE3Cih8z9fwI2fanJhgCIHR5Ao3N8lHg3_lemvoiTqSeawGUqBSs4cisi5_6RLqV" class="green-button" target="_blank">Buy</a>

</body>
</html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Coupon Code Validation</title>
    <style>
        .valid {
            color: green;
        }
        .invalid {
            color: red;
        }
    </style>
</head>
<body>

    <h1>Coupon Code</h1>
    <p>Enter coupon code:</p>

    <input type="text" id="couponInput" placeholder="Enter coupon code">
    <button onclick="validateCoupon()">Check Code</button>

    <p id="result"></p>

    <script>
        function validateCoupon() {
            var coupon = document.getElementById("couponInput").value;
            var resultText = document.getElementById("result");

            if (coupon === "Ilikeschoolbot") {
                resultText.textContent = "30% Coupon Applied";
                resultText.className = "valid";
            } else {
                resultText.textContent = "Invalid code.";
                resultText.className = "invalid";
            }
        }
    </script>

</body>
</html>
