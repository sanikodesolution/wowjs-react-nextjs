# wowjs-react-nextjs
Wowjs Working With React NextJs

`` npm install wowjs ``
<br>
Under _app.js
`<br>`
``

function MyApp({ Component, pageProps }) {
    useEffect(() => {
        
        const WOW = require('wowjs');
        window.wow = new WOW.WOW({
            live: false
        });
        window.wow.init();
    }, []);
}

export default MyApp
``
`<br>`
Under Layout Js
`<br>`
``

    useEffect(() => {
        
        const WOW = require('wowjs');
        window.wow = new WOW.WOW({
            live: false
        });
        window.wow.init();
    }, [])
``
