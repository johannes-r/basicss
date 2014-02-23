# basicss.scss

Base styles I've been using recently...

**basicss.scss** includes [normalize.css](http://github.com/necolas/normalize.css) by Nicolas Gallagher and is heavily inspired by Harry Roberts work such as [inuitcss](http://inuitcss.com/) or his [blog](http://csswizardry.com).

## Usage:

Install with [bower](http://bower.io):

`bower install --save basicss`

**style.scss** should look something like this:

    /**
     * style.scss
     */

    /**
     * basicss overrides
     * 
     * any defaults in basicss/basicss/_settings.scss
     * may be overridden...
     */

    $arrowObject: true;
    $buttonObject: false;
    $fontPrimary: "Proxima-nova", sans-serif;
    $arrowSize: 20px;

    /**
     * basicss
     */

    @import 'path/to/basicss/basicss';

    /**
     * userstyles
     */

    @import 'path/to/yourstyles/nav';
    @import 'path/to/yourstyles/whatever';

