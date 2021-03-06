# Drop-in switcher for previewing minimal CSS frameworks

This is a quick drop-in CSS switcher to allow for previewing some of the many minimal CSS-only frameworks that are available. See the [demo](https://dohliam.github.io/dropin-minimal-css) or [drop the switcher](#usage) into your own page to see how [different frameworks](#list-of-frameworks) would look together with your content.

This project only includes _minimal_ frameworks, in other words, boilerplate / classless frameworks that require no adjustment of the corresponding HTML and can be simply dropped into the project to provide a starting point for further design. No additional javascript, compiling, pre-processors, or fiddling with classes should be required for these to look good and be responsive.

* [1 Usage](#usage)
  * [1.1 Keyboard shortcut](#keyboard-shortcut)
  * [1.2 Bookmarklet](#bookmarklet)
  * [1.3 API](#api)
* [2 Frameworks](#frameworks)
  * [2.1 Adding frameworks](#adding-frameworks)
  * [2.2 List of frameworks](#list-of-frameworks)
  * [2.3 Theme collections](#theme-collections)
* [3 See also](#see-also)
  * [3.1 Other similar collections](#other-similar-collections)
* [4 Acknowledgements](#acknowledgements)
* [5 License](#license)

## Usage

To use the CSS switcher, just add the following line anywhere within the body tag on your page:

```html
<script src="https://dohliam.github.io/dropin-minimal-css/switcher.js" type="text/javascript"></script>
```

That's it! You should now be able to cycle through the different frameworks by choosing them from the dropdown at the top of the page.

### Keyboard shortcut

You can quickly switch between frameworks by pressing the [modifier key or keys on your keyboard](https://github.com/dohliam/xsampa#access-keys) + `s` to focus the switcher dropdown menu, followed by the up and down keys to move up and down the list.

### Bookmarklet

The bookmarklet is a convenient way to preview how different CSS frameworks would look on any HTML page. Just paste the following code into your address bar to create a CSS switcher for any site:

```javascript
javascript:(function()%7Bvar%20body%20%3D%20document.getElementsByTagName('body')%5B0%5D%3Bscript%20%3D%20document.createElement('script')%3Bscript.type%3D%20'text%2Fjavascript'%3Bscript.src%3D%20'https%3A%2F%2Fdohliam.github.io%2Fdropin-minimal-css%2Fswitcher.js'%3Bbody.appendChild(script)%7D)()
```

Or alternatively, drag the link at the top of the [demo page](https://dohliam.github.io/dropin-minimal-css) to your browser's bookmark bar.

Boomarklet generated by the [Bookmarklet Creator](http://mrcoles.com/bookmarklet/). Thanks to [markdown-css](https://github.com/mrcoles/markdown-css) for the idea!

### API

There is a simple API available to allow linking directly to particular stylesheets on the demo page. For example:

https://dohliam.github.io/dropin-minimal-css/?sakura

The above links directly to the demo with [Sakura CSS](https://dohliam.github.io/dropin-minimal-css/?sakura).

## Frameworks

### Adding frameworks

If you know of a minimal framework that hasn't been included here, please create an [issue](https://github.com/dohliam/dropin-minimal-css/issues) or [pull request](https://github.com/dohliam/dropin-minimal-css/pulls) so that we can add it to the list!

### List of frameworks

* [a11yana](https://dohliam.github.io/dropin-minimal-css/?a11yana) by @alexandersandberg ([Source](https://github.com/alexandersandberg/a11yana) · [MIT](https://github.com/alexandersandberg/a11yana/blob/master/LICENSE.md))
* [awsm](https://dohliam.github.io/dropin-minimal-css/?awsm) by @igoradamenko ([Source](https://github.com/igoradamenko/awsm.css) · [MIT](https://github.com/igoradamenko/awsm.css/blob/master/LICENSE.md))
* [bahunya](https://dohliam.github.io/dropin-minimal-css/?bahunya) by @Kimeiga ([Source](https://github.com/Kimeiga/bahunya) · [MIT](https://github.com/Kimeiga/bahunya/blob/master/LICENSE))
* [bare](https://dohliam.github.io/dropin-minimal-css/?bare) by @longsien ([Source](https://github.com/longsien/BareCSS) · [MIT](https://github.com/longsien/BareCSS/blob/master/LICENSE))
* [base](https://dohliam.github.io/dropin-minimal-css/?base) by @matthewhartman ([Source](https://github.com/matthewhartman/base) · [MIT](https://github.com/matthewhartman/base#license))
* [bullframe](https://dohliam.github.io/dropin-minimal-css/?bullframe) by @marcop135 ([Source](https://github.com/marcop135/bullframe.css) · [MIT](https://github.com/marcop135/bullframe.css/blob/master/LICENSE.md))
* [bulma](https://dohliam.github.io/dropin-minimal-css/?bulma) by @jgthms ([Source](https://github.com/jgthms/bulma) · [MIT](https://github.com/jgthms/bulma/blob/master/LICENSE))
* [caiuss](https://dohliam.github.io/dropin-minimal-css/?caiuss) by @IonicaBizau ([Source](https://github.com/IonicaBizau/CaiuSS) · [MIT](https://github.com/IonicaBizau/CaiuSS/blob/master/LICENSE))
* [caramel](https://dohliam.github.io/dropin-minimal-css/?caramel) by @Lumios ([Source](https://github.com/lumios/caramel) · [MIT](https://github.com/lumios/caramel/blob/master/LICENSE))
* [cardinal](https://dohliam.github.io/dropin-minimal-css/?cardinal) by @cbracco ([Source](https://github.com/cardinalcss/cardinalcss) · [MIT](https://github.com/cardinalcss/cardinalcss/blob/master/LICENSE.md))
* [centurion](https://dohliam.github.io/dropin-minimal-css/?centurion) by @justinhough ([Source](https://github.com/justinhough/Centurion) · [GPL](https://github.com/justinhough/Centurion/blob/master/LICENSE.md))
* [chota](https://dohliam.github.io/dropin-minimal-css/?chota) by @jenil ([Source](https://github.com/jenil/chota) · [MIT](https://github.com/jenil/chota/blob/master/LICENSE))
* [cirrus](https://dohliam.github.io/dropin-minimal-css/?cirrus) by @spiderpig86 ([Source](https://github.com/Spiderpig86/Cirrus) · [MIT](https://github.com/Spiderpig86/Cirrus/blob/master/LICENSE))
* [clmaterial](https://dohliam.github.io/dropin-minimal-css/?clmaterial) by @24aitor ([Source](https://github.com/24aitor/CLMaterial) · [MIT](https://github.com/24aitor/CLMaterial/blob/master/LICENSE))
* [codify](https://dohliam.github.io/dropin-minimal-css/?codify) by @zdroid ([Source](https://github.com/zdroid/codify.css) · [MIT](https://github.com/zdroid/codify.css/blob/master/LICENSE.md))
* [comet](https://dohliam.github.io/dropin-minimal-css/?comet) by @marcbruederlin ([Source](https://github.com/marcbruederlin/comet) · [MIT](https://github.com/marcbruederlin/comet/blob/master/LICENSE))
* [concise](https://dohliam.github.io/dropin-minimal-css/?concise) by @ConciseCSS ([Source](https://github.com/ConciseCSS/concise.css) · [MIT](https://github.com/ConciseCSS/concise.css/blob/master/LICENSE))
* [concrete](https://dohliam.github.io/dropin-minimal-css/?concrete) by @louismerlin ([Source](https://github.com/louismerlin/concrete.css) · [MIT](https://github.com/louismerlin/concrete.css/blob/master/LICENSE))
* [cutestrap](https://dohliam.github.io/dropin-minimal-css/?cutestrap) by @tylerchilds ([Source](https://github.com/tylerchilds/cutestrap) · [GPL](https://github.com/tylerchilds/cutestrap/blob/master/LICENSE))
* [flat-ui](https://dohliam.github.io/dropin-minimal-css/?flat-ui) by @Designmodo ([Source](https://github.com/designmodo/Flat-UI) · [CC BY & MIT](https://github.com/designmodo/Flat-UI#copyright-and-license))
* [fluidity](https://dohliam.github.io/dropin-minimal-css/?fluidity) by @mrmrs ([Source](https://github.com/mrmrs/fluidity) · [MIT](https://github.com/mrmrs/fluidity/blob/master/README.md))
* [furtive](https://dohliam.github.io/dropin-minimal-css/?furtive) by @johno ([Source](https://github.com/johno/furtive) · [MIT](https://github.com/johno/furtive/blob/master/LICENSE))
* [generic](https://dohliam.github.io/dropin-minimal-css/?generic) by @Vereis ([Source](https://github.com/Vereis/generic.css) · [MIT](https://github.com/Vereis/generic.css))
* [github-markdown](https://dohliam.github.io/dropin-minimal-css/?github-markdown) by @sindresorhus ([Source](https://github.com/sindresorhus/github-markdown-css) · [MIT](https://github.com/sindresorhus/github-markdown-css/blob/gh-pages/license))
* [gutenberg](https://dohliam.github.io/dropin-minimal-css/?gutenberg) by @bafs ([Source](https://github.com/bafs/Gutenberg/) · [MIT](https://github.com/BafS/Gutenberg/blob/master/LICENSE))
* [hack](https://dohliam.github.io/dropin-minimal-css/?hack) by @egoist ([Source](https://github.com/egoist/hack) · [MIT](https://github.com/egoist/hack/blob/master/LICENSE))
* [hello](https://dohliam.github.io/dropin-minimal-css/?hello) by @arp242 ([Source](https://github.com/arp242/hello-css) · [PD/ISC](https://github.com/arp242/hello-css))
* [hiq](https://dohliam.github.io/dropin-minimal-css/?hiq) by @jonathanharrell ([Source](https://github.com/jonathanharrell/hiq) · [MIT](https://github.com/jonathanharrell/hiq/blob/master/license.md))
* [holiday](https://dohliam.github.io/dropin-minimal-css/?holiday) by @EvgenyOrekhov ([Source](https://github.com/EvgenyOrekhov/holiday.css) · [MIT](https://github.com/EvgenyOrekhov/holiday.css/blob/master/LICENSE))
* [html-starterkit](https://dohliam.github.io/dropin-minimal-css/?html-starterkit) by @zitrusfrisch ([Source](https://github.com/zitrusfrisch/HTML-StarterKit) · [MIT](https://github.com/zitrusfrisch/HTML-StarterKit#its-free))
* [hyp](https://dohliam.github.io/dropin-minimal-css/?hyp) by @krszwsk ([Source](https://github.com/krszwsk/hyp) · [MIT](https://github.com/krszwsk/hyp/blob/master/LICENSE))
* [kathamo](https://dohliam.github.io/dropin-minimal-css/?kathamo) by @debashisbarman ([Source](https://github.com/kathamo/Kathamo) · [MIT](https://github.com/kathamo/Kathamo/blob/master/LICENSE))
* [koochak](https://dohliam.github.io/dropin-minimal-css/?koochak) by @peyman3d ([Source](https://github.com/peyman3d/koochak) · [MIT](https://github.com/peyman3d/koochak/blob/master/LICENSE))
* [kraken](https://dohliam.github.io/dropin-minimal-css/?kraken) by @cferdinandi ([Source](https://github.com/cferdinandi/kraken) · [MIT](https://github.com/cferdinandi/kraken/blob/master/LICENSE.md))
* [kube](https://dohliam.github.io/dropin-minimal-css/?kube) by @imperavi ([Source](https://github.com/imperavi/kube) · [MIT](https://github.com/imperavi/kube/blob/master/LICENSE))
* [latex](https://dohliam.github.io/dropin-minimal-css/?latex) by @davidrzs ([Source](https://github.com/davidrzs/latexcss) · [MIT](https://github.com/davidrzs/latexcss/blob/master/LICENSE))
* [lemon](https://dohliam.github.io/dropin-minimal-css/?lemon) by @appalaszynski ([Source](https://github.com/lucasarvelo/lemon) · [MIT](https://github.com/lucasarvelo/lemon/blob/master/LICENSE))
* [lit](https://dohliam.github.io/dropin-minimal-css/?lit) by @Ajusa ([Source](https://github.com/Ajusa/lit) · [MIT](https://github.com/Ajusa/lit/blob/master/LICENSE))
* [lotus](https://dohliam.github.io/dropin-minimal-css/?lotus) by @goatslacker ([Source](https://github.com/goatslacker/lotus.css) · [MIT](https://github.com/goatslacker/lotus.css#license))
* [markdown](https://dohliam.github.io/dropin-minimal-css/?markdown) by @mrcoles ([Source](https://github.com/mrcoles/markdown-css) · [MIT](https://github.com/mrcoles/markdown-css/blob/master/license.txt))
* [marx](https://dohliam.github.io/dropin-minimal-css/?marx) by @mblode ([Source](https://github.com/mblode/marx) · [MIT](https://github.com/mblode/marx/blob/master/LICENSE.md))
* [material](https://dohliam.github.io/dropin-minimal-css/?material) by @daemonite ([Source](https://github.com/daemonite/material) · [MIT](https://github.com/Daemonite/material/blob/master/LICENSE))
* [materialize](https://dohliam.github.io/dropin-minimal-css/?materialize) by @Dogfalo ([Source](https://github.com/Dogfalo/materialize) · [MIT](https://github.com/Dogfalo/materialize/blob/v1-dev/LICENSE))
* [mercury](https://dohliam.github.io/dropin-minimal-css/?mercury) by @wmeredith ([Source](https://github.com/wmeredith/MercuryCSS) · [MIT](https://github.com/wmeredith/MercuryCSS/blob/master/LICENSE))
* [milligram](https://dohliam.github.io/dropin-minimal-css/?milligram) by @cjpatoilo ([Source](https://github.com/milligram/milligram) · [MIT](http://cjpatoilo.mit-license.org/))
* [min](https://dohliam.github.io/dropin-minimal-css/?min) by @owenversteeg ([Source](https://github.com/owenversteeg/min) · [MIT](https://github.com/owenversteeg/min#license))
* [mini](https://dohliam.github.io/dropin-minimal-css/?mini) by @Chalarangelo ([Source](https://github.com/Chalarangelo/mini.css) · [MIT](https://github.com/Chalarangelo/mini.css/blob/master/LICENSE))
* [minimal](https://dohliam.github.io/dropin-minimal-css/?minimal) by @billyshall ([Source](https://github.com/billyshall/minimalcss) · [MIT](https://github.com/billyshall/minimalcss/blob/master/license.txt))
* [minimal-stylesheet](https://dohliam.github.io/dropin-minimal-css/?minimal-stylesheet) by @chr15m ([Source](https://github.com/chr15m/minimal-stylesheet) · [MIT](https://github.com/chr15m/minimal-stylesheet/blob/master/LICENSE))
* [mobi](https://dohliam.github.io/dropin-minimal-css/?mobi) by @xcatliu ([Source](https://github.com/mobi-css/mobi.css) · [MIT](https://github.com/mobi-css/mobi.css/blob/master/LICENSE))
* [motherplate](https://dohliam.github.io/dropin-minimal-css/?motherplate) by @leemunroe ([Source](https://github.com/leemunroe/motherplate) · [MIT](https://github.com/leemunroe/motherplate/blob/master/LICENSE))
* [mu](https://dohliam.github.io/dropin-minimal-css/?mu) by @BafS ([Source](https://github.com/BafS/mu) · [MIT](https://github.com/BafS/mu/blob/gh-pages/LICENSE))
* [mui](https://dohliam.github.io/dropin-minimal-css/?mui) by @amorey ([Source](https://github.com/muicss/mui) · [MIT](https://github.com/muicss/mui/blob/master/LICENSE.txt))
* [new](https://dohliam.github.io/dropin-minimal-css/?new) by @3x ([Source](https://github.com/xz/new.css) · [MIT](https://github.com/xz/new.css/blob/master/LICENSE))
* [mvp](https://dohliam.github.io/dropin-minimal-css/?mvp) by @andybrewer ([Source](https://github.com/andybrewer/mvp) · [MIT](https://github.com/andybrewer/mvp/blob/master/LICENSE))
* [no-class](https://dohliam.github.io/dropin-minimal-css/?no-class) by @davidpaulsson ([Source](https://github.com/davidpaulsson/no-class) · [MIT](https://github.com/davidpaulsson/no-class/blob/master/LICENSE.txt))
* [normalize](https://dohliam.github.io/dropin-minimal-css/?normalize) by @necolas ([Source](https://github.com/necolas/normalize.css) · [MIT](https://github.com/necolas/normalize.css/blob/master/LICENSE.md))
* [oh-my-css](https://dohliam.github.io/dropin-minimal-css/?oh-my-css) by @egoist ([Source](https://github.com/egoist/oh-my-css) · [MIT](https://github.com/egoist/oh-my-css/blob/gh-pages/LICENSE))
* [paper](https://dohliam.github.io/dropin-minimal-css/?paper) by @rhyneav ([Source](https://github.com/papercss/papercss) · [ISC](https://github.com/papercss/papercss/blob/master/license))
* [papier](https://dohliam.github.io/dropin-minimal-css/?papier) by @alexanderGugel ([Source](https://github.com/alexanderGugel/papier) · [MIT](https://github.com/alexanderGugel/papier/blob/master/LICENSE.md))
* [pavilion](https://dohliam.github.io/dropin-minimal-css/?pavilion) by @getpavilion ([Source](https://github.com/getpavilion/pavilion) · [MIT](https://github.com/getpavilion/pavilion/blob/master/license))
* [picnic](https://dohliam.github.io/dropin-minimal-css/?picnic) by @FranciscoP ([Source](https://github.com/picnicss/picnic) · [MIT](https://github.com/picnicss/picnic/blob/master/LICENSE))
* [preface](https://dohliam.github.io/dropin-minimal-css/?preface) by @cluzier ([Source](https://github.com/cluzier/PrefaceCSS) · [MIT](https://github.com/cluzier/PrefaceCSS/blob/master/LICENSE))
* [primer](https://dohliam.github.io/dropin-minimal-css/?primer) by @primer ([Source](https://github.com/primer/css) · [MIT](https://github.com/primer/css/blob/master/LICENSE))
* [propeller](https://dohliam.github.io/dropin-minimal-css/?propeller) by @digicorp ([Source](https://github.com/digicorp/propeller) · [MIT](https://github.com/digicorp/propeller/blob/master/LICENSE))
* [pure](https://dohliam.github.io/dropin-minimal-css/?pure) by @yahoo ([Source](https://github.com/yahoo/pure/) · [BSD](https://github.com/yahoo/pure/blob/master/LICENSE.md))
* [roble](https://dohliam.github.io/dropin-minimal-css/?roble) by @violapeter ([Source](https://gitlab.com/violapeter/roble) · [MIT](https://gitlab.com/violapeter/roble/-/blob/master/package.json))
* [sakura](https://dohliam.github.io/dropin-minimal-css/?sakura) by @oxalorg ([Source](https://github.com/oxalorg/sakura) · [MIT](https://github.com/oxalorg/sakura/blob/master/LICENSE.txt))
* [sanitize](https://dohliam.github.io/dropin-minimal-css/?sanitize) by @csstools ([Source](https://github.com/csstools/sanitize.css) · [CC0](https://github.com/csstools/sanitize.css/blob/master/LICENSE.md))
* [scooter](https://dohliam.github.io/dropin-minimal-css/?scooter) by @dropbox ([Source](https://github.com/dropbox/scooter) · [Apache](https://github.com/dropbox/scooter/blob/master/LICENSE.md))
* [semantic-ui](https://dohliam.github.io/dropin-minimal-css/?semantic-ui) by @Semantic-Org ([Source](https://github.com/Semantic-Org/Semantic-UI) · [MIT](https://github.com/Semantic-Org/Semantic-UI/blob/master/LICENSE.md))
* [shoelace](https://dohliam.github.io/dropin-minimal-css/?shoelace) by @claviska ([Source](https://github.com/claviska/shoelace-css) · [MIT](https://github.com/claviska/shoelace-css/blob/master/LICENSE.md))
* [siimple](https://dohliam.github.io/dropin-minimal-css/?siimple) by @jmjuanes ([Source](https://github.com/siimple/siimple) · [MIT](https://github.com/siimple/siimple/blob/master/LICENSE.md))
* [simple](https://dohliam.github.io/dropin-minimal-css/?simple) by @neculaesei ([Source](https://github.com/tukangslicing/simplecss) · [MIT](https://opensource.org/licenses/mit-license.php))
* [skeleton](https://dohliam.github.io/dropin-minimal-css/?skeleton) by @dhg ([Source](https://github.com/dhg/Skeleton) · [MIT](https://github.com/dhg/Skeleton/blob/master/LICENSE.md))
* [skeleton-framework](https://dohliam.github.io/dropin-minimal-css/?skeleton-framework) by @skeleton-framework ([Source](https://github.com/skeleton-framework/skeleton-framework) · [MIT](https://github.com/skeleton-framework/skeleton-framework/blob/master/LICENSE))
* [skeleton-plus](https://dohliam.github.io/dropin-minimal-css/?skeleton-plus) by @oltdaniel ([Source](https://github.com/oltdaniel/skeleton-plus) · [MIT](https://github.com/oltdaniel/skeleton-plus/blob/master/LICENSE))
* [snack](https://dohliam.github.io/dropin-minimal-css/?snack) by @nzbin ([Source](https://github.com/snack-ui/snack) · [MIT](https://github.com/snack-ui/snack/blob/master/LICENSE))
* [spectre](https://dohliam.github.io/dropin-minimal-css/?spectre) by @picturepan2 ([Source](https://github.com/picturepan2/spectre) · [MIT](https://github.com/picturepan2/spectre/blob/master/LICENSE))
* [style](https://dohliam.github.io/dropin-minimal-css/?style) by @ungoldman ([Source](https://github.com/ungoldman/style.css) · [ISC](https://github.com/ungoldman/style.css/blob/master/license.md))
* [stylize](https://dohliam.github.io/dropin-minimal-css/?stylize) by @vasanthv ([Source](https://github.com/vasanthv/stylize.css) · [MIT](https://github.com/vasanthv/stylize.css/blob/master/LICENSE))
* [tachyons](https://dohliam.github.io/dropin-minimal-css/?tachyons) by @tachyons-css ([Source](https://github.com/tachyons-css/tachyons/) · [MIT](https://github.com/tachyons-css/tachyons/blob/master/license))
* [tacit](https://dohliam.github.io/dropin-minimal-css/?tacit) by @yegor256 ([Source](https://github.com/yegor256/tacit) · [MIT](https://github.com/yegor256/tacit/blob/master/LICENSE))
* [tent](https://dohliam.github.io/dropin-minimal-css/?tent) by @ulinaaron ([Source](https://github.com/sitetent/tentcss) · [MIT](https://github.com/sitetent/tentcss/blob/master/LICENSE))
* [thao](https://dohliam.github.io/dropin-minimal-css/?thao) by @Sanfra1407 ([Source](https://github.com/ThaoFramework/Thao/) · [Apache](http://www.apache.org/licenses/LICENSE-2.0))
* [vanilla](https://dohliam.github.io/dropin-minimal-css/?vanilla) by @bradleytaunt ([Source](https://github.com/bradleytaunt/vanilla-css) · [MIT](https://github.com/bradleytaunt/vanilla-css/blob/master/LICENSE))
* [vital](https://dohliam.github.io/dropin-minimal-css/?vital) by @doximity ([Source](https://github.com/doximity/vital) · [Apache](https://github.com/doximity/vital/blob/master/LICENSE.md))
* [water](https://dohliam.github.io/dropin-minimal-css/?water) by @kognise ([Source](https://github.com/kognise/water.css) · [MIT](https://github.com/kognise/water.css/blob/master/LICENSE.md))
* [wing](https://dohliam.github.io/dropin-minimal-css/?wing) by @KingPixil ([Source](https://github.com/KingPixil/wing/) · [MIT](https://github.com/KingPixil/wing/blob/master/LICENSE))
* [writ](https://dohliam.github.io/dropin-minimal-css/?writ) by @causal-agent ([Source](https://github.com/programble/writ) · [ISC](https://github.com/programble/writ/blob/master/LICENSE))
* [yamb](https://dohliam.github.io/dropin-minimal-css/?yamb) by @runxel ([Source](https://github.com/runxel/yamb-css) · [Blue Oak](https://github.com/runxel/yamb-css/blob/master/LICENSE.md))
* [yorha](https://dohliam.github.io/dropin-minimal-css/?yorha) by @metakirby5 ([Source](https://github.com/metakirby5/yorha) · [MIT](https://github.com/metakirby5/yorha/blob/master/LICENSE))

### Theme collections

* **[asciidoctor-skins](https://github.com/https://github.com/darshandsoni/asciidoctor-skins)** by @darshandsoni:
  * [ads-gazette](https://dohliam.github.io/dropin-minimal-css/?ads-gazette) by @darshandsoni ([Source](https://github.com/darshandsoni/asciidoctor-skins) · [MIT](https://github.com/darshandsoni/asciidoctor-skins/blob/gh-pages/LICENSE))
  * [ads-medium](https://dohliam.github.io/dropin-minimal-css/?ads-medium) by @darshandsoni ([Source](https://github.com/darshandsoni/asciidoctor-skins) · [MIT](https://github.com/darshandsoni/asciidoctor-skins/blob/gh-pages/LICENSE))
  * [ads-notebook](https://dohliam.github.io/dropin-minimal-css/?ads-notebook) by @darshandsoni ([Source](https://github.com/darshandsoni/asciidoctor-skins) · [MIT](https://github.com/darshandsoni/asciidoctor-skins/blob/gh-pages/LICENSE))
  * [ads-tufte](https://dohliam.github.io/dropin-minimal-css/?ads-tufte) by @darshandsoni ([Source](https://github.com/darshandsoni/asciidoctor-skins) · [MIT](https://github.com/darshandsoni/asciidoctor-skins/blob/gh-pages/LICENSE))
* **[bootswatch](https://github.com/https://github.com/thomaspark/bootswatch)** by @thomaspark:
  * [boot-cerulean](https://dohliam.github.io/dropin-minimal-css/?boot-cerulean) by @thomaspark ([Source](https://github.com/thomaspark/bootswatch) · [MIT](https://github.com/thomaspark/bootswatch/blob/gh-pages/LICENSE))
  * [boot-cosmo](https://dohliam.github.io/dropin-minimal-css/?boot-cosmo) by @thomaspark ([Source](https://github.com/thomaspark/bootswatch) · [MIT](https://github.com/thomaspark/bootswatch/blob/gh-pages/LICENSE))
  * [boot-cyborg](https://dohliam.github.io/dropin-minimal-css/?boot-cyborg) by @thomaspark ([Source](https://github.com/thomaspark/bootswatch) · [MIT](https://github.com/thomaspark/bootswatch/blob/gh-pages/LICENSE))
  * [boot-darkly](https://dohliam.github.io/dropin-minimal-css/?boot-darkly) by @thomaspark ([Source](https://github.com/thomaspark/bootswatch) · [MIT](https://github.com/thomaspark/bootswatch/blob/gh-pages/LICENSE))
  * [boot-flatly](https://dohliam.github.io/dropin-minimal-css/?boot-flatly) by @thomaspark ([Source](https://github.com/thomaspark/bootswatch) · [MIT](https://github.com/thomaspark/bootswatch/blob/gh-pages/LICENSE))
  * [boot-journal](https://dohliam.github.io/dropin-minimal-css/?boot-journal) by @thomaspark ([Source](https://github.com/thomaspark/bootswatch) · [MIT](https://github.com/thomaspark/bootswatch/blob/gh-pages/LICENSE))
  * [boot-lumen](https://dohliam.github.io/dropin-minimal-css/?boot-lumen) by @thomaspark ([Source](https://github.com/thomaspark/bootswatch) · [MIT](https://github.com/thomaspark/bootswatch/blob/gh-pages/LICENSE))
  * [boot-paper](https://dohliam.github.io/dropin-minimal-css/?boot-paper) by @thomaspark ([Source](https://github.com/thomaspark/bootswatch) · [MIT](https://github.com/thomaspark/bootswatch/blob/gh-pages/LICENSE))
  * [boot-readable](https://dohliam.github.io/dropin-minimal-css/?boot-readable) by @thomaspark ([Source](https://github.com/thomaspark/bootswatch) · [MIT](https://github.com/thomaspark/bootswatch/blob/gh-pages/LICENSE))
  * [boot-sandstone](https://dohliam.github.io/dropin-minimal-css/?boot-sandstone) by @thomaspark ([Source](https://github.com/thomaspark/bootswatch) · [MIT](https://github.com/thomaspark/bootswatch/blob/gh-pages/LICENSE))
  * [boot-slate](https://dohliam.github.io/dropin-minimal-css/?boot-slate) by @thomaspark ([Source](https://github.com/thomaspark/bootswatch) · [MIT](https://github.com/thomaspark/bootswatch/blob/gh-pages/LICENSE))
  * [boot-spacelab](https://dohliam.github.io/dropin-minimal-css/?boot-spacelab) by @thomaspark ([Source](https://github.com/thomaspark/bootswatch) · [MIT](https://github.com/thomaspark/bootswatch/blob/gh-pages/LICENSE))
  * [boot-superhero](https://dohliam.github.io/dropin-minimal-css/?boot-superhero) by @thomaspark ([Source](https://github.com/thomaspark/bootswatch) · [MIT](https://github.com/thomaspark/bootswatch/blob/gh-pages/LICENSE))
  * [boot-yeti](https://dohliam.github.io/dropin-minimal-css/?boot-yeti) by @thomaspark ([Source](https://github.com/thomaspark/bootswatch) · [MIT](https://github.com/thomaspark/bootswatch/blob/gh-pages/LICENSE))
* **[markdowncss](https://github.com/https://github.com/markdowncss)** by @johnotander:
  * [md-air](https://dohliam.github.io/dropin-minimal-css/?md-air) by @johnotander ([Source](https://github.com/markdowncss/air) · [MIT](https://github.com/markdowncss/air/blob/master/LICENSE))
  * [md-modest](https://dohliam.github.io/dropin-minimal-css/?md-modest) by @johnotander ([Source](https://github.com/markdowncss/modest) · [MIT](https://github.com/markdowncss/modest/blob/master/LICENSE))
  * [md-retro](https://dohliam.github.io/dropin-minimal-css/?md-retro) by @johnotander ([Source](https://github.com/markdowncss/retro) · [MIT](https://github.com/markdowncss/retro/blob/master/LICENSE))
  * [md-splendor](https://dohliam.github.io/dropin-minimal-css/?md-splendor) by @johnotander ([Source](https://github.com/markdowncss/splendor) · [MIT](https://github.com/markdowncss/splendor/blob/master/LICENSE))
* **[w3c-core](https://github.com/https://www.w3.org/StyleSheets/Core/)** by @Bert Bos:
  * [w3c-chocolate](https://dohliam.github.io/dropin-minimal-css/?w3c-chocolate) by @Bert Bos ([Source](https://www.w3.org/StyleSheets/Core/) · [W3C](https://www.w3.org/Consortium/Legal/2015/copyright-software-and-document))
  * [w3c-midnight](https://dohliam.github.io/dropin-minimal-css/?w3c-midnight) by @Bert Bos ([Source](https://www.w3.org/StyleSheets/Core/) · [W3C](https://www.w3.org/Consortium/Legal/2015/copyright-software-and-document))
  * [w3c-modernist](https://dohliam.github.io/dropin-minimal-css/?w3c-modernist) by @Bert Bos ([Source](https://www.w3.org/StyleSheets/Core/) · [W3C](https://www.w3.org/Consortium/Legal/2015/copyright-software-and-document))
  * [w3c-oldstyle](https://dohliam.github.io/dropin-minimal-css/?w3c-oldstyle) by @Bert Bos ([Source](https://www.w3.org/StyleSheets/Core/) · [W3C](https://www.w3.org/Consortium/Legal/2015/copyright-software-and-document))
  * [w3c-steely](https://dohliam.github.io/dropin-minimal-css/?w3c-steely) by @Bert Bos ([Source](https://www.w3.org/StyleSheets/Core/) · [W3C](https://www.w3.org/Consortium/Legal/2015/copyright-software-and-document))
  * [w3c-swiss](https://dohliam.github.io/dropin-minimal-css/?w3c-swiss) by @Bert Bos ([Source](https://www.w3.org/StyleSheets/Core/) · [W3C](https://www.w3.org/Consortium/Legal/2015/copyright-software-and-document))
  * [w3c-traditional](https://dohliam.github.io/dropin-minimal-css/?w3c-traditional) by @Bert Bos ([Source](https://www.w3.org/StyleSheets/Core/) · [W3C](https://www.w3.org/Consortium/Legal/2015/copyright-software-and-document))
  * [w3c-ultramarine](https://dohliam.github.io/dropin-minimal-css/?w3c-ultramarine) by @Bert Bos ([Source](https://www.w3.org/StyleSheets/Core/) · [W3C](https://www.w3.org/Consortium/Legal/2015/copyright-software-and-document))

## See also

* [workflow](https://github.com/dohliam/workflow) - Quick prototyping script for creating rich html and pdfs from markdown documents (based on dropin-minimal-css)
* [asciidoctor-skins](https://github.com/darshandsoni/asciidoctor-skins) - CSS stylesheets for asciidoctor (with a switcher based on dropin-minimal-css)

### Other similar collections

* [CSS Bed](https://github.com/ubershmekel/cssbed) by @ubershmekel
* [classless-css](https://github.com/dbohdan/classless-css) by @dbohdan
* [cleanrmd](https://github.com/gadenbuie/cleanrmd) by @gadenbuie
* [awesome-css-frameworks](https://github.com/troxler/awesome-css-frameworks) by @troxler

## Acknowledgements

* Sample HTML5 markup based on [html5-test-page](https://github.com/cbracco/html5-test-page) by @cbracco (MIT)
* Example images in the demo are by [MichaelMaggs](https://commons.wikimedia.org/wiki/User:MichaelMaggs) on [Wikimedia Commons](https://commons.wikimedia.org)
* Example videos provided by the [Blender Foundation](https://peach.blender.org/) via the [HTML5-Test-Videos](https://github.com/benhosmer/HTML5-Test-Videos) project
* Embedded audio [Night Owl](https://freemusicarchive.org/music/Broke_For_Free/Directionless_EP/Broke_For_Free_-_Directionless_EP_-_01_Night_Owl) by [Broke For Free](https://freemusicarchive.org/music/Broke_For_Free) at the [Free Music Archive](https://freemusicarchive.org/)
* Special thanks to [Tacit CSS](https://github.com/yegor256/tacit), which was the original inspiration for making this list to answer the question "Where can I find more frameworks like Tacit?"
* Table of contents made with [tocdown](https://github.com/dohliam/tocdown)

## License

MIT.
