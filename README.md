## Still_Coding...
> Live Demo Version ===> xmas.ffwpu-myanmar.cf
### > Sample Flow
``` javascript
$(document).ready(function () {
            // Init Side Nav
            $('.button-collapse').sideNav();
            
            // Init Modal
            $('.modal').modal();

            // Scrollfire
            const options = [
                {
                    selector: '.row-1', offset: 50, callback: function(el) {
                        Materialize.fadeInImage($(el));
                    }
                },

                {
                    selector: '.row-2', offset: 300, callback: function(el) {
                        Materialize.fadeInImage($(el));
                    }
                },

                {
                    selector: '.row-3', offset: 400, callback: function(el) {
                        Materialize.fadeInImage($(el));
                    }
                }
            ];

            Materialize.scrollFire(options);
        });
```
