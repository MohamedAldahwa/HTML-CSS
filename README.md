# HTML-CSS


<!DOCTYPE html>
<html>
<head>
  <title>Jetsetter Concierge Travel Planning</title>
  <link href="https://fonts.googleapis.com/css?family=Open+Sans:300,400,600,700|Quicksand:300,700" rel="stylesheet">
  <style>
    body{
        background-color: #FFFFFF;
        margin: 0px;
        padding:0px;
    }
    .header{
        background-image: url(https://content.codecademy.com/programs/code-foundations-path/airplane.jpeg);
        background-position: center center;
        background-size: cover;
        height: 550px;
        width: 100%;
    }
    .overlay:before {
        content: " ";
        z-index: 1;
        display: block;
        position: absolute;   
        height: 100%;
        width: 100%;
        background: rgba(0, 0, 0, 0.6);
    }
    .overlay * {
        position: relative;
    }
    #header-text{
        margin: 0 auto;
        position: relative;
        text-align: center;
        top: 25%;
        width: 60%;
        z-index: 2 !important;
        font-weight: bold;
    }
    h1{
        color: white;
        font-family: 'Quicksand', sans-serif;
        font-size: 70px;
        font-weight: 400;
        line-height: 60px;
        margin: 0px;
    }
    h2{
        color: #ffffff;
        font-family: 'Open Sans',sans-serif;
        text-align: center;
        font-size: 28px;
        font-weight: 100;
    }
    h3{
        color: #ffffff;
        font-family: 'Quicksand', sans-serif;
        font-size: 28px;
        font-weight: 400;
        line-height: 30px;
        margin: 10px 0px;
        text-align: center;
    }
    h4{
        color: #cccccc;
        font-family: 'Quicksand',sans-serif;
        font-size: 16px;
        font-weight: 300;
    }
    p{
        color: white;
        font-family: 'Open Sans',sans-serif;
        font-size: 16px;
        font-weight: 100;
        line-height: 24px;
        margin: 0 auto;
        text-align: center;
        width: 60%;
    }
    .partner{
        padding: 20px;
        text-align: center;
        margin: auto;
        border-bottom: 1px solid #eeeeee;
        position: relative;
        background-color: white;
        z-index: 3;
    }
    .partner img{
        position: relative;
        top: 6px;
    }
    .main{
        background: url(https://content.codecademy.com/programs/code-foundations-path/shards.png);
        margin: 0px;
        padding: 40px;
    }
    .value-props{
        margin: 40px auto;
        width: 60%;
    }
    .prop{
        border: 1px solid #ffffff;
        padding: 40px 0px;
        margin: 5px 0px;
        text-align: center;
    }
    .prop h2{
        font-family: 'Quicksand',sans-serif;
        font-size: 24px;
    }
  </style>
</head>
<body>
    <div class="overlay">
        <div class="header">
            <div id="header-text">
                <h1>Jetsetter Concierge</h1>
                <h2>Whether you're looking for adventure or luxury, let us help you plan your perfect getaway.</h2>
            </div>
        </div>
    </div>
    <div class="partner">
            <h4>Proud Partner of Am South Airlines <img src="https://content.codecademy.com/programs/code-foundations-path/amsoair.png" id="aa-logo" width="150px"></h4>
    </div>
    <div class="main">
        <h3>Why You Should Choose Jetsetter Concierge Travel Planning</h3>
      <p>With over <a href="/resume.html">25 years of experience</a> in concierge, high-end travel planning, we'll provide you with the highest quality services. Every vacation is unique, custom, and tailored to your tastes.</p>

        <div class="value-props">
            <div class="prop">
                <img src="https://content.codecademy.com/programs/code-foundations-path/diamond.png" width="60px">
                <h2>Unique</h2>
                <p>We don't do standardized packages because we know everyone wants something different. Every vacation will be uniquely customized to your tastes.</p>
            </div>

            <div class="prop">
                <img src="https://content.codecademy.com/programs/code-foundations-path/diamond.png" width="60px">
                <h2>Experienced</h2>
                <p>Our quarter century of experience in travel planning combines local knowledge with international taste. You'll be amazed at what we can provide!</p>
            </div>

            <div class="prop">
                <img src="https://content.codecademy.com/programs/code-foundations-path/diamond.png" width="60px">
                <h2>Luxury</h2>
                <p>We understand that you expect the world of your vacation - Jetsetter can provide once-in-a-lifetime experiences at top-of-the-line quality.</p>
            </div>
        </div>
    </div>
</body>
</html>
