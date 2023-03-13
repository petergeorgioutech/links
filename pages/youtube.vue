<template>
  <div>
  </div>
</template>

<script>

export default {
  head: {
    script: [
      {
        hid: 'onload',
        innerHTML: `
          window.onload = function() {
        var fallback = "https://www.youtube.com/watch?v=CzYe6oh96mw",
        app = "vnd.youtube://watch?v=CzYe6oh96mw";

        if( /Android|iPhone|iPad|iPod/i.test(navigator.userAgent) ) {
            window.location = app;
            window.setTimeout(function() {
                window.location = fallback;
            }, 25);
        } else {
            window.location = fallback;
        }

        function killPopup() {
            window.removeEventListener('pagehide', killPopup);
        }

        window.addEventListener('pagehide', killPopup);
      };
        `,
        type: 'text/javascript',
        charset: 'utf-8'
      }
    ]
  },
  layout: 'default',
};
</script>