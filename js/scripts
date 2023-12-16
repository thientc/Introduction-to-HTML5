var _paq = _paq || [];
_paq.push(['disableCookies']);
_paq.push(['trackPageView']);
_paq.push(['enableLinkTracking']);
(function() {
  var u="//pixelbrackets.de/depot/piwik/";
  _paq.push(['setTrackerUrl', u+'piwik.php']);
  _paq.push(['setSiteId', '11']);
  var d=document, g=d.createElement('script'), s=d.getElementsByTagName('script')[0];
  g.type='text/javascript'; g.async=true; g.defer=true; g.src=u+'piwik.js'; s.parentNode.insertBefore(g,s);
})();

var textToCopy = document.querySelector('body div pre').innerText;
var copyButton = document.querySelector('.copy');
copyButton.addEventListener('click' , ()=> {
  navigator.clipboard.writeText(textToCopy).then(
    function() {
      copyButton.innerText = 'Copied';
    },
    function() {
      copyButton.innerText = 'Error';
    }
  )
})
