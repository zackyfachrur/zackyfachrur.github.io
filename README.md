### Publish Web pertama kali di github 👍
#
#### Import css style below into https://github.com/zahsey/zahsey.github.io/blob/master/assets/css/style.css 

Preview Smooth Scroll :
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
