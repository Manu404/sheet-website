# sheet-website
Sheet music sharing for https://emmanuelistace.be

deps folder contain a zip of the abcwebplayer(https://wim.vree.org/js/) not available on npm, will see with the author to publish it through npm, meanwhile, prefered to add the zip itself 

    npm install gulp --global
    npm install
    gulp

Gulp tasks

    clean, css, scss, js, vendor
	init => generate fav icons and build
	fav => build fav icons (slow)
	inject => inject html tags for favicon into index
    prod => build folder to deploy
    build => dev build (clean, deps, merge, minify)
    watch => watch js and scss
    pack => build zip for deployment from prod folder
