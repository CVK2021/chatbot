
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <title>Sample Page | Preview your chat widget</title>
  <meta name="description" content="ChatBot Sample Page to preview your chat widget">

  
  <link rel="canonical" href="https://www.chatbot.com/preview/">
  
  <script type="application/ld+json">
  {
    "@context": "https://schema.org",
    "@graph": [{"@context":"https://schema.org","@type":"Corporation","brand":"ChatBot","name":"ChatBot","sameAs":["https://twitter.com/chatbotcom"],"url":"https://www.chatbot.com/"}]
  }
  </script>

  <meta name="robots" content="noindex">

  <link rel="icon" href="/favicon.ico">

  <meta property="og:locale" content="en_US" />
  <meta property="og:type" content="article" />
  <meta property="og:title" content="Sample Page | Preview your chat widget" />
  <meta property="og:description" content="ChatBot Sample Page to preview your chat widget" />
  <meta property="og:url" content="https://www.chatbot.com/preview/" />
  <meta property="og:site_name" content="ChatBot" />

  <meta name="twitter:card" content="summary_large_image" />
  <meta name="twitter:description" content="ChatBot Sample Page to preview your chat widget" />
  <meta name="twitter:title" content="Sample Page | Preview your chat widget" />
  <meta name="twitter:site" content="@chatbotcom" />

  
      

      

      <meta property="og:image" content="https://www.chatbot.com/og-images/og-image.71001a3911f5b36ce85247ad661524ab1307aab4892c38b225473e75e743997e.png" />
      <meta name="twitter:image" content="https://www.chatbot.com/og-images/og-image.71001a3911f5b36ce85247ad661524ab1307aab4892c38b225473e75e743997e.png" />
  

  <script>
      scrollOffsetFunction = function() {
        var navElements = document.getElementsByClassName("c-navbar");
        if (typeof navElements[0] !== "undefined") {
          var navRect = navElements[0].getBoundingClientRect();
          var navStyle = getComputedStyle(navElements[0]);
          if (navStyle.position === "sticky" || navStyle.position === "fixed") {
            return navRect.bottom - navRect.top + 30;
          }
        }
        return 0;
      }
    </script>

  

    <script>(function(w,d,s,l,i){w[l]=w[l]||[];w[l].push({'gtm.start':
    new Date().getTime(),event:'gtm.js'});var f=d.getElementsByTagName(s)[0],
    j=d.createElement(s),dl=l!='dataLayer'?'&l='+l:'';j.async=true;j.src=
    'https://www.googletagmanager.com/gtm.js?id='+i+dl;f.parentNode.insertBefore(j,f);
    })(window,document,'script','dataLayer','GTM-NQCSXSR');</script>

  

  
    <link rel="preload" as="style" href="/dist/css/main.c62957b7429060f74cf02ec1c146b77a23ed6bff7e8a94dab51dfc6bcf100b3a.css">
    <link rel="stylesheet" href="/dist/css/main.c62957b7429060f74cf02ec1c146b77a23ed6bff7e8a94dab51dfc6bcf100b3a.css">
  

  
</head>

<body>
  <noscript><iframe src="https://www.googletagmanager.com/ns.html?id=GTM-NQCSXSR" height="0" width="0" style="display:none;visibility:hidden"></iframe></noscript>

  
    <div class="o-wrapper">
        
<header class="c-navbar u-shadow">
    <div class="c-navbar__content">
        <a href="/" class="c-navbar__logo"><img src="chatbot-logo.svg" width="141" height="33" alt="ChatBot logo"></a>

        <div class="c-navbar__actions u-flex u-flex-wrap u-items-center">
            <svg width="24" height="12" viewBox="0 0 24 12" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path fill-rule="evenodd" clip-rule="evenodd" d="M3 7.11572V5.1001H23.05C23.1605 5.1001 23.25 5.18964 23.25 5.3001V6.91572C23.25 7.02618 23.1605 7.11572 23.05 7.11572H3Z" fill="#006CFF"/>
                <path fill-rule="evenodd" clip-rule="evenodd" d="M7.45594 0.204956C7.53858 0.132969 7.66376 0.140902 7.73666 0.222747L8.83137 1.4519C8.90484 1.53439 8.89752 1.66081 8.81504 1.73427C8.81423 1.73499 8.81342 1.7357 8.8126 1.7364L3.81268 6.04637L8.81351 10.3849C8.89795 10.4601 8.90526 10.5865 8.8318 10.669L7.73697 11.8983C7.66395 11.9803 7.5385 11.9881 7.45589 11.9158L0.75 6.04637L7.45594 0.204956Z" fill="#006CFF"/>
            </svg>
            <a href="//app.chatbot.com" class="u-text-black u-text-p6-bold">
                Back to application
            </a>
        </div>
    </div>
</header>

<section class="o-container u-hidden u-Py-2xl" id="widget">
    <div class="u-maxw-6 u-pb-2xs">
        <h1 class="u-text-p2 u-Mb-xs">Sample Page</h1>
        <p class="u-text-p5 u-Mb-sm">
            This is a sample page of your ChatBot widget.
            You&nbsp;can&nbsp;manipulate it using the buttons below.
        </p>
    </div>

    <div class="u-text-p6">
        <button onclick="BE_API.openChatWindow();return false;" class="c-btn u-mr-2xs u-mb-xs v--primary">Open chat window</button>
        <button onclick="BE_API.closeChatWindow();return false;" class="c-btn u-mb-xs v--primary">Close chat window</button>
    </div>
</section>

<section class="o-container u-hidden u-Py-2xl" id="widget-error">
    <div class="u-maxw-6 u-pb-2xs">
        <h1 class="u-text-p2 u-Mb-xs">Oops!</h1>
        <p class="u-text-p5 u-Mb-sm">
            Looks like this widget doesn't exist.
        </p>

        <div class="u-text-p6">
            <a href="//app.chatbot.com" class="c-btn u-mr-2xs v--primary">Back to application</a>
        </div>
    </div>
</section>

<section class="u-Pb-md u-mx-auto">
    <div class="u-Pb-xs u--mr-2xl u-flex u-justify-between">
        <div class="t-preview-block u-rounded u-bg-gray-900"></div>
        <div class="t-preview-block u-rounded u-bg-gray-900"></div>
        <div class="t-preview-block u-rounded u-bg-gray-900"></div>
        <div class="t-preview-block u-rounded u-bg-gray-900"></div>
        <div class="t-preview-block u-rounded u-bg-gray-900"></div>
    </div>

    <div class="u--Ml-2xl u-flex u-justify-between">
        <div class="t-preview-block u-rounded u-bg-gray-800"></div>
        <div class="t-preview-block u-rounded u-bg-gray-800"></div>
        <div class="t-preview-block u-rounded u-bg-gray-800"></div>
        <div class="t-preview-block u-rounded u-bg-gray-800"></div>
        <div class="t-preview-block u-rounded u-bg-gray-800"></div>
    </div>
</section>

<style type="text/css">
    .t-preview-block {
        min-width: 250px;
        width: 19%;
        height: 20rem;
        margin: 0 .5rem;
    }

    .t-preview-block:first-child {
        margin-left: -.5rem;
    }
</style>


    </div>


  
  

  
      
      <script async defer src="/dist/js/main.f930d0a1bf8ce88ba916f265859513357a78f9ab4a3a22b3f2f5eec2453f0375.js"></script>
    

  

    
</body>
</html>



<script type="text/javascript">
    window.__be = window.__be || {};
    window.__be.id = "60ae27b7b2ee370007b022b7";
    (function() {
        var be = document.createElement('script'); be.type = 'text/javascript'; be.async = true;
        be.src = ('https:' == document.location.protocol ? 'https://' : 'http://') + 'cdn.chatbot.com/widget/plugin.js';
        var s = document.getElementsByTagName('script')[0]; s.parentNode.insertBefore(be, s);
    })();
</script>

