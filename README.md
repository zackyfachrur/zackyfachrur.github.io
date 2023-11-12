### Publish Web pertama kali di github 👍

Smooth Scroll and Inject AOS Framework :
```js
$(document).ready(function () {
    AOS.init();
    $("a").on("click", function (event) {
        if (this.hash !== "") {
            event.preventDefault();
            var hash = this.hash;
            
            $("html, body").animate(
                {
                    scrollTop: $(hash).offset().top,
                },
                800,
                function () {
                    window.location.hash = hash;
                }
            );
        } // End if
    });
});
```
#### Domain https://zahsey.github.io/
